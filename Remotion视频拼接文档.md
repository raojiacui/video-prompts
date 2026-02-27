# Remotion 视频拼接项目文档

## 项目概述

使用 Remotion 框架将 10 个视频（b1-b10）进行简单拼接，并添加背景音乐。

## 项目信息

- **项目路径**: `C:\Users\雨下雨停\remotion-video-edit`
- **输出路径**: `C:\Users\雨下雨停\remotion-video-edit\out\video.mp4`
- **分辨率**: 1920x1080 (Full HD)
- **帧率**: 30 FPS
- **总时长**: 80 秒 (10个视频 × 8秒)

## 源文件

### 视频文件
| 文件名 | 大小 | 日期 |
|--------|------|------|
| b1.mp4 | 5.9 MB | 2026-02-27 11:14 |
| b2.mp4 | 2.9 MB | 2026-02-27 11:20 |
| b3.mp4 | 3.3 MB | 2026-02-27 11:24 |
| b4.mp4 | 3.8 MB | 2026-02-27 11:28 |
| b5.mp4 | 2.9 MB | 2026-02-27 11:31 |
| b6.mp4 | 1.2 MB | 2026-02-27 11:34 |
| b7.mp4 | 6.4 MB | 2026-02-27 11:37 |
| b8.mp4 | 5.6 MB | 2026-02-27 11:41 |
| b9.mp4 | 3.8 MB | 2026-02-27 11:45 |
| b10.mp4 | 4.8 MB | 2026-02-27 11:48 |

**源路径**: `D:\雨下雨停\OneDrive\文档\`

### 背景音乐
- **文件名**: `2026年02月26日 12点31分.m4a`
- **路径**: `D:\雨下雨停\OneDrive\文档\xwechat_files\wxid_bpf7wbqsa29r22_95ba\msg\file\2026-02\`

## 项目结构

```
remotion-video-edit/
├── src/
│   ├── Root.tsx          # 主配置文件，定义视频路径和参数
│   └── VideoEdit.tsx     # 视频拼接组件
├── public/
│   └── videos/
│       ├── b1.mp4 - b10.mp4  # 源视频文件
│       └── music.m4a         # 背景音乐
├── out/
│   └── video.mp4          # 输出视频
├── package.json
└── tsconfig.json
```

## 配置文件详解

### Root.tsx - 主配置

```typescript
import { Composition, staticFile } from "remotion";
import { VideoEdit } from "./VideoEdit";

// 10 videos × 8 seconds × 30fps = 2400 frames
const TOTAL_FRAMES = 2400;

export const RemotionRoot: React.FC = () => {
  return (
    <>
      <Composition
        id="VideoEdit"
        component={VideoEdit}
        durationInFrames={TOTAL_FRAMES}
        fps={30}
        width={1920}
        height={1080}
        defaultProps={{
          videoPaths: [
            staticFile("videos/b1.mp4"),
            staticFile("videos/b2.mp4"),
            // ... b3-b10
            staticFile("videos/b10.mp4"),
          ],
          musicPath: staticFile("music.m4a"),
        }}
      />
    </>
  );
};
```

### VideoEdit.tsx - 拼接逻辑

核心逻辑：
- 每个场景 240 帧（8秒 @ 30fps）
- 根据当前帧计算应该显示哪个视频
- 同时播放背景音乐
- 支持字幕叠加（可选）

```typescript
// 每个场景的帧数
const SCENE_DURATIONS = [240, 240, 240, 240, 240, 240, 240, 240, 240, 240];

// 计算当前场景
let accumulatedFrames = 0;
let currentSceneIndex = 0;

for (let i = 0; i < SCENE_DURATIONS.length; i++) {
  if (frame < accumulatedFrames + SCENE_DURATIONS[i]) {
    currentSceneIndex = i;
    break;
  }
  accumulatedFrames += SCENE_DURATIONS[i];
}
```

## 使用方法

### 1. 预览视频

```bash
cd C:/Users/雨下雨停/remotion-video-edit
pnpm start
```

在浏览器中打开 `http://localhost:3000` 预览效果。

### 2. 渲染最终视频

```bash
cd C:/Users/雨下雨停/remotion-video-edit
pnpm build
```

输出文件: `out/video.mp4`

### 3. 自定义参数

修改 `src/Root.tsx`:
- `durationInFrames`: 总帧数
- `fps`: 帧率
- `width/height`: 分辨率

修改 `src/VideoEdit.tsx`:
- `SCENE_DURATIONS`: 每个场景的帧数
- 添加/修改字幕内容

## 技术栈

- **Remotion 4.x**: React 视频框架
- **TypeScript**: 类型安全
- **React 19**: UI 框架
- **FFmpeg**: 底层视频处理（由 Remotion 自动调用）

## 输出规格

| 参数 | 值 |
|------|-----|
| 编码器 | H.264 |
| 容器 | MP4 |
| 分辨率 | 1920×1080 |
| 帧率 | 30 FPS |
| 总时长 | 80 秒 |
| 音频 | 包含背景音乐 |

## 剪辑过程总结

### 步骤 1: 准备源文件
- 从 `D:\雨下雨停\OneDrive\文档\` 复制 10 个视频文件
- 复制背景音乐文件

### 步骤 2: 配置项目
- 更新 `Root.tsx` 设置视频路径
- 配置总帧数（2400帧 = 80秒）

### 步骤 3: 拼接逻辑
- 使用 Remotion 的 `useCurrentFrame` hook 跟踪当前播放位置
- 根据帧数计算当前应播放的视频
- 无缝切换，无转场效果

### 步骤 4: 渲染输出
- 使用 `pnpm build` 命令渲染
- Remotion 自动调用 FFmpeg 进行视频编码
- 支持 7x 并发渲染加速

## 注意事项

1. **文件路径**: 确保 `public/videos/` 目录包含所有源视频
2. **音乐格式**: 支持 .m4a, .mp3 等常见音频格式
3. **渲染时间**: 80秒视频约需 5-10 分钟（取决于硬件性能）
4. **帧数计算**: 每场景帧数 = 视频时长(秒) × fps

---

生成日期: 2026-02-27

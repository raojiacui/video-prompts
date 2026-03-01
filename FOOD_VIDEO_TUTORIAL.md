# 美食视频剪辑 - Remotion 教程

## 项目概述

将 11 个美食视频片段（sw1-sw11）拼接成一个完整的视频，并配上字幕和背景音乐。

## 视频素材

| 片段 | 源文件 | 字幕 |
|------|--------|------|
| 1 | sw1.mp4 | 新疆大盘鸡 |
| 2 | sw2.mp4 | 白菜猪肉炖粉条 |
| 3 | sw3.mp4 | 羊蝎子火锅 |
| 4 | sw4.mp4 | 金汤佛跳墙 |
| 5 | sw5.mp4 | 泰式绿咖喱鸡 |
| 6 | sw6.mp4 | 过桥米线 |
| 7 | sw7.mp4 | 椰子鸡火锅 |
| 8 | sw8.mp4 | 韩式海鲜拉面 |
| 9 | sw9.mp4 | 猪脚姜 |
| 10 | sw10.mp4 | 匈牙利牛肉炖肉 |
| 11 | sw11.mp4 | 腊味煲仔饭 |

## 技术参数

- **分辨率**: 1920x1080
- **帧率**: 30fps
- **单片段时长**: 8秒
- **总时长**: 88秒 (11 x 8秒)
- **输出格式**: MP4 (H.264)

## 文件结构

```
remotion-video-edit/
├── src/
│   ├── Root.tsx          # 视频配置
│   └── VideoEdit.tsx    # 视频编辑组件
├── public/
│   ├── videos/           # 视频素材
│   │   ├── sw1.mp4
│   │   ├── sw2.mp4
│   │   └── ... sw11.mp4
│   └── music.m4a         # 背景音乐
└── out/
    └── video.mp4         # 渲染输出
```

## 配置步骤

### 1. 安装依赖

```bash
cd remotion-video-edit
pnpm install
```

### 2. 复制视频素材

将 sw1.sw11.mp4 从源目录复制到 public/videos/：

```bash
cp "D:/雨下雨停/OneDrive/文档/sw*.mp4" public/videos/
```

### 3. 配置视频参数

编辑 `src/Root.tsx`：

```tsx
<Composition
  id="FoodVideo"
  component={VideoEdit}
  durationInFrames={2640}  // 11 x 8s x 30fps
  fps={30}
  width={1920}
  height={1080}
  defaultProps={{
    videoPaths: [
      staticFile("videos/sw1.mp4"),
      // ... 其他视频
    ],
    subtitles: [
      "新疆大盘鸡",
      // ... 其他字幕
    ],
    musicPath: staticFile("music.m4a"),
  }}
/>
```

### 4. 渲染视频

```bash
pnpm build
```

输出文件：`out/video.mp4`

## 字幕样式

- 位置：屏幕顶部
- 字体：Microsoft YaHei (黑体)
- 大小：56px
- 颜色：白色带阴影
- 背景：半透明黑色渐变

## 注意事项

1. **音乐文件**：需要提供 `green-to-blue.mp3` 文件，目前使用 `music.m4a` 作为占位
2. **视频时长**：每个片段固定 8 秒，可根据实际需求调整
3. **帧率**：统一使用 30fps

## 输出文件

- **位置**: `C:/Users/雨下雨停/remotion-video-edit/out/video.mp4`
- **大小**: ~20MB

---

剪辑日期: 2026-03-01

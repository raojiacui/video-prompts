# ARROW 视频 AI 提示词合集

> 43个电影镜头的动态叙事脚本与生成参数

---

## 1. 警局集结 - 推门而入

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing a [police officer in dark blue uniform] performing [walking through glass doors into a crowded plaza of officers, transitioning to a low-angle close-up of faces looking up at the sky in awe].

**时空演变:**
- **Start:** 从室内过道远景开始，主体背影接近玻璃大门，门外可见模糊的大规模警察集结，散射自然光模拟阴天环境
- **Action:** 主体推开双扇玻璃门，光线从室外涌入，镜头穿过人群，视角高度下降融入警察方阵
- **End:** 最终画面定格在仰角特写，展现众人惊愕、凝重的眼神及抬头动作

**Camera Movement:** Tracking shot following the action, handheld shake for immersive feel, transitioning from indoor to outdoor with downward tilt.

**Physics/Details:** 制服面料纹理细腻、玻璃反射质感、写实的人物皮肤纹理、人群穿梭的密度感

**Visual Bible:** 冷色调以深蓝色（警服）、灰色（天空、建筑）和冷白光为主，低饱和度，胶片颗粒感

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 21:9
duration_s: 6-8
physics_simulation: crowd dynamics, cloth simulation, glass reflection
consistency_guard: photorealistic, consistent character style, cinematic realism
negative: morphing, disappearing objects, extra limbs, logic errors, defying gravity, bright colors, smiling, sunshine
```

---

## 2. 直升机编队 - 仰望天际

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [police officers in formation] performing [looking up in shock as military Black Hawk helicopters fly overhead in V-formation].

**时空演变:**
- **Start:** 低角度仰拍，对焦在人群惊恐、严肃的面部表情，背景纯白的阴霾天空
- **Action:** 镜头快速向上方云层拉升，直升机底部剪影由模糊变清晰，出现多架直升机编队
- **End:** 镜头持续拉高，呈现V字形排开的直升机群，下方现代都市建筑群逐渐显现，最后淡出至黑色背景UI

**Camera Movement:** Tilt-up and crane shot with zoom out, steady medium pace with cinematic openness.

**Physics/Details:** 直升机螺旋桨高速旋转的动态模糊效果、螺旋桨下压的气流细节、人群同步仰望的动作

**Visual Bible:** 低饱和度青灰色调（Cine-blue/Teal）+ 阴天白灰色天空 + 直升机黑色剪影，胶片颗粒感

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 2.35:1
duration_s: 6-8
physics_simulation: helicopter rotor dynamics, aerial perspective
consistency_guard: photorealistic, consistent helicopter formation, cold teal color grading
negative: morphing, disappearing helicopters, extra rotors, cartoonish, bright sunny, cheerful
```

---

## 3. 东京塔俯冲 - 数字嵌套

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [Tokyo Tower's spire] performing [extreme zoom-out from close-up down to street level POV with AR floating menus, then transitioning to a hand holding a smartphone].

**时空演变:**
- **Start:** 塔尖特写，镜头锁定红色塔身，蓝天白云背景，呈现缓慢的微动或静止状态
- **Action:** 镜头垂直高度下降，塔身结构开始延展，出现明显的运动模糊和AR浮动UI菜单
- **End:** 镜头极速后撤，显示出刚才的影像其实是一个正在被滑动的智能手机屏幕

**Camera Movement:** Extreme zoom-out / Drone drop with rapid acceleration and high motion blur.

**Physics/Details:** 镜头快速下坠产生的动态模糊、AR式浮动UI菜单的悬浮感、广角畸变和色散边缘

**Visual Bible:** 湛蓝色天空 + 国际橘/白色（塔体）+ 城市混杂色调，高清实景纹理

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 21:9 or 16:9
duration_s: 4-5
physics_simulation: vertical motion blur, AR interface physics
consistency_guard: photorealistic, consistent tower architecture, clear AR overlay
negative: morphing, unstable tower, blurry hands, low resolution, bad phone reveal
```

---

## 4. 巴黎铁塔扭曲 - 超现实转场

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [a shocked blonde woman] performing [showing her phone screen with the Eiffel Tower melting and twisting like a snake, giant floating computer UI menus in the sky].

**时空演变:**
- **Start:** 女性手持手机，双眼圆睁，表现出震惊和不可思议，背景是模糊的客厅
- **Action:** 女性举起手机正对镜头，镜头向屏幕中心汇聚，穿透屏幕进入超现实巴黎街头
- **End:** 埃菲尔铁塔发生剧烈的蛇形扭曲变形，巴黎街道两侧建筑纹理清晰，巨大的半透明OS右键菜单浮现

**Camera Movement:** Push-in shot with match cut transition through the smartphone screen.

**Physics/Details:** 铁塔像软件液化滤镜实时处理的扭曲效果、半透明数字化菜单的质感

**Visual Bible:** 冷调灰蓝色（室内）+ 浅蓝淡灰的自然底色（室外），点缀UI界面的纯白色

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 21:9
duration_s: 6-8
physics_simulation: fluid deformation, liquefying effect
consistency_guard: photorealistic, surreal distortion, consistent Paris architecture
negative: morphing, extra limbs, stable tower, cartoonish, messy UI, low quality
```

---

## 5. 模拟恐怖 - 聊天滚动

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [scrolling chat interface bubbles] performing [text popping up with messages like "LOOK. We're doomed..." and alien emojis, vertical scrolling movement].

**时空演变:**
- **Start:** 背景为扭曲的巴黎铁塔实景，右侧叠合半透明系统菜单
- **Action:** 场景切换至纯色背景，蓝色聊天气泡向上弹出，跟随大量外星人表情符号
- **End:** 消息向上滚动，米黄色对话框出现，背景变为灰色，画面右上角悬浮一帧模糊的风景缩略图

**Camera Movement:** Vertical scrolling with moderate speed, moving upwards.

**Physics/Details:** 水平扫描线（Scanlines）、明显的噪点、屏幕闪烁感、窗口重叠的半透明度

**Visual Bible:** 复古灰度 + 莫兰迪蓝（聊天气泡）+ 米白色（通知条），模拟录像带风格

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 2.35:1
duration_s: 4-6
physics_simulation: CRT scanline effect, digital scrolling
consistency_guard: VHS aesthetic, retro tech style, glitchy texture
negative: HD, clear, 4k, bright colors, smooth texture, realistic photography, modern smartphone UI
```

---

## 6. AR牧场 - 奶牛放大

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [a Holstein cow in pasture] performing [being selected by a futuristic AR interface with 3D bounding box and rapidly scaling up in size].

**时空演变:**
- **Start:** 全景镜头，屏幕左侧存在悬浮UI面板，草原上分布多只奶牛，背景为连绵的雪山
- **Action:** 镜头微弱推进，中心奶牛位置出现鼠标光标，被白色2D边框选中并进化为3D线框
- **End:** 目标奶牛开始表现出不自然的体积放大，镜头急速推向选中奶牛，UI面板在左侧保持动态悬浮

**Camera Movement:** Dolly in with gradually accelerating speed, straight forward towards center subject.

**Physics/Details:** 边框进化为3D线框（Bounding Box），奶牛体积的非自然放大

**Visual Bible:** 低饱和度莫兰迪色系，冷灰色、灰蓝色天幕，黑白相间的奶牛纹理，阴天漫反射光

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 2.35:1
duration_s: 4-6
physics_simulation: object scaling, AR tracking simulation
consistency_guard: photorealistic nature backdrop, clean UI design, consistent cow appearance
negative: blurry UI, low resolution, messy colors, sunlight, sunset, extra heads on cow
```

---

## 7. 男颜异变 - 眼球翻白

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [a man's eyes] performing [rolling back showing whites then snapping back to stare, with intense forehead wrinkling and twitching facial muscles].

**时空演变:**
- **Start:** 稳定的双眼平视，瞳孔微弱震颤，扫描线清晰
- **Action:** 镜头略微向左偏移，人物开始出现明显的额头肌肉收缩，眼球向上翻起仅露出眼白
- **End:** 眼球快速回正，瞳孔放大，展现出一种受惊或苏醒的刹那状态

**Camera Movement:** Extreme close-up with slow and jittery movement, slight forward zoom with micro-shaking.

**Physics/Details:** 额头皱纹剧烈加深、眼球翻白（Ahegao/Seizure effect）、面部肌肉抽动

**Visual Bible:** 暖肤色 + 强对比度 + 边缘RGB色散（Chromatic Aberration），贯穿始终的水平扫描线

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 2.35:1 or 4:3
duration_s: 3-4
physics_simulation: facial muscle animation, eye movement
consistency_guard: VHS aesthetic, retro-analog style, consistent face texture
negative: clean image, high definition, 4k, smooth skin, smiling, stable camera, cartoon
```

---

## 8. 上海东方明珠 - AR选择

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [Oriental Pearl Tower in Shanghai] performing [being approached by FPV drone cinematography with augmented reality interface and floating 3D wireframe bounding box selecting the tower sphere].

**时空演变:**
- **Start:** 初始远景，东方明珠位于中心，左下角出现AR菜单栏起点，白色鼠标准心在画面中央
- **Action:** 镜头缓慢向塔尖移动，白色选择框（BBox）开始出现并在塔顶球体周围生成
- **End:** 镜头极速俯冲穿过，焦点对准塔顶圆盘表面，产生强烈的动态模糊和近距离冲击感

**Camera Movement:** FPV drone push-in with tilting down, steady to fast acceleration.

**Physics/Details:** 3D线框包裹球体、数字交互的即时反馈、高空俯冲的速度感

**Visual Bible:** 灰蓝色调 + 晨曦微光，冷灰色的建筑群透出淡金色的江面反射光

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 21:9 or 16:9
duration_s: 5-8
physics_simulation: drone flight dynamics, AR tracking
consistency_guard: photorealistic, sharp details, consistent UI interface
negative: low quality, blurry UI, nighttime, messy colors, cartoonish, static camera
```

---

## 9. 伦敦塔桥拉伸 - 现实编辑

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [London Tower Bridge and Great Pyramids of Giza] performing [being stretched like rubber and morphing into giant black minimalist cubes through a reality-editing interface].

**时空演变:**
- **Start:** 实景塔桥俯瞰，UI面板切入，出现鼠标指针，塔桥局部受控制点牵引向上弯曲
- **Action:** 场景突变至埃及，展示尼罗河与金字塔全景，UI面板跟随，金字塔被白色高亮线框选中
- **End:** 金字塔发生形变降解，最终重构为平滑的黑色哑光核心立方体

**Camera Movement:** Top-down aerial with smooth pan and slight tilt, steady cruise speed.

**Physics/Details:** 桥面呈现反物理的受力向上弯曲、金字塔形变降解为立方体

**Visual Bible:** 青蓝色调（泰晤士河/塔桥）过渡到暖沙色/深黑色（埃及/立方体），自然日光环境

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 2.35:1
duration_s: 8-10
physics_simulation: architectural morphing, geometric transformation
consistency_guard: photorealistic, consistent landmark structures, clean UI overlay
negative: low quality, blurry, messy UI, illogical shadows, cartoonish, low-poly
```

---

## 10. 比萨斜塔扶正 - AR操控

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [a photographer with DSLR] performing [using floating translucent AR interface to manipulate the Leaning Tower of Pisa in real-time, the tower moving and straightening].

**时空演变:**
- **Start:** 摄影师视角起始，鼠标光标点击倾斜的比萨斜塔塔尖
- **Action:** 塔体发生动态变化，塔身开始向左侧（垂直方向）缓慢回正，达到垂直状态后继续向左侧倾斜
- **End:** 塔体呈现出与初始方向相反的极大倾斜角度

**Camera Movement:** Fixed over-the-shoulder shot with subtle handheld micro-shaking, static.

**Physics/Details:** 塔体从倾斜变为垂直再变为反向倾斜的非物理形变

**Visual Bible:** 低饱和度莫兰迪色调，大地色（荒野棕）+ 淡蓝色（天空）+ 科技白（UI面板）

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 2.35:1
duration_s: 8-10
physics_simulation: object manipulation, architectural deformation
consistency_guard: photorealistic, surrealism, consistent tower texture
negative: shaky camera, low resolution, messy UI, distorted face, cartoon, vibrant colors
```

---

## 11. 咖啡馆到时代广场 - 快速摇移

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [a lone woman sitting by desk] performing [whip-pan transition from bustling cafe to facing New York Times Square, holding coffee cup, back view].

**时空演变:**
- **Start:** 室内中景，主体为讨论的青年，注意手势动作和背景电视内容
- **Action:** 镜头极速向左横移，出现明显的动感模糊和咖啡馆立柱，主体切换为女性背影
- **End:** 镜头向主体缓慢拉近，女性右手拿起纸质咖啡杯，画面重心向电脑屏幕和咖啡杯侧重

**Camera Movement:** Whip-pan transition followed by dolly-in, fast lateral move to forward focus.

**Physics/Details:** 快速横移产生的动感模糊、浅景深背景虚化效果

**Visual Bible:** 暖棕色调（室内木质与咖啡色）+ 冷蓝色调（纽约街景与屏幕光）强烈对比

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 21:9
duration_s: 6-8
physics_simulation: motion blur, depth of field transition
consistency_guard: photorealistic, movie screen grab, consistent character
negative: static, cartoon, low resolution, extra fingers, blurry face, distorted city
```

---

## 12. T恤印花开场 - 极速拉远

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [3D design software UI of Times Square] performing [dramatic zoom-out transitioning into Statue of Liberty on t-shirt print, ending with view of person wearing shirt outdoors].

**时空演变:**
- **Start:** 特写设计软件界面，背景是模糊的纽约街头
- **Action:** 自由女神像3D模型在屏幕中央由下至上生成并占据主体，鼠标指针出现，画面质感变得粗犷
- **End:** 画面完全揭示，这是一个印在浅色T恤背后的图案，背景变为模糊的室外草地

**Camera Movement:** Extreme pull-back / continuous zoom out with accelerating speed.

**Physics/Details:** 红色复古波普风"BOOM"爆炸贴纸突然出现、织物褶皱纹理显现

**Visual Bible:** 霓虹蓝、艳丽红 + 自由女神青绿色 + 背景米色织物色

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 21:9
duration_s: 4-6
physics_simulation: fabric texture, rapid zoom motion
consistency_guard: mixed media aesthetic, pop art style, consistent Statue of Liberty
negative: blurry face, messy UI, low resolution, shaky camera, static background
```

---

## 13. 雨中停车场 - 战场穿透

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [two teenagers in streetwear] performing [handing money to floating AR interface, fast dolly in through interface transitioning to gritty battlefield with soldiers].

**时空演变:**
- **Start:** 两名青年背对镜头，观察悬浮的白色AR菜单，鼠标光标在界面上移动
- **Action:** 左侧青年侧头，右侧青年拿出美钞递向前方的UI界面，镜头加速向UI界面推进
- **End:** 镜头完全穿透UI界面，画面稳定，主体变为全副武装的士兵在战火纷飞的荒原上躬身奔跑

**Camera Movement:** Fast dolly in with match cut/zoom through transition, accelerating to high speed.

**Physics/Details:** 穿透UI界面产生的径向模糊（Motion Blur）、潮湿地面的反射

**Visual Bible:** 冷灰色调，雨后城市的青灰色与柏油路反光，战场荒地的土褐色与硝烟灰

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 21:9
duration_s: 5-8
physics_simulation: motion blur, wet ground reflection, AR interface transparency
consistency_guard: hyper-realistic, consistent character transition, video game cutscene style
negative: low quality, cartoon, bright colors, sunny, slow movement, bad anatomy
```

---

## 14. 战场POV - 士兵突进

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [modern soldiers in tactical gear] performing [walking, aiming rifles with intermittent muzzle flashes, through smokey battlefield].

**时空演变:**
- **Start:** 初始视角，近景士兵准备举枪，左侧地面焦黑，远景烟雾较淡
- **Action:** 中景士兵开火，产生明显的黄色枪口闪光，镜头向左平移，背景中的黑烟位置左移
- **End:** 镜头仰角提升，重点转向地平线上的多处起火点和弥漫的浓烟

**Camera Movement:** Handheld tracking / First-person shooter perspective with medium pace and rhythmic shakes.

**Physics/Details:** 黄色枪口闪光、广角镜头畸变（鱼眼效果）、动态模糊

**Visual Bible:** 冷调灰度 + 焦土褐，高噪点、低反差、动态模糊

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 21:9
duration_s: 5-8
physics_simulation: gunfire muzzle flash, smoke particle dynamics
consistency_guard: gritty combat footage, wide-angle lens distortion, consistent soldier gear
negative: cartoon, vibrant colors, static camera, clean environment, peaceful, bright sunshine, low resolution
```

---

## 15. 新闻播报嘴部 - 模拟故障

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [news anchor's mouth] performing [aggressive speaking with CRT monitor glitch effect, thick horizontal scanlines, saturated RGB split, 90s analog broadcast aesthetic].

**时空演变:**
- **Start:** 嘴部半张，扫描线清晰，重心在下半脸正中
- **Action:** 嘴部闭合甚至做出吞咽或紧抿动作，随后突然张大呈现剧烈的说话/呐喊状
- **End:** 嘴部动态演变，伴随画面亮度的轻微闪烁，色散现象随动作剧烈程度增加

**Camera Movement:** Extreme close-up with micro-jitter, static station.

**Physics/Details:** 嘴部剧烈开合动作、夸张的口型变化、下颌肌肉抽动

**Visual Bible:** 高饱和度深蓝色背景 + 肤色 + 极高亮度的红绿边缘色散

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 21:9
duration_s: 2-3
physics_simulation: CRT scanline effect, video signal interference
consistency_guard: VHS aesthetic, 90s analog broadcast style, consistent mouth movement
negative: clean image, high definition, 4k, smooth skin, cinematic lighting, slow motion, wide shot
```

---

## 16. 城市塌陷 - 宏观毁灭

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [city section] performing [collapsing into rectangular abyss with volumetric dust, followed by terrified people running for lives on dusty street].

**时空演变:**
- **Start:** 高空俯瞰，城市中心出现亮蓝色矩形目标框，光标移动锁定
- **Action:** 矩形框内的建筑物开始物理陷落，边缘产生初级烟尘，中心区域完全下沉形成巨大的矩形地洞
- **End:** 视角突变，地面低角度拍摄，人群迎面跑来，背景是垂直下落的结构与遮天蔽日的尘幕

**Camera Movement:** Dolly in then fast tracking, accelerating from top-down to eye-level horizontal.

**Physics/Details:** 建筑物物理陷落、烟浪向外扩散、动态模糊

**Visual Bible:** 冷灰色调 + 亮蓝色虚线框（UI Overlay）+ 灰土色，胶片颗粒感

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 21:9
duration_s: 8-10
physics_simulation: structural collapse physics, volumetric dust simulation
consistency_guard: hyper-realistic Hollywood blockbuster, consistent building destruction
negative: static, bright colors, sunny day, cartoon, stable camera, peaceful
```

---

## 17. 人群消失 - 数字擦除

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [desolate city street] performing [large crowd of people disappearing through digital wipe effect to reveal abandoned cars and ruins].

**时空演变:**
- **Start:** 人群密集，向画面深处流动，两侧可见撞毁的车辆和建筑碎片
- **Action:** 画面底部出现蓝色矩形选框特效，UI界面出现在左上角，人群开始变得稀疏或呈现半透明消失状态
- **End:** 人群被完全移除，画面焦点转向静止的废弃轿车和路边堆积如山的瓦砾

**Camera Movement:** Slow dolly in, forward along the street axis.

**Physics/Details:** 数字擦除效果、人群逐渐淡出/消失

**Visual Bible:** 极低饱和度的灰冷色调，弥漫的灰色浓烟、废墟瓦砾的粗糙质感

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 2.35:1
duration_s: 8-10
physics_simulation: digital wipe effect, crowd fading
consistency_guard: apocalyptic realism, volumetric fog, consistent city ruins
negative: bright colors, sunshine, happy people, clean streets, vibrant, saturation, cartoon, smooth skin
```

---

## 18. F-22编队 - 机壳撕裂

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [F-22 Raptor formation] performing [flying above clouds with cockpit POV tilting horizons, ending with extreme close-up of fuselage skin tearing to reveal internal mechanical structures].

**时空演变:**
- **Start:** 侧后方跟随镜头，展示F-22战斗机编队穿梭在浓厚的积云中
- **Action:** 视角切换至单机斜后方，背景云海更为开阔，第一人称视角展示座舱仪表盘随战机侧翻而倾斜
- **End:** 极近距离特写，蒙皮完全撕裂，显露出精密的机身骨架和管线结构

**Camera Movement:** Follow shot to extreme close-up, fast and dynamic, forward zoom to right wing root.

**Physics/Details:** 大G力机动、机壳撕裂、机械结构暴露

**Visual Bible:** 冷蓝色调 + 纯白云海 + 战机金属灰，拉丝铝合金质感

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 21:9
duration_s: 6-8
physics_simulation: aircraft aerodynamics, structural failure simulation
consistency_guard: photorealistic military documentary, consistent aircraft details
negative: cartoon, stylized, slow motion, blurry cockpit, static, low-detail mechanics
```

---

## 19. 飞行员座舱 - 横滚机动

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [fighter pilot in cockpit] performing [switching to exterior view of F-22 Raptor performing high-speed barrel roll above clouds with digital HUD overlay].

**时空演变:**
- **Start:** 机舱内视角，飞行员佩戴氧气面罩和头盔，头部有微小摆动，背景窗外可见划痕和深蓝色天空
- **Action:** 视角转到机舱外，F-22战斗机出现在画面中心，开始向右上方倾斜
- **End:** 战机进行大角度横滚运动，画面出现数码三角几何扫描线，背景云层快速掠过

**Camera Movement:** POV to third-person chase view, rapid acceleration and rotation.

**Physics/Details:** 大角度横滚运动、数码UI叠加、极端运动模糊

**Visual Bible:** 冷静的灰蓝色调，深海军蓝（天空）、浅灰色（战机涂层/云层）、军绿色（飞行服）

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 21:9
duration_s: 4-6
physics_simulation: barrel roll dynamics, extreme motion blur
consistency_guard: hyper-realistic, military documentary style, consistent aircraft
negative: cartoon, blurry, static, bright colors, passenger plane, slow motion, low resolution
```

---

## 20. 巨型奶牛漫步 - 超现实都市

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [gargantuan black-and-white Holstein cow named Lily] performing [walking ponderously through hyper-realistic New York City street with massive hooves stepping over cars and buildings].

**时空演变:**
- **Start:** 初始全景，巨型奶牛侧身横跨街道，鼠标指针指向其背部，上方有悬浮UI
- **Action:** 奶牛开始迈步，前肢抬起并落地，相机缓慢靠近，下方出现红色新闻跑马灯
- **End:** 镜头角度进一步抬升并向中心收拢，视觉焦点锁定在奶牛穿越摩天大楼窄缝的过程

**Camera Movement:** High-angle chasing shot, slow and steady, moving forward and slightly tilting down.

**Physics/Details:** 巨大蹄子跨越街道、尾巴晃动、身体随步伐的沉重晃动

**Visual Bible:** 冷调城市灰 + 建筑砖红 + 奶牛黑白色，DDTV新闻跑马灯叠加

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 21:9
duration_s: 8-10
physics_simulation: massive creature physics, hoof impact dynamics
consistency_guard: photorealistic surrealism, consistent cow scale, high-detail city model
negative: cartoon, bright colors, drawing, anime, small cow, blurry buildings, static
```

---

## 21. 巨型奶牛漫步（重复）

*注：此镜头与镜头20内容相同*

---

## 22. 士兵投降与转身 - 环绕运镜

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [two soldiers in battlefield] performing [arc shot around them, one surrendering with hands up then turning around to walk away together with the other].

**时空演变:**
- **Start:** 对峙开始，左侧士兵高举双手，神情高度紧张（张嘴呼吸）
- **Action:** 镜头开始左移，左侧士兵表现出极度的不安，近处士兵的身影逐渐遮挡画面中心
- **End:** 原本投降的士兵放下双手，转过身去，镜头完全移动到两人身后，呈现双人并肩走向远方的背影

**Camera Movement:** Arc shot / orbital movement, steady medium pace, counter-clockwise around subjects.

**Physics/Details:** 举手投降的动作转变、身体转向的流畅性

**Visual Bible:** 低饱和度莫兰迪色调，冷灰色、军绿色与荒野土褐色

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 2.35:1
duration_s: 8-10
physics_simulation: character movement animation, smooth camera orbit
consistency_guard: hyper-realistic war movie aesthetic, consistent tactical gear
negative: cartoon, bright colors, sunshine, smiling, clear sky, low-res, shaky cam
```

---

## 23. 悬浮人影 - 战场迷雾

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [two soldiers in camouflaged tactical gear] performing [looking at many mysterious humanoid figures floating in thick foggy sky with digital targeting UI scanning, one soldier aiming rifle].

**时空演变:**
- **Start:** 双人背影，迷雾中仅见一个微弱黑影
- **Action:** 镜头后移，迷雾中出现更多黑影，黑影外部出现数字化定位框，左侧士兵开始做出举枪瞄准的动作
- **End:** 更多的黑影在天空中排列出现，左侧士兵保持瞄准姿态，镜头持续缓慢后拉

**Camera Movement:** Slow dolly out, backward movement with steady pace.

**Physics/Details:** 浓雾效果、悬浮人影的静止状态、数字化定位框的动态扫描

**Visual Bible:** 冷色调 + 迷彩绿/大地棕，高饱和度缺失，以灰、白、暗绿为主

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 21:9
duration_s: 8-10
physics_simulation: volumetric fog, floating figures physics
consistency_guard: tactical sci-fi, horror realism, consistent soldier appearance
negative: vibrant colors, sunny, smiling, fast movement, explosion, low-res, cartoon
```

---

## 24. 女官发言与金蚁 - 蒙太奇

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [middle-aged female official speaking] performing [solemnly at podium then sudden cut to macro extreme close-up of golden ant crawling on legal documents].

**时空演变:**
- **Start:** 人物中景，闭口凝视，背景徽章清晰可见
- **Action:** 人物开口说话，神情焦虑，带有明显的口型变化，闭眼沉思
- **End:** 视角骤降，极特写镜头对准一只金色蚂蚁在纸张边缘移动，背景中人物手部呈现模糊的散景

**Camera Movement:** Static to macro tracking with rhythmic transition, sudden focal point shift.

**Physics/Details:** 蚂蚁爬行的微小动作、人物说话的面部肌肉运动

**Visual Bible:** 冷灰色调为主，点缀性的金色（蚂蚁）和深灰色（西装）

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 2.35:1
duration_s: 8
physics_simulation: ant movement simulation, facial expression dynamics
consistency_guard: hyper-realistic film, political thriller style, consistent textures
negative: cartoon, bright colors, blurry background (first part), distorted face, fast camera shake
```

---

## 25. 金蚁爬行与女性侧脸 - 微观对比

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [golden ant on dark wood desk] performing [crawling next to pen, followed by close-up profile of serious middle-aged woman with subtle facial expressions].

**时空演变:**
- **Start:** 微距视角，笔尖即将落纸，蚂蚁在焦外缓慢爬向纸张边缘
- **Action:** 焦点锁定在金色蚂蚁上，它爬到了圆形的木纹缝隙处，笔尖移开，蚂蚁继续爬行
- **End:** 场景突跳至中年女性侧脸，通过微小的口型变化表现内心的挣扎或倾听

**Camera Movement:** Fixed macro (first part) / side profile close-up (second part), stationary camera with subject movement.

**Physics/Details:** 蚂蚁触角的清晰运动、女性嘴唇的细微开合

**Visual Bible:** 深木色/冷灰蓝 + 金色主体（蚂蚁）+ 肤色

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 2.39:1
duration_s: 6-8
physics_simulation: macro insect movement, subtle facial animation
consistency_guard: hyper-realistic, cinematic film stock, extreme detail
negative: fast motion, bright colors, blurry skin, cartoonish, handheld shake
```

---

## 26. 男性眼神 - 模拟电视

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [stern middle-aged man's eyes] performing [subtle eyebrow movement with VHS glitch style, heavy scanlines, 1980s news broadcast aesthetic].

**时空演变:**
- **Start:** 双眼居中，视线平视，扫描线清晰可见
- **Action:** 镜头微弱下移，眉头开始微微隆起，左侧耳朵轮廓边缘随镜头微移露出更多细节
- **End:** 构图向左侧推移，画面重心由双眼平衡转向右侧眼部的凝视，图像噪点随时间波动

**Camera Movement:** Static with subtle handheld wobble, slow and steady.

**Physics/Details:** 眉头微微隆起、瞳孔微弱震颤

**Visual Bible:** 暖肤色 + 阴影处的深褐色 + 左侧边缘微弱的蓝绿霓虹光

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 21:9
duration_s: 3-4
physics_simulation: CRT scanline effect, video signal interference
consistency_guard: retro-analog, cyber-noir imagery, consistent face
negative: HD, 4K, sharp focus, smooth skin, cartoon, 3D render, bright sunny lighting
```

---

## 27. 发光路板铺设 - 城市建设

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [high-tech glowing solar road panels] performing [being installed by engineers, rapid vertical pull-back to expansive aerial bird's eye view of complete city intersection covered in LED grids].

**时空演变:**
- **Start:** 近景，工人半蹲调整发光路地板，焦点在手部和地板接触位置
- **Action:** 镜头开始拉升，背景中的军绿色工程车和街道环境变得明显，极近距离特写地板表面的LED点阵
- **End:** 镜头急速拉升并模糊，最终全景展示完美的十字路口布局，发光板呈规则几何排列

**Camera Movement:** Drone pull-back climb with accelerated speed, vertical upwards and backwards.

**Physics/Details:** LED点阵的微光、模块化地砖的拼接

**Visual Bible:** 冷灰/深蓝路面 + 工程荧光黄（工人制服）+ 警示红（巴士/路边元素）

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 21:9
duration_s: 5-8
physics_simulation: urban infrastructure, LED grid physics
consistency_guard: photorealistic cinematic documentary, geometric precision
negative: blurry hands, messy layout, organic shapes, chaotic traffic, low resolution
```

---

## 28. 巴黎无人机群 - 扭曲铁塔

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [fleet of black industrial drones] performing [flying over Paris with eerily twisted and spiraling Eiffel Tower in background, transitioning to extreme close-up of drone's mechanical body].

**时空演变:**
- **Start:** 全景确立场景，三架无人机队形稳定，扭曲的埃菲尔铁塔位于视觉中心
- **Action:** 主镜头开始锁定右侧最大的无人机，主体在画面中占比迅速增大，景深发生变化
- **End:** 极近距离特写，展现无人机机身的Logo标识、红色指示灯及复杂的机械云台结构

**Camera Movement:** Forward push-in / tracking, steady and fast, towards drone on the right.

**Physics/Details:** 埃菲尔铁塔诡异的螺旋状扭曲、无人机的悬停稳定性

**Visual Bible:** 灰蓝色调 + 昏黄余晖，低饱和度的都市背景与深黑色的金属无人机对比

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 2.35:1
duration_s: 4-6
physics_simulation: drone flight dynamics, surreal distortion effect
consistency_guard: photorealistic sci-fi film aesthetic, consistent drone details
negative: straight Eiffel Tower, bright daylight, cartoon, low resolution, shaky camera, blurry textures
```

---

## 29. 迪拜无人机群 - 高空物流

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [black industrial hexacopter drones] performing [pulling back from carbon fiber texture close-up to cinematic wide aerial view of fleet flying over Dubai skyline with Burj Khalifa].

**时空演变:**
- **Start:** 极近景，焦点在于机身的碳纤维检查纹理，背景完全模糊
- **Action:** 镜头快速后退，主体无人机轮廓显现，迪拜塔及背景建筑群开始进入模糊的视域
- **End:** 大远景，画面稳定，展示庞大的无人机群在摩天大楼间有条不紊地飞行

**Camera Movement:** Zoom out / pull back, fast start to steady glide, backward and upward.

**Physics/Details:** 碳纤维纹理细节、无人机悬停稳定性、高空雾霾效果

**Visual Bible:** 冷调灰蓝 + 工业金属黑 + 城市沙土冷色调

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 2.39:1
duration_s: 5-8
physics_simulation: drone swarm dynamics, atmospheric perspective
consistency_guard: hyper-realistic, sleek industrial design, vast scale
negative: shaky camera, low quality, cartoon, organic shapes, messy wires, bright saturated colors
```

---

## 30. 奶牛吊装 - 城市上空

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [Holstein cow] performing [being hoisted by heavy ropes high above modern city skyline, surreal cinematic movie scene].

**时空演变:**
- **Start:** 微距视角，聚焦眼球，瞳孔中映射出微弱的城市轮廓，湿润的结膜质感
- **Action:** 中远景切换，奶牛头部和上半身入画，粗重的吊绳出现在身体两侧，背景出现灰蒙蒙的天空
- **End:** 全景建立，奶牛全身入画，下方开始出现密集的城市高楼建筑群，左侧前景出现工作人员

**Camera Movement:** Extreme zoom out with fast acceleration, backward movement.

**Physics/Details:** 粗重绳索的张力、奶牛悬空的轻微摇晃

**Visual Bible:** 低饱和度工业色调，冷灰色天空 + 黑白奶牛 + 灰调建筑群 + 工作人员高亮荧光黄

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 2.35:1
duration_s: 4-6
physics_simulation: rope tension physics, suspended object dynamics
consistency_guard: high-end cinematography, photorealistic, 8k
negative: cartoon, 3D render, low quality, cheerful, bright colors, sunny, wings on cow
```

---

## 31. 无人机吊装与立方体城市 - 科幻转场

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [supervisor with walkie-talkie on rooftop] performing [sideways tracking shot, swarms of industrial drones lifting massive LED panels, cutting to girl opening curtains to grid-patterned minimalist cityscape].

**时空演变:**
- **Start:** 焦点在于指挥员侧脸，背景中巨大的牛形装置和远处的摩天大楼
- **Action:** 镜头向右后方平移，露出更多无人机群及悬挂的黑色屏幕方阵
- **End:** 场景突变转为室内，人物从黑暗中拉开窗帘，窗外的城市建筑物表面布满白色的网格发光点

**Camera Movement:** Sideways tracking / horizontal pan, steady medium pace, left to right.

**Physics/Details:** 无人机群吊运LED面板的协同运动、窗帘拉开的布料物理

**Visual Bible:** 低饱和度冷色调 + 工业黄（荧光背心），青灰色与朦胧的白

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 2.35:1
duration_s: 8-10
physics_simulation: drone swarm coordination, fabric curtain physics
consistency_guard: dystopian sci-fi, hyper-realistic, consistent modular buildings
negative: sunny, bright colors, cheerful, retro, messy textures, cartoon
```

---

## 32. 士兵山脊行进 - 浓雾迷途

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [two special forces soldiers] performing [transitioning from side close-up to high-angle overhead view, walking on narrow rocky mountain ridge surrounded by thick dense fog].

**时空演变:**
- **Start:** 侧面平视，左侧士兵看向前方，右侧士兵侧身持枪，背景为虚化的浓雾
- **Action:** 镜头开始小幅度俯视调整，左侧士兵头部微低，身体重心前倾准备起步
- **End:** 镜头猛然升至高空，视角变为俯瞰，两名士兵呈纵队/并肩行走在极窄的乱石山脊上

**Camera Movement:** High-angle crane shot / pull-out zoom, medium-fast, backward and upward.

**Physics/Details:** 浓雾的流动感、崎岖山脊的行走动态

**Visual Bible:** 冷调青灰色 + 迷彩色，漫反射柔光，浓雾造成的低对比度

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 2.35:1
duration_s: 5-8
physics_simulation: volumetric fog, rugged terrain walking
consistency_guard: hyper-realistic war film aesthetic, highly detailed textures
negative: sunny, bright colors, smiling, clear sky, urban, civilian clothes, low quality
```

---

## 33. 嘴部扫描到MSG球体 - 模拟转场

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [glitchy VHS extreme close-up of man's talking mouth] performing [panning right with TV scanlines, transitioning to high-angle night shot of Las Vegas MSG Sphere glowing with giant yellow emoji smiley face].

**时空演变:**
- **Start:** 镜头持续向右移动，人物的嘴唇从画面中心通过并伴随张合动作，背景地球Logo产生位移
- **Action:** 扫描线噪声始终贯穿，嘴巴快速张合
- **End:** 视觉突变切换到拉斯维加斯全景，中心是巨大发光笑脸，眼睛眯起

**Camera Movement:** Horizontal pan follow by hard cut, medium and steady, rightwards.

**Physics/Details:** 嘴唇的快速张合动作、笑脸表情的细微变化

**Visual Bible:** 高饱和度RGB电子色调（蓝、白、肤色）+ 深邃的夜景金黄色与黑色底色

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 21:9
duration_s: 4-5
physics_simulation: CRT scanline effect, digital display physics
consistency_guard: glitch art, vaporwave, cyber-realism, consistent face structure
negative: natural sunlight, clear skin, HD clean image, 3D animation style, bright daytime
```

---

## 34. 拉斯维加斯蓝光爆发 - 能量脉冲

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [giant glowing blue orb activating in dark city] performing [followed by close-up of boy in goggles peeking through blinds, ending with satellite view of blue energy pulse spreading through city streets].

**时空演变:**
- **Start:** 漆黑的城市背景仅有微弱灯光
- **Action:** 巨大的球体被激活，释放出强烈蓝色光域照亮周围建筑，转场至室内少年戴护目镜窥视
- **End:** 视角跃升至高空，展现蓝色能量沿街道网络呈放射状迅速扩散

**Camera Movement:** Multi-shot transition with rapid switching and extreme pull-out.

**Physics/Details:** 蓝色光域的体积光扩散、能量脉冲的涟漪效果

**Visual Bible:** 荧光蓝 + 深邃黑 + 城市路网的暖黄光影

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 2.35:1
duration_s: 8-10
physics_simulation: energy pulse propagation, volumetric lighting
consistency_guard: modern sci-fi, consistent blue energy motif
negative: daylight, bright, cheerful, low resolution, blurry faces, cartoon, sunny
```

---

## 35. 卷发男子仰望 - 蓝光脉冲

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [curly-haired man's back] performing [looking up at night horizon, massive glowing electric blue pulse light suddenly erupts and illuminates behind dark silhouette trees].

**时空演变:**
- **Start:** 特写背影，人物微微抬头，背景为灰暗的地平线
- **Action:** 人物背部轮廓被微弱勾勒，背景下方隐约有白光透出，突变后背景呈现亮蓝色带状强光
- **End:** 强光达到峰值，蓝色光晕在画面中扩散，更宽广的视野视图

**Camera Movement:** Dolly back / zoom out, slow and steady, straight backward.

**Physics/Details:** 蓝色光域的突然爆发和扩散

**Visual Bible:** 午夜蓝 + 霓虹蓝 + 阴影黑，强烈的背光效果

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 2.35:1
duration_s: 4-5
physics_simulation: light burst dynamics, atmospheric scattering
consistency_guard: Snyder-esque cinematography, realistic, sci-fi noir
negative: daylight, bright face, smiling, blurred person, low resolution, messy colors
```

---

## 36. 山脉蓝光到监控室 - 危机响应

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [mysterious glowing electric blue light spreading over dark mountain] performing [then cutting to vast industrial factory interior, ending with back view of female commander looking at massive control room monitors].

**时空演变:**
- **Start:** 显示山脉异象，蓝色光斑逐渐变亮并扩张
- **Action:** 转场至工厂内部，视角平视可见工人走动与大型机械设备
- **End:** 黑场过渡后，主体出现背光剪影，前景为监控设备，背景为弧形巨幕

**Camera Movement:** Slow push-in / cross-cut, forward/center, slow and steady.

**Physics/Details:** 蓝色光域的脉动扩散

**Visual Bible:** 电离蓝色 + 工业土黄色 + 深黑色背景

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 21:9
duration_s: 8-10
physics_simulation: atmospheric light diffusion, volumetric glow
consistency_guard: modern sci-fi / industrial noir, massive scale
negative: cartoon, low quality, bright daylight, cheerful, static, blurry faces
```

---

## 37. 落地窗前双人 - 城市夜景

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [man and woman silhouettes] performing [standing in front of massive floor-to-ceiling window overlooking glowing blue metropolitan night city, slow rack focus].

**时空演变:**
- **Start:** 高亮监控大屏，女性背影清晰，充满科技压抑感
- **Action:** 光线骤降进入黑场过渡，模糊的双人背影出现处于极度虚焦状态
- **End:** 焦点逐渐清晰，背光加强，城市夜景蓝调增强，双人并肩而立

**Camera Movement:** Fixed camera with pulling focus, slow and progressive, stationary.

**Physics/Details:** 从虚焦到实焦的平滑过渡、城市灯光的Bokeh虚化效果

**Visual Bible:** 冷蓝色调 + 琥珀色背光 + 沉稳黑

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 21:9
duration_s: 8-10
physics_simulation: depth of field transition, city light bokeh
consistency_guard: modern noir / dramatic cinema, high contrast
negative: bright daylight, sunny, front view, face, cartoon, colorful, chaotic, blurry foreground after focus
```

---

## 38. 伦敦夜景到蓝屏 - 数字崩溃

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [London city lights at night] performing [cinematic zoom-out transitioning into digital blue screen of death with white text "We need to talk.", glitch art style].

**时空演变:**
- **Start:** 泰晤士河岸实景航拍，蓝色光斑在城市中心蔓延
- **Action:** 视角转为垂直俯视，城市街道变成发光的金色网格，蓝色区域呈几何状扩大
- **End:** 完全进入纯蓝色屏状态，浮现简短的白色排版文字

**Camera Movement:** Zoom out and tilt down, accelerated transition, vertical.

**Physics/Details:** 城市灯光到数字矩阵的形变过渡

**Visual Bible:** 午夜蓝 + 琥珀金 + 荧光蓝（数字故障色）

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 21:9
duration_s: 6-8
physics_simulation: digital pixel sorting, urban to digital transition
consistency_guard: surrealist digital surveillance, retro-tech aesthetics
negative: daylight, sunny, clouds, low resolution, blurry text, messy colors
```

---

## 39. 蓝屏到新生儿 - 希望诞生

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [blue screen of death with text] performing [cinematic zoom-out over Earth at night, transitioning to close-up of newborn baby held by surgeon in dim hospital].

**时空演变:**
- **Start:** 特写蓝屏界面，白色文字居中
- **Action:** 镜头向后拉露出屏幕边缘及后方地球夜景，视觉进一步扩张多个蓝色窗口在地球上空呈网格状分布
- **End:** 突变切场新生儿特写，光线聚焦在婴儿面部，医护人员戴口罩的侧影与产房内蓝色低照明环境

**Camera Movement:** Extreme zoom-out / quick pull-back, fast to sudden cut.

**Physics/Details:** 婴儿细微抽动、医护人员手部动作

**Visual Bible:** 科技蓝 + 极夜黑 + 肤色暖调及暗绿

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 2.35:1
duration_s: 8-10
physics_simulation: space view scaling, soft volumetric light
consistency_guard: dystopian sci-fi meets tender documentary, symbolic contrast
negative: cartoon, sunny, bright day, cheerful, low quality, blurry face
```

---

## 40. 城市灯光到星空 - 箭头对话

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [glowing city lights at night] performing [tilting up to vast starry sky, cursor blinking and typing a big "Hi" in the air, Makoto Shinkai anime style].

**时空演变:**
- **Start:** 斜向构图，右下角可见密集的城市夜景灯光
- **Action:** 镜头上移，地表灯光逐渐移出画面底缘，星空比例占据主导，白色发光轨迹流星划入
- **End:** 光标跳动，输入一个大写的"HI"，表明箭头操作者正在与人类交流

**Camera Movement:** Tilt up and pan, medium fast, diagonal upward.

**Physics/Details:** 星光的闪烁、流星的轨迹、光标的跳动

**Visual Bible:** 深蓝色 + 极光绿/荧光白 + 纯白，新海诚式唯美天文质感

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 2.35:1
duration_s: 4-5
physics_simulation: star twinkling, meteor trail animation
consistency_guard: hand-drawn anime aesthetic, Makoto Shinkai style
negative: static, blurry, low resolution, daytime, sun, low-quality stars, messy foreground, realistic photography
```

---

## 41. UI确认到现实操作 - 虚实过渡

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [minimalist grey digital confirmation window] performing [mouse cursor moving down, sudden jump cut to realistic close-up of hands operating computer mouse and mechanical keyboard].

**时空演变:**
- **Start:** 纯黑背景，鼠标光标出现
- **Action:** 画面中心弹出白色圆角对话框显示"crow"及确认信息，光标由上方平滑移动至对话框底部边缘
- **End:** 视觉跳跃切换至现实特写镜头，手部皮肤纹理可见，背景为游戏画面

**Camera Movement:** Static (fixed camera), instantaneous transition.

**Physics/Details:** 鼠标光标的平滑移动、手指点击和周边设备操作

**Visual Bible:** 黑/白/灰（UI部分）+ 温暖家居色调（现实部分）

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 21:9
duration_s: 4-5
physics_simulation: cursor movement animation, hand gesture physics
consistency_guard: UI design / cinematic realism, clean interface
negative: blurry, messy room, low resolution, multiple cursors, distorted fingers, bright daylight
```

---

## 42. 眼球到RTS游戏 - 虚拟沉浸

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [macro close-up of human eye] performing [reflecting video game, transitioning to top-down retro 2.5D RTS game scene with Roman legion soldiers moving on grass].

**时空演变:**
- **Start:** 瞳孔内反射光位置发生轻微位移，眼睑有细微颤动，深度焦距锁定在角膜
- **Action:** 画面完全切换至游戏界面，士兵方阵被白色选择框包围
- **End:** 鼠标点击虚线框出现，方阵整体开始向右上方平稳移动

**Camera Movement:** Macro zoom-in to screen transition, slow zoom then steady scrolling.

**Physics/Details:** 眨眼动作、像素方阵的移动

**Visual Bible:** 冷调肤色（蓝紫色调）+ 游戏高饱和度绿地与红甲士兵

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 2.35:1
duration_s: 8-10
physics_simulation: eye reflection dynamics, isometric grid movement
consistency_guard: hyper-realistic (eye) / 16-bit pixel art (game)
negative: blurry eyes, modern 3D graphics, distorted UI, floating limbs, messy pixels
```

---

## 43. 士兵躺平 - 打破第四面墙

### 动态叙事脚本 (Generative Script)
**Final Prompt (EN):**
A continuous shot showing [lone pixel art soldier] performing [standing to waving to sitting to lying flat on green grass, white speech bubble appearing above head with text, static isometric top-down gameplay view].

**时空演变:**
- **Start:** 主体士兵被选中（有选中框），处于站立待命状态
- **Action:** 出现对话框"就没人看见那有个箭头吗？"，士兵动作由站立转为举手示意
- **End:** 士兵完全平躺在地，对话框变为"我再也不想跟着那个箭头跑了"，画面完全黑转显示"ARROW"软件界面

**Camera Movement:** Static / fixed camera, zero movement.

**Physics/Details:** 像素小人从站立到挥手到下蹲到彻底躺平的动作转换

**Visual Bible:** 草绿色（地面）+ 鲜红色（士兵方阵）+ 灰褐色（UI框架），16位色深视觉

---

### 生成参数 (Generation Params)
```yaml
aspect_ratio: 21:9
duration_s: 8-10
physics_simulation: pixel sprite animation, 2D isometric movement
consistency_guard: 16-bit retro game / pixel art, high-definition pixel icons
negative: 3D render, realistic photography, blurry, smooth gradient, modern graphics, cinematic lighting
```

---

## 附录：统一负面提示词汇总

```yaml
common_negative:
  - morphing
  - disappearing objects
  - extra limbs
  - extra fingers
  - logic errors
  - defying gravity
  - cartoon
  - low resolution
  - blurry
  - messy
  - bright sunny
  - cheerful
  - stable camera (when motion is intended)
```

---

*文档生成日期: 2026-02-24*
*总计镜头数: 43*
*格式: ARROW 视频 AI 提示词模板 v1.0*

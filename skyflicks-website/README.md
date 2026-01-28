# SKYFLICKS 企业网站

这是一个基于提供的演示幻灯片创建的SKYFLICKS企业静态网站。

## 项目结构

```
skyflicks-website/
├── assets/         # 图片资源（把 Hero 背景图放这里）
├── video/          # 视频资源（竖屏9:16视频文件）
├── index.html      # 主HTML文件
├── styles.css      # 样式文件
├── script.js       # JavaScript交互文件
└── README.md       # 项目说明文件
```

## 功能特点

- **响应式设计**: 适配桌面、平板和移动设备
- **现代化UI**: 深色主题，符合企业形象
- **平滑动画**: 滚动时的淡入动画效果
- **交互效果**: 卡片悬停效果和图表动画

## 包含的内容

网站包含以下所有幻灯片内容：

1. **Hero Section** - SKYFLICKS主视觉介绍
2. **Video Showcase Section** - 竖屏9:16视频展示区
3. **What Are Micro-Dramas?** - 微短剧定义和市场数据
4. **Win-Win Value Proposition** - 三方价值主张
5. **The SKYFLICKS Entertainment Model** - 娱乐模式流程
6. **Benefits to Airlines** - 对航空公司的四大好处
7. **Cost Comparison** - 成本对比和VR眼镜特点
8. **Why Micro-Dramas Attract Passengers** - 吸引乘客的原因
9. **Beyond the Cabin** - 地面延续服务
10. **Partnership Models** - 三种合作模式
11. **Contact** - 联系信息

## 使用方法

1. 直接在浏览器中打开 `index.html` 文件
2. 将你上传的 SKYFLICKS 机舱背景图保存为 `assets/skyflicks-hero.jpg`（用于首页 Hero 背景）
3. 将你上传的 "Why Micro-Dramas Attract Passengers" 图片保存为 `assets/why-attract.jpg`（用于该板块左侧大图）
4. 将竖屏9:16比例的视频文件保存到 `video/` 文件夹中，命名为 `1.mp4` 和 `2.mp4`，用于视频展示区
5. 或使用本地服务器：
   ```bash
   # 使用Python
   python3 -m http.server 8000
   
   # 使用Node.js (需要安装http-server)
   npx http-server
   ```
6. 在浏览器中访问 `http://localhost:8000`

## 技术栈

- HTML5
- CSS3 (Grid, Flexbox, Animations)
- Vanilla JavaScript (Intersection Observer API)

## 浏览器支持

- Chrome (最新版本)
- Firefox (最新版本)
- Safari (最新版本)
- Edge (最新版本)

## 自定义

所有样式都在 `styles.css` 文件中，可以根据需要修改：
- 颜色主题
- 字体大小
- 间距和布局
- 动画效果

## 联系信息

- Email: info@skyflicks.io
- WeChat/LinkedIn: SKYFLICKS IFE Innovation

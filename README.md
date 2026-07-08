# Hello Codex

一个 AI 驱动的开发工具落地页 —— 展示 Codex 作为 Agent 化开发助手的产品形象。

## 概览

这是一个纯静态的品牌页面，包含：

- **英雄区** — 产品标语、版本状态、引导按钮
- **特性卡片** — 即时反馈、深度集成、多文件协作、可扩展、无限上下文、多模态
- **导航栏** — 桌面端行内展示，移动端折叠为全屏菜单
- **深色主题** — 微渐变背景、网格点阵、呼吸光晕

所有内容都打包在一个 `index.html` 文件中，无需构建工具或依赖。

## 本地预览

直接双击 `index.html` 在浏览器打开，或用任何静态服务器：

```bash
# Python
python3 -m http.server 8000

# Node.js
npx serve .
```

## 项目结构

```
hello-codex/
├── index.html    # 完整落地页（含样式与脚本）
└── README.md     # 本文件
```

## 技术栈

无 —— 纯 HTML + CSS + 少量原生 JavaScript。

- 字体：系统字体栈（SF Pro / Segoe UI / Roboto）
- 动画：纯 CSS keyframes
- 图标：内联 SVG
- 响应式：CSS media queries，无框架

## 许可

MIT

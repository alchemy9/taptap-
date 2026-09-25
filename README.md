# TapTap 官网复刻

一个基于 TapTap (https://www.taptap.cn) 首页设计的静态网页复刻项目，使用纯 HTML/CSS/JavaScript 实现，无任何框架依赖。

## 项目结构

```
taptap-clone/
├── taptap.html          # 主页面（单文件自包含）
├── assets/              # 图片资源
│   ├── game-*.jpg       # 游戏封面图（cover）
│   └── game-*-icon.jpg  # 游戏图标（icon）
├── README.md
└── .gitignore
```

## 功能特性

- **顶部导航栏**：TapTap Logo、游戏分类标签横向滚动、搜索框、登录按钮
- **Hero 轮播**：9 款游戏大图自动轮播，支持左右箭头切换和底部指示点
- **游戏卡片网格**：响应式布局（桌面 5 列 / 平板 3 列 / 手机 2 列）
- **交互效果**：分类标签切换、卡片 hover 悬浮、Toast 提示
- **深色主题**：还原 TapTap 官方深色视觉风格

## 本地运行

直接用浏览器打开 `taptap.html` 即可，无需构建工具或服务器。

```bash
# 或者用本地服务器
cd taptap-clone
python3 -m http.server 8080
# 访问 http://localhost:8080/taptap.html
```

## 技术栈

- 原生 HTML5 + CSS3 + JavaScript
- 无框架、无构建工具、无外部依赖
- 响应式设计（CSS Grid + Media Query）
- 轮播效果纯 JS 实现

## 说明

- 本项目仅用于学习和演示目的
- 所有游戏图片版权归 TapTap 及原游戏开发者所有
- 页面数据为静态演示数据，未接入真实 API

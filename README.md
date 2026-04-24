# LiveFilms 官网

LiveFilms（能拍胶片效果的 Live Photo）的官方介绍网站与隐私政策页面。

## 设计理念

- **极简主义**：大量留白，突出内容本质
- **暗色调**：纯黑背景，呼应胶片美学
- **零依赖**：HTML5 + CSS3 + 原生 JavaScript

## 文件结构

```
livefilms/
├── index.html          # 主页面（含 i18n 多语言）
├── privacy.html        # 隐私政策页面
├── css/
│   ├── style.css       # 全局样式
│   └── privacy.css     # 隐私政策页样式
├── js/
│   └── main.js         # 交互逻辑
└── README.md
```

## 本地预览

```bash
open livefilms/index.html
# 或
python3 -m http.server 8000 -d livefilms
```

## GitHub Pages

本仓库通过 GitHub Pages 部署，访问地址：
https://lfp1224.github.io/livefilms/

---

© 2026. Crafted with precision by LFP.

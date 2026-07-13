# 🎂 致 FLatWhite · 18 岁生日快乐

一个使用纯 HTML/CSS/JS 构建的液态玻璃风格生日祝福网页，献给最特别的你。
<img width="2538" height="1310" alt="image" src="https://github.com/user-attachments/assets/d47f53bd-f343-49e8-a7e9-9f236394a655" />


## ✨ 特色

- **液态玻璃设计**：采用磨砂玻璃拟态风格，配合星空粒子背景
- **星空画布**：Canvas 绘制的动态星空背景
- **照片回忆墙**：涵盖 2023-2025 年的精选照片集
- **五彩纸屑**：点击触发的彩色纸屑飘落动画
- **涟漪效果**：鼠标移动的水波纹交互
- **响应式设计**：适配桌面与移动设备
- **流畅动效**：使用弹性曲线和弹簧动画

-
  <img width="2533" height="1296" alt="屏幕截图 2026-07-13 133750" src="https://github.com/user-attachments/assets/e954ea1b-8be1-4bc9-a860-45b789c56065" />


## 📁 项目结构

```
.
├── index.html          # 主页面（单文件应用）
├── assets/
│   └── photos/         # 照片集
│       ├── 2023-*.jpg  # 2023 年回忆（8张）
│       ├── 2024-*.jpg  # 2024 年回忆（9张）
│       └── 2025-*.jpg  # 2025 年回忆（9张）
├── .gitignore
└── README.md
```

## 🚀 使用方式

直接在浏览器中打开 `index.html` 即可查看。

或使用任意静态服务器：

```bash
# Python
python -m http.server 8080

# Node.js (npx)
npx serve .
```

## 🎨 设计语言

| 元素 | 描述 |
|------|------|
| 背景 | 纯黑 + 星空粒子 Canvas |
| 容器 | 半透明玻璃态 + backdrop-filter 模糊 |
| 强调色 | `#bf5af2`（紫）、`#ff6ec7`（粉）、`#ffd60a`（金） |
| 字体 | SF Pro / PingFang SC / Microsoft YaHei |

## 📝 License

仅供个人使用，祝 FlatWhite 18 岁生日快乐 🎈

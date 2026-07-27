
# 🎨 卡通可爱风在线工作台 - 静态原型预览集合

> 一套高对比描边、温暖橙黄配色、圆润造型的在线工作台前端原型。像贴纸一样活泼，像工具一样好用。

![GitHub Pages](https://img.shields.io/badge/部署-GitHub%20Pages-blue?logo=github)
![静态站点](https://img.shields.io/badge/类型-静态%20HTML-green)
![无后端](https://img.shields.io/badge/后端-无需%20API-lightgrey)
![协议](https://img.shields.io/badge/协议-可自由使用-orange)

---

## 📖 这是什么？

这是一个 **前端界面原型合集**，展示了一个“卡通可爱风”的在线工作台会是什么样子。

你可以把它理解成：
- 🖥️ 一套 **网页版工作台** 的设计草图
- 🧩 6 个不同页面的 **可交互静态 Demo**
- 🎯 给设计师、开发者、产品经理的 **视觉参考包**

### 适合谁用？

| 角色 | 你能得到什么 |
|------|--------------|
| 🎨 设计师 | 完整的配色、字体、圆角、阴影规范 |
| 💻 前端开发 | 可直接运行的 HTML/CSS 代码，复制就能用 |
| 📋 产品经理 | 6 个常用工作台页面的布局参考 |
| 🎓 学习者 | 用 Tailwind CSS 写卡通风格界面的实战案例 |

---

## ✨ 项目亮点

- 🎨 **6 套完整页面原型**：创意空间、项目看板、任务列表、日历、工作台、首页
- 🌈 **统一设计语言**：温暖橙黄渐变 + 高对比描边 + 圆润造型
- 📱 **响应式布局**：桌面端 12 栏网格，移动端自动适配单栏
- 🚀 **零依赖部署**：纯静态文件，可直接托管到 GitHub Pages / Vercel / Netlify
- 🎯 **开箱即用**：无需构建步骤，无需 npm install，双击即可预览

---

## 🖼️ 页面预览

本项目包含 **6 个独立页面版本**，每个版本都是完整可运行的 HTML 文件：

| 版本 | 页面 | 说明 |
|------|------|------|
| `_1/code.html` | 🎪 创意空间 | 充满活力的工作台首页，包含欢迎区和快捷入口 |
| `_2/code.html` | 📁 项目看板 | Projects 页面，展示项目卡片和状态标签 |
| `_3/code.html` | ✅ 任务列表 | Tasks 页面，任务清单、进度条、筛选器 |
| `_4/code.html` | 📅 日历 | Calendar 页面，月视图、事件标记、日程管理 |
| `_5/code.html` | 🏠 工作台 | Workbench 主界面，侧边栏 + 内容区组合 |
| `_6/code.html` | 🏡 首页 | Home 页面，导航入口和功能概览 |
| `404/code.html` | 😿 404 页面 | 自定义错误页面，保持风格统一 |

> 💡 每个版本目录下都有 `screen.png` 预览图，不用打开浏览器也能快速查看效果。

---

## 🎨 设计系统详解

本项目采用名为 **Vibrant Workspace** 的设计系统，核心风格是“新粗野主义 + 卡哇伊美学”的结合。

### 色彩方案：日出光谱

整体采用温暖的橙黄色调，让界面看起来像 sunrise 一样充满能量。

| 颜色 | 色值 | 用途 |
|------|------|------|
| 🟠 Primary Orange | `#FF8F1C` | 主按钮、品牌色、关键高亮 |
| 🟡 Secondary Yellow | `#FFD23F` | 次要操作、背景装饰、庆祝状态 |
| ⚫ Deep Ink | `#333333` | 粗描边、正文文字、高对比元素 |
| ⚪ Neutral | `#F9F9F9` | 主背景色，比纯白更柔和护眼 |

**渐变规则**：主要使用 Primary Orange → Secondary Yellow 的 45° 渐变，用于 Hero 区域和重点元素。

### 字体组合

| 字体 | 用途 | 特点 |
|------|------|------|
| **Plus Jakarta Sans** | 标题、标签 | 圆润几何感，Bold/Extra Bold 让文字能“扛住”粗描边 |
| **Be Vietnam Pro** | 正文 | 技术感与温暖感平衡，适合长时间阅读 |

> ⚠️ 所有文字都不要用纯黑色，统一使用 Deep Ink `#333333`，视觉更柔和。

### 布局与间距

- **桌面端**：12 栏网格，最大宽度 1280px，间距 24px
- **移动端**：单栏布局，左右边距 16px
- **基础单位**：8px 网格系统，所有间距都是 8 的倍数
- **卡片内边距**：最小 16px，避免文字被粗边框“挤到”

### 立体与层次

不用模糊阴影，而是用“硬阴影”创造贴纸般的立体感：

- **描边**：所有可交互元素都有 2-3px 的 `#333333` 实线边框
- **硬阴影**：4px 偏移 + 极低模糊，像贴纸“跳”出页面
- **按压态**：点击时去掉阴影偏移 + 向下移动 2px，模拟物理按键

### 圆角规范

| 组件 | 圆角值 | 示例 |
|------|--------|------|
| 小元素（标签、复选框） | `0.25rem` | 圆角小标签 |
| 标准按钮、输入框 | `1rem` | 主要操作按钮 |
| 内容卡片、弹窗 | `1.5rem` | 大卡片容器 |
| 特殊按钮 | `9999px` | 胶囊形按钮 |

### 组件样式速查

| 组件 | 样式说明 |
|------|----------|
| 🔘 按钮 | 橙色背景 + 3px 深色描边 + 4px 硬阴影，文字粗体居中 |
| 🃏 卡片 | 白色背景 + 深色描边，顶部有对比色 Header |
| 📝 输入框 | 16px 内边距 + 2px 描边，聚焦时变 3px 并泛橙光 |
| 🏷️ 标签 | 胶囊形小容器，深色描边 + 明亮背景色 |
| 📊 进度条 | 粗圆角轨道 + 橙色填充，可加“糖果条纹”图案 |

---

## 🗂️ 项目结构

```
stitch_cartoon_style_online_workbench/
├── index.html                      # 预览导航入口，汇总所有版本
├── README.md                       # 项目说明（就是你现在看的这个文件）
├── .gitignore                      # Git 忽略规则
├── .github/
│   └── workflows/
│       └── pages.yml                # GitHub Actions 自动部署配置
├── _1/code.html + screen.png       # 版本 1：创意空间
├── _2/code.html + screen.png       # 版本 2：项目看板
├── _3/code.html + screen.png       # 版本 3：任务列表
├── _4/code.html + screen.png       # 版本 4：日历
├── _5/code.html + screen.png       # 版本 5：工作台
├── _6/code.html + screen.png       # 版本 6：首页
├── 404/
│   ├── code.html                   # 自定义 404 页面
│   └── screen.png                  # 404 页面预览图
├── vibrant_workspace/
│   └── DESIGN.md                   # 完整设计系统文档
└── cute_anime_lion_character_vibrant_workspace_mascot_cartoon_style_bold_black/
    └── screen.png                  # 吉祥物预览图
```

---

## 🚀 快速开始

### 方式一：双击直接打开（最简单）

直接双击 `index.html`，浏览器会打开预览导航页，点击即可查看各个版本。

### 方式二：本地服务器预览（推荐）

如果你需要模拟真实网站环境（比如避免某些 CDN 资源的跨域问题），可以用本地服务器：

```bash
# 如果你安装了 Node.js
npx serve .

# 或者用 Python
python -m http.server 8080
# Python 3 专用命令
python -m http.server 8080 --directory .
```

然后打开浏览器访问 `http://localhost:3000`（serve）或 `http://localhost:8080`（Python）。

### 方式三：部署到 GitHub Pages（永久在线）

本项目已经内置了 GitHub Actions 自动部署配置，推送到 `main` 分支后会自动部署。

**如果你会用 Git：**

```bash
# 1. 克隆仓库
git clone https://github.com/你的用户名/你的仓库名.git
cd stitch_cartoon_style_online_workbench

# 2. 推送到你的 GitHub 仓库
git remote set-url origin https://github.com/你的用户名/你的仓库名.git
git push -u origin main
```

**如果不会用 Git（手动上传）：**

1. 打开你的 GitHub 仓库页面
2. 把项目里的所有文件和文件夹上传进去
3. 进入 **Settings → Pages**
4. **Source** 选择 **GitHub Actions**
5. 等待 1-2 分钟，访问 `https://你的用户名.github.io/你的仓库名/`

> 📌 **注意**：上传时请保留目录结构，特别是 `.github/workflows/pages.yml` 必须上传，否则自动部署不会生效。

---

## 🛠️ 技术栈

| 技术 | 用途 |
|------|------|
| HTML5 | 页面结构 |
| Tailwind CSS CDN | 样式框架，无需编译 |
| Google Fonts | Plus Jakarta Sans + Be Vietnam Pro |
| Material Symbols | 图标库 |
| GitHub Actions | 自动部署到 GitHub Pages |

**没有用到**：React、Vue、Webpack、npm、后端服务器。这就是纯静态 HTML，打开就能跑。

---

## 📐 设计原则总结

1. **高对比厚描边**：所有关键元素都有 2-3px 深色边框，增强可读性和卡通感
2. **温暖橙黄渐变**：主色调用橙黄渐变，营造阳光、活力的氛围
3. **圆润造型**：拒绝尖锐边角，全部使用大圆角，亲和力拉满
4. **8px 基础间距**：所有间距都是 8 的倍数，保持视觉节奏一致
5. **硬阴影**：用偏移阴影代替模糊阴影，像贴纸一样“跳”出来
6. **按压反馈**：点击元素时向下位移，模拟真实物理按键

---

## 🤝 如何使用这些原型？

### 作为设计参考
直接打开各个 `code.html` 文件，截图或标注后交给开发团队。

### 作为开发起点
复制任意 `code.html` 文件，替换里面的示例内容，接入你的后端 API 即可变成真实产品。

### 作为学习案例
阅读代码中的 Tailwind CSS 类名，学习如何用 utility-first 的方式实现复杂 UI。

### 作为交付模板
把整套原型发给客户或团队，快速确认视觉方向，避免“做出来才发现不喜欢”。

---

## ❓ 常见问题

**Q: 这些页面是静态的，能真正用吗？**
A: 目前是纯前端原型，没有后端数据。但可以直接接入 API 变成真实产品，代码结构已经搭好。

**Q: 可以用在自己的项目里吗？**
A: 可以。本项目作为设计参考和前端模板使用，无 License 限制。

**Q: 为什么用 Tailwind CDN 而不是本地构建？**
A: 为了“开箱即用”。CDN 方式让任何人 Clone 下来就能直接打开，无需安装任何依赖。

**Q: 能改颜色和字体吗？**
A: 可以。每个 `code.html` 里的 `<script>tailwind.config = {...}</script>` 就是主题配置，修改里面的颜色和字体即可全局生效。

**Q: 移动端显示正常吗？**
A: 正常。所有页面都做了响应式处理，桌面端显示多栏布局，手机端自动变成单栏。

---

## 📮 联系与反馈

如果你喜欢这个设计风格，或者想基于它继续开发，欢迎 Star ⭐ 这个仓库。

如有问题或建议，可以在 GitHub 上提 Issue。

---

## 🎉 致谢

设计灵感来源：
- **Neo-Brutalism** 新粗野主义设计运动
- **Kawaii / Cute UI** 卡哇伊可爱风界面
- 现代在线工作台工具如 Notion、Linear、Arc Browser

---

**最后更新：** 2026-07-27
**状态：** ✅ 已部署，可正常访问

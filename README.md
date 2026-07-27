# stitch_cartoon_style_online_workbench

卡通可爱风在线工作台静态原型预览集合。风格统一为高对比描边、温暖橙黄配色和圆润造型，适合快速预览或作为前端设计参考。

## 项目结构

- `index.html` - 预览导航入口，列出所有页面版本
- `_1/code.html` ~ `_6/code.html` - 6 个静态页面原型
- `404/code.html` - 自定义 404 页面
- `vibrant_workspace/DESIGN.md` - 设计系统说明
- 各版本目录下包含 `screen.png` 预览图

## 本地预览

直接双击 `index.html`，或在终端执行：

```bash
npx serve .
# 或
python -m http.server 8080
```

然后打开浏览器访问对应路径即可。

## 部署到 GitHub Pages

### 方式一：GitHub Actions 自动部署

本仓库已包含 `.github/workflows/pages.yml`，只需：

1. 在 GitHub 仓库的 **Settings → Pages** 中，将 **Source** 改为 **GitHub Actions**
2. 推送代码到 `main` 分支
3. 工作流会自动构建并部署到 `gh-pages` 分支
4. 稍后访问 `https://<username>.github.io/<repo>/`

### 方式二：直接设置 Pages 源

1. 进入 GitHub 仓库 **Settings → Pages**
2. **Source** 选择当前分支，文件夹选择 **Root**，保存
3. 等待几分钟，访问 `https://<username>.github.io/<repo>/`

## 设计说明

详见 `vibrant_workspace/DESIGN.md`。

核心原则：
- 高对比厚描边
- 温暖橙黄渐变
- 圆润造型与硬阴影
- 8px 基础间距

## 备注

本项目为静态原型集合，不含构建脚本和后端逻辑，可直接托管到任意静态站点服务。

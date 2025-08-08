# Promptable TravelDesign

按钮化选择 + 手动补充的旅行 **Prompt 生成器**，以及一个 **新加坡 4D3N 示例页面**。

- 首页：`index.html`（生成器，含日期下拉、主题/背景/emoji 选择、导出 .txt/.md、一键清空/重置/示例填充）
- 示例：`/examples/singapore-4d3n.html`（横向时间线 + 横滑卡片，Tropical 度假风）

## 使用方法

1. 打开 **index.html**：选择日期、目的地、预算，点选偏好与外观；在「手打补充」里加入你的额外要求。
2. 点 **生成 Prompt**，复制到 ChatGPT/Cursor；按提示生成 HTML 单页行程。
3. 将生成的 HTML 保存到本仓库的 **`/examples/`** 目录，即可作为案例展示。

## GitHub Pages 部署

1. 将本项目 push 到仓库：`Jianan-Huang0609/Promptable_TravelDesign`
2. 进入仓库 **Settings → Pages**：
   - Source: `Deploy from a branch`
   - Branch: `main`（或你的默认分支），Folder: `/ (root)`
3. 保存后访问：  
   - 首页（生成器）：`https://jianan-huang0609.github.io/Promptable_TravelDesign/`  
   - 示例页：`https://jianan-huang0609.github.io/Promptable_TravelDesign/examples/singapore-4d3n.html`

## 本地开发

- 直接双击 `index.html` 在浏览器打开即可。
- 生成器使用 `localStorage` 记忆你的选择。
- 无需构建/打包；所有依赖均为 CDN（Font Awesome, Motion One）。

## 许可

仅用于个人/学习目的；示例页面未引用受版权限制的图片。

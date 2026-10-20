# 🌧️ 雨夜便利店

以雨夜便利店为主题的 Three.js 三维场景，包含雨滴、湿地反光、室内灯光，以及角色进店购物的自动运镜短片。

**[▶ 直接打开网页体验](https://08102317cdw-art.github.io/rainy-konbini/)**

**[🎬 自动播放场景短片](https://08102317cdw-art.github.io/rainy-konbini/?play)**

无需下载、安装依赖或登录 GitHub。建议使用支持 WebGL 2 的现代浏览器。

## 操作方式

- 鼠标左键拖动：旋转观察。
- 滚轮：缩放。
- 鼠标右键拖动：平移。
- 触摸屏：单指旋转，双指缩放和平移。
- 自动播放入口会循环播放约 78 秒的场景短片。

当前版本支持环绕查看与自动运镜，尚未提供键盘控制角色漫游。

## 文件与本地运行

- `rainy-konbini-diorama.html`：完整独立网页，包含打包后的场景脚本和 Three.js。
- `index.html`：网站首页，将查询参数传递给场景页面。
- `.github/workflows/pages.yml`：推送到 main 后自动发布 GitHub Pages。

直接用浏览器打开 `rainy-konbini-diorama.html` 即可运行。也可在仓库目录执行 `python -m http.server 8000`，然后访问 `http://localhost:8000/`。

当前提供的是原始文件夹中的单文件打包版本；目录中没有未打包的模块源码、构建配置或源映射文件。

## 开源许可

本项目采用 [MIT 许可证](LICENSE)。内嵌的第三方库许可见 [第三方说明](THIRD_PARTY_NOTICES.md)。

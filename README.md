# 作品集 Portfolio

静态网页，无需构建，可直接用 GitHub Pages 发布。

## 文件

- `index.html` 　整张连续长页（文字为可选中的真文字）
- `assets/` 　　 页面图片（已压缩为网页尺寸）

本地预览：直接双击 `index.html`。

## 发布到 GitHub Pages

1. 登录 github.com，右上角 **+ → New repository**，仓库名例如 `portfolio`，选 **Public**，创建。
2. 进入仓库，点 **uploading an existing file**（或 Add file → Upload files），把本文件夹里的
   `index.html`、`README.md` 和整个 `assets` 文件夹一起拖进去，点 **Commit changes**。
3. 仓库 **Settings → Pages**：Source 选 **Deploy from a branch**，Branch 选 `main`、目录选 `/ (root)`，点 **Save**。
4. 等 1–2 分钟，访问 `https://<你的用户名>.github.io/portfolio/`。
   （如果仓库名取为 `<你的用户名>.github.io`，网址就是 `https://<你的用户名>.github.io/`。）

## 使用

- 一张连续的长页面，向下滚动阅读；顶部导航跳转章节，目录每一行可点击。
- 点击任意图片放大查看；带 ↗ 标记的二维码可直接点击打开对应视频 / H5，也可手机扫码。
- 链接末尾加 `#p12`、`#p17` 等可直接跳到对应项目。
- 手机上建议横屏查看。

## 更新

网页由 PPT 转换生成。PPT 改动后重新生成，再用新文件覆盖仓库里的 `index.html` 和 `assets/` 即可。

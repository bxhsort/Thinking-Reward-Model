# TRM Project Website

This folder contains the complete static TRM project website, including the selected logo, figures, tables, and PDF figures. It requires no build command or server backend.

## 用 GitHub Pages 公开发布

1. 在 https://github.com/new 创建仓库，例如 `trm-project`，选择 **Public**，勾选添加 README。
2. 在仓库中选择 **Add file → Upload files**，上传本文件夹内的内容，保留 `assets/` 子文件夹结构，然后点击 **Commit changes**。不要直接上传 ZIP；仓库首页应能直接看到 `index.html`。
3. 打开仓库 **Settings → Pages**。
4. 在 **Build and deployment** 中选择 **Source: Deploy from a branch**，**Branch: main**，目录选择 **/(root)**，点击 **Save**。
5. 等待部署完成，在同一页面点击 **Visit site**。发布可能需要几分钟，GitHub 文档说明最长可能需要约 10 分钟。

普通项目仓库的网页地址格式：`https://你的GitHub用户名.github.io/trm-project/`。
如果采用其他仓库名，末尾路径也随之改变。

`index.html`、`style.css`、`app.js` 和 `assets/` 必须保持同级。`.nojekyll` 是空文件，用来直接发布静态文件。
之后在仓库中提交更新，会触发网页重新发布。

官方说明：
- https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

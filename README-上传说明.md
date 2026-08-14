# GitHub Pages 上传说明

请将本文件夹中的全部内容上传到同一个 GitHub 仓库，并保持以下结构：

```text
index.html
.nojekyll
assets/
```

## 发布步骤

1. 在 GitHub 创建一个新仓库。
2. 点击 `Add file` -> `Upload files`，上传本文件夹中的 `index.html`、`.nojekyll` 和整个 `assets` 文件夹。
3. 打开仓库的 `Settings` -> `Pages`。
4. 在 `Build and deployment` 中选择 `Deploy from a branch`。
5. Branch 选择 `main`，目录选择 `/ (root)`，点击 `Save`。
6. 等待数分钟，GitHub 会显示公开访问链接。

## 注意事项

- 不要只上传 `index.html`，图片、视频和简历都存放在 `assets` 文件夹中。
- 不要修改文件与文件夹的相对位置，否则网页素材会无法显示。
- 所有待上传文件均不超过 25 MB。
- 两个较大的视频已无损拆分为多个 `.part` 文件。网页会在点击播放按钮后自动加载并重组，请勿删除或重命名这些分片。
- 视频首次播放需要下载全部对应分片，加载时间取决于访问者的网络速度。

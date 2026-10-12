# Zhonghao Zhang — Ready-to-publish website

这是完整静态发布版，包含主页、五个项目详情页、About、Resume，以及全部图片、原始 GIF、视频和简历 PDF。
无需 Node.js、源码构建或额外下载。

## 本地查看
解压整个压缩包，双击 index.html。保持所有文件和文件夹的位置不变。
论文等外部链接仍需要联网。
如果浏览器限制本地文件，可在当前文件夹运行 python -m http.server 8000，然后访问 http://localhost:8000。

## 发布到你的 GitHub Pages
目标仓库：https://github.com/Zhong-Hao-Zhang/zhong-hao-zhang.github.io
目标网址：https://zhong-hao-zhang.github.io

1. 解压 ZIP。
2. 打开仓库 Code 页面，点击 Add file → Upload files。
3. 上传解压后文件夹里面的所有文件和子文件夹；不要把 ZIP 文件直接上传，也不要再套一层文件夹。
   仓库根目录应直接出现 index.html、about、research、resume、_next 等。
   请保留根目录的 .nojekyll 文件。若未上传，可用 Add file → Create new file，文件名填 .nojekyll，内容留空，提交。
4. 点击 Commit changes，提交到 main。
5. 仓库 Settings → Pages → Build and deployment → Source：选择 Deploy from a branch。
6. Branch 选择 main，文件夹选择 /(root)，点击 Save。
7. 等待 GitHub Pages 部署完成，再打开目标网址。

此版本不需要 GitHub Actions 自定义工作流，GIF 已是完整原文件，不需要合并分片。

## 发布到其他静态网站托管
上传解压后的全部文件及子文件夹。网站入口为根目录 index.html，构建命令留空。
支持 GitHub Pages、Netlify、Cloudflare Pages 以及普通静态 Web 服务器。

## 分享给别人
可以直接发送这个 ZIP。对方解压并打开 index.html 就可以查看页面；也可以按上面步骤上传发布。

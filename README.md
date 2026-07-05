# 计算机网络刷题网站 V4 Deploy Safe 版

这是 GitHub Pages 部署安全版：

- 保留 V4 多文件结构
- 保留 262 道题库
- 保留 MathJax 公式渲染
- 保留大题图片与应用题图片
- 移除 docx / rar / 中文说明文件等非网页资源，避免 Pages 部署失败
- 添加 `.nojekyll`
- `sw.js` 为不强缓存版本

上传 GitHub Pages：把本文件夹内所有内容上传到仓库根目录，设置 Pages 为 `main / root`。

根目录应直接看到：

```text
index.html
style.css
app.js
questions.js
manifest.webmanifest
sw.js
.nojekyll
assets/
README.md
```

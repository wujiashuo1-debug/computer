# 计算机网络刷题网站 V2｜V4结构 + MathJax公式渲染版

本版本沿用软件工程 V4 的多文件工程结构：

- `index.html`
- `style.css`
- `app.js`
- `questions.js`
- `manifest.webmanifest`
- `sw.js`
- `assets/`

## 本版新增

- 接入 MathJax 公式渲染。
- 支持 `$...$`、`$$...$$`、`\\(...\\)`、`\\[...\\]` 公式。
- 切换题目、展开答案、提交刷题后会自动重新渲染公式。
- 对常见的 `2^5`、`2^(32-28)` 这种纯文本指数表达做了轻量转写，方便看 CIDR / 子网计算类题目。

## GitHub Pages 上传方式

解压 ZIP 后，进入文件夹，把里面所有内容上传到仓库根目录。
仓库根目录应该直接看到：

```text
index.html
style.css
app.js
questions.js
assets/
```

不要把整个外层文件夹套进去。

## 注意

MathJax 通过 CDN 加载，所以公式渲染需要联网。普通文字、图片、题库本体不依赖 MathJax。

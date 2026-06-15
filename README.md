# VansamaZWT Blog

博客使用 Hexo 6.3.0 和 Butterfly 4.9.0，发布到：

https://vansamazwt.github.io

## 日常写作

在本目录打开 PowerShell。

新建文章：

```powershell
npm run new -- "文章标题"
```

文章会生成在 `source/_posts/`。编辑对应的 Markdown 文件后，本地预览：

```powershell
npm run preview
```

浏览器打开 http://localhost:4000。

确认无误后发布：

```powershell
npm run publish
```

## 新设备恢复

安装 Node.js 22 和 Git，然后在博客源码目录运行：

```powershell
npm ci
npm run preview
```

源码保存在远端 `source` 分支，生成的网站保存在 `main` 分支。不要直接在
`main` 分支编辑文章。

## 常用目录

- `source/_posts/`：文章
- `scaffolds/post.md`：新文章模板
- `_config.yml`：站点和发布配置
- `themes/butterfly/`：主题及自定义样式

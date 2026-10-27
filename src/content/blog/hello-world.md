---
title: 你好，世界
publishDate: 2026-10-27 10:00:00
description: '这是这个博客的第一篇文章。'
tags:
  - 随笔
---

欢迎来到我的博客，这里是第一篇文章。

这个博客用来记录一些想法、笔记和生活片段。以后想写东西的时候，直接新建一个 Markdown 文件就可以了。

## 怎么写新文章

在 `src/content/blog/` 目录下新建一个文件夹（文件夹名会成为网址的一部分），里面放一个 `index.md`：

```md
---
title: 文章标题
publishDate: 2026-11-01 09:00:00
description: '一句话概括这篇文章'
tags:
  - 随笔
---

正文从这里开始。
```

保存后本地运行 `npm run dev` 就能预览，推送到 GitHub 后会自动发布上线。

# 我的技术文档

欢迎访问我的个人文档网站。本网站使用 MkDocs 构建，通过 GitHub Actions 自动部署到 GitHub Pages。

- 作者：zgypx228
- 实践主题：静态文档自动部署
- [关于本项目](about.md)
- [使用指南](guide.md)
- [API 参考](api.md)

## 这个网站是怎么来的

我写的只是 `docs/` 目录下的几个 Markdown 文件。每次我把这些文件推到 `main`，GitHub Actions 会自动跑一遍：装依赖、执行 `mkdocs build` 生成 `site/`、再把 `site/` 作为发布产物交给 GitHub Pages。所以网页上的内容和我仓库里的 Markdown 是同一份东西，只是中间多了一道自动构建。

自动部署验证：这是我第二次推送后更新的内容。

本次自动更新于 2026-11-23 23:50 生效：我没有点任何手动部署按钮，只是把这一句提交并 push，网站就自己重建了。

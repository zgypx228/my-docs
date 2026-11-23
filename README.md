# my-docs

使用 MkDocs Material 编写、由 GitHub Actions 自动构建并部署到 GitHub Pages 的个人文档网站。

- 网站地址：https://zgypx228.github.io/my-docs/
- 个人实验报告：[report/README.md](report/README.md)

## 本地预览

```bash
python -m venv .venv
source .venv/Scripts/activate   # Windows Git Bash；PowerShell 用 .\.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
python -m mkdocs serve
```

然后打开 http://127.0.0.1:8000/ 。

## 目录说明

| 路径 | 作用 |
| --- | --- |
| `docs/` | 网站源码，四页 Markdown |
| `mkdocs.yml` | 站点配置与导航 |
| `.github/workflows/deploy.yml` | 自动构建与部署工作流 |
| `report/` | 实验报告与关键步骤截图 |
| `site/` | 构建产物，已忽略，不提交 |

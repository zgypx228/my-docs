# 使用指南

1. 修改 docs 目录中的 Markdown 文件。
2. 在本地预览并检查页面及链接。
3. 提交修改并推送到 main 分支。
4. 在 Actions 页面查看构建与部署状态。
5. 打开网站检查内容是否更新。

## 常用命令

```bash
# 本地预览，默认 http://127.0.0.1:8000/
python -m mkdocs serve

# 构建网站并严格检查警告（有警告就失败）
python -m mkdocs build --strict
```

`--strict` 这个参数很关键：它把"警告"升级成"错误"。本地随便跑一下可能看不出问题，但在 Actions 里只要有一个死链或 YAML 写错，构建就会直接失败，网站也就不会更新。早点用 `--strict`，问题在本地就能暴露。

返回[首页](index.md)，或看 [API 参考](api.md)。

# 我的技术文档

这是一个使用 MkDocs Material 构建、由 GitHub Actions 自动发布到 GitHub Pages 的示例文档项目。

网站：https://jokerzsd.github.io/my-docs/

## 本地预览

```bash
python -m pip install mkdocs-material
mkdocs serve
```

在浏览器中打开 `http://127.0.0.1:8000/`。

## 自动发布

修改 `docs/`、`mkdocs.yml` 或部署工作流并推送到 `main` 后，工作流会构建网站、更新 `gh-pages` 分支，并发布到 GitHub Pages。也可以在 Actions 页面手动运行工作流。

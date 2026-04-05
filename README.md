# LeetCode-Top-100

LeetCode 高频题练习与笔记。

## GitHub Pages

静态站点源码位于 [`docs/`](./docs/)（入口为 `docs/index.html`）。发布由 [`.github/workflows/pages.yml`](./.github/workflows/pages.yml) 完成（**不经过 Jekyll**）。

在仓库 **Settings → Pages** 中：

1. **Build and deployment → Source** 选 **GitHub Actions**（不要再用 “Deploy from a branch”）。
2. 推送 `main` 后工作流会上传 `docs/` 并部署；也可在 **Actions** 里手动 **Run workflow**。
3. 站点地址：`https://<你的用户名>.github.io/LeetCode-Top-100/`

若曾用 “从分支 `/docs` 部署” 并出现 Jekyll 报错，按上面改为 **GitHub Actions** 即可。

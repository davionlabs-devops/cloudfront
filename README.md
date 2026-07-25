# cloudfront redirect

静态跳转页:`apex-nexus.sxxw.site` → `https://d1u4uxgoy48nj6.cloudfront.net`

## 部署
1. GitHub 仓库 Settings → Pages → Source 选 `main` / `root`。
2. Custom domain 填 `apex-nexus.sxxw.site`(仓库内 `CNAME` 文件已配好),勾选 Enforce HTTPS。
3. 腾讯云 DNSPod 加解析:`apex-nexus` CNAME → `flywithbug.github.io`。

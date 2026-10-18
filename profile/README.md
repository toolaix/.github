# toolaix

一词一页 SEO 小工具矩阵 · One-keyword SEO micro-tools.

每个仓库 = 一个可独立上线的垂直工具站（计算器 / 转换器 / 报价器）。  
Starter 模板：[tool-starter](https://github.com/toolaix/tool-starter)

## 约定

| 项 | 选择 |
| --- | --- |
| 框架 | Next.js（App Router） |
| 部署 | Cloudflare Pages |
| 收款 | Creem（国内个人出海优先） |
| SEO | 一词一页 + FAQ + 长尾矩阵 |
| 证伪 | GSC 14/30 天漏斗 |

## 新开一个工具

```bash
# 用 template 建仓后：
cp -R tool-starter my-tool && cd my-tool
# 改 site.config.ts → 填主词与定价 → deploy
```

找词流程见 skill：`one-keyword-page-seo`（[linxai/dev-skills](https://github.com/linxai/dev-skills/tree/main/one-keyword-page-seo)）。

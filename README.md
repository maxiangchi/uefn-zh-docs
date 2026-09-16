# Fortnite / UEFN 官方文档中文镜像

Epic Games 官方 Fortnite 文档（UEFN + Fortnite Creative）的简体中文镜像，共 **251 页**，纯静态站点。

## 在线预览

    https://maxiangchi.github.io/uefn-zh-docs/

首页为 `index.html`；全部子教程索引见 `pages/sub-index.html`。

## 仓库内容

| 路径 | 内容 |
| --- | --- |
| `index.html` | 首页（36 篇主文档卡片式入口） |
| `pages/` | 251 个页面：36 篇主文档（`NN-*.html`）+ 214 篇子教程 + `sub-index.html` 索引 + 专题页 |
| `assets/` | `epic.css`（Epic 官方样式表）、`patch.css`（本地布局层）、`logo-epic.svg` |
| `.nojekyll` | 关闭 Jekyll 处理，Pages 原样发布全部文件 |
| `README_阅读说明.txt` | 原始阅读说明 |

英文原文与图片清单（`_source/`、`_source2/`、`_img*/`）仅保留在本地，不随仓库发布。

## 部署

GitHub → Settings → Pages → Source: *Deploy from a branch* → Branch: `main` / `/ (root)` → Save。
静态站无构建步骤，推送后约 1 分钟生效。

## 说明

- 全部链接为**相对路径**，仓库放在根目录或子目录均可正常浏览。
- 正文配图 2700+ 处为 **Epic 官方 CDN 热链**（`dev.epicgames.com`），需联网加载；正文文字离线可读。
- 术语策略：Verse / UEFN / Scene Graph / Lumen / Niagara 及设备与属性名保留英文原名；每页顶部附英文原文链接。
- 本地浏览：直接双击 `index.html`。

## 版权

内容版权归 **Epic Games** 所有（含 Epic 官方样式表）。本镜像仅供**学习交流**，不作商业用途；如权利人提出异议，将立即移除。

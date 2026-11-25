# 名为主Owner，实为交付与背责——时间线与证据索引（公开摘要页）

这是一个用于公开发布事件的静态单页网站（纯 HTML，无任何依赖），核心内容来自在线文档
[《入职某手3个多月：owner是假，锅是真》](https://my.feishu.cn/wiki/M9Y8wY2xxiD94ykLZKhcI2EKnyd)（核心材料）与
[《置身手内》](https://my.feishu.cn/wiki/DfELwo0WeiDOuikuvJjcLazpndf)（叙事复盘版）。

## 本地预览

直接在浏览器打开 `index.html` 即可。

## 部署到 GitHub Pages

仓库：`leo-star-cyber/ks-accusation`。

1. 仓库 Settings → Pages → Source 选择 `Deploy from a branch`，Branch 选择 `main` 与 `/ (root)`，保存。
2. 几分钟后即可通过 `https://leo-star-cyber.github.io/ks-accusation/` 访问。

（本地如需重新推送：`git push origin main`）

## 自定义内容

- 页面为单文件 `index.html`，所有章节均以 `<section id="...">` 组织（概览 / 人物 / 时间线 / 管理过程记录 / 协作失真记录 / 小结 / 诉求 / 录音说明 / 文档 / 建议 / 联系），直接编辑对应区块即可。
- 顶部导航锚点在 `<header>` 的 `.nav-links` 中。

# 入职快手3个多月：名为主Owner，实为交付与背责——时间线与证据索引（公开摘要页）

这是一个用于公开发布事件的静态单页网站（纯 HTML，无任何依赖），核心内容来自在线文档
[《入职快手3个多月：名为主Owner，实为交付与背责——时间线与证据索引》](https://my.feishu.cn/wiki/M9Y8wY2xxiD94ykLZKhcI2EKnyd)（核心材料）与
[《一个理想主义工程师的握手、放手与复盘》](https://my.feishu.cn/wiki/DfELwo0WeiDOuikuvJjcLazpndf)（叙事复盘版）。

## 本地预览

直接在浏览器打开 `index.html` 即可。

## 部署到 GitHub Pages

1. 在 GitHub 创建仓库（本站对应 `YaoYang-Star/ks-accusationZ`）。
2. 推送代码：
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin git@github.com:YaoYang-Star/ks-accusationZ.git
   git push -u origin main
   ```
3. 仓库 Settings → Pages → Source 选择 `Deploy from a branch`，Branch 选择 `main` 与 `/ (root)`，保存。
4. 几分钟后即可通过 `https://yaoyang-star.github.io/ks-accusationZ/` 访问。

## 自定义内容

- 页面为单文件 `index.html`，所有章节均以 `<section id="...">` 组织（概览 / 人物 / 时间线 / 管理过程记录 / 协作失真记录 / 小结 / 诉求 / 录音说明 / 文档 / 建议 / 联系），直接编辑对应区块即可。
- 顶部导航锚点在 `<header>` 的 `.nav-links` 中。
- 联系方式目前在 `#contact` 区块（Issue 渠道），如有微信号等可直接替换该段文字。

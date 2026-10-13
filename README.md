# 世界奶龙大学 · World Nailong University

网友整活二创网站，与奶龙 IP 方及任何真实大学均无关系。

## 文件

- `index.html` — 主页（奶龙居中 + 背景校徽 + “正在进入世界奶龙大学”）
- `logo.svg` — 原创校徽（圆形双环 + 环形中英文校名 + 书本/月桂/小龙图案，仅供玩梗，未抄袭任何真实高校校徽）
- `nailong.png` — 奶龙图（白底已转透明）
- `CNAME` — 绑定自定义域名（部署到 GitHub Pages 时使用）

## GitHub Pages 部署步骤

1. 在 GitHub 新建仓库（如 `nailong-university`），把本目录所有文件推上去。
2. 仓库 Settings → Pages → Source 选 `main` 分支 `/ (root)`，保存。
3. 稍等 1-2 分钟，访问 `https://<用户名>.github.io/nailong-university/` 即可。

## 绑定 “世界奶龙大学.com” 域名

1. 在任意域名注册商购买 IDN 域名 `世界奶龙大学.com`
   （系统内部实际注册的是 punycode：`xn--rhqr3y0gz4ec38cpb7c.com`）。
2. 域名 DNS 添加两条记录：
   - `A` 记录指向 GitHub Pages IP：`185.199.108.153`、`185.199.109.153`、`185.199.110.153`、`185.199.111.153`
   - 或 `CNAME` 记录指向 `<用户名>.github.io`
3. 仓库 Settings → Pages → Custom domain 填入 `xn--rhqr3y0gz4ec38cpb7c.com`（或直接填中文域名），勾选 Enforce HTTPS。
4. 浏览器地址栏输入 `世界奶龙大学.com` 即可访问。

## 被搜索引擎搜到

- 页面已内置 SEO meta（标题/描述/关键词含“世界奶龙大学”）。
- 上线后到 Google Search Console / Bing Webmaster 提交 `https://世界奶龙大学.com/`，一般数天到两周内收录。

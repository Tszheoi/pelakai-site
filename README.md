# pelakai-site

个人介绍页，部署在 `pelakai.tszheoi-law.top`。

纯静态，无 Functions、无环境变量。

## 结构

```
public/index.html            页面
public/favicon.ico           图标（多尺寸）
public/favicon-32.png
public/favicon-16.png
public/apple-touch-icon.png
```

## Cloudflare Pages 配置

- 框架预设：**None**
- 构建命令：**留空**
- 构建输出目录：`public`
- 环境变量：**不需要**

## 内容

- `Hi, my name is Tszheoi Law`
- `I'm the Unknown Developer.`
- 「Know more」按钮 → 弹邮件（地址由 JS 拼接，避免被爬虫抓取）

## 改内容

直接改 `public/index.html`，推送后自动重新部署。

## 域名

`pelakai.tszheoi-law.top`

> 这个项目是 Git 连接型；仓库推送即部署，不用再拖 zip。

# 我的海岛日记

一个 Codex 实战复刻的海岛摄影个人网站，适合部署到 Vercel、Netlify 或 GitHub Pages。

## Vercel 部署

### 方式一：网页部署

1. 打开 [Vercel](https://vercel.com) 并登录。
2. 新建项目，导入包含本目录文件的 GitHub 仓库。
3. Framework Preset 选择 `Other`。
4. Build Command 留空。
5. Output Directory 留空或填写 `.`。
6. 点击 Deploy。

### 方式二：Vercel CLI

```bash
npx vercel
```

首次部署按提示登录并选择当前目录。生产部署使用：

```bash
npx vercel --prod
```

## 文件说明

- `index.html`：Vercel 默认入口页面。
- `island-diary.html`：本地保留的同款页面文件。
- `vercel.json`：静态站点路由和缓存配置。
- `.vercelignore`：排除与站点无关的视频、字幕和脚本文件。

# UrbanAI-101

Spatial statistics and urban analytics — Jupyter Book.

## 在线阅读 (Read online)

Book will be available at:

**https://\<your-username\>.github.io/UrbanAI-101/**

after you enable GitHub Pages (see below).

## 本地构建 (Build locally)

```bash
pip install -r requirements.txt
jupyter-book build .
# Open _build/html/index.html in browser
```

## 发布到 GitHub Pages (Deploy to GitHub Pages)

1. **启用 GitHub Pages**  
   仓库 → **Settings** → **Pages** → **Build and deployment** → Source 选择 **GitHub Actions**。

2. **推送代码**  
   将本仓库推送到 GitHub 后，每次推送到 `main`（或 `master`）分支会自动触发 Actions 构建并发布。

3. **查看站点**  
   构建完成后，在 **Settings → Pages** 中会显示站点地址，一般为：  
   `https://<username>.github.io/UrbanAI-101/`

## 目录结构

- `_config.yml` — Jupyter Book 配置
- `_toc.yml` — 目录
- `intro.md` — 书籍首页
- `2_spatial-statistics/` — 空间统计章节与笔记本

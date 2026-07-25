# 台灣在地新聞部落格

讓每個人都能找到想要的資訊，感受友善快樂的傳遞。

## 網站結構

```
taiwan-local-news/
├── _config.yml          # 網站基本設定
├── _layouts/
│   ├── default.html     # 主要版型
│   └── post.html        # 文章版型
├── _posts/              # 所有文章放這裡
├── assets/css/
│   └── style.css        # 網站樣式
├── index.html           # 首頁
└── .github/workflows/
    └── deploy.yml       # 自動部署設定
```

## 新增文章

在 `_posts/` 資料夾新增一個 Markdown 檔案，檔名格式：

```
YYYY-MM-DD-文章標題.md
```

每篇文章開頭需要有以下 front matter：

```markdown
---
layout: post
title: "文章標題"
date: 2026-07-25 09:00:00 +0800
county: 台北市
categories: [特殊活動]   # 可選：特殊活動、公告政策
---
```

## 文章分類

- `特殊活動`：市集、節慶、展覽、表演等
- `公告政策`：地方政府公告、補助、新制上路等

## 著作權規範

- 禁止直接複製原文句子，所有內容以自己的話重新表達
- 每則新聞附原始連結與來源名稱
- 來源以各縣市政府官網、觀光局網站、旅遊社網站為主

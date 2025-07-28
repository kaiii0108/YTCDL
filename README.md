# 🎬 YouTube Thumbnail Viewer & Extractor

這是一個簡單的網頁工具，讓你快速預覽並取得 **YouTube 影片縮圖**的不同解析度版本。  
支援輸入單一或多個影片 ID / 網址，並自動解析出縮圖連結。

> 💡 本工具由 [ChatGPT](https://openai.com/chatgpt) 協助產生與撰寫。

---

## ✨ 功能特色

- ✅ 支援貼上 YouTube 影片 ID 或完整網址
- ✅ 自動抓取五種解析度縮圖：
  - `default.jpg` (320×180)
  - `mqdefault.jpg` (480×360)
  - `hqdefault.jpg` (640×480)
  - `sddefault.jpg` (1280×720)
  - `maxresdefault.jpg` (最大解析度)
- ✅ 支援批量解析（用逗號 `,` 及 `{}` 分隔多筆）
- ✅ 直接顯示圖片預覽與圖片連結

---

## 🖥️ 使用方式

1. 開啟 `index.html`（或部署於 GitHub Pages）
2. 在輸入框中貼上：
   - YouTube 影片 ID（例如：`dQw4w9WgXcQ`）
   - YouTube 網址（如 `https://www.youtube.com/watch?v=dQw4w9WgXcQ`）
   - 多筆 ID 或網址（可用逗號及花括號分隔`{https://www.youtube.com/watch?v=dQw4w9WgXcQ,https://www.youtube.com/watch?v=dQw4w9WgXcQ}`）
3. 點擊「產生縮圖」按鈕
4. 下方會顯示所有解析度的圖片連結與預覽圖

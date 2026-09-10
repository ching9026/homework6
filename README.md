# Homework 6 — VTuber 個人介紹網頁

這是一個使用 **HTML + CSS** 製作的單頁式人物介紹網頁作業，主題為 NIJISANJI VTuber **Ratna Petit（ラトナ・プティ）**。

本作業主要練習基本網頁排版、CSS 樣式設計、圖片與超連結整合，以及 YouTube 影片嵌入等前端基礎功能。

並使用github.io: https://ching9026.github.io/homework6/01057151-Exercise6-2.html
---

## 專案內容

主要頁面：

```text
01057151-Exercise6-2.html
```

整個頁面將 HTML 與 CSS 寫在同一個檔案中，不需要額外安裝套件即可執行。

---

## 功能與內容

網頁包含以下內容：

- VTuber 基本資料介紹
- 所屬團體與生日、身高等資訊
- YouTube / Twitch / Twitter 外部連結
- 人物背景與簡介
- 粉絲名稱資訊
- 人際關係與合作成員介紹
- 圖片展示
- YouTube 影片嵌入播放
- 履歷式單頁版面設計

---

## 使用技術

| 類別 | 技術 |
|---|---|
| 網頁結構 | HTML5 |
| 樣式設計 | CSS3 |
| 多媒體 | `<img>`、YouTube `<iframe>` |
| 外部連結 | `<a>` Hyperlink |
| Layout | Block / Inline-block / Position |

此專案沒有使用 JavaScript 或任何前端框架，主要目的是熟悉 HTML 與 CSS 的基本操作。

---

## 頁面結構

```text
homework6/
├── README.md
└── 01057151-Exercise6-2.html
```

HTML 頁面大致分成：

```text
Header / Basic Information
        │
        ├── Name
        ├── Affiliation
        ├── Height
        ├── Birthday
        └── Social Media

Profile
        │
        ├── Background
        ├── Introduction
        └── Embedded YouTube Video

Relationships
        │
        ├── Debut Members
        └── VTuber Collaboration Members
```

---

## 如何執行

### 方法一：直接開啟

下載 Repository 後，直接使用瀏覽器開啟：

```text
01057151-Exercise6-2.html
```

即可查看頁面。

### 方法二：使用 Local Server

若使用 VS Code，可以安裝 **Live Server** Extension 後執行。

也可以使用 Python：

```bash
python -m http.server 8000
```

接著在瀏覽器開啟：

```text
http://localhost:8000/01057151-Exercise6-2.html
```
---

## 學習重點

透過此作業主要練習：

1. 使用 HTML 建立網頁基本結構
2. 使用 CSS 設計文字、區塊與背景
3. 使用 `margin`、`padding`、`width` 等屬性控制版面
4. 使用 `position` 與 `inline-block` 進行元素定位
5. 建立可點擊的外部連結
6. 顯示網路圖片
7. 使用 `<iframe>` 嵌入 YouTube 影片
8. 將人物資訊整理成類似 Resume / Profile 的版面

---

## 參考來源

此作業的頁面設計有參考 CodePen 範例，原始 HTML 內亦保留相關 Reference 註解。

- CodePen Resume Layout Reference
- Pixabay / Web Image Resources

部分人物圖片與影音內容來自外部網站，其著作權屬於原作者及相關平台所有。

---

## 可改善方向

若要進一步將此作業升級成較完整的前端作品，可以考慮：

- 將 CSS 拆成獨立的 `style.css`
- 改善 Responsive Web Design，支援手機版
- 避免使用固定 `650px` 圖片尺寸
- 使用 Flexbox / CSS Grid 重構版面
- 將外部圖片改成本地 assets 或更穩定的來源
- 加入 Navigation Bar
- 增加 Dark Mode
- 使用 JavaScript 加入互動效果
- 改善 Accessibility，例如圖片 `alt` 屬性

---

## 專案性質

此 Repository 為 Web Programming 課程作業，主要展示 **HTML / CSS 基礎網頁設計能力**。

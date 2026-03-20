# 東湧 10 週年 × 商業周刊｜ESG 永續建築論壇

單頁式提案展示網頁，用於呈現東湧 OUNOVA 品牌十週年與商業周刊策略合作的 ESG 論壇企劃。

## 專案概覽

- **客戶**：東湧實業股份有限公司（東湧 OUNOVA）
- **合作媒體**：商業周刊
- **主題**：真數據・真節能 ESG 永續建築論壇
- **用途**：媒體提案展示（純展示，無互動表單）

## 頁面結構

| 單元 | 說明 |
|------|------|
| Navbar | 東湧 Logo + 商周 Logo，固定頂部導覽 |
| Ticker | 品牌關鍵字跑馬燈 |
| Hero | 雙欄版面，左側標題文案，右側 KPI 數據 |
| 品牌里程碑 | 關中集團 50 年 × 東湧 10 年 × 商周合作 |
| ESG 痛點 | 四大建築熱水能耗盲區 |
| 產品照片帶 | 四張產品情境圖 |
| 數據實證 | 實驗室 × 現場雙軌驗證數據 |
| 論壇單元 | 四大論壇議程 |
| 旗艦案例 | 三大實績案例圖 |
| 數位賦能 | IoT 監控功能 + 即時 Dashboard |
| 精準受眾 | 商周讀者數據（動態計數器） |
| CTA | 結尾訴求文案 |
| Footer | 版權資訊 |

## 技術規格

- **純 HTML / CSS / JS**，無框架依賴
- 字型：Yantramanav（英數）+ Noto Sans TC（中文）
- 品牌色：`#cf0213`（東湧紅）、`#111111`、`#ffffff`
- 響應式斷點：`900px`
- 動態效果：IntersectionObserver 捲動揭露、數字計數器

## 檔案結構

```
東湧/
├── index.html       # 主網頁（單一檔案）
├── BWlogo-red.svg   # 商業周刊官方 Logo
├── 東湧Logo.png     # 東湧 Logo（備用）
└── README.md
```

## 部署

已部署至 GitHub Pages：
**https://potatodigital-bwdp.github.io/ounova-bw-forum/**

更新步驟：
```bash
git add index.html
git commit -m "update"
git push
```

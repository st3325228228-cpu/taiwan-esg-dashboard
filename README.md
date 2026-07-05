# Taiwan ESG Dashboard

台灣 ESG 與溫室氣體排放資料視覺化儀表板，透過網頁介面呈現企業環境資料，協助使用者查詢、比較與觀察不同公司的排放情況。

本 Repository 為靜態展示網站，使用 GitHub Pages 部署。

## 線上展示

[開啟 Taiwan ESG Dashboard](https://st3325228228-cpu.github.io/taiwan-esg-dashboard/)

## 主要功能

- 顯示企業 ESG 與環境相關資料
- 查詢公司溫室氣體排放資訊
- 比較不同企業的排放數據
- 以圖表呈現資料分布與差異
- 提供響應式網頁介面
- 支援 GitHub Pages 靜態部署

## 系統架構

```text
使用者瀏覽器
      ↓
GitHub Pages 靜態網站
      ↓
index.html
      ↓
ESG 資料儀表板或外部應用
```

## 使用技術

- HTML5
- CSS3
- JavaScript
- ESG Data Visualization
- Responsive Web Design
- GitHub Pages

## 檔案結構

```text
taiwan-esg-dashboard/
├── index.html
└── README.md
```

## 本機執行

可以直接使用 Python 啟動本機伺服器：

```bash
python -m http.server 8000
```

接著在瀏覽器開啟：

```text
http://localhost:8000
```

## GitHub Pages 部署

1. 進入 Repository 的 `Settings`
2. 點選左側 `Pages`
3. Source 選擇 `Deploy from a branch`
4. Branch 選擇 `main`
5. 資料夾選擇 `/root`
6. 點選 `Save`
7. 等待 GitHub Pages 完成部署

## 專案目的

本專案用於練習與展示：

- ESG 資料應用
- 企業環境資料呈現
- 資料視覺化
- 響應式網頁設計
- 靜態網站部署
- GitHub Pages 使用

## 注意事項

- ESG 資料可能因來源更新時間而存在差異。
- 排放數據應以官方公開資料或企業永續報告為準。
- 本專案僅供學習、資料展示與研究使用。
- 若頁面整合外部網站，外部服務失效時可能無法正常顯示。

## 未來改進方向

- 加入公司名稱與產業篩選
- 增加年度排放趨勢圖
- 加入公司間比較功能
- 顯示資料來源與更新日期
- 增加 CSV 下載功能
- 加入更多 ESG 指標
- 改善行動裝置介面

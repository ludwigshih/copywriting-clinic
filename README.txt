文案急診室｜第一單元 GitHub Pages 正式分離版

檔案結構
- index.html：網站頁面結構
- style.css：全部視覺樣式
- app.js：互動、評分、存檔與頁面切換
- unit01.json：第一單元十二題、智慧填空句型、詞語及示範內容
- .nojekyll：停用不必要的 Jekyll 處理

部署方式
1. 解壓縮 ZIP。
2. 將上述五個檔案上傳至 GitHub 儲存庫根目錄。
3. GitHub：Settings > Pages > Deploy from a branch。
4. Branch 選 main，Folder 選 / (root)，按 Save。
5. 等待約 1 至 5 分鐘，再開啟 GitHub Pages 網址。

重要
- 五個檔案必須放在同一層。
- 這是正式分離版，index.html 不含內嵌題庫。
- 不可直接雙擊本機 index.html 測試，請使用 GitHub Pages。
- 後續修改題目時只需更新 unit01.json；修改互動時更新 app.js；修改外觀時更新 style.css。

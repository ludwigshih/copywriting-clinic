文案急診室｜第一單元 GitHub Pages 正式分離版（Chrome修正版）

修正重點：
1. app.js、style.css、unit01.json 加入版本參數，避免 Chrome 使用舊快取。
2. 回到首頁、遊戲說明、文案工具均加入明確全域函式與事件監聽。
3. 每次重新開啟網站都會顯示遊戲介紹與醫生代號入口。
4. 已有瀏覽器進度時，可直接以原 Dr.代號繼續。

部署時必須完整覆蓋：index.html、style.css、app.js、unit01.json、.nojekyll。
部署後請用 Ctrl+F5 強制重新整理一次。

# 【口碑案例優化】各店案例管理

美加集團 品牌行銷部 內部工具。單一 `index.html`，以 GitHub Pages 發佈。

- 資料（案例、術前術後照）只存在各自電腦的瀏覽器（IndexedDB），不會上傳到 GitHub 或任何伺服器。
- 分院之間用「匯入報表／匯出 XLSX」交換資料。清除瀏覽器資料會讓本機案例消失，請定期匯出。
- 檢視者連結：網址後加 `?role=viewer`（僅介面限制，非登入權限）。

⚠️ 這個 repo 公開，只能放程式碼。絕對不要提交顧客資料、Excel 報表或照片（`.gitignore` 已擋下常見格式）。

術前術後照僅供內部案例管理；對外使用前須依醫療法醫療廣告相關規定另行審查。

外部套件：SheetJS xlsx 0.18.5、html2canvas 1.4.1、Google Fonts（Noto Sans TC）。

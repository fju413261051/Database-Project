## 高鐵訂票系統資料庫
### 資料庫系統概論
組別：12

組員名單
- 組員：蔡沁和 / 413261374
- 組員：謝旻姍 / 413261130
- 組員：王靖婷 / 413261051
- 組員：吳翊歆 / 413261180

以 SQL Server 實作的高鐵訂票系統資料庫範例，包含資料表結構與示範資料。

| 檔案名稱 | 說明 |
| :--- | :--- |
| CreateTable  | 建立資料表結構（Schema）、主鍵/外鍵 |
| InsertTableData  | 插入營運基礎設定、測試帳號與示範訂票資料 |

所有表單:
member（會員）、booking（訂位）、ticket（車票）、ticket_type（票種）、station（車站）、train（車次）、stop_at（停靠點）、seat（座位）、fare_rule（票價規則）

使用方式:
建立資料庫 Project
執行 CreateTable 建立資料表
執行 InsertTableData 匯入示範資料

33

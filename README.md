### 高鐵訂票系統資料庫

以 SQL Server (T-SQL) 實作的高鐵訂票系統資料庫範例，包含資料表結構與示範資料。

檔案:	說明
First.sql:	建立資料表（schema）
First-insert.sql:	插入示範資料
資料表:

member（會員）、booking（訂位）、ticket（車票）、ticket_type（票種）、station（車站）、train（車次）、stop_at（停靠點）、seat（座位）、fare_rule（票價規則）

使用方式:
建立資料庫 Project
執行 First.sql 建立資料表
執行 First-insert.sql 匯入示範資料

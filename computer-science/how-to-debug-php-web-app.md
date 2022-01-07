# How to Debug PHP Web App

## 流程
- 判定是前端還是後端造成的問題？
- 主機問題？程式問題？資料庫問題？

---

## 前端問題

### F12
- Console Tab
- Network Tab

## 後端問題

### HTTP 狀態
- HTTP 403 沒有權限

  常見狀況：(會員) 檔案無法上傳。  
  解決方法：檢查 linux 主機權限設定。  

- HTTP 404 找不到網頁

  常見狀況：路徑錯誤。  
  解決方法：檢查路徑。  

- HTTP 500 Server 錯誤

  常見狀況：主機錯誤 / 程式錯誤。  
  解決方法：去主機上查看 log 檔案。  
  ```sh
  tail -f /var/log/apache2/<www.example.com>-error.log
  ```

### Apache2 httpd error log
- 關鍵字 `PHP Fatal Error` / `fatal`

## 資料庫問題
- 欄位不一致

  常見狀況：欄位不一致。   
  解決方法：先拿到 SQL 語句，用其他資料庫管理工具 (phpMyAdmin) 執行，再看錯誤訊息。  

---

## 其他方法
- 二分搜

  傳統 echo / var_dump / error_log，加上二分搜尋法。
  
- git commit

  從 git commit 中找問題，適合追蹤近期才發生的錯誤。

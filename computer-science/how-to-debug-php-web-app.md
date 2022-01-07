# How to Debug PHP Web App

### 流程
- 判定是前端還是後端造成的問題？
- HTTP 403 / HTTP 404 / HTTP 500 / ...
- F12 javascript error

### HTTP 狀態
##### HTTP 403 沒有權限
常見狀況：(會員) 檔案無法上傳。  
解決方法：檢查 linux 主機權限設定。  

##### HTTP 404 找不到網頁
常見狀況：路徑錯誤。  
解決方法：檢查路徑。  

##### HTTP 500 Server 錯誤
常見狀況：主機錯誤 / 程式錯誤。  
解決方法：去主機上查看 log 檔案。  
```sh
tail -f /var/log/apache2/<www.example.com>-error.log
```

### F12

### 方法
- 傳統 echo / var_dump / error_log，加上二分搜尋法。
- git commit，適合追蹤近期才發生的錯誤。

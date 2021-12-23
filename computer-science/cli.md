# CLI Quick Reference

### chown - 更改擁有者/群組
```sh
chown -R userName:groupName apps/
```

### chmod - 更改資料夾權限
```sh
chmod -R 755 apps/
```
```sh
chmod -R 775 public/
```

### [unzip](https://linux.die.net/man/1/unzip) - 解壓縮
```sh
zip -r filename.zip folder/
```
```sh
unzip -o download.zip -d to_dir/

-o: 覆蓋
-d: 解壓資料夾
```

### tar - 壓縮/解壓縮
```sh
# 壓縮
tar zcvf filename.tar.gz folder/
```
```sh
# 解壓縮
tar zxvf filename.tar.gz
```

### wget - 下載
```sh
wget example.com
```

### su 切換使用者
```sh
su - username
```

### ifconfig - 網路狀態
```sh
ifconfig
```

### tail - 查看 log
```sh
head readme.txt
```

```sh
tail -f /var/log/apache2/error.log
```

### less - 看檔案
```sh
ifconfig | less
```

### grep - 搜尋內容
```sh
grep "search_term" *.php
```

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

### unzip - 解壓縮
```sh
zip -r filename.zip folder/
```
```sh
unzip download.zip
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

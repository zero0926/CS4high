# 文件管理
```
mkdir
more
cat
diff
grep
rm
touch
ln
file
cp
find
split
mv
```
# 檔案壓縮與打包
```
使用 tar 工具將檔案與目錄打包成為單一歸檔 (archive, 未壓縮, 或稱為 tar ball)
打包參數 -cvf (c: 建立新歸檔, v: 顯示詳情, f: 指定檔名)
拆封參數 -xvf (x: 取出歸檔, v: 顯示詳情, f: 指定檔名)
tar 可配合壓縮工具，打包兼壓縮歸檔
壓縮參數 -czvf (gzip), -cjvf (bz2)
解壓參數 -xzvf (gzip), -xjvf (bz2)
解開 tar ball 的指令最後可以加上 -C path 來指定解出檔案存放的位置
https://www.eebreakdown.com/2016/08/linux.html
```
# 行程管理Process management
```
利用ps命令監控系統行程
利用pstree監控系統行程
利用lsof監控系統行程與程式
利用pgrep查詢系統行程
使用crontab任務調度
使用kill和killall終止行程
```
```
循序漸進Linux（第2版） 基礎知識 伺服器搭建 系統管理 性能調優 虛擬化與集群應用
高俊峰 人民郵電出版社
第15章 Linux系統進程管理434
```


# 網路常用指令
```
ifconfig
scp
netstat
traceroute
telnet
wget
```
### wget
```
Linux 使用 wget 指令自動下載網頁檔案教學與範例
https://blog.gtwang.org/linux/linux-wget-command-download-web-pages-and-files-tutorial-examples/
```

# OpenWrt_Packages
## 公钥
#### 命令安装
```
echo -e "untrusted comment: public key 29026b52f8ff825c\nRWQpAmtS+P+CXP4/60amOLDZs7jqKfTrFlKt5+UHYTU0ED9pRmh73vz7" >"/etc/opkg/keys/29026b52f8ff825c"
```
#### 下载 mime.pub
```
curl -# -L --fail "http://openwrt.11121314.xyz/mime.pub" -o mime.pub
```
```
wget -q http://openwrt.11121314.xyz/mime.pub --show-progress
```
#### 安装公钥
```
opkg-key add mime.pub
```

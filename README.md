# OpenWrt_Packages
## 公钥
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

# iPod-touch-web-server-shadowsocks-server



Pre-required programs:
1. OpenSSH
2. lighttpd
3. python 2.7.3 on ios (https://storage.googleapis.com/google-code-archive-downloads/v2/code.google.com/yangapp/python_2.7.3-3_iphoneos-arm.deb)
4. shadowsocks-python
5. wifiutil (https://github.com/oh-orange/wifiutil)



自建plist来实现以下功能：
1. 强制wifi连接，保证稳定联网
2. 后台强制运行shadowsocks服务器
3. 每天6：30AM定时启动网页服务器
4. 每天凌晨12：00AM定时重启以维持稳定运行




iPod model: iPod touch 4 32GB, 256MB RAM, 800MHz Cortex-A8 CPU. 
plist reference: https://developer.apple.com/legacy/library/documentation/Darwin/Reference/ManPages/man5/launchd.plist.5.html




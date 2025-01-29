### 自用AX6一键编译脚本
- IMM官方项目没有NSS加速，要编译没有nss加速的是首选！

- LEDE显示有nss，但是测试WIFI有问题，内网中上传速度特别慢。

- 以下两个项目是支持大分区，而且带NSS加速！

1、LiBwrt：https://github.com/LiBwrt-op/openwrt-6.x.git build-AX6-IPQ脚本【该项目近期发现nss加速启动不了】
2、VIKINGYFY： https://github.com/VIKINGYFY/immortalwrt.git build-AX6-NSS脚本【该项目nss加速满血，500m跑满cpu占用个位数!】

- 注意：
nss加速默认是开启的，不要去防火墙里打开系统的硬件或软件卸载加速，会有不可预测的冲突！
测试只要跑大流量cpu占用很低或没有就是NSS加速在起作用了！  

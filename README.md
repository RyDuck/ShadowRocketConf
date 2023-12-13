# shadowrock配置文件

这是一个关于ios shadowrock app的配置文件，主目的是去除ads。有两种手段：

- 使用rule-set：在请求ad url的时候，dns请求返回NXDOMAIN、或者服务器拒接访问
- 使用小火箭的模块+http解密


### Shadowrocket打开HTTPS解密方法（配合模块使用）
 - 1.点击配置文件ⓘ - HTTPS解密 - 证书 - 生成新的CA证书 - 安装证书。
 - 2.手机设置 - 已下载描述文件 - 安装
 - 3.手机设置 - 通用 - 关于本机 - 证书信任设置 - 开启对应Shadowrocket证书信任。
 - 4.没换一次conf配置文件好像就要重新安装小火箭的证书


### [常见模块汇总地址](https://whatshub.top/)



引用：[deezertidal](https://github.com/deezertidal/shadowrocket-rules)

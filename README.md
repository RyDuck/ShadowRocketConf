# shadowrock配置文件


小火箭的module相当于是对当前配置文件的一个重写，其本质也是  conf配置文件：
    1. module的优先级高于当前的conf配置文件
    2. module的先后顺序就是优先级
    3. 可以开启多个module，但是只能选择一个conf配置文件
    4. module不是conf配置文件的一部分



这是一个关于ios shadowrocket app的配置文件，主要目的是飞流+去广告。有两种手段：

- 使用rule-set：在请求ad广告的url的时候，其dns请求返回NXDOMAIN、或者服务器拒接访问
- 使用小火箭的模块 + 配置文件的http解密


### Shadowrocket打开HTTPS解密方法（配合模块使用）
 - 1.点击配置文件ⓘ - HTTPS解密 - 证书 - 生成新的CA证书 - 安装证书。
 - 2.手机设置 - 已下载描述文件 - 安装
 - 3.手机设置 - 通用 - 关于本机 - 证书信任设置 - 开启对应Shadowrocket证书信任。
 - 提示：每每换一次conf配置文件好像就要重新安装小火箭的证书


### [常见模块汇总地址](https://whatshub.top/)

引用：[deezertidal](https://github.com/deezertidal/shadowrocket-rules)

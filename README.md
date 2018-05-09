#这是一个windows客户端和面板对接的分支

=======================
感谢朝阳群众，此项目所有工作均由朝阳群众完成，我只是个上传的

特性：填写网址/api/login、用户名和密码既可以获取节点
例如：
 - 网址:http://example/api/login
 - 用户名:user
 - 密码:passwd
 
爬虫模式介绍:只要用户中心有ssr://批量链接即可获取节点，无需更新面板（爬虫模式目前暂不支持Uim版，支持魔改版、魔改91vps版）
例如：
 - 网址:http://example/ （注意：最后必须要有'/'）
 - 用户名:user
 - 密码:passwd
 
使用：Uim版面板请切换ShadowsocksR-for-Windows-with-login-support分支，魔改版原版和魔改91vps版请手动更新或使用爬虫模式

客户端：https://github.com/dumplin233/shadowsocks-csharp/releases

面板：https://github.com/NimaQu/ss-panel-v3-mod_Uim/commits/ShadowsocksR-for-Windows-with-login-support








#欢迎使用ss panel v3 mod 再次修改版


**ss-panel-v3-mod**是一款转为shadowsocks设计的web前端面板，再次感谢ss-panel-v3mod 的制作者，修改后的功能简介：

- **支付系统集成**：集成 支付宝当面付 黛米付 易付通 码支付等多种支付系统，使用方法见项目[wiki](https://github.com/NimaQu/ss-panel-v3-mod_Uim/wiki/)
- **UI** ：修改为 ~~援交~~ 圆角、并自定义了几个图标的显示，节点列表等級0可见等級1节点但无法看见节点详情，增加了国家图标显示
- **商店**：商品增加同时连接设备数，用户限速属性
- 从肥羊那里**抄**来的：新用户注册现金奖励|高等级节点体验|设备数量限制
- **优化**：css和js等置入本地提升加载速度
- 增加**v2Ray** 功能，详情请看 [wiki](https://github.com/NimaQu/ss-panel-v3-mod_Uim/wiki/V2Ray-%E5%AF%B9%E6%8E%A5%E6%95%99%E7%A8%8B)

telegram交流群：https://t.me/joinchat/GQehSEV7LEU1Z6E8aQ4z3w

telegtam 频道 ：https://t.me/sspanel_Uim  管理模式参考91yun管理

**原作者** [galaxychuck](https://github.com/galaxychuck)

[支持开发者请点我](https://github.com/NimaQu/ss-panel-v3-mod_UIM#%E5%85%B3%E4%BA%8E%E6%8D%90%E8%B5%A0)

本面板在[宝塔面板5.6.0](www.bt.cn)，宝塔安装版 nginx1.12，php 7.1 ，mysql 5.7 上全部功能测试通过

## 搭建教程

感谢LALA制作教程：https://lala.im/2398.html

GitHub Wiki : https://github.com/NimaQu/ss-panel-v3-mod_Uim/wiki/%E5%89%8D%E7%AB%AF%E5%AE%89%E8%A3%85

Wiki已经启用，欢迎为此面板维护wiki

#### 鸣谢

##### [galaxychuck](https://github.com/galaxychuck)

- 面板**原作者**

##### [dumplin](https://github.com/dumplin233) 

- 码支付对接 + 码支付当面付二合一
- 为面板加入 AFF 链接功能
- 商品增加限速和限制 ip 属性
- 多端口订阅
- 解决用户列表加载缓慢历史遗留问题

##### [rinSama](https://github.com/mxihan)

- 整理分类 config.php
- spay 优化

##### [miku](https://github.com/xcxnig)

- 美观和性能优化

##### [Tony Zou](https://github.com/ZJY2003)

- 为公告增加群发邮件功能
- 节点负载情况显示&用户账户过期在首页弹窗提醒
- 增加返利列表

[**indexyz**](https://github.com/Indexyz)

- 为面板增加 v2Ray 功能

##### 还有所有被引用过代码的同学，以及所有提交过issue的同学。

#### 关于捐赠

您对我们的帮助将是支持我们做下去的动力，只需您在购买部分产品或向他人推荐产品时从我们的返利链接购买，这就是对我们很大的支持了。~~没有钱了，肯定要做啊，不做没有钱用啊，打工是不可能打工的，这辈子不可能打工的~~

##### dumplin

- [码支付-微信收款功能开通](https://codepay.fateqq.com/i/39756)


##### NimaQu


- [魔方云 - 低成本极速高效 专属您的私有云](https://www.cubecloud.net/aff.php?aff=796)


##### galaxychuck

- [黛米付-支付接入](https://www.daimiyun.cn/register.php?aff=624)
- [冲上云霄云主机](http://console.soar-clouds.com/aff.php?aff=94)

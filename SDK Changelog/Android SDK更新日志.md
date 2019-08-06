###  Android SDK & Android_Unity SDK更新日志

#### V 4.2.0

1.增加原生模版渲染方式

2.新增tapjoy平台

3.支持 admob视频多层配置

4.支持 unity 多层配置

5.增加百度，广点通，Mintegral，金山云 针对targetSdkVersion >= 24特殊处理逻辑，[Android](https://github.com/yumimobi/YumiMediationSDKDemo-Android/blob/master/docs/YumiMediationSDK%20for%20Android%20Download%20Page.md) &
 [Unity](https://github.com/yumimobi/YumiMediationSDK-Unity/blob/master/source/document/YumiMediationSDK%20for%20Unity(zh-cn).md#752-gdt%E5%B9%BF%E7%82%B9%E9%80%9A-%E5%B9%B3%E5%8F%B0%E8%AF%B7%E6%B1%82%E4%B8%8D%E5%88%B0%E5%B9%BF%E5%91%8A%E9%97%AE%E9%A2%98)
 
6.升级[三方SDK](https://github.com/yumimobi/YumiMediationSDKDemo-Android/blob/master/docs/YumiMediationSDK%20for%20Android%20Download%20Page.md)


#### V 4.1.0

1. 升级 interstitial & video & Splash 请求配置逻辑
2. 移除 banner 轮播动画
3. 支持 GDRR协议接口
4. 增加视频下载完成主动回调
5. 增加视频点击回调
6. 增加支持开屏的平台: Baidu 、BytedanceAds 、GDT
7. 增加 Inneractive 平台 ，支持广告形式 ：Banner、Interstitial、Video
8. 升级三方 SDK ，详情https://github.com/yumimobi/YumiMediationSDKDemo-Android/blob/master/docs/YumiMediationSDK%20for%20Android%20Download%20Page.md

注：410版本接口进行了更新，请按照文档重新接入；Untiy 插件更新时，请将老插件删除干净，再引入新插件。

#### V 3.6.3

1.update 广点通  sdk to 4.40.910 

2.优化banner展示效果

#### V 3.6.1

1. 优化YUMI获取权限

#### V 3.6.0
1. YUMI支持可玩物料类型（插屏 & 视频）,支持插页式视频物料
2. 修改原生广告聚合逻辑和返回的数据接口，增加百度,admob,facebook平台原生广告
3. 修改 adtype 的枚举值
4. 增加SMART_BANNE
5. 新增 IQzone banner、interstitial 、video 广告形式
6. 新增 Mintegral interstitials video广告形式
7. 上报参数增加 osVersion 和 brand
8. 优化debugcenter逻辑
9. 更新adcolony，admob, inmobi依赖的google_play_services到11.0.4版本
10. update Chartboost sdk to 7.3.1
11. update Facebook sdk to 5.1.0
12. update InMobi sdk to 7.2.2
13. 修复 Applovin 激励视频奖励回调错误
14. interstitial & video增加新的上报节点，增加更多宏变量参数
15. Untiy插件SDK:接口字段做了优化和修改，请按照文档重新接入
 
#### V 3.4.1

1. 修改 DebugCenter 提示信息
2. 去除禁止 HTTPS 主机认证的全局设定

#### V 3.4.0

如您使用Unity插件接入SDK 3.4.0版本，请先将此前版本删除并按照最新文档重新接入。

1.更新百度SDK到5.8，新增视频广告形式

2.更新ZPLAYAds SDK到2.3.0

3.更新广点通SDK到4.20.580，新增视频广告形式并实现插屏&原生自渲染功能

4.vungle支持多层配置（插屏&激励视频）

5.支持facebook header bidding功能，支持广告形式banner，插屏，视频

6.Applovin支持服务端配置banner参数

7.更新banner，插屏，视频配置请求及使用逻辑

8.视频增加新的上报节点

9.修复已知问题

#### V 3.3.9

1.ironsource 支持多层配置（插屏、视频）

2.视频平台重试逻辑优化 

3.更新百度SDK到5.7.0

4.更新Facebook SDK到4.99.3

5.更新Vungle SDK到6.3.17

6.更新Unity SDK到2.3.0，区分中国区&海外区Unity adpter单独接入

7.Applovin 支持banner 在 info.plist 增加 sdk key


#### V 3.3.8

1.Android sdk 间隔逻辑优化

2.新增金山云（视频）、IronSource（插屏+视频）平台

3.更新  ZPLAYAds 到2.1.1

4.优化debug center 模块



#### V 3.3.7
1.优化请求逻辑

2.更新facebook到4.99.1

3.更新mobvista 到8.13.0

4.更新 APPLovin逻辑

5.更新ZPLAYAds逻辑

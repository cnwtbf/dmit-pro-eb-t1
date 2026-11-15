# DMIT怎么样：Pro、EB、T1 三档到底差在哪？洛杉矶 $9.99 的入门款够用吗？香港 Pro 为什么 $39.90 起（附全套餐价格表）

DMIT 值不值得买，取决于你要的是中国大陆方向的低延迟，还是便宜的算力。前一件事它做得确实好：第三方测评里洛杉矶 Pro 全国平均延迟 140–180ms，晚高峰基本稳住，香港机房到大陆主要城市多在 50ms 以内，磁盘 IO 实测平均读写约 839 MB/s。后一件事它不占优势：洛杉矶 Pro 入门款 TINY 月付 $9.99，香港 Pro 最低 $39.90/月，同样价钱在别处能买到配置高得多的机器。

麻烦在于套餐。三个机房 × 三档线路，同一档里还有七八种配置，名字都叫 TINY、MINI、STARTER，价格却差好几倍。下面把三档线路的真实差别、各机房全部在售套餐的价格、换 IP 和退款政策摊开讲，看完你能直接决定买哪一档，或者决定不买。

## 三句话选完：谁该买哪一档

> **只想跑脚本、做备份、练手**：洛杉矶 T1 TINY，$6.90/月，年付 $76.90。便宜，但别指望它访问快。
> **面向国内用户建站、预算每月 $10 上下**：洛杉矶 Pro TINY 或 EB TINY，都是 $9.99/月。Pro 走 CN2 GIA 给 1000GB 流量，EB 走 CMIN2 给 1500GB。
> **要极低延迟、主要服务国内用户**：香港 Pro TINY，$39.90/月。延迟能压到 50ms 以内，代价是 1 核 1GB、每月 500GB 流量。
> **需要日本 IP 或做游戏加速**：东京 Pro TINY，$21.90/月起。

👉 [查看 DMIT 当前全部套餐与价格](https://www.dmit.io/aff.php?aff=9081)

## Pro、EB、T1 差在哪，T1 为什么最容易买错

三档的差别在线路，不在硬件。三个档位用的都是 AMD EPYC 平台和企业级 SSD，同一机房内 CPU、内存、硬盘的配置表几乎一样，价格差全在网络上。

**Premium（Pro）** 是旗舰档，官方描述为“全球优化 + 三网 CN2 GIA 直连”：电信走 CN2 GIA，联通走 AS9929，移动走 CMI/CMIN2。中国大陆方向的三家运营商都照顾到了，晚高峰掉速最不明显。

**Eyeball（EB）** 是中端档，官方描述为“移动首选 + 三网 CMIN2 直连”。移动用户走它性价比最高，电信和联通也有优化但优先级不如 Pro。

**Tier 1（T1）** 是经济档，线路写的是“国际优化 + 中国大陆普通线路”。这句话的意思是：它没有任何中国大陆专属优化，出口走的是普通国际带宽。

洛杉矶的 Pro 和 EB 定价完全一样，区别在流量配额。同样是 $9.99/月，Pro TINY 给 1000GB 流量、1Gbps 端口，EB TINY 给 1500GB、2Gbps 端口。DMIT 在这里把选择权交给了你：想要线路质量选 Pro，想要流量额度选 EB。

T1 是新人最容易踩坑的一档。很多人看到“香港 T1”就默认香港机房离得近、延迟低，实际买完发现电信联通绕路日本甚至美国，延迟比美西的 Pro 套餐还高。机房位置不等于网络路径，T1 卖的是香港的国际出口，不是香港到大陆的专线。如果你的用户在中国大陆，T1 只适合对延迟不敏感的用途，比如定时任务、备份节点、跨境 API 调用。

确定要面向国内用户提供服务，就从 Pro 或 EB 的入门款起步，多花的钱买的是晚高峰那几小时。

👉 [按 $9.99 的入门价开一台洛杉矶 Pro](https://www.dmit.io/aff.php?aff=9081)

## 全套餐价格表

下面是各机房、各线路档当前在售的套餐。价格均为官网标示月付价（T1 的 WEE 为年付），币种为美元。年付价另算，在下一节单独讲。

### 洛杉矶 Premium（LAX.Pro，三网 CN2 GIA）

| 套餐 | CPU / 内存 / 硬盘 | 月流量 / 端口 | 月付 | 购买 |
| --- | --- | --- | --- | --- |
| TINY | 1核 / 2GB / 20GB SSD | 1000GB / 1Gbps | $9.99 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| Pocket | 2核 / 2GB / 40GB SSD | 1500GB / 4Gbps | $14.90 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| STARTER | 2核 / 2GB / 80GB SSD | 3000GB / 10Gbps | $29.90 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| MINI | 4核 / 4GB / 80GB SSD | 5000GB / 10Gbps | $58.88 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| MICRO | 4核 / 4GB / 160GB SSD | 7000GB / 10Gbps | $74.99 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| MEDIUM | 6核 / 8GB / 160GB SSD | 15000GB / 10Gbps | $168.88 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| LARGE | 8核 / 16GB / 320GB SSD | 25000GB / 10Gbps | $338.88 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| GIANT | 12核 / 24GB / 640GB SSD | 50000GB / 10Gbps | $619.99 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |

**LAX.Pro 不限流量系列**（带宽封顶，流量不计）：

| 套餐 | CPU / 内存 / 硬盘 | 带宽上限 | 月付 | 购买 |
| --- | --- | --- | --- | --- |
| uMINI | 2核 / 2GB / 40GB SSD | 30Mbps | $239.99 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| uMICRO | 4核 / 8GB / 80GB SSD | 50Mbps | $399.99 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| uMEDIUM | 4核 / 8GB / 120GB SSD | 100Mbps | $799.99 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| uLARGE | 8核 / 16GB / 240GB SSD | 200Mbps | $1399.99 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |

不限流量系列是给有稳定带宽需求的业务准备的，个人用户看价格就知道不用考虑。

### 洛杉矶 Eyeball（LAX.EB，三网 CMIN2）

| 套餐 | CPU / 内存 / 硬盘 | 月流量 / 端口 | 月付 | 购买 |
| --- | --- | --- | --- | --- |
| TINY | 1核 / 2GB / 20GB SSD | 1500GB / 2Gbps | $9.99 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| Pocket | 2核 / 2GB / 40GB SSD | 3000GB / 4Gbps | $14.90 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| STARTER | 2核 / 2GB / 80GB SSD | 5000GB / 10Gbps | $29.90 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| MINI | 4核 / 4GB / 80GB SSD | 10000GB / 10Gbps | $58.88 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| MICRO | 4核 / 4GB / 160GB SSD | 14000GB / 10Gbps | $74.99 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| MEDIUM | 6核 / 8GB / 160GB SSD | 30000GB / 10Gbps | $168.88 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| LARGE | 8核 / 16GB / 320GB SSD | 50000GB / 10Gbps | $338.88 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| GIANT | 12核 / 24GB / 640GB SSD | 100000GB / 10Gbps | $619.99 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |

### Tier 1（洛杉矶 / 香港 / 东京三机房同价同配）

| 套餐 | CPU / 内存 / 硬盘 | 月流量 | 计费 | 购买 |
| --- | --- | --- | --- | --- |
| WEE | 1核 / 1GB / 20GB SSD | 1000GB | $36.90/年 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| TINY | 1核 / 1GB / 20GB SSD | 2000GB | $6.90/月 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| STARTER | 1核 / 2GB / 40GB SSD | 4000GB | $12.90/月 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| MINI | 2核 / 2GB / 60GB SSD | 8000GB | $21.90/月 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| MICRO | 4核 / 4GB / 80GB SSD | 16000GB | $32.90/月 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| MEDIUM | 4核 / 8GB / 160GB SSD | 32000GB | $49.90/月 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| LARGE | 8核 / 16GB / 320GB SSD | 64000GB | $99.90/月 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| GIANT | 8核 / 24GB / 640GB SSD | 128000GB | $199.90/月 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |

三个机房的 T1 套餐配置和价格一致，下单时在页面里选机房。流量给得比 Pro、EB 大方，这正是它便宜的原因：没有中国大陆优化。

### 香港 Premium（HKG.Pro，CN2 GIA）

| 套餐 | CPU / 内存 / 硬盘 | 月流量 / 端口 | 月付 | 购买 |
| --- | --- | --- | --- | --- |
| TINY | 1核 / 1GB / 20GB SSD | 500GB / 1Gbps | $39.90 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| STARTER | 1核 / 2GB / 40GB SSD | 1000GB / 1Gbps | $79.90 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| MINI | 2核 / 2GB / 60GB SSD | 1500GB / 1Gbps | $119.90 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| MICRO | 4核 / 4GB / 80GB SSD | 2000GB / 1Gbps | $159.90 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| MEDIUM | 4核 / 8GB / 160GB SSD | 2500GB / 1Gbps | $179.90 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| LARGE | 8核 / 16GB / 320GB SSD | 3000GB / 1Gbps | $239.90 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| GIANT | 8核 / 24GB / 640GB SSD | 6000GB / 1Gbps | $499.90 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |

### 香港 Eyeball（HKG.EB，CMIN2）

| 套餐 | CPU / 内存 / 硬盘 | 月流量 / 端口 | 月付 | 购买 |
| --- | --- | --- | --- | --- |
| TINYv2 | 1核 / 1GB / 20GB SSD | 1000GB / 1Gbps | $29.90 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| STARTERv2 | 1核 / 2GB / 40GB SSD | 2000GB / 2Gbps | $59.90 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| MINIv2 | 2核 / 2GB / 60GB SSD | 3000GB / 2Gbps | $89.90 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| MICROv2 | 4核 / 4GB / 80GB SSD | 4000GB / 4Gbps | $129.90 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| MEDIUMv2 | 4核 / 8GB / 160GB SSD | 6000GB / 4Gbps | $199.90 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| LARGEv2 | 8核 / 16GB / 320GB SSD | 12000GB / 4Gbps | $389.90 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| GIANTv2 | 8核 / 24GB / 640GB SSD | 24000GB / 4Gbps | $789.90 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |

香港 EB 的 TINYv2 比香港 Pro 的 TINY 便宜 $10，流量翻倍，配置都是 1 核 1GB。这 $10 买的是 Pro 的 CN2 GIA 优先级。

### 东京 Premium（TYO.Pro）

| 套餐 | CPU / 内存 / 硬盘 | 月流量 / 端口 | 月付 | 购买 |
| --- | --- | --- | --- | --- |
| TINY | 1核 / 1GB / 20GB SSD | 500GB / 1Gbps | $21.90 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| STARTER | 1核 / 2GB / 40GB SSD | 1000GB / 1Gbps | $39.90 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| MINI | 2核 / 2GB / 60GB SSD | 2000GB / 1Gbps | $79.90 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| MICRO | 4核 / 4GB / 80GB SSD | 4000GB / 1Gbps | $159.90 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| MEDIUM | 4核 / 8GB / 160GB SSD | 5000GB / 1Gbps | $259.90 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| LARGE | 8核 / 16GB / 320GB SSD | 8000GB / 1Gbps | $429.90 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| GIANT | 8核 / 24GB / 640GB SSD | 15000GB / 1Gbps | $799.90 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |

### 东京 Eyeball（TYO.EB）

| 套餐 | CPU / 内存 / 硬盘 | 月流量 / 端口 | 月付 | 购买 |
| --- | --- | --- | --- | --- |
| TINY | 1核 / 1GB / 20GB SSD | 1000GB / 1Gbps | $25.90 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| STARTER | 1核 / 2GB / 40GB SSD | 2000GB / 2Gbps | $55.90 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| MINI | 2核 / 2GB / 60GB SSD | 3000GB / 2Gbps | $85.90 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| MICRO | 4核 / 4GB / 80GB SSD | 4000GB / 4Gbps | $119.90 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| MEDIUM | 4核 / 8GB / 160GB SSD | 6000GB / 4Gbps | $179.90 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| LARGE | 8核 / 16GB / 320GB SSD | 12000GB / 4Gbps | $369.90 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |
| GIANT | 8核 / 24GB / 640GB SSD | 24000GB / 4Gbps | $749.90 | [ 选这款](https://www.dmit.io/aff.php?aff=9081) |

## 月付还是年付：差价能到 26%

年付不是所有套餐都划算，具体得看是哪一款。用官网标价算一笔：

洛杉矶 Pro TINY 月付 $9.99，一年 $119.88；年付价 $88.88，折合 $7.41/月，省下 $31，约 26%。这是全套套餐里年付折扣最大的一档。

洛杉矶 Pro Pocket 月付 $14.90，一年 $178.80；年付 $159.98，省约 $19，折扣 11%。Pro STARTER 月付 $29.90，一年 $358.80；年付 $322.99，省约 $36，折扣 10%。配置越高，年付折扣的比例越小。

T1 系列反过来。T1 TINY 月付 $6.90，一年 $82.80；年付 $76.90，只省 $5.90，折扣 7%。T1 STARTER 和 T1 MINI 的年付价正好等于月付乘 12，等于没有年付优惠。

结论很简单：买 Pro 的入门款，年付值得考虑；买 T1，月付和年付差别很小，先用月付试一两个月更稳。

续费价是另一回事。官网价格页标的是当前售价，没有明确写第二年是否同价续费。下单前在结账页确认一下续费金额，别只看到首期价格就付款。

## 换 IP、退款、换机房：下单前该知道的政策

**IP 被墙可以换。** 每 15 天可以免费更换一次被封的 IP，其他情况 $5 一次。2026 年 1 月起支持用户自助换 IP，不用再提工单等客服处理。

**退款有窗口期。** 官网条款写的是购买后 3 天内、流量使用不超过 30GB 可以申请全额退款；超过 3 天在 30 天内，可按比例退还剩余金额。有条件限制，测试要在前几天做完。

**不能换机房。** 买了香港想换洛杉矶，只能重新买一台，数据自己迁。选机房这一步没有后悔药，下单前想清楚用户在哪。

**维护不发邮件通知。** 硬件升级有时会造成短暂中断，用户反馈较多的一点是这类维护不主动发邮件提醒，机器会突然失联一段时间。跑业务的话要有心理准备，或者自己做一套监控。

**工单是英文的。** 没有实时中文在线客服，有时能碰到会中文的客服，响应速度评价不一：有人几小时内就收到回复，也有人觉得慢。

**流量超了是限速，不是断网。** 套餐说明里标注了超额后的限速带宽，Pro 和 EB 的入门款大约是 4Mbps，T1 大约是 100–200Mbps。具体数字以你买的那个套餐页面为准。跑视频或者大文件传输的话，提前在面板里开流量告警。

**支付方式对国内用户友好。** 支付宝、微信支付、PayPal、信用卡都支持。

新用户最稳妥的买法是先月付开一台，3 天内把线路、延迟、流媒体解锁都测一遍，不合适就退。

👉 [趁 3 天退款窗口试一台洛杉矶 Pro](https://www.dmit.io/aff.php?aff=9081)

## 谁不适合买 DMIT

**只想找最便宜机器跑脚本的。** T1 TINY $6.90/月不算贵，但市面上有更便宜的。DMIT 的溢价买的是中国大陆方向的线路质量，你用不上就不该付这个钱。

**对中断零容忍的业务。** 维护不提前通知这一条，足以让一部分业务型用户放弃。

**完全依赖中文实时客服的。** 只有英文工单，遇到紧急问题只能等邮件回复。

**需要频繁换机房或按小时计费的。** DMIT 不支持跨机房迁移，也不做按小时计费，这类需求它满足不了。

## 和搬瓦工、Vultr 比，差在哪

搬瓦工的面板是自研的 KiwiVM，成熟度比 DMIT 用的 WHMCS 高，套餐升级、迁移、快照这些操作更顺手。磁盘性能上第三方实测差距明显，DMIT 平均读写约 839 MB/s，搬瓦工约 427 MB/s，跑数据库这类 IO 敏感的应用会感受到差别。同配置下搬瓦工价格更高，两家旗舰套餐的网络质量接近，DMIT 的部分线路还略占优势。

Vultr 的定位完全不同：全球多地域节点、按小时计费，适合需要多地部署、短期项目或者随时销毁重建的场景。它不做中国大陆方向的专门优化，拿它和 DMIT 的 Pro 系列比国内访问速度没有意义。要国内快选 DMIT，要节点多、计费灵活选 Vultr。

## 常见问题

**DMIT 的原生 IP 是住宅 IP 吗？**

不是。DMIT 提供的是注册地与机房所在地一致的原生 IP，比数据中心广播 IP 干净，在平台眼里更接近真实本地 IP，流媒体和部分服务的识别通过率更高。但它不等同于家庭宽带分配到的住宅 IP。要做账号矩阵这类需要住宅 IP 的操作，得另外买专门的住宅代理服务。

**流媒体能解锁吗？**

第三方实测的说法是洛杉矶套餐除 Netflix、Disney+ 之外，YouTube Premium 等主流流媒体大多可以解锁，IP 区域识别为洛杉矶本地。流媒体平台的风控策略经常变，别把它当成长期保证。

**香港和洛杉矶怎么选？**

香港延迟 30–50ms，价格是洛杉矶 Pro 的四倍，流量配额只有一半。洛杉矶 Pro 延迟 140–180ms，配置更高、价格更低。用户主要在华南、对延迟极其敏感、预算充足，选香港；其余情况洛杉矶 Pro 的性价比高得多。

**新手能用吗？**

可以。控制台基于 WHMCS，开机、重装系统、查看流量都在面板里完成，操作逻辑和主流服务商一致，不需要专门学。

**DMIT 会跑路吗？**

运营时间超过五年，有固定的数据中心合作，收款渠道是支付宝、PayPal 这类正规通道，风险相对可控。但没有任何人能对一家商业公司打包票，重要数据自己留备份。

## 最后怎么定

只需要一台便宜机器跑脚本、做备份 → T1 TINY，$6.90/月，别买它的香港机房指望低延迟。

面向国内用户建站、预算在 $10/月左右 → 洛杉矶 Pro TINY 或 EB TINY，看你更需要线路优先级（Pro）还是流量额度（EB）。

延迟优先、用户集中在国内 → 香港 Pro TINY，$39.90/月，做好流量规划，500GB 用起来很快。

需要日本 IP、游戏加速、东亚节点 → 东京 Pro TINY，$21.90/月起。

下单前确认三件事：结账页显示的续费价、退款窗口的具体条件、购物车里选的到底是哪个机房的哪一档线路。第三条最容易出错，T1 和 Pro 的套餐名长得一模一样。

👉 [打开 DMIT 价格页，对照本文表格下单](https://www.dmit.io/aff.php?aff=9081)

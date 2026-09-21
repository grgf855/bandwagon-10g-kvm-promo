# 搬瓦工 10G KVM PROMO V5：年付$49.99的限量版CN2 GIA套餐，配置、补货规律和值不值得买一文讲清

搜“搬瓦工 10G KVM PROMO V5”的人，大多卡在同一个问题上：这款年付 49.99 美元、号称搬瓦工性价比天花板的限量套餐，到底还在不在售，补货有没有规律，和常规的 CN2 GIA-E 套餐比省了什么、又亏了什么。这篇文章把这些一次说清楚，文末附上搬瓦工目前在售全部套餐的对比表。

## 10G KVM PROMO V5 是什么套餐

先对个暗号。这个套餐的官方全名是 **SPECIAL 10G KVM PROMO V5 – LOS ANGELES – CN2 GIA LIMITED EDITION**，属于搬瓦工的限量版系列，核心卖点是三网 CN2 GIA 线路加一个非常低的年付价格。

具体配置：

- CPU：1 核
- 内存：512 MB
- 硬盘：10 GB SSD（RAID-10）
- 流量：500 GB/月
- 带宽：1 Gbps
- 价格：$49.99/年（折合每月约 4.17 美元）
- 机房：默认洛杉矶 CN2 GIA 机房，支持在包括 DC6 CN2 GIA-E、DC9 CN2 GIA 在内的十余个机房之间免费迁移（不同时期开放的机房列表略有变化，以控制面板实际显示为准）

注意别和另一款老套餐搞混。2021 年那款叫“10G KVM PROMO”的方案年付只要 19.99 美元，但走的是普通 CN2 线路，早就下架了，现在属于老玩家手里的“传家宝”。你在搜的这款 V5 是带 CN2 GIA 的限量版，是另一个东西，价格也差着一倍多。

另外，这款套餐目前处于**缺货状态**。我们核验时直接访问了官方购物车页面，返回的是 "Out of Stock"——这不是第三方传的旧消息，是当前的真实库存状态。

## 为什么这么抢手：限量版省在哪

同样的钱在搬瓦工能买到什么，对比一下就很直观。

花 49.99 美元年付，如果买常规款，你只能拿到 KVM PROMO 20G（1GB 内存、1TB 流量、1Gbps，普通线路机房）；而 10G KVM PROMO V5 给你的是三网 CN2 GIA 回程线路。如果把线路拉到同一档，最接近的常规套餐是 CN2 GIA-E 20G（2.5Gbps 带宽、1TB 流量、1GB 内存），年付 169.99 美元，是 V5 限量版的三倍多。

换句话说，限量版省下的钱，是用配置换的：

| 对比项 | 10G KVM PROMO V5（限量版） | CN2 GIA-E 20G（常规版） |
| --- | --- | --- |
| 价格 | $49.99/年 | $49.99/季，$169.99/年 |
| 内存 | 512 MB | 1 GB |
| 硬盘 | 10 GB SSD | 20 GB SSD |
| 流量 | 500 GB/月 | 1 TB/月 |
| 带宽 | 1 Gbps | 2.5 Gbps |
| 线路 | 三网 CN2 GIA | 三网 CN2 GIA |

一句话概括：用不到常规版三分之一的价格，拿到同级别的线路，代价是内存砍半、流量减半、带宽缩水。对于跑代理、轻度科学上网这类对线路敏感、对配置不敏感的用途，这笔交换多数人觉得划算；但如果你想在上面跑建站加数据库，512 MB 内存和 10 GB 硬盘会很快成为瓶颈。

有用户在 NodeSeek 论坛收到续费账单后的评价挺有代表性：“性能是真的烂，网络是真的稳”，最后因为流量只有 500G，转去找了 750G 流量的平替。买之前想清楚自己的用途，比纠结价格更重要。

## 限量版的三个限制，下单前必须知道

**CPU 限制是最大的坑。** 根据搬瓦工官方服务条款，限量版套餐的 CPU 平均使用率限制在单核的 30%（The Plan 是 45%，SLA 套餐则没有这个限制）。它限制的是一小时内的平均负载，短时间跑满没问题，但长时间高负载会被限速。当代理、跑轻量服务没影响，想拿来跑计算任务就不用考虑了。

**退款窗口很窄。** 搬瓦工的退款政策只覆盖新注册账户：注册 30 天内、账户下 VPS 少于 3 台、累计支付金额低于 100 美元等条件同时满足才能退。这款套餐 49.99 美元的年付金额本身符合额度要求，但如果你是注册很久的老账户，基本没有退款这条路。好在这款只支持年付，本来也没有月付试错选项。

**缺货是常态。** 这款套餐大部分时间都处于售罄状态，能不能买到取决于补货。

## 补货规律：什么时候能买到

综合长期记录搬瓦工补货的第三方站点（比如 VPS GO 和几个补货通知频道）的统计，可以总结出几个还算稳定的规律：

1. **补货间隔**：一般 1～2 周一次，运气好 5～7 天，赶上资源紧张时可能拖到半个月以上。
2. **补货后存活时间**：每次补货通常能撑 1～2 天才会售罄，不需要拼手速秒杀，看到通知后当天内下单基本来得及。
3. **历史上的“周五见”**：早期补货经常固定在周五上午，但近年官方已经不再遵守固定时间，整体越来越随机，周五只是概率略高的参考项。

所以实际的抢购策略很简单：不需要蹲点，加入搬瓦工的补货通知渠道（官方 Telegram 通知频道或中文社区的补货通知群），收到通知后 24 小时内完成下单即可。买不到就等下一轮，这款套餐一年里总有几次补货窗口。

价格方面说一句实话：截至 2026 年 9 月，搬瓦工官网没有长期有效的公开优惠码。2026 年 2 月曾短暂出现过一枚 6.77% 循环折扣码 NODESEEK2026，几天后就失效了，历史上限量版补货时也偶有可用码。下单前可以再搜一下最新状态，结账页的 promo code 栏有就填，没有就按原价买——为等一个不确定的折扣而错过补货窗口，通常不划算。

## 10G KVM PROMO V5 值不值得抢

基于上面核验的信息，给三种典型情况直接下判断：

**适合抢**：用途是代理、轻量科学上网，月流量 300G 以内，对配置没要求但对线路有要求。49.99 美元拿三网 CN2 GIA，这个价位目前没有同级别的替代品。

**不建议抢**：需要跑网站、数据库或任何吃内存的服务。512 MB 内存装个 Debian 后可用空间非常有限，直接看常规 CN2 GIA-E 更合适。

**无所谓抢不抢**：如果只是临时用几个月，限量版不支持月付，年付 49.99 美元起，灵活性不如月付套餐。

## 搬瓦工全套餐对比表（当前官网在售）

下面是目前官网购物车页面公开展示的全部常规套餐。限量版（包括本文主角 10G KVM PROMO V5）只在补货时出现，不在常驻列表里，所以不占表格行——想碰运气等补货，可以先用这个链接进官方页面熟悉一下购买流程：[👉 查看搬瓦工当前在售套餐](https://bit.ly/BandwagonHost)。

**常规 KVM 系列（多机房，普通线路）**

| 套餐 | 内存 | CPU | 硬盘 | 流量/月 | 带宽 | 最低价 | 购买 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 20G KVM PROMO | 1 GB | 2核 | 20 GB | 1 TB | 1 Gbps | $49.99/年 | [ 前往购买](https://bandwagonhost.com/aff.php?aff=79616&pid=44) |
| 40G KVM PROMO | 2 GB | 3核 | 40 GB | 2 TB | 1 Gbps | $52.99/半年，$99.99/年 | [ 前往购买](https://bandwagonhost.com/aff.php?aff=79616&pid=45) |
| 80G KVM PROMO | 4 GB | 4核 | 80 GB | 3 TB | 1 Gbps | $19.99/月，$199.99/年 | [ 前往购买](https://bandwagonhost.com/aff.php?aff=79616&pid=46) |
| 160G KVM PROMO | 8 GB | 5核 | 160 GB | 4 TB | 1 Gbps | $39.99/月，$399.99/年 | [ 前往购买](https://bandwagonhost.com/aff.php?aff=79616&pid=47) |
| 320G KVM PROMO | 16 GB | 6核 | 320 GB | 5 TB | 1 Gbps | $79.99/月，$799.99/年 | [ 前往购买](https://bandwagonhost.com/aff.php?aff=79616&pid=48) |
| 480G KVM PROMO | 24 GB | 7核 | 480 GB | 6 TB | 1 Gbps | $119.99/月，$1199.99/年 | [ 前往购买](https://bandwagonhost.com/aff.php?aff=79616&pid=49) |

**CN2 GIA-E 系列（洛杉矶，11机房可迁移，主力推荐）**

| 套餐 | 内存 | CPU | 硬盘 | 流量/月 | 带宽 | 最低价 | 购买 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CN2 GIA-E 20G | 1 GB | 2核 | 20 GB | 1 TB | 2.5 Gbps | $49.99/季，$169.99/年 | [ 查看套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=87) |
| CN2 GIA-E 40G | 2 GB | 3核 | 40 GB | 2 TB | 2.5 Gbps | $89.99/月，$299.99/年 | [ 查看套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=88) |
| CN2 GIA-E 80G | 4 GB | 4核 | 80 GB | 3 TB | 2.5 Gbps | $56.99/月，$549.99/年 | [ 查看套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=89) |
| CN2 GIA-E 160G | 8 GB | 6核 | 160 GB | 5 TB | 5 Gbps | $86.99/月，$879.99/年 | [ 查看套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=90) |
| CN2 GIA-E 320G | 16 GB | 8核 | 320 GB | 8 TB | 5 Gbps | $159.99/月，$1599.99/年 | [ 查看套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=91) |
| CN2 GIA-E 640G | 32 GB | 10核 | 640 GB | 10 TB | 10 Gbps | $289.99/月，$2759.99/年 | [ 查看套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=92) |
| CN2 GIA-E 1280G | 64 GB | 12核 | 1280 GB | 12 TB | 10 Gbps | $549.99/月，$5399.99/年 | [ 查看套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=93) |

**SLA 系列（洛杉矶 DC5，NVMe 硬盘，99.99% 在线率保障，CPU 无限制）**

| 套餐 | 内存 | CPU | 硬盘 | 流量/月 | 带宽 | 最低价 | 购买 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SLA 20G | 1 GB | 2核 | 20 GB | 1 TB | 2.5 Gbps | $65.89/季，$239.99/年 | [ 了解详情](https://bandwagonhost.com/aff.php?aff=79616&pid=164) |
| SLA 40G | 2 GB | 3核 | 40 GB | 2 TB | 2.5 Gbps | $116.99/季，$399.99/年 | [ 了解详情](https://bandwagonhost.com/aff.php?aff=79616&pid=165) |
| SLA 80G | 4 GB | 4核 | 80 GB | 3 TB | 2.5 Gbps | $69.99/月，$699.99/年 | [ 了解详情](https://bandwagonhost.com/aff.php?aff=79616&pid=166) |
| SLA 160G | 8 GB | 6核 | 160 GB | 5 TB | 5 Gbps | $109.99/月，$1099.99/年 | [ 了解详情](https://bandwagonhost.com/aff.php?aff=79616&pid=167) |
| SLA 320G | 16 GB | 8核 | 320 GB | 8 TB | 5 Gbps | $199.99/月，$1999.99/年 | [ 了解详情](https://bandwagonhost.com/aff.php?aff=79616&pid=168) |
| SLA 640G | 32 GB | 10核 | 640 GB | 10 TB | 10 Gbps | $369.99/月，$3699.99/年 | [ 了解详情](https://bandwagonhost.com/aff.php?aff=79616&pid=169) |
| SLA 1280G | 64 GB | 12核 | 1280 GB | 10 TB | 10 Gbps | $699.99/月，$6999.99/年 | [ 了解详情](https://bandwagonhost.com/aff.php?aff=79616&pid=170) |
| SLA 1280G（15TB流量） | 64 GB | 12核 | 1280 GB | 15 TB | 10 Gbps | $879.99/月，$8799.99/年 | [ 了解详情](https://bandwagonhost.com/aff.php?aff=79616&pid=171) |
| SLA 1280G（20TB流量） | 64 GB | 12核 | 1280 GB | 20 TB | 10 Gbps | $1159.99/月，$11598.99/年 | [ 了解详情](https://bandwagonhost.com/aff.php?aff=79616&pid=172) |

**亚太 CN2 GIA V5 系列（新加坡 / 大阪 / 东京 / 香港）**

| 位置 | 入门套餐 | 内存 | 硬盘 | 流量/月 | 带宽 | 最低价 | 购买 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 新加坡 | 40G | 2 GB | 40 GB | 500 GB | 1.5 Gbps | $49.99/月，$499.99/年 | [ 前往购买](https://bandwagonhost.com/aff.php?aff=79616&pid=173) |
| 新加坡 | 80G | 4 GB | 80 GB | 1 TB | 1.5 Gbps | $86.99/月，$869.99/年 | [ 前往购买](https://bandwagonhost.com/aff.php?aff=79616&pid=174) |
| 新加坡 | 160G | 8 GB | 160 GB | 2 TB | 2.5 Gbps | $165.99/月，$1665.99/年 | [ 前往购买](https://bandwagonhost.com/aff.php?aff=79616&pid=175) |
| 新加坡 | 320G | 16 GB | 320 GB | 4 TB | 2.5 Gbps | $329.99/月，$3199/年 | [ 前往购买](https://bandwagonhost.com/aff.php?aff=79616&pid=176) |
| 新加坡 | 640G | 32 GB | 640 GB | 6 TB | 5 Gbps | $549.99/月，$5549.99/年 | [ 前往购买](https://bandwagonhost.com/aff.php?aff=79616&pid=177) |
| 新加坡 | 1280G | 64 GB | 1280 GB | 8 TB | 5 Gbps | $1059.99/月，$10559.99/年 | [ 前往购买](https://bandwagonhost.com/aff.php?aff=79616&pid=178) |
| 大阪 | 40G | 2 GB | 40 GB | 500 GB | 1.5 Gbps | $49.99/月，$499.99/年 | [ 前往购买](https://bandwagonhost.com/aff.php?aff=79616&pid=134) |
| 大阪 | 80G | 4 GB | 80 GB | 1 TB | 1.5 Gbps | $86.99/月，$869.99/年 | [ 前往购买](https://bandwagonhost.com/aff.php?aff=79616&pid=135) |
| 大阪 | 160G | 8 GB | 160 GB | 2 TB | 1.5 Gbps | $165.99/月，$1665.99/年 | [ 前往购买](https://bandwagonhost.com/aff.php?aff=79616&pid=136) |
| 大阪 | 320G | 16 GB | 320 GB | 4 TB | 1.5 Gbps | $329.99/月，$3279.99/年 | [ 前往购买](https://bandwagonhost.com/aff.php?aff=79616&pid=137) |
| 大阪 | 640G | 32 GB | 640 GB | 6 TB | 1.5 Gbps | $549.99/月，$5549.99/年 | [ 前往购买](https://bandwagonhost.com/aff.php?aff=79616&pid=138) |
| 大阪 | 1280G | 64 GB | 1280 GB | 8 TB | 1.5 Gbps | $1059.99/月，$10559.99/年 | [ 前往购买](https://bandwagonhost.com/aff.php?aff=79616&pid=139) |
| 东京 | 40G | 2 GB | 40 GB | 500 GB | 1.2 Gbps | $89.99/月，$899.99/年 | [ 选这个方案](https://bandwagonhost.com/aff.php?aff=79616&pid=108) |
| 东京 | 80G | 4 GB | 80 GB | 1 TB | 1.2 Gbps | $155.99/月，$1559.99/年 | [ 选这个方案](https://bandwagonhost.com/aff.php?aff=79616&pid=109) |
| 东京 | 160G | 8 GB | 160 GB | 2 TB | 1.2 Gbps | $299.99/月，$2999.99/年 | [ 选这个方案](https://bandwagonhost.com/aff.php?aff=79616&pid=110) |
| 东京 | 320G | 16 GB | 320 GB | 4 TB | 1.2 Gbps | $589.99/月，$5899.99/年 | [ 选这个方案](https://bandwagonhost.com/aff.php?aff=79616&pid=111) |
| 东京 | 640G | 32 GB | 640 GB | 6 TB | 1.2 Gbps | $989.99/月，$9989.99/年 | [ 选这个方案](https://bandwagonhost.com/aff.php?aff=79616&pid=123) |
| 东京 | 1280G | 64 GB | 1280 GB | 8 TB | 1.2 Gbps | $1889.99/月，$18989.99/年 | [ 选这个方案](https://bandwagonhost.com/aff.php?aff=79616&pid=125) |
| 香港 | 40G | 2 GB | 40 GB | 500 GB | 1 Gbps | $89.99/月，$899.99/年 | [ 立即购买](https://bandwagonhost.com/aff.php?aff=79616&pid=95) |
| 香港 | 80G | 4 GB | 80 GB | 1 TB | 1 Gbps | $155.99/月，$1559.99/年 | [ 立即购买](https://bandwagonhost.com/aff.php?aff=79616&pid=96) |
| 香港 | 160G | 8 GB | 160 GB | 2 TB | 1 Gbps | $299.99/月，$2999.99/年 | [ 立即购买](https://bandwagonhost.com/aff.php?aff=79616&pid=97) |
| 香港 | 320G | 16 GB | 320 GB | 4 TB | 1 Gbps | $589.99/月，$5899.99/年 | [ 立即购买](https://bandwagonhost.com/aff.php?aff=79616&pid=98) |
| 香港 | 640G | 32 GB | 640 GB | 6 TB | 1 Gbps | $989.99/月，$9989.99/年 | [ 立即购买](https://bandwagonhost.com/aff.php?aff=79616&pid=122) |
| 香港 | 1280G | 64 GB | 1280 GB | 8 TB | 1 Gbps | $1889.99/月，$18989.99/年 | [ 立即购买](https://bandwagonhost.com/aff.php?aff=79616&pid=124) |

**迪拜电商系列**

| 套餐 | 内存 | CPU | 硬盘 | 流量/月 | 带宽 | 最低价 | 购买 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Dubai 20G | 1 GB | 2核 | 20 GB | 500 GB | 1 Gbps | $19.99/月，$169.99/年 | [ 查看套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=114) |
| Dubai 40G | 2 GB | 3核 | 40 GB | 1 TB | 1 Gbps | $32.99/月，$299.99/年 | [ 查看套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=115) |
| Dubai 80G | 4 GB | 4核 | 80 GB | 2 TB | 1 Gbps | $56.99/月，$549.99/年 | [ 查看套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=116) |
| Dubai 160G | 8 GB | 6核 | 160 GB | 3 TB | 1 Gbps | $86.99/月，$879.99/年 | [ 查看套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=117) |
| Dubai 320G | 16 GB | 8核 | 320 GB | 4 TB | 1 Gbps | $159.99/月，$1599.99/年 | [ 查看套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=118) |
| Dubai 640G | 32 GB | 10核 | 640 GB | 5 TB | 1 Gbps | $289.99/月，$2759.99/年 | [ 查看套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=119) |
| Dubai 1280G | 64 GB | 12核 | 1280 GB | 6 TB | 1 Gbps | $549.99/月，$5399.99/年 | [ 查看套餐](https://bandwagonhost.com/aff.php?aff=79616&pid=120) |

所有套餐均为 KVM 虚构化（KiwiVM 面板），带免费自动备份、免费快照、1 个独立 IPv4 和 /64 IPv6，支持 CentOS、Debian、Ubuntu、RockyLinux、AlmaLinux，在线率保障 99.95%（SLA 系列为 99.99%）。全部是自管服务，官方不提供代运维。

## 最后的购买建议

如果你认定了 10G KVM PROMO V5，那就把补货通知渠道设好，看到通知当天内下单，用年付 49.99 美元把这款三网 CN2 GIA 的门票拿到手。抢不到也别硬等——预算翻三倍买常规 CN2 GIA-E 20G，配置翻倍、流量翻倍、带宽翻倍还常年有货，对很多人来说反而是更省心的选择。

唯一要记住的是：这款套餐买了大概率是长期持有的，CPU 限制决定了它的天花板，但只要你的用途是“稳稳地连上去”而不是“使劲跑”，它至今仍是搬瓦工产品线里性价比最不讲道理的一个。

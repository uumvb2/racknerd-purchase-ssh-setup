# racknerd 购买教程：从选套餐到 SSH 登录，新手一次搞懂两条产品线的价格差异、真实续费价和下单避坑点

RackNerd 的购买流程本身很简单：官网选套餐 → 选机房 → 付款 → 收开通邮件，全程十几分钟。真正容易踩坑的是选套餐这一步——官网同时挂着两条产品线，价格体系完全不同，选错一条线，同样的钱可能只买到别人一半的配置。这篇教程按实际下单顺序讲清楚每一步该怎么选。

> **选购速览**：大多数预算敏感的个人用户，直接选常年挂在 specials 页面的年付 KVM 特价套餐即可。入门档 1 GB（1 vCPU / 20 GB SSD / 3 TB 月流量）**$21.99/年**，折合每月约 $1.83，官方明确写明终身同价续费。👉 [查看 RackNerd 特价套餐当前价格](https://bit.ly/RacKnerd)

## 先分清两条产品线：特价年付 vs 常规月付

这是 RackNerd 官网最容易被新手忽略的一件事：KVM VPS 有两条并行产品线，计费方式和性价比差异很大。

**一条是 specials 特价线**，常年挂在官网 specials 页面，只按年付出售，价格压得很低，官方标注为终身同价续费。另一条是**常规 KVM VPS 线**，按月付费为主，适合需要灵活随时取消的用户，但同样内存档位下单价明显更高。

**Specials 特价套餐（全部年付，续费同价）：**

| 套餐 | 内存 / CPU | SSD 存储 | 月流量 | 年付价格 | 购买入口 |
| --- | --- | --- | --- | --- | --- |
| 1 GB Special（最受欢迎） | 1 GB / 1 vCPU | 20 GB RAID-10 | 3 TB @ 1Gbps | $21.99/年 | [ 开通 1 GB Special](https://my.racknerd.com/cart.php?a=add&pid=952&aff=11397) |
| 2 GB Special | 2 GB / 2 vCPU | 35 GB RAID-10 | 5 TB @ 1Gbps | $35.99/年 | [ 开通 2 GB Special](https://my.racknerd.com/cart.php?a=add&pid=953&aff=11397) |
| 4 GB Special | 4 GB / 3 vCPU | 60 GB RAID-10 | 7 TB @ 1Gbps | $59.99/年 | [ 开通 4 GB Special](https://my.racknerd.com/cart.php?a=add&pid=954&aff=11397) |
| 6 GB Special | 6 GB / 6 vCPU | 100 GB RAID-10 | 12 TB @ 1Gbps | $89.99/年 | [ 开通 6 GB Special](https://my.racknerd.com/cart.php?a=add&pid=955&aff=11397) |
| 8 GB Special | 8 GB / 7 vCPU | 150 GB RAID-10 | 20 TB @ 1Gbps | $119.99/年 | [ 开通 8 GB Special](https://my.racknerd.com/cart.php?a=add&pid=956&aff=11397) |

**常规 KVM VPS 套餐（洛杉矶 Asia Optimized 线路，月付为主）：**

| 套餐 | 内存 / CPU | SSD 存储 | 月流量 | 价格 | 购买入口 |
| --- | --- | --- | --- | --- | --- |
| 512 MB | 512 MB / 1 vCore | 30 GB RAID-10 | 500 GB @ 1Gbps | $26.99/年 | [ 购买 512 MB 方案](https://my.racknerd.com/cart.php?a=add&pid=1&aff=11397) |
| 1 GB | 1 GB / 2 vCore | 50 GB RAID-10 | 1 TB @ 1Gbps | $17.99/月 | [ 购买 1 GB 方案](https://my.racknerd.com/cart.php?a=add&pid=20&aff=11397) |
| 2 GB | 2 GB / 3 vCore | 75 GB RAID-10 | 2 TB @ 1Gbps | $20.59/月 | [ 购买 2 GB 方案](https://my.racknerd.com/cart.php?a=add&pid=21&aff=11397) |
| 4 GB | 4 GB / 4 vCore | 130 GB RAID-10 | 3 TB @ 1Gbps | $24.59/月 | [ 购买 4 GB 方案](https://my.racknerd.com/cart.php?a=add&pid=22&aff=11397) |
| 6 GB | 6 GB / 5 vCore | 170 GB RAID-10 | 4 TB @ 1Gbps | $27.59/月 | [ 购买 6 GB 方案](https://my.racknerd.com/cart.php?a=add&pid=23&aff=11397) |
| 8 GB | 8 GB / 6 vCore | 220 GB RAID-10 | 5 TB @ 1Gbps | $36.59/月 | [ 购买 8 GB 方案](https://my.racknerd.com/cart.php?a=add&pid=24&aff=11397) |
| 12 GB | 12 GB / 7 vCore | 300 GB RAID-10 | 6 TB @ 1Gbps | $55.99/月 | [ 购买 12 GB 方案](https://my.racknerd.com/cart.php?a=add&pid=25&aff=11397) |

两条线里有三个容易被忽视的价格细节：

1. **常规线的 512 MB 套餐是年付 $26.99**，而 specials 线的 1 GB 套餐年付只要 $21.99。同样一年的钱，特价线内存翻倍、流量翻六倍。除非你明确需要 30 GB 硬盘或特定机房，否则这个 512 MB 方案没有选的理由。
2. **常规线月付的 1 GB 是 $17.99/月**，一年就是 $215.88，是特价线 1 GB（$21.99/年）的近十倍。月付的价值在于灵活，不在于省钱。
3. 除了黑五、新年这类节日节点会放出库存有限的更低价套餐（往年 1 GB 年付曾低至 $10.60 一档），**常年可买的价格基准就是上表 specials 页的数字**。节日套餐卖完即下架，不建议为了等促销一直拖着不买。

## 下单流程：六步走完

从点开套餐到能 SSH 登录，整个流程是这样的：

1. **选套餐**。在上面的表格里点对应方案的购买链接，进入购物车页面。
2. **选机房**。RackNerd 自有基础设施覆盖约 20 个数据中心位置，包括洛杉矶、圣何塞、西雅图、达拉斯、芝加哥、纽约、亚特兰大、阿什本、多伦多、阿姆斯特丹、伦敦、都柏林等。热门机房偶尔断货，选不了就换邻近的。
3. **选操作系统**。下单时可以选 CentOS、Rocky Linux、AlmaLinux、Fedora、Debian 或 Ubuntu；想装别的系统，开通后开工单申请 custom ISO 即可。
4. **付款**。支持 PayPal、信用卡，以及通过 Coinify 用 30 多种加密货币支付。年付套餐一次性扣全年费用。
5. **收开通邮件**。付款后几分钟内会收到包含 IP 地址、root 密码和控制面板登录信息的邮件。
6. **连接服务器**。Mac/Linux 直接 `ssh root@你的IP`，Windows 用系统自带 SSH 客户端或 PuTTY。登录后先改 root 密码。

套餐是 KVM 虚拟化、非托管服务（unmanaged），也就是说系统层面的问题要自己解决，RackNerd 负责 24/7 的工单支持应对网络、硬件和面板层面的问题。

## 机房怎么选：看你的用户在哪

选机房的核心标准只有一个：离你的访问者近。给国内用户用，就选美西的洛杉矶或圣何塞——有长期使用者反馈，美西机房从国内连接的延迟普遍在 150–200ms 区间，晚高峰相对稳定；美东的纽约机房延迟会到 250–300ms 起步。主要面向欧洲用户就选阿姆斯特丹、伦敦或都柏林，美国本土用户则按地理就近选达拉斯、芝加哥或东海岸节点即可。

另外一件事很少有文章提到：**免费 IPv6 地址目前只在洛杉矶和法国机房提供**，最多可申请 100 个，需要开通服务后单独开工单索取，其他机房暂不支持。如果你的项目明确需要 IPv6，下单时就要把机房定在洛杉矶或法国。

## 续费价格的真实情况

这是搜“racknd 购买教程”的人最常带着的疑问：第一年 $21.99，第二年会不会涨到几十刀？按官方 specials 页面的明确说明：**这些特价套餐是终身同价续费的，你想保留服务多久，就可以按同一个价格续多久。** 续费操作是登录客户区 → Services 页面 → 打开对应 VPS → 点 "Generate Renewal Invoice" 生成账单后支付，支持提前续费。

有两处边界要讲清楚。其一，同价续费只覆盖你下单时买的那台机器那个套餐；中途想升级配置，是按新套餐当前价格算的，而且 RackNerd 支持升到上一档（升级只需一次约 1 分钟的重启），不支持降级，也不能把已购资源合并。其二，节日限定的超低价套餐在库存卖完后，下一年度可能不再以原套餐开放续费，官方会提前邮件通知并引导迁移到 specials 同档套餐——常年 specials 页面那批套餐没有这个问题。

👉 [锁定终身同价续费的年付套餐](https://bit.ly/RacKnerd)

## 按用途定内存：一键应用的内存门槛

RackNerd 所有特价套餐都带自家 ctrl 控制面板，除了常规的重启、重装系统、HTML5 VNC 控制台、防火墙规则，还内置了一键应用安装，应用装好后凭据直接在面板里显示。官方给出的各应用内存要求很明确：

- **OpenClaw：至少 8 GB 内存**（也就是只有 8 GB Special 能跑）
- Hermes Agent、AnythingLLM、Ollama、LibreChat：至少 4 GB
- n8n、Coolify：2 GB 即可
- Docker 也可以跑，ctrl 一键装 Portainer，或者自己 SSH 上去装

这个清单其实是最实用的选套餐依据。只想挂个博客、跑几个轻量脚本，1 GB 够用；打算自建 AI 相关服务或跑一组 Docker 容器，4 GB 是起步线；想在面板里直接一键部署 OpenClaw 这类大内存应用，就只能上 8 GB Special。👉 [开通 4 GB Special 跑 Ollama、n8n 这类应用](https://my.racknerd.com/cart.php?a=add&pid=954&aff=11397)

## 几个常见问题

**买完之后能不能换机房？** 可以。RackNerd 支持同一套餐在不同机房之间免费迁移，热门机房断货时先买其他机房、之后再迁，是可行的操作路径。

**买错了套餐怎么办？** 套餐本身可以升级到上一档（升级按新套餐当前价格计费，需一次短暂重启），不支持降级。所以拿不准配置时，宁可从低档买起，不够再升。

**支持什么付款方式？** PayPal、信用卡，以及通过 Coinify 支持 30 多种加密货币。没有支付宝或微信支付。

**系统坏了能自己救吗？** 可以。ctrl 面板里有 HTML5 VNC 带外控制台，系统进不去也能进控制台排障或重装，root 密码也能在面板里直接重置。

**要不要用优惠码？** specials 页面的特价套餐不需要填任何优惠码，页面价格即最终价。看到需要输码才能享受的价格，反而不在官方常年特价范围内。

## 下单前的最后确认

按用途给个直白的结论：练手、挂博客、跑轻量脚本，1 GB Special $21.99/年 起步即可；小站加数据库、跑 n8n 或 Coolify，选 2–4 GB；自建 AI 应用或跑一组服务，直接上 8 GB Special，$119.99/年 换 7 核 CPU、150 GB SSD 和 20 TB 月流量。需要月付灵活性的再考虑常规 KVM 线，单纯图便宜的不要碰那条线。下单前确认两件事：机房是否给到（热门位置偶尔缺货），以及是否需要 IPv6——需要的话机房必须是洛杉矶或法国。👉 [前往 RackNerd 选好机房并完成下单](https://bit.ly/RacKnerd)

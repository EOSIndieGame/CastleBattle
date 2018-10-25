# CastleBattle

![CastleBattle](https://github.com/EOSIndieGame/CastleBattle/blob/master/castlebattle-256.png)

Castle Battle（城堡战争）是一款基于 EOS区块链的多人在线策略类角色扮演游戏，BM-RPG (Blockchain based Multiplayer Role-playing Game)。
由 EOSIndieGame 开发


## 游戏世界观

### 第一章：荒蛮对抗 （当前）

> 布洛克世界元年，第一个生命体在碧特大陆诞生。
> 布洛克5年，以塞瑞姆大陆出现高级文明。
> 布洛克9年6月，依欧艾斯大陆异军突起，进入荒蛮生长的阶段。同年10月，大陆逐渐出现小规模的团体，据守在不同的城堡，以掠夺其他城堡资源为乐，至此在依欧艾斯大陆上的荒蛮对抗拉开了序幕...


### 第二章：王城战争

> 经过一段时间毫无组织的资源掠夺，人们发现，单打独斗已经无法获得稳定的资源，于是开始考虑拉帮结派建立联盟，随着联盟的不断扩大，攻城略地，最终成为了规模庞大的王城。至此，城堡间的摩擦正式升级为国家级别的王城战争！


### 第三章：战后重建

> 长达1年的王城战争对这片依欧艾斯大陆造成了沉重的代价。存活下来的几个超级大国也开始反思并寻求更多的合作，重建家园。为了不让士兵们失去斗志，各个超级王城之间约定：定期举行友谊第一的”王城杯锦标赛“。


### 第四章：地下城探秘

> 布洛克11年，依欧艾斯大陆一片繁荣，超级大国早已恢复了元气，随着领土的不断扩张，人们开始去探索依欧艾斯大陆那些人迹罕至的未知领域以获取更多的知识与财宝...


### 第五章：发现新大陆！






## 游戏玩法

### 第一章：荒蛮对抗（公测中。新角色，新道具持续更新中）

在游戏开始前的3分钟，为游戏准备阶段，游戏准备的这3分钟内，用户可以投入0.2 - 3个数量之间的EOS，作为游戏中的对战资源。每局游戏所有玩家最大投入EOS总数为40 EOS，到达这个值后，不再允许加入更多玩家。 

准备时间结束后，会根据用户的资源数量随机分成2只队伍：红队和蓝队，在准备阶段成功投入EOS的玩家方可进入游戏。

游戏界面 分为上中下 3个部分。

上面是战斗画面，中间是双方城堡基本属性、兵力以及队伍资源使用情况，下面为用户的操作区域，用户仅可以使用在准备阶段投入的EOS数量(0.2 - 3)，最下面的属性条显示的是本局游戏的剩余时间，以及个人本轮可用资源的情况。

游戏的目标是在5分钟内通过派兵，巩固城防等方式保护自己的城堡，打爆对方的城堡，如果5分钟内 双方城堡都没有被打爆，血量高的一方胜利。

失败方投入EOS的95%将作为奖金按胜利方用户投入比例分配给胜利方，另外5%作为开发团队的研发费用。 同时所有参与的玩家都会获得10 * 投入EOS数量的平台代币IGC (Indie Game Coin) 作为奖励。 *平台代币可用于解锁额外的兵种或道具卡牌等。


** 游戏内容不断更新中，大家对游戏内容有任何意见可以向我们提: eosindiegame@163.com ，也可以直接在 github提issue **


### 第二章：王城战争（开发中）


## 兵种及道具说明简介：

### 兵种：

#### 步兵小勇：

小勇是最基本的步兵单位，攻守兼备。 

价格：0.2， 攻击：10，防御：10，血量：60，速度：3


#### 弓手小方（需要使用IGC解锁）：

小方射出的箭，可以无视城堡的额外防御，一直以基本的城堡防御(10)计算。

价格： 0.2，攻击：20，防御： 6，血量：40，速度：5

#### 法师小月（开发中）



### 道具：

#### 城堡防御：

给城墙增加额外的防御力

价格：0.4，增加城堡防御力 0.5


#### 城堡血量：

修复城墙损坏的部分

价格：0.2，增加城堡血量 45


#### 城堡攻击（需要使用IGC解锁）：

给城堡增加额外的攻击力

价格：0.6，增加城堡攻击力 0.8





## 计算公式以及部分数据

- 士兵每秒掉血量 = 城堡攻击力 / 士兵防御力  

- 城堡每秒掉血量 = 士兵攻击力 / 城堡防御力

- 城堡初始数据： 血量：5000，攻击：10，防御：10

- 2个城堡之间的距离是100。

- 士兵从发出到敌方城堡的时间(s) =  距离(100) / 士兵速度

### 补充

- 城堡默认对所有正在攻击城堡的士兵造成伤害。
- 部分兵种会有特殊的技能，比如 弓手小方 会忽略城堡额外增加的防御力。
- 未来可能会根据用户数量以及反馈修改部分数据。
- **以上游戏参数，投入数量，每局时间等数据会根据游戏的情况，再不影响平衡性的情况下进行调整**




## TOKEN IGC (Indie Game Coin)

Castle Battle 作为 EOSIndieGame 的第一款游戏，共解锁 30000000 枚 Token。

IGC作为游戏中的代币主要应用场景有：前期解锁购买新的角色和道具卡牌，后面的游戏内容包括但不限于建立联盟，发起联盟之间的战争，解锁地下城副本等。

其中游戏过程中产出70%，5%用于游戏在未来运营活动和宣传中使用，5%用于奖励对游戏有突出贡献的玩家，剩下20%为团队保留。


Token IGC 更具体介绍的请查看： [EOS-IndieGame](https://github.com/EOSIndieGame/EOS-IndieGame#tokenigc-indie-game-coin)




## 开源与合作

- 所有玩家除了可以对游戏内容提出意见和反馈，也可以参与到 开发与设计当中： 比如：设计新的角色、道具属性和动画效果，为游戏绘制新的场景等等。
- 第三方项目团队可以以赞助的形式（赞助优先考虑空投持IGC玩家），在不影响用户体验和平衡性的前提下，将自己品牌的一些元素植入游戏中，包括但不限于ui，token或游戏元素的植入。
- 邮箱：eosindiegame@163.com 以及 [Github issue](https://github.com/EOSIndieGame/CastleBattle/issues)




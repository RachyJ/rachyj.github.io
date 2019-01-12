---
layout: post
title: 2018 AI and Agile Conference 之智能时代
category: selfedu
description: 2018敏捷与人工智能峰会(Agile & AI Conference)之人工智能
---

周六参加了在思科杭州研发中心举行的“2018人工智能及敏捷大会”，大会的主题是“智能时代、敏捷先行”，这篇先总结一下人工智能方面的收获。

会议日程如下：

![大会日程](https://mmbiz.qpic.cn/mmbiz_png/pF9WtFDsDfNsvEXKhBgctd9N59oriayrHc2nhzck2gZxe1ChS79DyNkdbMHCbibrYpBjS0tjFQWx4oVXMPwOXicibg/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1)



## 大会总体印象

这次活动总体的印象挺好的。

8点多到会议大楼时，看到显眼的大会横幅，有小姐姐给我们金色签字笔签字留念。到了刷票，领访客牌，以及印有cisco和会议名称的帆布袋，里面有本子、笔、思科的钥匙扣，对自身品牌的推广做的挺好。

![](http://p319p95sa.bkt.clouddn.com/entrance-banner.jpg)

会议有专门负责在线直播业务方承接，有线上同步直播。会议设备看起来很高大上，毕竟思科是做这块业务的。

中午有营养平衡套餐，下午有茶歇、甜点，还有自助的咖啡和茶。有双头胶囊咖啡机和雀巢自动咖啡机，TWILIGHT茶包，菊花、枸杞等各种茶。

虽然开始和中间有些延迟，整体会议进行有序。

## 人工智能是什么

人工智能是什么？1956年，约翰·麦卡锡（ John McCarthy ）在达特茅斯会议上首次提出 Artificial Intelligence（人工智能）的概念。

> The study is to proceed on the basis of the conjecture that every aspect of learning or any other feature of intelligence can in principle be so precisely described that a machine can be made to simulate it.

简单来说，就是让机器拥有人的智能。

那人工智能的本质是什么呢？我觉得[这篇文章](https://mp.weixin.qq.com/s?__biz=MzI0ODcxODk5OA==&mid=2247485917&idx=2&sn=85c272a0947bddeb5f467f8a2212c856&chksm=e99d3a24deeab3322318e0ce9fc4e5417976fc7fc9defe5633d6d3692e8e6b477c49a337522b&mpshare=1&scene=1&srcid=0313SvLrge7AbzoEjfRDCQE9&pass_ticket=5WAacBCK1%2B4tIIr1%2B%2Bk4EeHF9cMhI7FZLh3c%2B%2FpwEQFzhCSly7tIcr0ndDLLG8rZ#rd)总结的挺好：人工智能的本质，就是用机器的”硅基大脑“来模拟或重现人类的”碳基大脑“。

![](http://p319p95sa.bkt.clouddn.com/machine-human-brain.jpg)

人工智能包含很多技术，我还只接触了皮毛，大概的版图：

![](http://p319p95sa.bkt.clouddn.com/AI-umbrella.png)

对人工智能的印象大多还比较粗浅，通过几个老师的分享，从应用和实现算法角度获取了一些新的知识。

## 人体运动行为感知与解析及其人机交互应用 

> 刘洪海，上海交通大学讲席教授，中组部千人计划。英国伦敦大学国王学院博士学位。刘洪海教授主要从事人体运动行为感知技术，生机电一体化及智能机器人理论与应用等方面的研究，在广义机器人系统运动学及“运动／认知”集成模型，人体运动信息检测、处理与生机电一体化系统技术，和定性模糊方法和在故障诊断上的应用等智能计算和智能机器人领域有较大国际影响。

### 有智能的假肢

想到假肢，你脑海中跳出的画面是什么？我首先想到的是僵硬的机械。

刘教授分享了他们在研究的假肢的一些最新进展：不仅每个指关节可以灵活运动，还可以通过智能分析肌肉信号自动控制假肢，作出相应的动作。这意味着，人们不用操作机械的开关，假肢能‘理解’人体的神经信号，做出相应的动作，甚至是一些很细微的动作。

大致的工作流程为：获取信号 - 算法分析 - 确定动作意图 - 发送指令 - 假肢做出相应动作。

理想情况，假肢可以直接理解脑电信号，但脑电信号微弱，噪声较多，实际运用中难度较大。肌肉收缩时的电信号 - 肌电信号（EMG），强度更大，可以更好地进行采集和分析。但肌电信号只能用于部分截肢，还有足够的肌肉可以用于信号采集的情况。如果是手臂全部截肢怎么办呢？这种情况可以把胳膊的主神经植入胸腔，这样大脑发给断臂的指令就会到达胸腔的位置。通过采集胸腔处的神经信号，算法分析，进而控制假肢。

Todd Kuiken在TED的演讲中分析了几个详细案例，可以看到智能假肢的发展和运用。
[Todd Kuiken: 托德･库伊肯: 有触觉的假肢 | TED Talk](https://www.ted.com/talks/todd_kuiken_a_prosthetic_arm_that_feels?language=zh-cn)

在不远的将来，希望有更多残障人士可以从中获益，可以有智能而灵敏的机械手弥补缺憾。

### 人工智能用于自闭症早期诊断

自闭症也称孤独症，通常在2-3岁表现出明显症状，主要表现为不同程度的语言发育障碍、人际交往障碍、兴趣狭窄和行为方式刻板。约有3/4的患者伴有明显的精神发育迟滞，部门患儿在某些方面会表现出极好的能力，比如电影[《雨人》](https://movie.douban.com/subject/1291870/)中的患有自闭症的雷蒙就有超强的记忆和算术能力。

自闭症的发病率呈上升趋势。美国疾病控制和预防中心估计，在美国59个儿童中有一个自闭症患者，其中多以男孩为主，男孩的自闭症发病比例为1/37, 女孩为1/151.

目前，大家对自闭症的具体发病原因还不清楚，只知是基因和环境共同影响所致。

自闭症儿童发病后的伤害通常很难逆转，如何尽早诊断，采取干预治疗，有重要意义。传统方法采用人工访谈，费时费力，而且准确率不高。刘教授演示了他们如何分析孩子的视频，进行目光注意力跟踪与识别帮助自闭症诊断。

![](http://p319p95sa.bkt.clouddn.com/eye-tracking.jpg)

Reference：[What Is Autism? | | Autism Speaks](https://www.autismspeaks.org/what-autism)

## 推荐算法在广告点击率预估上的应用

> 刘大鹏：腾讯广告推荐组 leader，具有10多年大数据挖掘及在相关领域精准推荐应用的工作经验，目前主要负责腾讯社交效果广告点击率预估及其优化。通过系统、算法、特征三位一体，追求技术与业务的最优结合，提升广告推荐效果。

腾讯的刘大鹏说了很多技术层面优化广告点击率的推荐算法演化历程。听起来他对于做技术乐在其中，放几页ppt。从消费者的角度，可以遇见未来接触的广告会越来越定制化，越来越”勾引“我们的钱包，所以谨记理性消费。

![](http://p319p95sa.bkt.clouddn.com/ad-challenge.jpg)

![](http://p319p95sa.bkt.clouddn.com/ad-algorithm-interation.jpg)

![](http://p319p95sa.bkt.clouddn.com/ad-understand-users.jpg)

## AICloud

随着业务对数据处理需求的不断增长，依赖网络将所需数据传到数据中心的云计算已经不能满足需求，一方面数据大，网络资源消耗大，另一方面，传输和处理的延时严重。海康威视介绍了他们的AICloud框架 - 云中心、边缘域、边缘节点。通过将边缘/终端设备智能化(内置集成智能芯片)，比如，在道路视频流中，通过车牌识别算法、人脸识别算法等，可以更高效地提取车牌信息和人脸等目标数据，在采集数据时更精准有效，传输目标数据更高效，从而提高数据处理和响应效率。

如果分享者可以以更通俗的语言，结合具体场景，可以让我这样的小白也能听懂的话更好。

Reference: 

[海康威视发布“AI Cloud”框架 行业应用全面开启_中证网](http://www.cs.com.cn/ssgs/gsxw/201710/t20171029_5540874.html)

[【企业观察----海康威视---AI Cloud解读】 - 雪球](https://xueqiu.com/7096399426/97854949)
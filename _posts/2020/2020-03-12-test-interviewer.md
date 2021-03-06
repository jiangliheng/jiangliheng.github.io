---
layout: post
title: "作为测试面试官给求职者的一些建议"
date: "2020-03-12 22:00"
category: 软件测试
tags: 软件测试 面试
author: jiangliheng
---
* content
{:toc}

最近公司业务快速发展，整个研发团队都在加紧招聘人员，我主要负责测试和运维的初面，偶尔参与二面。从年前到今天为止，陆陆续续收到简历仅百人（测试占大多数），进入初面的大概50%，初面通过的不到30%，进入二面就更少了，还有在面试通过后被 HR 干掉的。

企业招聘基本上都是找最“**合适**”的人，而不是找技术最牛或最优秀的人。主要原因：一是岗位匹配度；二是性价比问题。



# 简历筛选
以测试工程师的招聘来说说简历筛选过程。

## HR 筛选
HR一般会按照招聘要求中的关键字来搜索简历，比如接口自动化测试、性能测试、某些编程语言及工具、行业领域、专业证书等。

前期简历基本是海选+投递。

中后期面试官根据简历的质量，会适时调整招聘要求（针对投递）和筛选简历的关键字（针对海选）。

在招聘中高级测试人员时，我通常会让 HR 搜索的关键字：**软件评测师（软考中级）、PMP、特定技术栈工具**。

选择特定技术栈工具原因很简单：匹配度高，入职稍加培训即可进入工作状态。

至于为什么选择软件评测师和 PMP证书呢？
1. 证件本身就可以证明一个人的能力。
2. 我自己考过了，知道其中所要花费的时间和精力，以及这学习过程中的收获。
  - 软件评测师我考过2次。第一次是12年，匆忙准备2周左右，上午题过了，下午题差10分；第二次是14年，准备1个月左右考过了。
  - PMP 是15年带着几个同事一起考过的，准备了3个月左右，每天不少于2小时，我基本都是在上下班地铁上学习的，书研读不少于3遍。

**强烈推荐大家也去学习和考取这2个证书。**

## 面试官筛选
我一般根据岗位职责和技术要求，筛选简历时会有一些硬性条件。比如：
- **技能匹配度**；
- **业务匹配度**；
- **技术栈：特定编程语言或工具**。

其他非硬性条件，但也可能会被 Pass 掉。比如：
- **工作稳定性**：如果少于一年甚至是3-4个月换一个公司的，基本都不会考虑；
- **简历排版、错别字、专业性**，更严重的是简历与面试岗位不符合，曾经碰见过拿着产品经理的简历来面试测试工程师（他也确实做过测试工作）。

# 面试考察点
在面试时，通常会考察如下几点：
- **测试理论**：主要考察有没有扎实的测试理论基础，以及成体系的测试思想和理念。再强的能力也要建立在牢固的理论基础上。软件评测师的知识体系会有所帮助；
- **测试技术**：考察对用到的技术有没有足够的经验和深入的理解，比如：测试设计、操作系统、系统架构、数据库、linux、测试工具等相关技术；
- **代码能力**：最基本的编码能力，较好的逻辑思维能力，对于高级性能测试工程师，还要考虑算法效率方面；
- **管理能力**：初级岗位一般没有很高的要求。对于中高级岗位，通常考察团队管理、项目管理相关知识。PMP 体系知识会有所帮助；
- **业务能力**：领域知识和产品相关经验；
- **软技能**：自我学习意识、沟通能力、团队合作、执行力、时间观念、抗压能力等。

我个人重点关注的如下：
- **测试理论**
- **自主学习**
- **执行力**
- **沟通表达**
- **代码能力**

# 面试过程
我面试的基本原则是：所有的细节交流一定是基于对方简历和交流过程中所提及的；经验较少或未做过测试的主要看思路和自主学习意识。

## 自我介绍
时间1分钟以内，重点放在自己担任的角色和工作职责，突出自己的能力和成绩，项目情况占20%左右即可。若曾经的业务领域和项目与岗位相匹配，可以重点介绍一些。注意语言要简明扼要。

切忌冗长漫无目的的表述。

**考察点**

规划和表达能力。

## 离职原因
合理的理由，正能量的表达。

**考察点**

判断求职者的稳定性，挖掘隐性问题。

## 职业规划
诚实表达，合理规划。通常我会追问为了这个目标做过哪些学习和努力。

**考察点**

考察求职者的规划能力，愿景，以及工作动力。自我学习意识。

## 测试理论及技能
**问测试理论广度和深度**
针对登录功能设计下测试用例？
- 广度：各种测试类型及相应的测试设计方法和要点。
- 深度：每个测试类型下的细节。比如：测试用例设计方法有哪些？测试用例设计方法分别适用于什么场景，如何选择？判定表和因果图的区别？因果图设计用例步骤？缺陷能定位到代码行不？能定位到行的话，之后再问能改不？

**性能测试的广度和深度**
简单介绍下性能测试怎么做的？
- 听过基准测试没有？听过涌浪测试没，作用是什么？听过混合场景测试没？单场景和混合场景的区别，各自侧重点是什么？
    - 听过，基准测试怎么做？整个性能测试过程中起到什么作用？
- 做过瓶颈定位和性能调优没？
    - 举个例子说明
- 了解 sql 调优不？
    - 了解，常规调优手段有那些？分析过执行计划没?
- 了解 jvm 内存模型不？调优过没？
    - 如果了解，又会有很多深入的问题。比如：如何分析内存泄露，工具和命令用过哪些？Full GC 什么情况下会出现？看过GC log 没，GC 算法有哪些？分析过热点文件没？怎么分析的？分析完可以改不？

**考察点**

理论是否扎实，技术细节是否了解，考察技能的广度和深度，以及技术能力高低。

## 发散性问题
一般针对中高级会提问些发散性问题，比如：测试团队如何建设？不熟悉的业务领域功能怎么开展测试工作？

**考察点**

考察知识体系，测试思维和做事思路。

## 经验较少的领域
我通常会问他不熟悉的相关模块是如何工作的？或者他们的开发人员是如何工作的？产品形态以及如何盈利等等？

日常多关注多思考，诚实表达。

切忌回答：不是我负责的，我不太清楚；我工作太忙，没有时间等等此类消极的话。

**考察点**

主动学习、主动思考和整体把握能力。

## 解决问题的经历
工作中有没有遇到过什么难题，你是怎么解决的？性能测试中有没有怎么定位瓶颈和调优的，举个例子？

尽量将这个问题诠释出来，说一定比不说要好。

**考察点**

解决问题的思路和方法，以及部分技术细节。

## 查缺补漏
除了以上我们谈到的，还有没有您觉得做的还不错的，非测试工作也可以？

**考察点**

寻找加分项，考察其他知识面，以及主动学习能力；

## 向面试官提问
从公司，项目，职位，技术等方向进行提问。

**考察点**

考察求职者的主动思考能力，对公司职位的青睐度。

## 期望薪资
一般在面试结束时，才问期望薪资。根据市场行情和自身价值评估，说出一个区间值即可。

切忌反问，一方面显得不自信，另一方面也不会告诉你具体范围。

**考察点**

技能和薪资匹配度。

# 面试技巧
打铁还需自身硬，多多提升自己的能力。不要再想什么技巧了，所有的技巧基本上都没有什么用处，再好的技巧都是为了掩饰。

多展现积极主动的工作态度和责任心，是非常加分的。

面试通过后，又被 HR 刷掉的一部分就是被所谓的技巧坑害了。

# 面试官自我反思
对于面试官来说，你能真实考察出应聘者的能力吗？你判断的依据又是什么？

千里马难寻的背后往往是因为伯乐太少。

面试的过程其实是双方选择的过程，可以通过面试了解岗位的情况，以便做出适合自己的决定。

面试要坦诚，别装，即便你骗过了面试官，在之后的工作中你也骗不了。

**公司找合适的人，个人选择适合自己的公司。**

> 微信公众号：daodaotest

--- 
layout: post
title: "从Google搜索联想到了jQuery"
wordpress_id: 245
wordpress_url: http://www.wsria.com/?p=245
date: 2009-02-20 22:10:17 +08:00
category: google
tags: 
 - google
---
在用<a href="http://www.google.com/reader/shared/03764621998712729908" target="_blank">google阅读器</a>阅读新闻时看到一篇文章让我想到了很多，文章的标题《越Google，越无知？》，让我想到了前端程序员热爱的轻量级ajax框架jQuery，它以简单、快速编写javascript的方式方便了万万个程序员，而且我们不用考虑各种浏览器直接的差异，从而极大提高了开发效率；并且被微软、Nokia所使用，你有没有考虑过另外一方面呢？……
<!--more-->
下面是原文：
<pre><strong>被利益集团操纵的信息发布会使人失去判断力,海量阅读会改变人的思维方式,这样的担忧,两千多年前就有了.</strong>
佛罗里达州立大学道尔大厅的门楣上,刻着一句话:“知识的一半,是知道到哪里去寻找.”这句话现在可以改一下:“知识的一半,就是Google.”以 Google为代表的搜索引擎将人们获取信息的途径简化为键盘上的几次敲击,而搜索到的信息,足以让世界上最博学的人自叹不如.全人类历史上的所有智慧成 果就在指尖,触手可及.

这 种颠覆传统的技术也引发了不少担心和恐慌.2008年,一篇《Google在让我们变傻吗?》又引发关于新技术和人类能力关系的讨论.之所以说“又”,是 因为此类讨论并非首次.传说仓颉造字时“天雨粟,鬼夜哭”,满天神佛都表示不满;古登堡发明金属活字印刷术后,许多人说这种技术会让异端邪说蛊惑人心;世 界上第一台手持式计算器面世,有人担心它会降低人们的算数能力.

伴随着Google信息如潮水般汹涌而来的,是我们日益分散的注意力.马克·鲍尔莱因在《最愚蠢的一代:数字时代如何让美国年轻人变愚笨而且威胁到我们的 未来》一书中写道:网络时代成长起来的年轻人往往无法保持足够的注意力来读完一本书,甚至无法用心领会一首诗的含义;而麦琪·杰克逊在《正在到来的黑暗时 代》中警告说,我们的注意力在互联网的影响下会越来越分散,更容易陷入片面的认知,最终可能会沦为介于人和机器之间的怪物.

这些说法看上去很有道理.我们习惯了上网浏览,而非捧卷阅读;我们习惯了从一个主题沿着超级链接跳向另一个主题,而非一页接一页地逐步积累.总之,我们习惯了点到即止,走马观花.毕竟,我们面前摊开的是一个无尽的世界.

一些心理学家认为,这种全新的阅读方式将会影响我们的思考方式.这种“跳跃式”和“效率至上”的阅读方式会让我们的大脑变成一个“中转站”,被大量片面的 信息迅速填满而无暇思考.我们专注阅读和深入理解的能力会下降,而联想能力也会因此而逐渐丧失,随之而去的还有创造力——而创造力,正是人类智能的标志之 一.

互联网上无限制的信息还会带来另外一些副作用.斯坦福大学的科学史教授罗伯特·普罗科托认为,由于拥有大量金钱和权力的利益集团参与和操纵,网上信息的真实程度往往值得质疑.换句话说,互联网上的更多信息可能会让人变得无所适从,变得更加无知.

事实上,大哲人苏格拉底在两千多年前就提出过类似观点.他担心因为文字的发明,使书籍取代了人类本来应该存放在大脑中的知识,人类将“停止锻炼记忆从而变 得健忘”.因为书籍,人类可以“无需适当的指引便可获取大量信息”,于是“自认为拥有了知识,但实际上大多数时候都相当无知”,于是人们会“自负地认为自 己拥有智慧,但事实上并非如此”.苏格拉底的论述,是多么地符合众多“Google依赖者”的特征.

这种担心是合理的.然而,Google也不过只是一种工具而已,说它将会降低人的思考能力,未免有点夸大其辞了.我们不能说使用Google就会让人的智 力下降,正如我们不能说坐飞机就会降低人的体能一样.如何使用信息,和注意力的分配方式一样,是由我们自己的经历和经验所决定的.这一切的控制权依然在我 们手里,Google并不能代替我们思考.在这个意义上,Google和一个图书馆的图书索引并没有什么本质的不同.</pre>
看完这篇文章仔细的想想的确是这样的，只要在电脑前面或者手机可以上网我们遇到不懂的就会google一下，他会告诉我们一切的一切，所以我们离不开google，长时间形成的习惯就是只要遇到不会的就google一下，google会告诉我们正确的答案而且很及时，我们不用在像在图书馆书的海洋里一本本的翻阅，或许还没有找到我们想要的答案……，着及时为什么我们不能离开google的原因，当然本文不是谈论离开google

<strong>切入正题</strong>
话题转到我们经常使用的框架上来，程序员因为懒所以才开发了框架，没有几个程序员愿意整天复制重复的代码，有问题时又重复修改有问题的方法，这是愚蠢的做法，稍微有点开发经验的人肯定会写自己的公共方法、类库等等。就拿现在主流的jQuery来说吧，他确实很优秀，优秀到我们什么只需要一行代码就能够办很多事情，优秀到N多浏览器问题我们也不用考虑，优秀到千千万万个程序员被他征服；

为什么刚刚说了google搜索对人的思维有影响又来说jQuery？在没有jQuery、prototype这些框架之前我们操作DOM或者ajax肯定是自己写代码发送请求，但是这样我们还是陷入到了重复写代码的漩涡里，最终有人出来了开发了这么些个框架，我们都收益了，但是我们忘掉了基础的DOM操作，因为所有的事情jQuery都帮我们做完了，何况还有N多基于jQuery的插件呢……，最终本来熟悉的DOM操作和基本的JS随着使用框架的时间推移变得生疏了，每写一个功能都要想想，这是发生在上周帮同事调试程序是遇到的，就想刚刚引用的文章中说的“google只不过是一种工具”，其实jQuery也是一种工具，我们选择了google也选择了jQuery，我们不可能抛弃他，让他帮我们好好的服务吧，或许这就是<a href="http://www.wsria.com/archives/67" target="_blank">优秀程序员懒与笨</a>的形成基础

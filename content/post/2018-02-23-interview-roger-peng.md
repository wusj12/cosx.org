---
title: COS访谈第35期：Roger Peng
date: '2018-02-23'
author:
  - Earo Wang
  - 林枫
categories:
  - COS访谈
tags: [cos访谈，学者，可重复，自媒体，生活]
slug: interview-of-roger-peng
meta_extra: "编辑：林枫  审稿：Earo Wang，高涛"
forum_id: 419831
---
**COS编辑部按** 本文是Earo Wang对Roger Peng的采访稿，[原文传送门点击此处](http://user2018.r-project.org/blog/2018/01/24/interview-with-roger-peng/ )，翻译工作已经得到作者授权。

> **简介**   Roger Peng是约翰霍普金斯大学彭博公共卫生学院的生物统计学教授，他的研究兴趣主要集中于用统计学方法研究环境健康问题。他也是约翰霍普金斯数据科学专项课程、 Simply Statistics博客、Not So Standard Deviations播客（和Hilary Parker合创）和The Effort Report播客（和Elizabeth Matsui合创）的联合创始人，并在2016年荣获美国公共卫生协会颁发的Mortimer Spiegelman奖。

**Earo: 您在耶鲁读本科时暑期在两家公司做过软件工程师，想请您跟我们详细说说那段工作经历。**

**Roger**: 是的，那是很久之前的事了。我在1997和1998年曾作为软件工程师在两家公司做暑期实习。那时候的世界跟现在大不一样，还没有掀起互联网热潮。我的第一份工作是开发卫星通讯软件，主要是要用C++写一些图形用户界面（GUI）。当时我写代码会的是C语言，C++对我而言还有一点陌生。我只好去学习使用微软的Visual Studio和C++语言。这个学习过程其实还是蛮有意思的。至于我的第二份工作，则是在一家国防军事承包商开发潜艇导航软件。这次的工作就是在Unix环境下进行C语言开发，也是我之前就比较了解的。但是在那里我所做的工作数学味比较重，更像是在开发数学算法。这家公司有一个很大的软件开发组，组里面的人都很棒。我在做这份工作期间学到了很多C语言编程和Unix的知识。不过从这两份工作中，我也明白了一件事：我其实并不想成为一名软件工程师。我有着很好的机遇，但是这似乎不是我想要的。所以这两段经历让我下定决心以后不会再做这样的工作。

**Earo: 那么问题来了，为什么您会决定做一名学者呢？**

**Roger:** 我在做暑期实习的同时也在犹豫到底是继续读研还是留在公司工作。当时所有人都想要去微软这一类的软件公司工作。那时候还没有谷歌，所有人都想进微软。那时候微软是最好的工作单位，当然我认为现在那里也仍然是个工作的好去处。这样所有人都跑去做软件工程了，但我决定不随大流了，因为其实我对教书有一点执念。在公司里你是没有多少机会去教学生的。所以我选择去研究生院继续深造。当然还有一个很大程度上影响我决定的原因：我的哥哥也是一个学者。他所做的工作对我有着很大的影响。我喜欢做研究，我喜欢教书，这正是学者的主要工作。那时我还从没有想到过去做其他事情。

值得一说的是，那个时候统计领域不像现在机会这么多。学术界之外也有一些其他的机会。如果你有统计学博士学位，那么学界外有很多机会大都在制药公司。你大概只能指望SAS或是少数一些其他的东西派上用处。不像现在基本上每家公司都需要统计学家。这都是数据科学爆炸式发展带来的，而当时不是这样的，所以那些机会对我而言并没有什么吸引力。而学术界，我想无论过去还是现在都一直深深吸引着我。

**Earo: 您发表过一些关于可重复研究的论文，那么您是什么时候开始关注可重复性问题的呢？您觉得R语言在可重复研究中扮演着什么样的角色呢？**

**Roger:** 我开始思考关于可重复性是在我2005年进入约翰霍普金斯的时候。我在学校所做的大量工作都是关于环境健康和空气污染的研究。当时很多的研究因为环境条例的存在而备受争议，甚至现在也是，至少在美国是这样。这一块的研究一直富有挑战性，这是好事。当然，并不是科研就不能受到质疑。尤其在做一些与国家政策法规息息相关的研究时，我们格外需要保障其透明性。所以我觉得这可能就是一开始的情况。我想如果人们在某个领域工作，我们应该尽可能保持开放。因此，我们做的工作尽可能保障透明性，让人们有渠道获取我们的软件和数据，从而让更多的人了解我们在做什么。因为这是一个公共政策议题，不同于某些仅仅影响少数人的实验室科学议题。这项研究能影响成千上百万的人。这是我们研究这个问题的出发点。我们写了许多的论文来阐述这个问题有多重要，特别是在对政策影响巨大的研究领域，当然也包括环境污染研究。

我们就这么开始了研究，而R又是当时最好的选择。首先，R语言本身是一种开源语言，你可以测试代码了解这段代码是用来做什么的。其次，彼时已经有一些可以用来写报告的工具了。这使得我们可以在更大程度上保障可重复性和透明性。显然在过去十年里，随着knitr和其他一些相关工具的出现，这一块的功能进步神速。R中用来写可重复文档的工具相当复杂，不过我觉得这个问题已经差不多解决了。过去的工具都像是临时凑数，你必须把不同的东西拼凑起来，比如LaTex和其他一些工具。而现在就简单很多了，你可以直接在RStudio里使用markdown。这个问题90％都被搞定了，所以我想工具不再是问题。我们更需要关注的是怎么安排人加入到工作流中，还有保证一切都可重复的习惯。

**Earo: 您现在做可重复研究的工作流是什么样子的？**

**Roger:** 当我参加一个项目的时候，我倾向于先写一些R脚本。根据项目性质的不同，我经常做的一件事是用R Markdown文档记录需要进行预处理的数据。我现在经常用R Markdown文档，不像过去可能仅仅只是写个脚本了事。在R Markdown文档里，我可以记一些笔记，画一些图标方便检查。可能这些图标并不重要，也不会拿去发表或者做其他的什么，但是他们对于检查确认数据还是很有用的。

**Earo: 您不是一个只在高校里埋头做研究的学者，还给Simply Statistics写了很多博文，在Coursera上在线教数据科学的课程，还主持两个播客——Not So Standard Deviations和The Effort Report。您似乎很喜欢数字媒体。那么有没有什么故事想给我们分享？**

**Roger:** 这是一个很开放的问题。（哈哈）这些都起源于做网课。我在约翰霍普金斯的同事们和我一起探讨过把教学材料放到网上去的可能性。不过，我们其实并不是真的很了解怎么做才是最好的。2013年许多在线平台走进大众视野，比如Coursera，还有其他一些平台。它们开始不断发展，我们就想：“嗯，这是一个很好的机会。”不过我们以前也没什么经验。我们从来没有做过视频。所以我学了很多关于如何剪辑视频、如何录像、如何使用摄象头等知识。从那以后就一发不可收拾。我发现，学习新的东西真的很有意思。我想我真的乐在其中。我的同事可能对这方面就不那么感冒了，他们更希望别人能帮他们去做。而我喜欢剪辑和录制，我觉得很有趣。所以一旦这个做好了，我就觉得开办一个播客也未尝不可。我想要学习音频剪辑还有使用麦克风以及我们全部的设备。一开始并没有多少关于数据科学或者学术界的播客是符合我的口味的。这就是为什么我会创办这个播客（NSSD）。我觉得使用新技术、学习新工具来工作真的很好玩，即使这些工具可能跟数据科学工具并不一样。

**Earo: 但您用那些工具制作了很多数据科学的资料。**

**Roger:** 对，这大概就是我的想法。我确实希望用某种方式为数据科学社区做贡献，哪怕我不一定要写R包。不过我还是希望能或多或少为社区做点贡献。而且主要是我真的很觉得去做这些项目很有趣，它们可以让我学习到新东西。当然可能不会立竿见影，但是最终，我所学的东西是会反馈到我自己的学术和教学工作中来的。不好意思就是这样，我没有什么特别疯狂的故事。

**Earo: 您在录视频的时候找到了自己的最佳摄像角度吗？**

**Roger:** 事实上，这里有一个很有趣的故事。我在为在线课程录制讲座视频的时候，我总会把摄像头以同样的角度架设在办公室里。因为我的办公室没有很大的空间架摄像头，所以每次我都会把它放在同一个位置。背景永远是我的书架。所以每段课程视频都会有我的书架在背后。你可能会惊讶，不知道多少人给我的评论都是关于我的书架。他们总会评论我放在书架上各种各样的书。就比如，"哦，这个变了"或者"你把这个拿下书架了"。我从没有想过大家会注意到书架。

另一件事就是，我们在做课程的过程中发现音频的质量是最最重要的。视频本身可能并不关键，但是如果声音录制得不好，那么可能大家都会纷纷吐槽。我必须更好地去了解怎么录制好的音频，因为这对我们而言是把视频做好更重要的因素。

**Earo: 您能和我们再说说这些媒介的不同吗？比如说用怎样不同的方法收获目标听众呢？**

**Roger:** 整个经历中允许我做的一件事就是用不同类型的媒介做试验。因此，我们会使用这些视频来进行在线课程，我们还将视频发布到YouTube上。对于我们的每门课，我们都有一本对应的教科书，都是通过在线出版工具发布的。我们自己出版教材。在做出版和播客的过程中我受益良多。听众们真的是各种各样的。我的一个体会是当你创造了一样东西的时候，那仅仅是你要做的第一步。之后你需要思考如何把自己的创造推广开来，使那些想要体验的人能够有机会接触。这真的很难。

我们的书有一个很大的优势，那就是有课程作为配套机制。在上课的时候我们会说："这是我们的书。"这是个很好的配对，因为我们的书里有上课所需的全部材料，这样上课的人肯定会对书里的内容很感兴趣。但是如果你创建一个播客，人们怎么才会找到它呢？这个问题不是显而易见的。好在我已经创了播客，我们有博客和这些网课，还有Twitter以及社交媒体。所以我们已经基本建立好了这些发行渠道，但如果没有这样合适的渠道去做发行推广，想要触及某个特定的听众真的很难。这就是我从零开始学到的东西。一般可能会想我就是发点东西出来人们就会看得到，对吧？但其实根本不是这样的。

我们想做的，也并不是说像在电视上做广告那样。我们其实想找的人群其实很小。所以我们做了一点思考，想着如何能够直接地走进他们的视线。这正是我经常和那些想写书或者其他类似事情的人所说的。通常我跟他们说的第一件事就是："你认为对于想要或者需要的人，怎样才能够让他们人手一本你的书？"

**Earo: Not So Standard Deviations始于2015年9月，是一个半月（两星期）更新的播客，每次大概时长为一个小时。Hilary和你是怎么找到你们要说的话题的？**

**Roger:** 对于两个播客，我其实一直担心一件事，就是我们的话题可能要不够用了。然而，已经两年了，我们还没有江郎才尽。不过，我们每两周似乎都能找到一些可以探讨的话题。通常是新闻里的一些东西或者是我们想到刚刚发生的事。畅谈我们关于数据分析的一些基本问题，这应该是Hilary和我在做Not So Standard Deviations中做过最棒的事之一。一份好的数据分析的要素是什么？你又怎么教给别人？我想这是会时不时发生的老问题。我要去开一个会，或者她要跟某个人讨论，她想到了一些好点子，然后我们就会在播客上讨论。我想这种讨论可能会持续相当长的时间，除非我们用某种方法解决了这个问题。不过，展开这种对话还是很有趣的。而且慢慢地总会有什么好玩的事情发生。你可能会惊讶，两周时间能发生的事情太多太多了。

**Earo: 当别人说出"Roger，你是我的R语言老师"，或者"我看你的博客好多年了"，又或者"我非常喜欢你的播客"，诸如此类的话时，你会不会感到很自豪？**

**Roger:** 我不知道该不该用"自豪"这个词。当有人跟你说那样的话，看到我们做的东西能给他们带来一些积极的影响，当然会让我有满足感。这也正是我们做这些事的初衷。我们在单位日复一日地教学，但我们只能接触到很有限的一群人，那些有钱来上课的人，那些旅行到巴尔的摩或者其他什么原因来大学里的人。而现在，随着Coursera和其他那些在线课程的发展，我们可以惠及更多的人。我真的很高兴能碰见这些人，听到他们的故事和他们学习的经历。听到他们的话我真的很开心。有时候大家还没认出我脸的时候就先辨认出我的声音，这真的很有意思。他们会说："哦，我好像在哪里听过你的声音。"因为他们之前听这个声音听了好多个小时。这一直让我觉得有点意思。

**Earo: 你在澳大利亚已经待了半年左右。你觉得现在生活得怎么样？你最喜欢的是什么呢？**

**Roger:** 我说过澳大利亚真的很神奇。对我和我的家人而言那半年都是一段很神奇的经历。我们怀念那段日子的点点滴滴。真的很不可思议。从美国来到澳大利亚，还是很容易适应的。这儿的人们很善良。一切都很友好。人们对待生活的态度可能有一些不同，大家看起来都很轻松。显然，就人口而言，这是个小地方。我觉得这对于澳大利亚的风土人情而言影响也是挺大的。墨尔本很棒，这里的食物也很美味。

**Earo: 但你依然在喝Long Black（译者注：一种美式黑咖啡）啊。**

**Roger:** 对，我戒不掉美式咖啡啊。与我而言咖啡一定是美式口味。不过我从墨尔本人这里学到了很多。对我而言在这里生活真的很精彩，要让我离开我肯定会非常难过的。

> 图为Roger在莫纳什大学"乒乓室"打乒乓球。
![pingpong](https://user2018.r-project.org/img/roger-peng.png)











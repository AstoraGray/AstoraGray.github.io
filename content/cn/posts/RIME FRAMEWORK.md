---
title: RIME FRAMEWORK
date: 2024-10-10
categories: ['CORE']
draft: false
---

​	是什么时候我想开发一个游戏框架的呢？我想应该是在我一次次开发游戏时，每当代码量超过1w时，就开始觉得开发困难，但我是一个比较固执的人，我要么就自己造一个框架，要么就不用框架来写。于是在完成「海马切片」第一版开发后，我意识到了如果不用框架开发游戏将没有章法，「海马切片」项目内各种代码量子依赖，甚至会出现回看一周前的代码也会理不顺的情况，就像一个乱纪元，毫无规律。在我们生活的这个世界上，一切都有其规律可循，模拟一个世界的前提也是需要创造出尽然有序的系统，简洁而清楚，在宇宙诞生之初也是两颗高速运转的粒子撞在了一起，才产生了万物。

​	在「海马切片」之后，我做了一个「通用横板游戏关卡编辑器」，同时写了一个状态机的框架，根据Unity自身Animator的架构来写，分了Main和Additive状态，这样我能够随意切换Main状态并且随意添加和删除Additive状态，但当时我设计的这个状态机过于死板，死死的遵守设计模式的原则来写，最后整体的架构没有大问题，但是新的功能写的非常痛苦，创建一个新的状态的代价都是巨大的。在毕设答辩之后我也对这个项目失去了兴趣，原因之一是如果我要完成一个能支持过场演出程度的编辑器实在太难，目前编辑器停留在基础层面，后面工作量将会是巨大的，我意识到了我完成游戏之前先做编辑器的想法是非常难实现的，因为如果仅仅支持创意工坊，那目前就已经够用了其实，但是要撑得起整个游戏主线流程，那远远不够。其实还有一个原因，那就是这个项目已经牢牢绑定了我写的状态机的框架，像陷入了泥潭，很难解脱。在这一次的开发过程中我有什么收获呢？我验证了我学习毛星云的设计模式理念是正确可行的，但意识到我仍然有很多要学习，从我写的框架来看，非常的稚嫩，不能够投入到开发使用。

​	在毕业之后我进入到了一家游戏公司，虽然做的游戏非常烂，但不可否认的是在那段时间我的成长是非常迅速的，我学到了一些系统的设计理念，比如能够管理几百个UI面板的导航系统，以及个个工具的设计方法，命名规范等等，于此同时，在晚上我也会反编译一些项目来看，比如「怪兽远征」。这让我也差不多有半个专业级别的开发水平了，当然，我是有一些依据才敢这样自我抬高的。这些因，将会为后面我要写的框架奠定基础。

​	在受不了做烂游戏，以及疯狂的加班压榨后，我选择了裸辞，在裸辞之前我找到了新的工作，也就是Vision - Pro平台的Unity App开发，也就是我写这篇文章时候的工作，当然，如果你是在之后看到的这篇文章，我可能已经不做这个了。这份工作非常好，也给了我很多自我提升的时间和精力，在这段时间我负责工作项目的客户端程序的主要部分，在完成了一个个工具提高生产力后，我的代码水平也达到了前所未有的高度。某一天，我在Github上找到了一个开源的独立游戏项目「Slider」，于是克隆到本地进行研究，我发现它的代码是如此的优美有序，甚至比我任职的上一家公司的代码要好看很多，像一件艺术品，在将「Slider」的整体架构看了一遍后我也有了写游戏代码框架的想法。

​	从前面的种种原因，促成了现在的结果，我要做一个轻量级的游戏开发框架，名字叫「Rime Framework」，这个名字也不是空穴来风，早在给「通用横板游戏关卡编辑器」开源的时候，朋友Mors让我给它去一个简洁而特别的名字，于是在想了无数个名字之后，我想到了「湖心亭看雪」中的"雾凇沆砀，天与云与山与水，上下一白。"非常符合当时我的心境，于是我将雾凇指代自己的一种心境上的向往，便有了这个名字。「Rime Framework」很轻，就像雾凇上的白霜一般，覆之于上，将其包裹着的物体装饰的冰洁、神圣。

​	框架中的设计理念遵循周易中阴阳的概念，Controls和States互为阴阳，分别管理游戏所有的输入、所有的状态，Cycles和Pools互为阴阳，分别管理游戏中所有的生命周期、所有的池。目前框架的底子已成型，在测试使用后发现非常简洁好用，在之后我将会把他开源，反哺Github社区。

​	写这篇文章的时候，我会时不时的陷入一种虚无主义的情绪中，前几天的诺贝尔物理学奖颁给了深度学习之父，仿佛我们的人类研究自然科学的时代将要落幕了，目前的通用大语言模型进步越来越快，我写代码还有意义吗？至少在此时此刻是有意义的，在这个时间点，这个电脑前面写这篇文章的行为是有意义的。虽然在五年之后，程序员这一职业可能不在了，但把握当下不正是对抗虚无的一种方式吗？我称自己为世纪末的设计师。

<audio controls autoplay>
  <source src="/audios/Dreiton_1.mp3" type="audio/mpeg">
  Your browser does not support the audio tag.
</audio>
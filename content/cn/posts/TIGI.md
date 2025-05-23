---
title: TIGI
date: 2024-11-20
categories: ['OUTERCORE']
draft: false
---

​	逛完了weplay 2024，这次经历对我影响很大，首先我感受到了全球游戏开发者的想象力和决心，其次也拓宽了我构思游戏的思路，也就是「想象力」，今天在小黑盒里看到「风暴之门」下面的一个评论，说的是以微操为主的War3类游戏已经不适合现在的玩家了，确实，RTS的微操是被暴雪带坏了，导致各大厂商都在卷微操，红警3、帝国4等等，之前我构思过一个游戏，甚至有过之而无不及，在我构思的这个游戏里面，击败敌人甚至需要考虑高低差、地形、重力，甚至弓箭手的自动瞄准也不是指向性的，这意味着箭矢能被躲掉，当然也可以手操，持盾真的能挡住攻击等等。简直就是把神界原罪的地形和骑砍的战斗整合到了RTS里面，在我想出这个游戏后首先是非常激动，把它分享给我的朋友，朋友是一名RTS玩家，他告诉我说操作太过于复杂了，而我当时还沉浸在自己的天才策划案中，但事后深入思考，现如今RTS游戏的操作已经足够复杂了，何必更加复杂呢？减少微操，增加策略性才是RTS的出路。

​	AlphaGo曾经击败过围棋冠军李世石，但是它不论怎么训练，至少目前无法击败星际争霸的冠军，因为围棋对局的可能性是可以列出来的虽然这个总数比宇宙中所有的粒子都多，但对于AI不断的训练则有接近的可能，而星际争霸对局的可能性近乎无限，过于复杂，AI也是无能为力。所以我什么会突然从RTS扯到围棋呢，对的，我现在有一个想法，把围棋和RTS结合起来，并且基本的内容在我大脑里已经显现。它不需要微操，并且对局可能性远大于围棋，并且泛意义来讲也属于RTS，我给这个游戏取名为「天基Tigi」。

​	天基是一个以围棋为基础玩法的RTS游戏，游戏中玩家需要每回合建造基地，规划兵线最终取得游戏的胜利，胜利条件和围棋一致，占领最多的地块。那么，让我们来模拟一下这个游戏，首先游戏的地图和围棋棋盘一致，玩家一开始没有任何经济，需要建造天基塔来围地获得地块，天基塔是免费的，每回合只能建造一个建筑，获得地块之后周围的天际塔开始产生经济效益，比如每回合一个天基塔产生这块区域地块的经济，这时候玩家开始出兵，出兵需要建造兵营，也是一个建筑物，放下建筑之后兵营朝向方向每回合自动出兵，并且并且兵营可以使用经济升级，有步兵、骑兵等等。

​	基本的战斗逻辑则和围棋一样，建筑和士兵在某一时刻彻底围住对方这部分的实体则消灭他们，转化为自己的地块促进天基塔经济和走向胜利。建筑是有生命值的，每个建筑生命值不同，士兵进入对方建筑则扣除对方建筑生命，士兵之间的对局则以谁先出手为准，就像国际象棋一样，所以士兵也是有概率吃掉对方骑士的。但不同的是，士兵有行动顺序和移动格数，比如在我的回合，骑士的行动优先级最大，所以骑士走完之后士兵移动，骑士走2格，士兵走1格。所有兵种的初始方向都是兵营的朝向，但是呢，有一个非常重要的机制来了，那就是撞墙。撞墙可以是士兵走到地图边缘，也可以是士兵走到建筑又或是士兵遇到自己的士兵，撞墙之后则可以选择这个士兵向他的左边走还是右边走，这个机制极大的增加了游戏的策略性，配合包围机制，可以杀敌人于无形。

​	关于后面的扩展，这个游戏的扩展潜力是无限的，比如我在游戏中增加一个建筑，传送带，可以直接改变士兵的朝向后使其向前一格，敌人则无法使用，只能摧毁它，又或者我加入一个巨炮，能够每回合攻击这条线上的敌人，并且如果是友军，那么这个炮弹则会触发撞墙机制，可以选择向左或者向右移动，炮弹也纳入围棋的基本机制，只要有某一时刻和建筑和士兵围住了对方，则被围住部分全无。又或者后面加入比如不死族，骸骨堆，每回合向四周扩展，但生命值只有1点等等，这个游戏我认为可玩性很高。

​	关于游戏的美术风格，我想用博斯的「人间乐园」来表现，因为天基这个游戏能够包罗世间万物的物体进去，它可以做成一个新的类别的游戏。

<audio controls autoplay>
  <source src="/audios/God Rest You Merry Gentlemen.mp3" type="audio/mpeg">
  Your browser does not support the audio tag.
</audio>

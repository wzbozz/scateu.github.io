---
layout: post
title:  "面试奇遇记"
date: 2015-08-01 23:35
---

在飞机上无聊, 写个段子好了. 

话说, 大约半年之前那段时间我在一家做手机游戏的公司, 团队人手不够, 需要招聘iOS工程师. 

有一个小伙子过来面试, 看简历的话, 尽管学校不是特别好, 但是在"香港某游戏公司北京分公司"里工作过一年. 

然后就约过来聊一聊. 

我不喜欢特别正经八百的面试, 通常我会先讲几个[段子](https://github.com/tuna/duanzi), 把对方逗乐了, 气氛融洽了之后, 面试的状态就比较自然, 容易看出真实水平. 同时也避免现场过于紧张, 真有本事的人没有发挥好, 错失千里马. 

于是跟这位候选人聊了半天, 觉得还不错, 感觉人很靠谱的样子. 于是说下周末我正好加班, 你可以带上你的作品过来, 我们从技术层面沟通一次. 

第二次, 他背着一台新买的Macbook Pro过来了. 我为什么知道这是新买的呢? 因为他连触摸板都用不利索, 没有设置成触摸触发, 点鼠标经常点空. 当时我还在想, 没准人家之前一直用Mac Mini开发, 临时买的电脑, 情有可原. 

然后高潮来了. 

他点开了事先打开的Xcode, 处于搜索结果界面. 搜索的是什么呢? 是他的姓名的全拼. 然后他指着这几个文件说, 这几个模块是他独立完成的. 我一看对吼, 文件头上的Author的确是他. 

但是, 我一眼就发现Xcode的文件管理栏有点不对头, 这几个文件名旁边有一个M标记. 

M是Modified的意思, Xcode集成了git. 


于是我当着他的面, 迅速打开Terminal, git diff了一下, 李鬼立刻就现原形了. 然而, 这小子居然没有看懂我做了什么(这自然与我敲的飞快有一定关系哈哈哈啊哈哈), 恬着脸继续侃侃而谈. 

结果呢, 就给他发了一张"我觉得你挺不错的回去我跟领导汇报一下尽快给你答复出门左手有电梯路上小心保持联系啊哈"卡. 

所以说一定要好好学会用git. 


完. 


# 技术心得

此处整理一些自己的技术感悟，技术心得，技术方面的总结。

## 技术感悟

### 技术开发 vs 厨师做法

技术开发 就像 厨师做饭：

解决一个问题，实现一个功能，可能有多种方案，需要技术人员根据经验和能力，做个权衡和取舍，且十八般武艺要都略懂，且部分技术要精通，好在需要的时候，选择适合的工具去组合和搭配实现自己要的东西。

就像厨师做饭，各种工具，比如电饭锅，高压锅，微波炉，电烤箱，各种尺寸的锅，油盐酱醋，等等，都要懂，且有些工具精通优缺点在哪里，这样才能用不同工具组合搭配，做出自己希望的美味。

### C语言：指针和变量

C语言的**指针**和**实体**之间的关系。就像**钥匙**和**房子本身**之间的关系。

且对应的变量，比如**结构体有几个值**，或者实体占用空间的大小几个字节？就像普通的房子的内部结构占的大小。比如**两房或三房**，更大的话那就快变成别墅了。

普通使用者想要使用指针，就像在一个小区里很多房子不知道要去哪里。拿了指针就像知道了你的房间的地址，获得楼栋号码，就可以拿着钥匙去找到你要的房间地址了。

### 不同领域知识需要大量精力才能专而精

不同行业，领域内有专门的协议，如果想要研究透，需要花不少精力的

比如：

* 软件框架或协议
    * `jabber`
        * 邮件服务器领域：
          * [jabber协议概述 - codefans - BlogJava](http://www.blogjava.net/codefans/articles/20022.html)
    * `XMPP`
        * 即时通讯=聊天 系统
* 硬件协议
    * `USB`协议
    * `蓝牙`协议

等等。

如果只是了解个概念，那很快的，可以速成。

但是想要深入了解和研究具体实现细节，就需要专门从事该领域很长时间，才可能达到专业和精通的水平的。

### 代码写的不好-》有难闻的味道

比如：

[Killing Switch Statements in React with the Strategy Pattern](https://glcheetham.name/2016/05/20/killing-switch-statements-in-react-with-the-strategy-pattern/)

> I'm of the opinion that the presence of a switch statement, or an if-else, is a very pungent [code smell](https://en.wikipedia.org/wiki/Code_smell)

提到的：

> Code smell, also known as bad smell, in computer programming code, refers to any symptom in the source code of a program that possibly indicates a deeper problem

如果代码写的不好，作为有经验的人员，能闻出**代码**中不好的**味道**。

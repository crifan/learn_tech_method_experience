# 维基百科

去学习一个，对于自己来说是全新的未知的新知识，其中利用网络资源的一个很有效的入门手段是：`维基百科`

* 维基百科
  * 英文：`Wikipedia`
  * 简称：`维基`=`wiki`
  * 主页：
    * https://en.wikipedia.org/
  * 是什么：一个百科全书式的网站
  * 做什么：对世界上的各种事物进行解释
    * 尤其是计算机技术，解释的透彻和明白
      * 对于搞技术的，往往都会用得到
  * 特点
    * 能把东西解释的清楚
      * 对于任何一个词条，往有概述，历史，版本，背景，特点等等非常全面的解释
    * 全球所有人都可以编辑和更新
      * 促进不断改进
        * 越加准确和符合实际
    * 有多种语言
      * 英文版
          * 很多技术和事物都是说英文国家发明的，源于英文系的国家
            * 所以
              * 英文版内容往往是最准确和最全面的
              * 且往往也是英文版解释的最清晰和易懂
      * 中文版
        * 虽然中国人更习惯看（简体）中文（或繁体中文）
          * 但是中文版很多词条的内容不是很全
            * 不过和百度百科等竞品比，依旧有很大的参考价值
  * 适用于
    * 尤其是对一个技术名词不是很了解的情况下，去wiki，可以快速了解其所属技术领域和该技术的概况
  * 相关
    * 国内有个百度百科
      * 其中有些（或者说很多）内容是参考（拷贝）了维基百科的中文版

## 举例：如何有效利用wikipedia

我之前是做嵌入式领域的技术，但是也没听过`现场总线`

所以对于想要 从无到有 从完全陌生到希望知道，对于现场总线， 其大概是个什么东西，大概是用来干啥的，希望有个基本的概念上的了解

所以去google搜：

现场总线

可以找到 wiki的解释：

作为中国人，可以先看看中文的解释：

[现场总线 - 维基百科，自由的百科全书](https://zh.wikipedia.org/wiki/%E7%8F%BE%E5%A0%B4%E7%B8%BD%E7%B7%9A)

> 现场总线是许多工业用通讯协定的总称，一般用在即时分散式控制系统，IEC 61158是有关现场总线的标准，不过也有一些现场总线未列在IEC 61158中，如Modbus、LonWorks、CANopen等。
> 
> 一个复杂的自动化系统（例如组装生产线）会需要一个有组织的控制系统阶层才能运作。在此阶层的顶端一般是人机界面（Human Machine Interface, HMI），可以让操作员监控及使用此系统。中间层则由许多可编程逻辑控制器（PLC）组成，PLC之间借由网络系统（如Ethernet）传递资料。低层则是由现埸总线连接PLC及感测器、致动器、马达、开关、阀门、接触器等实际动作或侦测的元件。

但是其实解释的不够透彻，还是看英文原版：

[Fieldbus - Wikipedia](https://en.wikipedia.org/wiki/Fieldbus)

> Fieldbus is the name of a family of industrial computer network protocols used for real-time distributed control, standardized as IEC 61158.
> 
> A complex automated industrial system — such as manufacturing assembly line — usually needs a distributed control system—an organized hierarchy of controller systems—to function. In this hierarchy, there is usually a Human Machine Interface (HMI) at the top, where an operator can monitor or operate the system. This is typically linked to a middle layer of programmable logic controllers (PLC) via a non-time-critical communications system (e.g. Ethernet). At the bottom of the control chain is the fieldbus that links the PLCs to the components that actually do the work, such as sensors, actuators, electric motors, console lights, switches, valves and contactors.


会更加清楚:
* 首先 现场总线，只是一个 name名字 而已
  * -》 意思是 不是某种具体的技术和东西
* 但是是 一些东西的 总称
  * 具体包含哪些东西呢？
    * 包含的是：一组的 工业用的（industrial） 通讯协议 （computer network protocols ）
      * 与工业用相对应的：可能其他领域就是 民用的？军用的？
  * 用于什么场景或领域呢？
    * 用于实时的 分布式控制系统
      * 那肯定就有：
        * 与实时的相对应的：非实时的领域/场景
        * 与分布式相对应的：比如 集中式的系统
      * 虽然上述与此对应的领域，我们更不熟悉
      * 但是至少知道 现场总线 是 知道其侧重点是针对于实时的 分布式的
  * 而这类协议综合起来，形成了一个国际标准：IEC 61158

至此，基本上就大概了解了 现场总线 大概就是：

* 是一堆协议的总称
* 这堆协议：
  * 是工业用的 通讯协议
  * 侧重于规范 实时的 分布式的
  * 综合起来对应着国际标准：`IEC 61158`

由此实现了：

从无到有 对 现场总线 有了基本的了解。

> #### info:: 后续教程
>
> 后来的后来，在对现场总线有了稍微多点的了解后，又去整理出了系列内容，需要的可以去参考：
> 
> [现场总线Fieldbus简析](https://www.crifan.com/files/doc/docbook/fieldbus_intro/release/html/fieldbus_intro.html)

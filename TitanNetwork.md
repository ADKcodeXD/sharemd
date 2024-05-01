# Titan Network 挖矿教程

RootData链接：
https://www.rootdata.com/zh/Projects/detail/Titan%20Network?k=MTE5NjQ%3D

未融资，声量很小，一个极其早期的项目。

官网链接：

<a href="https://www.titannet.io/">https://www.titannet.io/</a>

介绍：

> Titan Network是一个数字资源网络，旨在通过激励社区空闲资源与全球需求匹配，让每个用户都能轻松利用DePIN服务的力量，参与构建价值互联网。

工作原理：

利用网络和硬盘的资源，提供网络服务。类似于做种。


**由于是国人项目，加上关注度比较低，因此需要注意跑路风险：**

本文只介绍如何挖矿。

## 挖矿推荐

> 其实有PC 安卓 以及LINUX端
> 但是由于国内网络环境加上他的算法，使用国内IP非常没有性价比。
> 有条件可以买国外VPS 例如Vmiss等服务商提供的VPS

如果你想用PC或者安卓也可以

PC下载以下软件：

<a href="https://github.com/Titannet-dao/titanedge-desktop/releases/download/0.0.8/titan_win_v0.0.8.exe">https://github.com/Titannet-dao/titanedge-desktop/releases/download/0.0.8/titan_win_v0.0.8.exe</a>

Android端在此处下载：

<a href="https://www.titannet.io/download.html">https://www.titannet.io/download.html</a>

下载完都有中文，其实很简单，直接点开始赚钱就行了。

![gh](https://raw.githubusercontent.com/adkcodexd/sharemd/main/autoupload1714556080000axhrzl.png)

共享存储空间越大收益越高，但实际测试好像是6G-11G左右之后就边际效应递减，基本上没有更高的收益了。

PC和手机都要记得绑定你的身份码

![gh](https://raw.githubusercontent.com/adkcodexd/sharemd/main/autoupload1714556140000hjox04.png)

获取身份码需要再官方控制台进行注册，

点此处可以直达：

<a href="https://test1.titannet.io/intiveRegister?code=auwaFG">https://test1.titannet.io/intiveRegister</a>


注册好后在节点，控制台这里点击获取身份码就行了

![gh](https://raw.githubusercontent.com/adkcodexd/sharemd/main/autoupload17145562570000wtbdf.png)


## Linux 单/多开脚本

> 目前规则更改后，多开的收益会递减
> 当然也有人说多开的收益会更高，这个可根据个人来选择，我使用的是单开

![gh](https://raw.githubusercontent.com/adkcodexd/sharemd/main/autoupload1714556344000i3u1up.png)

收益规则也可以看上图

如果你没有节点，服务器，我非常推荐你去购买一个Vmiss服务器。

该云服务商非常好用，无论是搭梯子还是用来挖矿，都是十分不错的选择，目前我属于一鱼三吃（梯子，挖矿，指纹浏览器代理），而且价格只有一个月3刀。

>梯子速度很不错，一般都能够跑满速，一个月有1T左右的流量，有的服务器500G。
>不过缺点也有，就是配置较低，存储空间较少。
>需要购买的使用我的链接并且使用优惠码就能够达到上述价格
><a href="https://app.vmiss.com/aff.php?aff=2090">https://app.vmiss.com/aff.php?aff=2090</a>
>优惠码：20%OFF


当然如果你拥有服务器，那就非常方便了，直接执行社区提供的命令即可

**注意：该脚本为社区提供，执行前请确保源码是否有更改，是否有恶意程序，本人不负责任何财产损失**

```sh
wget -O duokai.sh https://521github.com/extdomains/raw.githubusercontent.com/a3165458/Titan-Network/main/duokai.sh && chmod +x duokai.sh && ./duokai.sh #中国内地以外
```

```sh
wget -O duokai.sh https://raw.githubusercontent.com/a3165458/Titan-Network/main/duokai.sh && chmod +x duokai.sh && ./duokai.sh #中国大陆以外
```

两者都可以，取决于git源的位置。

执行之后，有中文提示，根据你的需求往下填写就行了。
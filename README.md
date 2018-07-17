对一个好奇喵来说，什么东西都是新鲜的，吸引人的，特别是一些被封禁的东西，比如被亲爱的祖国屏蔽的一些国外站。

经过一翻探索，终于找到了一条大路，让我可以光明正大的上youtube，用google，跟一些外国朋友在facebook上互动，而不用受限于昂贵vpn的黑商限速。

先说一下这个翻墙的原理，只要明白了这个原理，才知道自己在做什么。

对于国内的小伙伴来说，翻墙，就是能够访问国外的应用服务器，但是有一些国外服务器是被祖国屏蔽了的，用我们国内的服务器是不可以正常访问的，换个思路，这时候我们可以国外的服务器访问国外的服务器，因为国外的服务器对全球的服务器都是完全没有屏蔽的，这样我们就可以轻松翻墙了。

顺着这个思路，首先我们得有一个国外的服务，那就买一个，不就是钱吗，哈哈，下面是我买国外服务器的网站，感觉不错，安利给盆友们

[点击这里就可以进入购买网站](https://www.vultr.com/?ref=7410987) 建议在电脑上操作，这样会更方便。

进去后是这个样子的，首先你得注册一个账号，用你的邮箱就可以进行注册。

![image](http://upload-images.jianshu.io/upload_images/5590388-2ea15c1791d826db?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

注册好之后登录，可以看到下面这样的界面，可以看到我已经买了一台服务器。

![image](http://upload-images.jianshu.io/upload_images/5590388-7e24b20c27da6d52?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

接下来就是购买了，这个很关键，成败在此一举，要认真哦

![image](http://upload-images.jianshu.io/upload_images/5590388-e7564829ebbaa268?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

点击上图的添加图标之后，如下图，这里有各个国家的，看你自己开心，想先那个就选那个。

并且还有相关的价格信息

![image](http://upload-images.jianshu.io/upload_images/5590388-fe28a86878d54d55?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![image](http://upload-images.jianshu.io/upload_images/5590388-f09e3f63f24e03f5?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

这个是服务器的规格，可以根据你的需求来，肯定是越贵的速度越快，这个不必说。

![image](http://upload-images.jianshu.io/upload_images/5590388-b469c1157d86a4dd?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

点击右下角就可以购买，还可以支付宝付款，这一刻真是觉得马云是真的牛批，感觉自己也好长脸，哈哈，第一次付钱还这么自豪！

购买成功后，就会跳转这个界面

![image](http://upload-images.jianshu.io/upload_images/5590388-e6f4c7755a61e0d4?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

这里有服务器登录的账号和密码

![image](http://upload-images.jianshu.io/upload_images/5590388-c40d1d780237a7d0?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

到这里你已经成功了一大半了。但是我们还需要对这个服务器进行设置。

如果你用的苹果电脑，那么你可以直接用它自带的小黑屏进行远程管理，但是如果你用的是windows系统，那么就需要用一些工具来进行管理了，

你有两个选择：1、通过安装虚拟机，装一个Linux系统，来进行远程管理。2、下载一个Putty，进行远程管理。

这里我选择的是第一种方式。安装的是ubuntu。这里就不展开说明了，大家可以自行百度解决，如果实在不懂可以私信我。

登录ubuntu后打开终端界面，如下图

![image](http://upload-images.jianshu.io/upload_images/5590388-a93b712a5cef916d?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

然后贴以下代码，**ssh '你的用户名'@‘你的ip’ ** 一个回车，然后输入密码

![image](http://upload-images.jianshu.io/upload_images/5590388-c06afc0874f1aa4b?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![image](http://upload-images.jianshu.io/upload_images/5590388-f97a25fb4ebbbf64?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

安装shadowsocks 
```
wget -N --no-check-certificate https://raw.githubusercontent.com/oogh/scripts/master/ssrmu.sh && chmod +x ssrmu.sh && bash ssrmu.sh
```
![image.png](https://upload-images.jianshu.io/upload_images/5590388-a233229d7c3d74dc.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
运行成功后会出现以下界面，按照步骤安装就可以了
![image.png](https://upload-images.jianshu.io/upload_images/5590388-66f51e1f6c5765b2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
添加账号

![image.png](https://upload-images.jianshu.io/upload_images/5590388-3e98e09578bf1e29.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![image.png](https://upload-images.jianshu.io/upload_images/5590388-abaa9aeed7dd193c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![image.png](https://upload-images.jianshu.io/upload_images/5590388-b3b53049a9c8b4ea.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![image.png](https://upload-images.jianshu.io/upload_images/5590388-76103e5944693eb9.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

接下来一路回车就可以完成
![image.png](https://upload-images.jianshu.io/upload_images/5590388-99d6c7ae0c4e8f48.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
到这里就乘下最后一步了，配置终端，就可以使用了
下载一下客户端配置软件，如下图
![image.png](https://upload-images.jianshu.io/upload_images/5590388-d33dc6d7dddd1687.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![image.png](https://upload-images.jianshu.io/upload_images/5590388-14c8fe684b4a808d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
windows客户端
![image.png](https://upload-images.jianshu.io/upload_images/5590388-56afc68e9749d18e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![image.png](https://upload-images.jianshu.io/upload_images/5590388-1182a01120c94bd3.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
手机客户端
![image.png](https://upload-images.jianshu.io/upload_images/5590388-b08e914a831c332a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
根据对应的信息填写就可以
到这里所有配置算是完成了,已经可以正常访问外国的网站了，这个成本要比去买黑商的要便宜。
如果朋友们在操作过程中遇到什么问题可以来简书私信我，我在这里等着你哦。

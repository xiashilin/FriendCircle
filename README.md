# FriendCircle
##一起来撸个朋友圈吧

欢迎来到本项目，这个项目是一个尝试性项目，目的在于从无到有撸出一个微信朋友圈。</br>

**本项目的一切实现思路以及逻辑都有记录，它们都有在我的简书文集记载：**

[代码实现逻辑（简书合集）](http://www.jianshu.com/notebooks/3224048/latest)

**每次更新的模块Gif预览都在另一个MD文件里，如果您对效果感兴趣，不妨去查看一下：**

[更新日志](https://github.com/razerdp/FriendCircle/blob/main-dev/UPDATE_LOG.md)

**因为在下的资金不足以支撑服务器的运行，因此不得不关闭服务器，不过我已经将数据库的文件转移出来了**

**该sql文件处于本项目的db文件夹下，而服务器的源代码处于 https://github.com/razerdp/MyServer 下（Intellij环境）**

**本项目不会停止开发，目前开发进度为小视频（50%），对glide封装和其他类的封装进行了一半，这个小视频基于该库：com.github.waynell:VideoListPlayer:1.2 ,其网址就是库名，非常感谢这位作者**

**最后，因为服务器的问题在下深表歉意，相关文件大家可以down下来在本地运行**

**最后的最后，非常感谢您关注本项目**


目前的最新进度：

##2016-04-21
朋友圈图片浏览指示器完成（评论后台交互完成）

代码解析地址：

http://www.jianshu.com/p/17c51bd5ba70

图片预览：

![](https://github.com/razerdp/FriendCirclePreview/blob/master/img/2016-04-21_dot_indicator.gif)

***

###如果您有PR申请，请提交到dev分支，谢谢-V-

###如果您遇到popup的导入失败，请在工程的gradle（不是app的gradle哦）加上这句话：

```xml
	allprojects {
		repositories {
			...
			maven { url "https://jitpack.io" }
		}
	}
```


#####关于作者我:
在下大四即将毕业小朋友一枚，工作（实习）半年，大三开始的Android开发，至今约一年。

#####关于项目：
本项目意在按照我的经验弄出一个微信朋友圈，也许无法完全实现，但高仿应该是没问题的，只是时间问题←_←。


本项目于2016/03/17 更改为mvp架构


本项目在更新的同时也会同步发布经验心得（撸代码的过程），不过因为在下才学疏浅，有些地方肯定做的不好，所以衷心希望如果您有好的建议或优化方案，可以留下脚印。

#####关于服务器：
目前服务器的数据都是模拟出来的假数据，因为这只是个展示性项目，意在如何实现一个朋友圈的UI和部分交互，并不是完全的弄一个朋友圈。

另外，因为之前为了方便，把地址写在APP下，然后服务器遭到了一次攻击，在下真的服了，这仅仅是个学生价格租的服务器，没有任何价值，有啥好攻击的。拿来当肉鸡都嫌不够塞牙缝。

所以，如果您download了项目，发现刷新时永远是网络错误，请查看FriendCircleApp.java下的rootUrl是否为一段我吐槽的string。

2016/05/25 服务器地址开放，反正在下也不管了，扔给阿里云- -

如果您是hacker，请放过本宝宝一马吧TAT

#####关于库：
因为不制造重复的轮子这句名言，本项目将会使用一些库，这些库基本都是github上比较流行，热度比较高的，比如下拉刷新框架使用的是android ultra pull to refresh(https://github.com/liaohuqiu/android-Ultra-Pull-To-Refresh) 等

当然，我们不能只用库，本项目也会有很多自定义控件（其实这些控件很早就上传到我的github了，只是木有人star....）

#####THANKS：
感谢嘉辉同志(git:[wenjiahui](https://github.com/wenjiahui))，在他star之后终于找到了他的git....，项目的adapter反射创建view思想来源于他的idea。

其次感谢我的实习公司：微聚(他们的app是[超级俱乐部](https://ba.iweju.com))，在这里我成长很快，没有他们的培养就没有这个项目的实现。

最后感谢开源库的开发者们，让我们可以快速实现业务功能。

##LICENSE：
***
The MIT License (MIT)

Copyright (c) [2016] [razerdp]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

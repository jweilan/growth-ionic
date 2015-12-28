# Growth

> A App Basis on Seven days.


##七日谈

![Web开发的七天里](seven.png)

###第一天：新的开始

> 我们迎来了我们的新的一个项目，看起来每个人都很兴奋。这一天过得很快，也做了特别多的事。

首先，我们搭建了自己本地的开发环境。我们选择了一门新的语言，也开始使用新的IDE，一个全新的开始。

接着，我们开始创建一个很简单的Hello，World——在绝大多数语言里都有这样的一个传统。这是一个Web项目，看来我们选用的框架里的Hello，World是一个TODO MVC。

呀！这个框架比原来那个框架看起来更简单，更直接也更加好用。

然后，我们开始去创建我们的构建系统了。让我们告别Ant，迎来新的构建工具，Gradle比他们强大多了。我们可以用这个构建工具来做很多的事情——依赖管理、编译和构造、打包。Gulp看上去很流行，让我们用Gulp吧。顺便再创建一个或多个用于发布和构建的服务器。

最后，在我们的持续构建系统中搭载相应的PipeLine来完成这些事。

第一天，就这样兴奋地结束了。

###第二天：令人期待的新体验

> “没办法，第一天就是得做那些事。”

现在，才开始真正的编码工作。我们拿到了一个任务，知道了它是做什么之后。

我们开始对其分步，第一步做什么，下一步做什么，每一步都很清楚了。可以编写我们的第一个测试，看来这个测试好像并没有想象中对么简单，我们需要Mock对象。

啊！这个组件需要Fake一个Service。第一个任务看来是完成编码了，让我们对其进行简单的重构。

我们已经有了单元测试，现在让我们添加一个功能测试。在我们这个例子里，似乎也需要一个集成测试。

终于可以Commit，并Push代码。

###第三天：上线准备

在我们不断地重复第二个步骤的时候，我们也要开始去考虑如何上线了。

我们是直接部署在Docker容器里呢？还是直接部署在服务器上呢？接着，我们还为其配置了缓存服务和均衡负载等等。

咦！这个配置是写死的！这里需要一个Toggle来控制功能是否上线！

###第四天： 数据分析

上线了几天后，发现一些数据发生了变化。网站的访问速度变快了，使得访问网站的人越来越多。

等等，这个地方好像没有人用过！

唔！这是一个Bug!

应用的性能比以前好多了，一个服务器可以顶以前的两个，一下子省了好多服务器。

看来，用户比较喜欢那个功能，我们增强一下这个功能吧。

###第五天：持续交付

> 又修了一个bug。

噢！我不觉得这个功能用户会喜欢。

哈！这个新功能看上去不错。

###第六天：恶梦

唉！这代码是谁写的！

这里需要重构一下，这里也需要重构一下。

什么！没有测试！

Shit!

###第七天：总结与计划

哈！我们的竞争对手使用了新的技术，而且我们的系统已经不行了。让我们设计一个更好的系统出来，这个组件我们可以使用这个技术，这个组件我们可以使用那个技术。

前途又是光明的。

## License

© 2015 [Phodal Huang](http://www.phodal.com). This code is distributed under the CC0 1.0 Universal license. See `LICENSE` in this directory.

[待我代码编成，娶你为妻可好](http://www.xuntayizhan.com/person/ji-ke-ai-qing-zhi-er-shi-dai-wo-dai-ma-bian-cheng-qu-ni-wei-qi-ke-hao-wan/)

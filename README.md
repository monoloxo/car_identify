
使用神经网络对汽车车型进行识别（对车头，车身，车尾任意部分拍照都可以识别）

  本程序的功能是对拍照后的车辆图片进行识别，判断该车是什么品牌的车，是品牌的什么车型。例如你照了一辆车，它可以判断他是大众的速腾，还是丰田的开凯美瑞，还是日产的天籁等等。之所做这么一款程序，源自本人以前的一个心愿吧。很久前在在唯品会工作期间，开发过一个品牌logo识别程序，能识别出品牌的程序，那时就想，能不能开发个识别车辆车型的程序，世界那么大，那么品牌的车，人只能识别其中很少品牌，如果能做个程序能通过照相把车品牌识别出来是多么酷，但是那时的想法只是通过车标logo进行匹配。直到后来见到一个懂车帝的app，我用自己的手机拍了自己的车，它精准识别出我的车是速腾，没有照车标，我是有点惊讶的，当时想它是怎么做到的。知道后来自己学了神经网络和深度学习的相关技术，就想或许卷积神经网络能很好的解决车型识别的问题。于是我就动手做了这样一个识别汽车车型的神经网络模型，识别率达83%左右（更多数据可以再进一步提高准确率），当然也能很好识别出我的速腾车。由于训练数据都是来自百度图片，百度图片有点坑，速腾车的图片可能给你混杂辆迈腾或者高尔夫，或者是车内内饰图片～～我也没有那么多时间去人工处理，所以对精准度有点影响，不然精准度会更高。当然有个good idea是拿goole图片训练个模型去检查百度中错误的图片，然后用百度图片的模型去检查google图片的错误～～这样可以达到自动去除错误的图片。
  
  
如果你觉得这代码对你的工作或者学习有用，请点个星

需要交流或者帮助的，可以发邮件给我676995058@qq.com,微信QQ同号： 676995058

# **手把手教你实现一个简单版的React**

前阵子，我们的[@luckyadam]( https://github.com/luckyadam)大神在组内进行了N期分享，讲述了如何从零开始造一个类React框架，听完之后，可谓收获良多。抱着学习的心态，我顺势总结一下这次分享，并且把如何造一个简单的类React框架的流程整理出来，分享给大家

### **Virtual Dom**

众所周知，Virtual Dom是React，Vue(2.0+)等框架的一个核心部分。要实现这样的一个框架，Virtual Dom的简单实现自然是必不可少的。

网上有许多文章对Virtual Dom的实现进行了深入详尽的介绍，我这里就只是简单的概括一下吧，细节的东西可以看我给出的文章链接及相关代码。
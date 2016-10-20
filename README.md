### 什么是API？
- API简单来讲可以是 **一个调用的函数**，**一个接口**。
- 抽象来说，**接口是一个内聚系统暴漏给外部的一切信息**，包含但不限于：
    + **调用方式：**比如通过lib库或者http接口等。
    + **调用约定：**比如lib的函数签名或者HTTP的参数，http method或者头信息，长短链接等等。
    + **依赖关系：**比如接口的调用需要涉及到第三方或者其他的准备工作等等。
- API一旦发布了，要改变的成本就很大很大。


### 好的API应该具有:
- **易于学习：**即使没有文档也易于使用。
- **不易误用：**这一点很重要，要减少使用者的心智负担。
- **易于满足需求：**API的完备性和正交性。能够容易的满足需求，完备性保证功能完整，正交性保证接口的简洁性，不需要为所有的需求提供接口，而是由用户去组合。
- **易于扩展性**


### 怎么样设计良好的API？
- **专一：**一个API的功能应该是单一的，需要能够很容易的解释和理解，也就会更好用。
- **尽可能的小：**小有很多的优势，易于理解和维护。
- **尽量少的外部依赖：**减少使用者的成本。
- **设计不被实现影响：**不要暴漏实现细节给用户，竟可能少的暴露，不止是内部细节，对于不必要的接口尽量不要发布，比如使用不多的功能，可以暂时不暴露接口。
- **良好的命名：**尽量做到自描述。
- **完善的文档，有DEMO更好**
- **考虑性能**


#### 参考文章
- [什么是好的API设计？](http://www.jianshu.com/p/f5ed9c8415b3)
- [javascript的api设计原则](http://www.cnblogs.com/constantince/p/5580003.html)
- [[译]设计更好的JavaScript API](http://dickeylth.github.io/2013/04/21/DesigningBetterJavaScriptAPIs/)
- [在SDK&API的开发中、你一定要知道的7件事！](http://www.jianshu.com/p/2ee50a2e3750)
- [如何设计出色的 JavaScript API](http://nuysoft.com/2013/09/24/secrets-of-awesome-javascript-api-design/)
- [JavaScript API 设计原则](http://jinlong.github.io/2015/08/31/secrets-of-awesome-javascript-api-design/)
- [出色的 JavaScript API 设计秘诀](https://www.oschina.net/translate/secrets-of-awesome-javascript-api-design)

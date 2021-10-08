# iframeLearn

在线访问：http://iframelearnparent.rayhomie.icu/

总结：

- **谁调用的postMessage来发送消息，就在谁的window下监听message事件来获取消息**。
- **当前页面下的脚本只能操作当前页面的dom来监听事件**。
- 在父页面中监听iframe的window的message事件，是无法捕获到消息的。
- 在iframe中监听父页面的window的message事件，也是无法捕获到消息的。

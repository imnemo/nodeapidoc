nodeapidoc
==========

The newest nodejs documents compiled from nodejs's git repository directly!  
算了，还是别拽英文了~ 嘿嘿  
当然，你也可以很简单的使用`make doc`命令自己编译一份文档，我编译一份放到本地也只是为了访问方便和快速，因为  
有相当一些时候，我访问node官网，速度都不那么给劲儿，虽然情况比以前好多了~~  
因为是直接从node源码中编译的文档，所以肯定是最新的，现在本文档是`V0.7.9-pre`，node官网文档是`V0.6.17`  
  
##Version##
V0.7.9-pre  

##How to use##
直接`git clone`一份到本地  
  
如果本地有搭有`apache`环境，那就把这些静态页面放到网站目录下吧，通过访问  
`http://localhost/nodeapidoc/api`  
*温馨提示:可以加入标签页哦！！*
  
如果没有搭建`apache`环境，那么可以自己使用`nodejs`hack一下喽，用`connect`实现很简单很简单吧~~  
  
如果懒到写`nodejs`代码都不愿意，那就直接在浏览器打开`index.html`文件吧，反正都是静态页面，不过这样会很丑！  

##TODO##
> 1、用connect写一个`nodejs`版服务器，练手嘛。。。虽然很简单！  
> 2、既然练手，那也得有点专业精神，包装成一个可全局安装的`node module`，这样可以直接通过命令行启动文档喽~**Cool!**  
否则如果用`nodejs`做服务端的话，还得先去命令行启动，然后到浏览器请求本地文档页面！  
  
##Relative##
[这哥们儿已经hack了一个比官方文档更漂亮且实用的文档了](http://millermedeiros.github.com/mdoc/examples/node_api/doc/)  
可搜索哦~~
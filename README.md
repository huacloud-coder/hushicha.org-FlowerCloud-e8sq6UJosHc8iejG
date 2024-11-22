## 思维导航

* [前言](https://github.com)
* [项目介绍](https://github.com)
* [项目源代码](https://github.com)
* [.NET环境准备](https://github.com)
* [使用 CLI 安装](https://github.com)
* [创建文档类型](https://github.com)
* [编辑内容模板](https://github.com)
* [创建内容节点](https://github.com)
* [查看运行效果](https://github.com)
* [项目源码地址](https://github.com)
* [优秀项目和框架精选](https://github.com)
* [DotNetGuide技术社区](https://github.com)

## 前言


今天大姚给大家分享一个.NET开源、免费（MIT License）、功能强大、灵活易用的内容管理系统：`Umbraco CMS`。本文将介绍在.NET中如何使用Umbraco CMS快速构建一个属于自己的内容管理系统。


## 项目介绍


Umbraco CMS是一个基于.NET开源、免费（MIT License）、功能强大、灵活易用的内容管理系统。它能够帮助你创建美观现代的网站，并与最新的.NET技术和各种服务集成。无论你是个人开发者还是企业客户，Umbraco CMS都是一个值得考虑的选择。


:[飞数机场](https://ze16.com)## 项目源代码



![](https://img2024.cnblogs.com/blog/1336199/202411/1336199-20241121205240465-1732230737.png)


## .NET环境准备


* 下载.NET 9\.0：[https://dotnet.microsoft.com/zh\-cn/download/dotnet/9\.0](https://github.com)


![](https://img2024.cnblogs.com/blog/1336199/202411/1336199-20241121205308554-525599066.png)


验证是否安装成功：



```
dotnet --list-sdks
```

![](https://img2024.cnblogs.com/blog/1336199/202411/1336199-20241121205323909-1584780927.png)


## 使用 CLI 安装


### 安装 Umbraco 模板：



```
dotnet new install Umbraco.Templates

```

![](https://img2024.cnblogs.com/blog/1336199/202411/1336199-20241121205340099-1775010354.png)


### 创建新项目



```
dotnet new umbraco --name MyUmbracoProject
```

![](https://img2024.cnblogs.com/blog/1336199/202411/1336199-20241121205400567-2109097072.png)


![](https://img2024.cnblogs.com/blog/1336199/202411/1336199-20241121205405634-1870682062.png)


### 项目运行


* https://localhost:44304/umbraco/section/content/dashboard/dashboardTabsContentIntro


![](https://img2024.cnblogs.com/blog/1336199/202411/1336199-20241121205418989-1233383024.png)


### 安装Umbraco


![](https://img2024.cnblogs.com/blog/1336199/202411/1336199-20241121205431317-2061650154.png)


![](https://img2024.cnblogs.com/blog/1336199/202411/1336199-20241121205435778-1009259894.png)


![](https://img2024.cnblogs.com/blog/1336199/202411/1336199-20241121205444018-123983618.png)


![](https://img2024.cnblogs.com/blog/1336199/202411/1336199-20241121205450462-400277579.png)


## 创建文档类型


![](https://img2024.cnblogs.com/blog/1336199/202411/1336199-20241121205504486-1359620216.png)


 创建名为：`DotNetGuide`的创建文档类型，并设置`Allow at root`。


![](https://img2024.cnblogs.com/blog/1336199/202411/1336199-20241121205517326-320675414.png)


## 编辑内容模板


### 下载模板代码


[https://umbra.co/Umbracotemplate](https://github.com)


![](https://img2024.cnblogs.com/blog/1336199/202411/1336199-20241121205536798-853173180.png)


 查看模板`index.html`样式：



![](https://img2024.cnblogs.com/blog/1336199/202411/1336199-20241121205548246-1903457591.png)


 




### 编辑DotNetGuide模板内容


![](https://img2024.cnblogs.com/blog/1336199/202411/1336199-20241121205612973-1956392445.png)


 复制模板`index.html`内容到DotNetGuide模板中：


![](https://img2024.cnblogs.com/blog/1336199/202411/1336199-20241121205628606-1065817812.png)


 复制 css 和 images 文件夹，并将其放在 MyUmbracoProject 文件夹内的 wwwroot 文件夹中。


![](https://img2024.cnblogs.com/blog/1336199/202411/1336199-20241121205638284-1370644713.png)


## 创建内容节点


![](https://img2024.cnblogs.com/blog/1336199/202411/1336199-20241121205650566-223396406.png)


![](https://img2024.cnblogs.com/blog/1336199/202411/1336199-20241121205655281-448206847.png)


![](https://img2024.cnblogs.com/blog/1336199/202411/1336199-20241121205700809-907102025.png)


## 查看运行效果


![](https://img2024.cnblogs.com/blog/1336199/202411/1336199-20241121205718077-18887800.png)


![](https://img2024.cnblogs.com/blog/1336199/202411/1336199-20241121205723516-2049778738.png)


![](https://img2024.cnblogs.com/blog/1336199/202411/1336199-20241121205730290-1109254952.png)


![](https://img2024.cnblogs.com/blog/1336199/202411/1336199-20241121205736201-465109854.png)


## 项目源码地址


更多项目实用功能和特性欢迎前往项目开源地址查看👀，别忘了给项目一个Star支持💖。


* 开源地址：[https://github.com/umbraco/Umbraco\-CMS](https://github.com)


## 优秀项目和框架精选


该项目已收录到C\#/.NET/.NET Core优秀项目和框架精选中，关注优秀项目和框架精选能让你及时了解C\#、.NET和.NET Core领域的最新动态和最佳实践，提高开发工作效率和质量。坑已挖，欢迎大家踊跃提交PR推荐或自荐（让优秀的项目和框架不被埋没🤞）。


* GitHub开源地址：[https://github.com/YSGStudyHards/DotNetGuide/blob/main/docs/DotNet/DotNetProjectPicks.md](https://github.com)
* Gitee开源地址：[https://gitee.com/ysgdaydayup/DotNetGuide/blob/main/docs/DotNet/DotNetProjectPicks.md](https://github.com)


## DotNetGuide技术社区


* DotNetGuide技术社区是一个面向.NET开发者的开源技术社区，旨在为开发者们提供全面的C\#/.NET/.NET Core相关学习资料、技术分享和咨询、项目框架推荐、求职和招聘资讯、以及解决问题的平台。
* 在DotNetGuide技术社区中，开发者们可以分享自己的技术文章、项目经验、学习心得、遇到的疑难技术问题以及解决方案，并且还有机会结识志同道合的开发者。
* 我们致力于构建一个积极向上、和谐友善的.NET技术交流平台。无论您是初学者还是有丰富经验的开发者，我们都希望能为您提供更多的价值和成长机会。



> [**欢迎加入DotNetGuide技术社区微信交流群👪**](https://github.com)





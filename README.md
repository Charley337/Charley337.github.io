# [Charley337] Welcome
> 目前我打算把本网站建成一个静态的，用于展示我学习成果的网站。

## 网站设计要求

* 网站应该方便管理页面，具有发布、删除页面的功能；

  为了实现这个功能，可能需要一个webserver进行本地操作，但我不希望有人能在github.io上访问到这一server的文件，不过就算能访问似乎也没什么问题。

* 编写一个新页面不应该很困难，应该只需要提供页面内容，由程序自动生成格式化页面；

* 网站应该具有统一的主题风格，且主题风格要容易更换；

* 网站应该有很好的导航功能；

* 网站应该是静态的（否则github.io无法实现）;

## 关于内容管理

计划的内容有以下部分：

* 帖子Post

  用文件夹来管理：

  content/post/page....

* 页面Page

  主要内容为markdown格式转化为html格式，要求主题风格统一

管理内容可以通过一个json表格，使用cms来管理，添加内容和删除内容都必须要通过cms来进行（cms需要一个身份验证，且可以更改密码）

**现在 cms 已经放在另一个仓库了：CMS-github.io** 
先进的.NET开源工作流快速开发平台 - [RoadFlow]
========

 [RoadFlow] 是 [路德软件][RoadFlow] 旗下集成工作流引擎的 .NET 快速开发平台，由从事六年以上OA及工作流开发与实施的团队设计开发，该工作流平台已应用于众多大型企事业单位。拥有全浏览器兼容的可视化流程设计器、表单设计器、基于角色的权限管理等先进设计理念，是您开发 **OA、CRM、HR** 等企事业各种应用管理系统的最佳基础平台。 [路德软件][RoadFlow] 兼承 “ **开放 分享 进步** ” 的原则,对 [RoadFlow] 工作流引擎开源，希望与广大工作流开发者共同进步！

 平台基于 **.Net** 的 **B/S** 架构开发，需要 **.Net Framework 4.0** 以上版本和 **IIS6.0** 以上运行环境。数据库支持 **SQLServer2005** 以上版本,也可以扩展支持 **MySql,Oracle** 等数据库（需要自己实现数据访问层）。

<img src="http://www.cqroad.cn/Images/img01.png">

# 平台特点

  * 客户端框架采用 jquery 为基础的 RoadUI ，轻量、简单、快速、可扩展
  * 全浏览器支持，支持 IE6+，火狐，谷歌等所有浏览器
  * 服务端采用基于Razor模板引擎的WebPage2技术开发，抛弃笨重的 WebForm 控件，ViewState 和 Page 类，更快速轻量
  * 采用 .Net 多层架构设计，支持 MSSQL，MySql，Oracle 等任意数据库扩展
  * 可扩展的缓存设计，支持 .Net 缓存，Memcached，Redis 等多种缓存方式
  * 可视化的流程设计器，使流程从设计到运行都可采用图形化展现

###可视化流程设计器
<img src="http://www.cqroad.cn/Images/img02.png">

 [RoadFlow] 可视化流程设计器基于 JavaScript Library 进行二次开发，和其它流程设计器相比无需Flash，Silverlight等第三方插件支持，并且完全兼容IE6+，Firefox，Google等浏览器。
###快捷的表单设计器
<img src="http://www.cqroad.cn/Images/img03.png">

 工作流表单设计器是在第三方html编辑器的基础上增加自定义的流程表单控件，通过可视化设计使表单控件和流程相关数据库表关联，以在流程流转过程中对业务流据的查看和更新。
###轻量的客户端框架
<img src="http://www.cqroad.cn/Images/img04.png">

 **RoadFlow** 没有采用 **Extjs** 等第三方富客户端框架，而是团队自己基于**jquery** 开发的轻量级客户端 - **RoadUI** ，该框架轻量，快速，易上手，对客户端性能消耗较低。

官方站点：<http://www.cqroad.cn/>

联系QQ：	**493501010**


##### 系统默认账号（N#个人问）：

演示用管理员帐号：

账号： **xh** 
密码： **111** 

应广大猿友要求添加习惯帐号 **admin** （其它你懂的）。

# 关于源代码的说明：
### 各个特性版本分支：
#### MVC
 —— 发布站点使用 **MVC** 模式。
#### WebApplication
 —— 发布站点使用 **Web应用程序**
#### WebSite
 —— 使用“站点目录”方式发布的站点。
#### CodeBuild
 —— 仅使用源代码就可编译版本。
### 标签
**WebApplication_vX.X、WebSite_vX.X、CodeBuild_vX.X** 标签 —— 对应主线不同版本的特性分支标签。
如果主线更新，但是没有对应的特性分支（例如，主线已到 v2.0 版，但是 WebApplication 分支还没出来），访客可以自己制作自己的特性分支：只要将现有的特性版本使用 git 衍合 到所需分支上即可。（所有对应版本的特性分支标签也是这么制作出来的）
### 版本
   * 按国人传统习惯，么有 “4”这个门牌，所以 **v1.4** 是不存在的。（版本控收集者们不用纠结的到处找到了，因为根本就没有。）
   * **v1.5** 由于由 **WebSite** 模式转换到 **WebApplication** 的 **MVC** 模式，所以变动较大，代码升级时请注意。

### 开发工具
目前的源代码需要: **VS2010** （需要安装 **MVC4** ）最低, **VS2012** 推荐。

### 软件包
现在官方已经自带定制版的 [LitJson] ，不再需要自己手动添加才能全部编译。

[RoadFlow]:http://www.cqroad.cn
[GitHub]:https://github.com
[git@osc]:http://git.oschina.net
[LitJson]:https://github.com/lbv/litjson/

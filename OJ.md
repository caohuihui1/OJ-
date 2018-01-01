#HTML5  
##简介：HTML5 是下一代 HTML 标准，是HTML最新的修订版本，2014年10月由万维网联盟完成标准制定。HTML5的设计目的是为了在移动设备上支持多媒体。  
##新特性：1.用于绘画的 canvas 元素  
         2.用于媒介回放的 video 和 audio 元素  
         3.对本地离线存储的更好的支持    
         4.新的特殊内容元素，比如 article、footer、header、nav、section  
         5.新的表单控件，比如 calendar、date、time、email、url、search  
##改进：+新元素  
       +新属性  
       +完全支持 CSS3  
       +Video 和 Audio，使用 HTML5 可以简单的在网页中播放 视频(video)与音频 (audio)  
       +2D/3D 制图  
       +本地存储  
       +本地 SQL 数据  
       +Web 应用  
##开发应用：  
+本地数据存储  
+访问本地文件  
+本地 SQL 数据  
+缓存引用  
+Javascript 工作者  
+XHTMLHttpRequest2  
##绘制图形：  
1.使用 <canvas> 元素  
2.使用内联 SVG  
3.使用 CSS3 2D 转换、CSS3 3D 转换  
##使用css3：  
1.新选择器  
2.新属性  
3.动画  
4.2D/3D 转换  
5.圆角  
6.阴影效果  
7.可下载的字体  
##添加很多语义元素：  
  <http://www.runoob.com/html/html5-intro.html>  
## 新表单元素, 新属性，新输入类型，自动验证  
##移除元素：    
-acronym
-applet
-	basefont
-	big
-	center
-	dir
-	font
-	frame
-	frameset
-	noframes
-	strike  
##应用缓存区：  
使用 HTML5，通过创建 cache manifest 文件，可以轻松地创建 web 应用的离线版本。
HTML5 引入了应用程序缓存，这意味着 web 应用可进行缓存，并可在没有因特网连接时进行访问。
##应用程序缓存为应用带来三个优势：  
1.	离线浏览 - 用户可在应用离线时使用它们  
2.	速度 - 已缓存资源加载得更快  
3.	减少服务器负载 - 浏览器将只从服务器下载更新过或更改过的资源。  
#	CSS  
##简介：  
-CSS 指层叠样式表 (Cascading Style Sheets)  
-	样式定义如何显示 HTML 元素  
-	样式通常存储在样式表中  
-把样式添加到 HTML 4.0 中，是为了解决内容与表现分离的问题  
-	外部样式表可以极大提高工作效率  
-	外部样式表通常存储在 CSS 文件中  
-	多个样式定义可层叠为一  
##用法：  
       -id和class选择器  
       -Backgrounds背景设置  
       -Test文本设置  
       -Fonts字体设置  
       -Link连接 ul列表样式 table表格 盒子模型 border边框   
       -Outline 轮廓属性  margin外边框 padding填充 float浮动  
       -导航栏 下栏菜单 提示工具 图片是否透明[等](http://www.runoob.com/css/css-intro.html)  
#	JavaScript  
##简介：  
javaScript 是互联网上最流行的脚本语言，这门语言可用于 HTML 和 web，更可广泛用于服务器、PC、笔记本电脑、平板电脑和智能手机等设备。  
##具体用法：<http://www.runoob.com/js/js-intro.html>  
#JQuery  
##简介：jQuery 是一个 JavaScript函数库。jQuery 库可以通过一行简单的标记被添加到网页中，极大地简化了 JavaScript 编程。  
##功能：  
-HTML 元素选取  
-	HTML 元素操作  
-	CSS 操作  
-	HTML 事件函数  
-	JavaScript 特效和动画  
-	HTML DOM 遍历和修改  
-	AJAX  
-	Utilities  
-	提供大量插件  
##语法：$(selector).action()  
## 选择器：jQuery 选择器允许您对 HTML 元素组或单个元素进行操作。  
jQuery 选择器基于元素的 id、类、类型、属性、属性值等"查找"（或选择）HTML 元素。 它基于已经存在的 CSS 选择器，除此之外，它还有一些自定义的选择器。  
jQuery 中所有选择器都以美元符号开头：$()。  
-元素选择器  
-ID选择器     
-.class选择器  
##事件：鼠标事件 键盘事件 表单事件 文档窗口事件  
##效果：隐藏显示 淡入淡出 滑动 动画 停止动画 jQuerycallback jQuery链  
#Bootstrap  
##简介：Bootstrap，来自 Twitter，是目前最受欢迎的前端框架。Bootstrap 是基于 HTML、CSS、JAVASCRIPT 的，它简洁灵活，使得 Web 开发更加快捷。  
##Bootstrap包的内容：  
-	 基本结构：Bootstrap 提供了一个带有网格系统、链接样式、背景的基本结构。  
-	CSS：Bootstrap 自带以下特性：全局的 CSS 设置、定义基本的 HTML 元素样式、可扩展的 class，以及一个先进的网格系统。  
-	组件：Bootstrap 包含了十几个可重用的组件，用于创建图像、下拉菜单、导航、警告框、弹出框等等。  
-	JavaScript 插件：Bootstrap 包含了十几个自定义的 jQuery 插件。您可以直接包含所有的插件，也可以逐个包含这些插件。  
-	定制：您可以定制 Bootstrap 的组件、LESS 变量和 jQuery 插件来得到您自己的版本。  
##bootstrap网格系统的工作原理：    
-行必须放置在 .container class 内，以便获得适当的对齐（alignment）和内边距（padding）。   
-	使用行来创建列的水平组。    
-	内容应该放置在列内，且唯有列可以是行的直接子元素。    
-	预定义的网格类，比如 .row 和 .col-xs-4，可用于快速创建网格布局。LESS 混合类可用于更多语义布局。    
-	列通过内边距（padding）来创建列内容之间的间隙。该内边距是通过 .rows 上的外边距（margin）取负，表示第一列和最后一列的行偏移。    
-	网格系统是通过指定您想要横跨的十二个可用的列来创建的。例如，要创建三个相等的列，则使用三个 .col-xs-4。    
##代码显示方式：   
-第一种是 <code> 标签。如果您想要内联显示代码，那么您应该使用 <code> 标签。    
-	二种是 <pre> 标签。如果代码需要被显示为一个独立的块元素或者代码有多行，那么您应该使用 <pre> 标签。    
##bootstrap表单布局：    
-垂直表单（默认）     
-内联表单   
-水平表单    
##站点引用bootstrap插件方式：    
-单独引用：使用 Bootstrap 的个别的 *.js 文件。一些插件和 CSS 组件依赖于其他插件。如果您单独引用插件，请先确保弄清这些插件之间的依赖关系。    
-编译（同时）引用：使用 bootstrap.js 或压缩版的 bootstrap.min.js。    
#Layui    
##简介：Layui 是一款采用自身模块规范编写的国产前端UI框架，遵循原生HTML/CSS/JS的书写与组织形式，门槛极低，拿来即用。其外在极简，却又不失饱满的内在，体积轻盈，组件丰盈，从核心代码到API的每一处细节都经过精心雕琢，非常适合界面的快速开发。    
#Ajax    
##简介：1.AJAX 是一种在无需重新加载整个网页的情况下，能够更新部分网页的技术.用于创建快速动态网页的技术。通过在后台与服务器进行少量数据交换，AJAX 可以使网页实现异步更新。
AJAX = 异步 JavaScript 和 XML。  
2.	XMLHttpRequest 用于在后台与服务器交换数据。这意味着可以在不重新加载整个网页的情况下，对网页的某部分进行更新.  
3.	使用 XMLHttpRequest 对象的 open() 和 send() 方法将请求发送到服务器  
4.	使用 XMLHttpRequest 对象的 responseText 或 responseXML 属性获取来自服务器的响应。  
#Javaee  
##简介：Java EE(Java Platform，Enterprise Edition)是sun公司推出的企业级应用程序版本。这个版本以前称为 J2EE。能够帮助我们开发和部署可移植、健壮、可伸缩且安全的服务器端 Java应用程序。Java EE 是在 Java SE 的基础上构建的，它提供Web 服务、组件模型、管理和通信 API，可以用来实现企业级的面向服务体系结构(service-oriented architecture，SOA)和 Web 2.0应用程序。  
##主要技术：  
  -JDBC(Java Database Connectivity)提供连接各种关系数据库的统一接口,可以为多种关系数据库提供统一访问，它由一组用Java语言编写的类和接口组成。JDBC为工具/数据库开发人员提供了一个标准的API，据此可以构建更高级的工具和接口，使数据库开发人员能够用纯 Java API 编写数据库应用程序，同时，JDBC也是个商标名。  
 -EJB(Enterprise JavaBeans)使得开发者方便地创建、部署和管理跨平台的基于组件的企业应用。  
-Java RMI(Java Remote Method Invocation)用来开发分布式Java应用程序。一个Java对象的方法能被远程Java虚拟机调用。这样，远程方法调用可以发生在对等的两端，也可以发生在客户端和服务器之间，只要双方的应用程序都是用Java写的。  
-JNDI(Java Naming and Directory Interface)提供从Java平台到的统一的无缝的连接。这个接口屏蔽了企业网络所使用的各种命名和目录服务。  
-JMAPI(Java Management API)为异构网络上系统、网络和服务管理的开发提供一整套丰富的对象和方法。  
-JMS(Java Message Service)提供企业消息服务，如可靠的消息队列、发布和订阅通信、以及有关推拉(Push/Pull)技术的各个方面。    
-JTS(Java transaction Service)提供存取事务处理资源的开放标准，这些事务处理资源包括事务处理应用程序、事务处理管理及监控。    
-JMF(Java Media Framework API)，它可以帮助开发者把音频、视频和其他一些基于时间的媒体放到Java应用程序或applet小程序中去，为多媒体开发者提供了捕捉、回放、编解码等工具，是一个弹性的、跨平台的多媒体解决方案。  
-Annotation(Java Annotation)，在已经发布的JDK1.5(tiger)中增加新的特色叫 Annotation。Annotation提供一种机制，将程序的元素如:类，方法，属性，参数，本地变量，包和元数据联系起来。这样编译器可以将元数据存储在Class文件中。这样虚拟机和其它对象可以根据这些元数据来决定如何使用这些程序元素或改变它们的行为。  
-JavaBeans，它是一个开放的标准的组件体系结构，它独立于平台，但使用Java语言。一个JavaBean是一个满足JavaBeans规范的Java类，通常定义了一个现实世界的事物或概念。一个JavaBean的主要特征包括属性、方法和事件。通常，在一个支持JavaBeans规范的开发环境(如Sun Java Studio 和IBM VisualAge for Java)中，可以可视地操作JavaBean，也可以使用JavaBean构造出新的JavaBean。JavaBean的优势还在于Java带来的可移植性。现在，EJB (Enterprise JavaBeans) 将JavaBean概念扩展到Java服务端组件体系结构，这个模型支持多层的分布式对象应用。除了JavaBeans，典型的组件体系结构还有DCOM和CORBA。  
-javaFX，Sun刚刚发布了JavaFX技术的正式版,它使您能利用 JavaFX 编程语言开发富互联网应用程序(RIA)。JavaFX Script编程语言(以下称为JavaFX)是Sun微系统公司开发的一种declarative, staticallytyped(声明性的、静态类型)脚本语言。JavaFX技术有着良好的前景，包括可以直接调用Java API的能力。因为 JavaFXScript是静态类型，它同样具有结构化代码、重用性和封装性，如包、类、继承和单独编译和发布单元，这些特性使得使用Java技术创建和管理大型程序变为可能。  
-JMX(Java Management Extensions，即Java管理扩展)是一个为应用程序、设备、系统等植入。  
管理功能的框架。JMX可以跨越一系列异构操作系统平台、系统体系结构和网络传输协议，灵活的开发无缝集成的系统、网络和服务管理应用。  
-JPA (Java Persistence API)，JPA通过JDK 5.0注解或XML描述对象-关系表的映射关系，并将运行期的实体对象持久化到数据库中。  
#Tomcat  
##简介：Tomcat 是一个轻量级应用服务器，在中小型系统和并发访问用户不是很多的场合下被普遍使用，是开发和调试JSP 程序的首选。对于一个初学者来说，可以这样认为，当在一台机器上配置好Apache 服务器，可利用它响应对HTML 页面的访问请求。实际上Tomcat 部分是Apache 服务器的扩展，但它是独立运行的，所以当你运行tomcat 时，它实际上作为一个与Apache 独立的进程单独运行的。  
#springMVC  
##简介：Spring MVC 是一个模型 - 视图 - 控制器（MVC）的Web框架建立在中央前端控制器servlet（DispatcherServlet），它负责发送每个请求到合适的处理程序，使用视图来最终返回响应结果的概念。Spring MVC 是 Spring 产品组合的一部分，它享有 Spring IoC容器紧密结合Spring松耦合等特点，因此它有Spring的所有优点。  
#	Mybatis  
##简介  
   MyBatis 是支持定制化 SQL、存储过程以及高级映射的优秀的持久层框架。MyBatis 避免了几乎所有的 JDBC 代码和手动设置参数以及获取结果集。MyBatis 可以对配置和原生Map使用简单的 XML 或注解，将接口和 Java 的 POJOs(Plain Old Java Objects,普通的 Java对象)映射成数据库中的记录。  
##功能架构：  
1.	API接口层：提供给外部使用的接口API，开发人员通过这些本地API来操纵数据库。接口层一接收到调用请求就会调用数据处理层来完成具体的数据处理。   
2.	数据处理层：负责具体的SQL查找、SQL解析、SQL执行和执行结果映射处理等。它主要的目的是根据调用的请求完成一次数据库操作。   
3.	基础支撑层：负责最基础的功能支撑，包括连接管理、事务管理、配置加载和缓存处理，这些都是共用的东西，将他们抽取出来作为最基础的组件。为上层的数据处理层提供最基础的支撑。   
#Maven  
##简介：Apache Maven 是一套软件工程管理和整合工具。基于工程对象模型（POM）的概念，通过一个中央信息管理模块，Maven 能够管理项目的构建、报告和文档。  
##Maven完成的工作：  
-构建  
-文档生成  
-报告  
-依赖  
-SCMs  
-发布  
-分发  
-邮件列表  
##maven的目标：  
-为开发者提供一个可复用、可维护、更易理解的工程综合模型  
-与这个模型交互的插件或者工具  
#Apache  
##简介：Apache是世界使用排名第一的Web服务器软件。它可以运行在几乎所有广泛使用的计算机平台上，由于其跨平台和安全性被广泛使用，是最流行的Web服务器端软件之一。它快速、可靠并且可通过简单的API扩充，将Perl/Python等解释器编译到服务器中。  
##特征：  
-支持最新的HTTP/1.1通信协议  
-拥有简单而强有力的基于文件的配置过程  
-支持通用网关接口  
-支持基于IP和基于域名的虚拟主机  
-支持多种方式的HTTP认证  
-集成Perl处理模块  
-集成代理服务器模块  
-支持实时监视服务器状态和定制服务器日志  
-支持服务器端包含指令(SSI)  
-支持安全Socket层(SSL)  
-提供用户会话过程的跟踪  
-支持FastCGI  
-通过第三方模块可以支持Java Servlets  
-如果你准备选择Web服务器，毫无疑问Apache是你的最佳选择。  
#Activemq  
##简介：  
   ActiveMQ 是Apache出品，最流行的，能力强劲的开源消息总线。ActiveMQ 是一个完全支持JMS1.1和J2EE 1.4规范的 JMS Provider实现,尽管JMS规范出台已经是很久的事情了,但是JMS在当今的J2EE应用中间仍然扮演着特殊的地位。  
##特性：  
1.多种语言和协议编写客户端。语言: Java, C, C++, C#, Ruby, Perl, Python, PHP。应用协议: OpenWire,Stomp REST,WS Notification,XMPP,AMQP   
2. 完全支持JMS1.1和J2EE 1.4规范 (持久化,XA消息,事务)   
3. 对Spring的支持,ActiveMQ可以很容易内嵌到使用Spring的系统里面去,而且也支持Spring2.0的特性   
4. 通过了常见J2EE服务器(如 Geronimo,JBoss 4, GlassFish,WebLogic)的测试,其中通过JCA 1.5 resource adaptors的配置,可以让ActiveMQ可以自动的部署到任何兼容J2EE 1.4 商业服务器上   
5. 支持多种传送协议:in-VM,TCP,SSL,NIO,UDP,JGroups,JXTA   
6. 支持通过JDBC和journal提供高速的消息持久化   
7. 从设计上保证了高性能的集群,客户端-服务器,点对点   
8. 支持Ajax   
9. 支持与Axis的整合   
10. 可以很容易得调用内嵌JMS provider,进行测试   
#Zookeeper  
##简介：  
     ZooKeeper是一种分布式协调服务，用于管理大型主机。在分布式环境中协调和管理服务是一个复杂的过程。ZooKeeper通过其简单的架构和API解决了这个问题。ZooKeeper允许开发人员专注于核心应用程序逻辑，而不必担心应用程序的分布式特性。  
##工作流：  
1一旦ZooKeeper集合启动，它将等待客户端连接。客户端将连接到ZooKeeper集合中的一个节点。它可以是leader或follower节点。一旦客户端被连接，节点将向特定客户端分配会话ID并向该客户端发送确认。如果客户端没有收到确认，它将尝试连接ZooKeeper集合中的另一个节点。 一旦连接到节点，客户端将以有规律的间隔向节点发送心跳，以确保连接不会丢失。  
2如果客户端想要读取特定的znode，它将会向具有znode路径的节点发送读取请求，并且节点通过从其自己的数据库获取来返回所请求的znode。为此，在ZooKeeper集合中读取速度很快。  
3如果客户端想要将数据存储在ZooKeeper集合中，则会将znode路径和数据发送到服务器。连接的服务器将该请求转发给leader，然后leader将向所有的follower重新发出写入请求。如果只有大部分节点成功响应，而写入请求成功，则成功返回代码将被发送到客户端。 否则，写入请求失败。绝大多数节点被称为 Quorum 。  
#	Kafka  
##简介： Apache kafka是消息中间件的一种。Apache Kafka是一个分布式发布 - 订阅消息系统和一个强大的队列，可以处理大量的数据，并使您能够将消息从一个端点传递到另一个端点。 Kafka适合离线和在线消息消费。 Kafka消息保留在磁盘上，并在群集内复制以防止数据丢失。 Kafka构建在ZooKeeper同步服务之上。 它与Apache Storm和Spark非常好地集成，用于实时流式数据分析。  
#C/C++    
##简介：  
1.	C语言，是一种通用的、过程式的编程语言，广泛用于系统与应用软件的开发。具有高效、灵活、功能丰富、表达力强和较高的移植性等特点，在程序员中备受青睐。C语言的设计目标是提供一种能以简易的方式编译、处理低级存储器、产生少量的机器码以及不需要任何运行环境支持便能运行的编程语言。    
2.	C++是一种使用非常广泛的计算机编程语言。C++是一种静态数据类型检查的、支持多重编程范式的通用程序设计语言。它支持过程化程序设计、数据抽象、面向对象程序设计、泛型程序设计等多种程序设计风格。  
#Docker  
##简介：Docker 是一个开源的应用容器引擎，基于 Go 语言 并遵从Apache2.0协议开源。Docker 可以让开发者打包他们的应用以及依赖包到一个轻量级、可移植的容器中，然后发布到任何流行的 Linux 机器上，也可以实现虚拟化。  
##架构：    
1.Docker 使用客户端-服务器 (C/S) 架构模式，使用远程API来管理和创建Docker容器。    
2.Docker 容器通过 Docker 镜像来创建。    
3.容器与镜像的关系类似于面向对象编程中的对象与类。    
#Mysql    
##Mysql是最流行的关系型数据库管理系统    
#Redis    
##简介：Redis是一个由Salvatore Sanfilippo写的key-value存储系统。Redis是一个开源的使用ANSI C语言编写、遵守BSD协议、支持网络、可基于内存亦可持久化的日志型、Key-Value数据库，并提供多种语言的API。  
##Redis数据类型  
 Redis支持五种数据类型：string（字符串），hash（哈希），list（列表），set（集合）及zset(sorted set：有序集合)。  
##Redis命令  
- Redis 命令用于在 redis 服务上执行操作。客户端语法：$ redis-cli  
- 在远程 redis 服务上执行命令。语法：$ redis-cli -h host -p port -a password  


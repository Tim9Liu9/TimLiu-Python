# TimLiu-Python
========
Python资源集合，持续更新。。。 [python 中文学习大本营](http://www.pythondoc.com/) 。
  
  Python库学习收集QQ群:  461273222  ,欢迎入群(入群答案：TimLiu-Python)。
###  目录
- [网页框架](#网页框架)
    - [Django](#Django)
    - [Flask](#Flask)
    - [Tornado](#Tornado)
    - [其他Web相关](#其他Web相关)
- [用户图形接口相关](#用户图形接口相关)
- [网络相关](#网络相关)
- [数据库相关](#数据库相关)
- [游戏相关](#游戏相关)
- [开源框架](#开源框架)
- [大数据与人工智能相关](#大数据与人工智能相关)
- [网络爬虫](#网络爬虫)
- [测试与代码分析审核](#测试与代码分析审核)
- [安全与破解相关](#安全与破解相关)
- [图表及图像相关](#图表及图像相关)
- [视频及语音相关](#视频及语音相关)
- [运维相关](#运维相关)
- [树莓派](#树莓派)
- [第三方平台](#第三方平台)
- [IDE](#IDE)
- [区块链](#区块链)
- [其他库](#其他库)  
- [完整项目](#完整项目) 
- [博客与播客及书籍文档](#博客与播客及书籍文档)
- [好的文章](#好的文章)
- [他人总结](#他人总结)

========
### 具体内容 =============================
========
#### 网页框架
##### Django
 * [Django](https://www.djangoproject.com/) - Django。 
 * [Channels](https://github.com/andrewgodwin/channels) - Channels旨在增强Django的异步能力，同时让Django不仅仅局限于Request-Response模型，能够支持WebSocket、HTTP2推送和背景任务。[2015年出现的十大流行Python库](http://codingpy.com/article/top-10-django-libraries-started-in-2015/) 。
 * [Django-Baker](https://github.com/krisfields/django-baker) - Django Baker可以帮助开发者快速启动项目。只要提供app名称，Django Baker就可以根据models.py文件中的models，自动生成视图、表单、URL、admin页面以及模板。[2015年出现的十大流行Python库](http://codingpy.com/article/top-10-django-libraries-started-in-2015/) 。
 * [Django-Q](https://github.com/Koed00/django-q) - Django Q是一个原生Django分布式任务队列处理应用，通过Python的mutliprocessing模块功能实现。[2015年出现的十大流行Python库](http://codingpy.com/article/top-10-django-libraries-started-in-2015/) 。
 * [django-webpack-loader](https://github.com/owais/django-webpack-loader) - Django webpack loader对[webpack-bundle-tracker](https://github.com/owais/webpack-bundle-tracker)的输出结果进行处理，让你可以在自己的Django应用中使用生成的bundles。[2015年出现的十大流行Python库](http://codingpy.com/article/top-10-django-libraries-started-in-2015/) 。
 * [django-hackathon-starter](https://github.com/DrkSephy/django-hackathon-starter) - django-hackathon-starter这是一个Django Web应用模板程序，可以帮助你快速生成应用。必定能够为你节省大量的开发时间，同时这个库也能用作开发者的学习指南。[2015年出现的十大流行Python库](http://codingpy.com/article/top-10-django-libraries-started-in-2015/) 。
 * [django-seed](https://github.com/Brobin/django-seed) - Django-seed通过[faker](https://github.com/joke2k/faker/)库，为Django模型生成测试数据。该库支持Python和Django的最新版本。[2015年出现的十大流行Python库](http://codingpy.com/article/top-10-django-libraries-started-in-2015/) 。
 * [django-tenants](https://github.com/tomturner/django-tenants) -  django-tenants让django驱动的网站支持多个tenants，这个功能时通过PostgreSQL schemas实现的。这是每个SASS（软件即服务）网站的核心功能。[2015年出现的十大流行Python库](http://codingpy.com/article/top-10-django-libraries-started-in-2015/) 。
 * [Python+Django构建的Blog](https://github.com/xushvai/io) - 基于Python+Django构建的Blog  <http://xushvai.github.io/io/>
 * [LibraryManagement](https://github.com/yumendy/LibraryManagement) - LibraryManagement图书管理系统(Django1.9.1+Bootstrap3)。
 * [CommunityManagement](https://github.com/yumendy/CommunityManagement) - 用Django基于组合模式开发的一个小型的社团管理系统。
 * [django-shop](https://github.com/awesto/django-shop) - Django做的开源电子商务网站(商城)
 * [weixin_market](https://github.com/weiguobin/weixin_market) - 基于mezzanine与django的web服务器——微信商城。
 * [deisp](https://github.com/deis/deisp) - 开源PaaS系统Deis是一个 Django/Celery API 服务器、Python CLI 和一组 Chef cookbooks 合并起来提供一个类似 Heroku 的应用平台，用于公有云和私有云。
 * [OSQA](https://github.com/dzone/OSQA) - 一款免费且开源的问答系统，采用Python的Django开发框架，基于中国优秀的问答系统CNProg，非常类似国外著名的技术问答网站http://stackoverflow.com。[官网](http://www.dzonesoftware.com/products/open-source-question-answer-software)
 * [ASKBOT-devel](https://github.com/ASKBOT/askbot-devel) - 一款免费且开源的问答系统，采用Python的Django开发
 * [taiga-back](https://github.com/taigaio/taiga-back) - Taiga功能非常强大的项目管理平台，用于初创企业和敏捷开发团队，采用Django 框架开发，前端基于 AngularJS 实现。
 * [django-simple-captcha](https://github.com/mbi/django-simple-captcha) - 一个第三方django APP，用于为表单添加验证码图片。
 * [django-pure-pagination](https://github.com/jamespacileo/django-pure-pagination) - Django的分页插件。
 * [DjangoUeditor](https://github.com/zhangfisher/DjangoUeditor) - 本模块帮助在Django应用中集成百度Ueditor HTML编辑器。
 * [Xadmin](https://github.com/sshwsfc/xadmin) - xadmin是一个替代django admin的项目,使用了更加灵活的架构设计及Bootstrap UI框架。 [官网](http://sshwsfc.github.io/xadmin/)
 * [django-debug-toolbar](https://pypi.python.org/pypi/django-debug-toolbar) - 查看某个页面中所有的context变量值，还可以看到HTTp头、模板、缓存等各种信息，总之很全面也很好用。
 * [Django-ERP](https://github.com/zhuinfo/Django-ERP) - Django-ERP是一款基于Django开发的ERP管理软件，包含常用的销售管理、采购管理、库存管理、组织管理等，支持按项目归集费用，支持工作流审批，支持采购单、报价单的批量导入。
 * [pylint-django](https://github.com/landscapeio/pylint-django) -  Django的pylint插件，用于分析Django的代码。
 * [djangOauth](https://github.com/X-Mars/djangOauth) - 基于 django + jwt 的 统一权限认证系统 ，账号的集中管理。
 * [sanic](https://github.com/huge-success/sanic) - 一款用python3.5+(async/await及uvloop)写的类flask的高性能web framework。

##### Flask
 * [flask](http://flask.pocoo.org/) - flask， [官方教程中文翻译1](http://www.pythondoc.com/flask/index.html) ，[官方教程中文翻译2](http://docs.jinkan.org/docs/flask/),[Flask使用小结](http://python.jobbole.com/84003/),[Flask开发团队Pocoo的内部编码风格指南| 编程派 | Coding Python.html](http://www.codingpy.com/article/pocoo-internal-style-guide-cn/)。
 * [Blog_mini](https://github.com/xpleaf/Blog_mini) - 基于Flask开发的开源博客系统，具有简洁的界面和强大的后台管理。
 * [lagou-finder](https://github.com/sagaxu/lagou-finder) - python3的flask项目,根据地图展示拉勾网招聘信息的项目。
 * [React-News-Board](https://github.com/ethan-funny/React-News-Board) - 实例讲解一个信息聚合阅读的项目,基于 Flask+React 的全栈开发和部署。
 * [Flask 常用库详情](https://juejin.im/post/57da3f4d79bc440065da3639) - flask-script、flask-login、flask-admin、Flask-WTF、flask-principal、flask-restful、flask-api、Flask-Mail、Flask-User、flask-security、flask-babel、flask-locale。

##### Tornado
 * [tornado](https://github.com/tornadoweb/tornado) - tornado是非阻塞式 Web 服务器框架，而且速度相当快。[官网](http://www.tornadoweb.org)，[Introduction to Tornado 中文翻译](http://demo.pythoner.com/itt2zh/index.html) , [中文教程](http://www.tornadoweb.cn/ )。

##### 其他Web相关
 * [Bottle](http://bottlepy.org/docs/dev/index.html) - Bottle是一个快速、简单、轻量的WSGI微型web框架。利用Bottle构建小型站点和API的时间以秒计算。这个框架只有一个py文件，可以把它放进任何目录。
 * [Tyrion](https://github.com/WuPeiqi/Tyrion) - 支持多WEB框架Form表单验证组件，其完美的支持Tornado、Django、Flask、Bottle Web框架。
 * [Wooey](https://github.com/wooey/Wooey) - Wooey 是一个简单的Python脚本的Web UI 界面。它能够提供日常数据分析，文件处理等功能。[2015年出现的十大流行Python库](http://codingpy.com/article/top-10-django-libraries-started-in-2015/) 。
 * [Odoo](https://sourceforge.net/projects/greenopenerp/files/) - 前OpenERP，开源的ERP和电子商务系统、CRM，功能强大。[官网](https://www.odoo.com/)
 * [stethoscope](https://github.com/Netflix/stethoscope) - 一个web应用，它收集一个指定用户的设备的信息，并为它们提供保护其系统的清晰具体的建议。
 * [Tryton](http://www.tryton.org/download.html) - Tryton是一个用于构建三层高级通用应用平台的商务框架，PostgreSQL作为数据库引擎,主模块用于以下活动领域：会计、发票开取、销售管理、采购管理、客户分析、库存管理、资源制造计划 (MRP)、项目管理、人力资源管理。
 * [cherrypy](https://github.com/cherrypy/cherrypy) - CherryPy是仅次于Django的网站开发框架，它最大的特性就是能够同时运行好几个web服务。
 * [TurboGears](https://github.com/TurboGears/tg2) - TurboGears是一种MVC架构的网站开发框架，它基于一些WSGI组件（比如SQLAlchemy, Ming, Repoze等）、模板引擎（ Genshi, Kajiki, Cheetah, Myghty）和大量的库文件以及中间件（middleware）。同时它具有 widgets控件，可以非常方便的生成一些特定的功能。
 * [Pyramid](https://github.com/Pylons/pyramid) - 由Pylons项目中的一部分演变而来，最大的特点就是灵活性和可扩展性（尤其和Django相比），可以自由的选择使用什么样的数据库、URL结构、模板风格等等。
 * [vibora](https://github.com/vibora-io/vibora) - 一款快速、异步和优雅的Python 3.6+ http 客户端/服务器框架。 [官方文档](https://docs.vibora.io/)
 * [alipay](https://github.com/fzlee/alipay) - 支付宝没有提供Python SDK。生成预付订单需要使用SHA1withRSA签名，签名的生成比较麻烦容易出错。这里提供了一个简单的库，希望能够简化一些Python开发的流程。(推荐使用)
 * [django-alipay](https://github.com/liuyug/django-alipay) - alipay api for django。
 * [alipay](https://github.com/lxneng/alipay) - 支付宝非官方的python实现。
 * [Responder](https://github.com/kennethreitz/responder) - 是一个web框架，基于 Starlette封装，和其他的web框架如django，flask相比，它速度更快。
 * [Molten](https://github.com/Bogdanp/molten) - 使用Python 3.6以上版本构建HTTP API的轻量化、可扩展，快速且高效的框架。它的核心简单易懂，同时高效、稳定，尽可能避免重大更改。也支持用类型注释进行静态类型检查以确保类型安全。

========
#### 用户图形接口相关
 * [pyglet](https://bitbucket.org/pyglet/pyglet/wiki/Home) - Pyglet是一个纯Python语言编写的跨平台框架，用于开发多媒体和窗口 * [pyglet](https://bitbucket.org/pyglet/pyglet/wiki/Home) - Pyglet是一个纯Python语言编写的跨平台框架，用于开发多媒体和窗口特效应用。
 * [kivy](https://kivy.org) - Kivy 是一个开源工具包能够让使用相同源代码创建的程序能跨平台运行。它主要关注创新型用户界面开发，如：多点触摸应用程序。Kivy 还提供一个多点触摸鼠标模拟器。基于 Cython(C extensions for Python) 构建，当前支持的平台包括：Linux、Windows、Mac OS X和Android。
 * [Py2exe](http://www.py2exe.org/) - 把Python脚本转换为windows平台上面可以运行的可执行程序（*.exe）的工具,通过修改源码可以支持python3.0的代码。
 * [pyinstaller](http://www.pyinstaller.org/) - 把Python脚本转换为能直接运行的可执行文件，支持python2.7、python3.3-3.5，支持Windows (32-bit and 64-bit)、Linux (32-bit and 64-bit)、Mac OS X (32-bit and 64-bit)平台。
 * [cx_Freeze](http://sourceforge.net/projects/cx-freeze/files/) - 把Python脚本转换为能直接运行的可执行文件，支持python3.x,特别简单。
 * [Tkinter](https://docs.python.org/3/library/tkinter.html) - Tkinter的是Tk的GUI工具包，与Python附带的Python接口。
 * [wxPython](http://wxpython.org/) - wxPython一个开源的Python接口的wxWindows。
 * [PyQt](http://sourceforge.net/projects/pyqt/files/) - PyQt是一个创建GUI应用程序的工具包。它是Python编程语言和Qt库的成功融合。Qt库是目前最强大的库之一,GPL与商业协议。
 * [PySide](http://wiki.qt.io/PySide) - 对跨平台的 GUI 工具集 Qt 的包装，捆绑在 Python 当中，LGPL协议。 
 * [Eric](http://www.eric-ide.python-projects.org/) - Eric一个支持python、Ruby的强大IDE，与PyQt配合功能非常强大。
 * [PyGTK](http://www.pygtk.org/) - 一系列的 Python 对 GTK+ GUI 库的包装。
 * [pyFacialRecognition](https://github.com/CloudsDocker/pyFacialRecognition) - 用10几行代码自己写个人脸识别程序。
 * [pyecharts](https://github.com/pyecharts/pyecharts) - pyecharts是一个用于生成Echarts图表的类库；而Echarts是百度开源的一个数据可视化JS库。使用pyecharts绘制的图表美观且具有交互性。[官网](http://pyecharts.org)。
 * [Snowy](https://github.com/prideout/snowy/) - Snowy是一个能够处理和生成图像的小模块。

========
#### 网络相关
 * [aiohttp](https://github.com/KeepSafe/aiohttp) - aiohttp是一个为 asyncio 提供了简洁易用的 HTTP 客户端和服务器的库。
 * [Requests](https://github.com/kennethreitz/requests/) - Requests是python的一个HTTP客户端库，跟urllib，urllib2类似，[官网](http://www.python-requests.org/en/latest/) ， [requests 源码阅读](https://github.com/wangshunping/read_requests)。
 * [Requests-cache](http://requests-cache.readthedocs.org/en/latest/index.html) - 缓存外部api请求, [使用教程](https://python.freelycode.com/contribution/detail/660)。 
 * [trip](https://github.com/littlecodersh/trip/) - Trip 是一个协程的网络库，如 Requests 一般简单的操作，程序不再被网络阻塞。[开源项目Trip: 给Requests加上协程](https://mp.weixin.qq.com/s/vczqner3bOlyvAPwCPPgqQ)。
 * [ppmessage](https://github.com/PPMESSAGE/ppmessage) - 皮皮消息，即插即用，在线客服，移动应用内即时通讯，私有的·微信·，自建的·钉钉·，开源，纯Python实现。
 * [uvloop](https://github.com/MagicStack/uvloop) - 一个完整的asyncio事件循环的替代品，它建立在libuv基础之上，由Cython编写而成。性能非常高！
 * [httpstat](https://github.com/reorx/httpstat) - 这个库能够直接将http请求的各状态在终端进行输出，类似于浏览器的调试模式！
 * [ppmessage](https://github.com/PPMESSAGE/ppmessage) - 皮皮消息，即插即用，在线客服，移动应用内即时通讯，私有的·微信·，自建的·钉钉·，开源，纯Python实现。
 * [picoev](https://github.com/kazuho/picoev) - meinheld(greenlet+picoev)使用的网络库，小巧轻量，相较于libevent在数据结构和事件检测模型上做了改进，所以速度更快。但从github看起来已经年久失修，用的人不多。
 * [aiowebsocket](https://github.com/asyncins/aiowebsocket) - AioWebSocket是一个遵循 WebSocket 规范的 异步 WebSocket 客户端，相对于其他库它更轻、更快。

========
#### 数据库相关
 * [SQLAlchemy](http://www.sqlalchemy.org/) - SQLAlchemy一个知名企业级的持久化模式的，专为高效率和高性能的数据库访问设计的，改编成一个简单的Python域语言的完整套件。它采用了数据映射模式（像Java中的Hibernate）而不是Active Record模式（像Ruby on Rails的ORM）。
 * [SQLObject](http://sqlobject.org/) - SQLObject是一个介于SQL数据库和Python之间映射对象的Python ORM, 类似于Ruby on Rails的ActiveRecord模式。
 * [Peewee](https://github.com/coleifer/peewee) - Peewee是一个小型但是十分强大的库，支持通过ORM的方式访问数据库，原生支持SQLite、MySQL和PostgreSQL等数据库。
 * [pony](https://github.com/ponyorm/pony) - [pony官网](https://ponyorm.com/) Pony是一个非常酷和新的 Python ORM ,它能够让你使用Python generators来查询一个数据库。这些generators然后会转成高效的SQL。
 * [asyncmongo](https://github.com/bitly/asyncmongo) - AsyncMongo是基于Tornado iploop的mongo数据库的异步库。
 * [influxdb-python](https://github.com/influxdata/influxdb-python) - InfluxDB -python 是一个时间序列数据库，用它来储存不同时间的测量值。通过 RESTFul API，它变得极其易用而且高效，另外，由于其内建了聚类功能，因此对数据的检索和分组也变得十分轻松。
 * [elasticsearch-dsl-py](https://github.com/elastic/elasticsearch-dsl-py) - elasticsearch-dsl-py提供基于JSON的完整的Query DSL查询表达式(DSL即领域专用语言)。
 * [MongoHub-Mac](https://github.com/bububa/MongoHub-Mac) - MongoHub-Mac：mongo 图形化管理工具。
 * [mongotron](https://github.com/officert/mongotron) - mongotron：mongo 图形化管理工具,基于Electron与AngularJS写成。
 * [tinydb](http://tinydb.readthedocs.org/en/latest/getting-started.html) - 一个小型的文档数据库，它允许你在本地文件中插入JSON数据并查询它。它只有1200多行代码，并且配有简单干净的文档和API。
 * [Dataset](https://github.com/pudo/dataset) - Dataset在数据库中即时保存数据。
 * [datasette](https://github.com/simonw/datasette) - DataSette可以很容易地把 CSV 文件转换为全特性的只读 REST JSON API，有许多特性，包括创建图表和 geo（用于创建交互式地图），并且很容易通过容器或第三方网络主机进行部署。
 * [csvs-to-sqlite](https://github.com/simonw/csvs-to-sqlite) - 把 CSV 文件很简单就转换为sqlite数据库文件。

========
#### 游戏相关
 * [游戏服务器端架构升级之路](http://python.jobbole.com/84234/) - 游戏服务器端架构升级之路，[参考flask设计的tcp server：haven](https://github.com/dantezhu/haven) 、 [参考flask设计的tcp server：maple](https://github.com/dantezhu/maple)。

========
#### 开源框架
 * [高效的Python数据分析框架Ibis](https://github.com/cloudera/ibis) - 高效的Python数据分析框架Ibis  [ibis-project](http://www.ibis-project.org/) , [通过IPN了解Ibis](http://nbviewer.ipython.org/github/cloudera/ibis-notebooks/tree/master/basic-tutorial/).
 * [RabbitMQ](http://www.rabbitmq.com/download.html) - 一个工业级的消息队列服务器，[RabbitMQ+Python入门经典-兔子和兔子窝](http://blog.csdn.net/linvo/article/details/5750987)
 * [ZeroMQ](http://www.rabbitmq.com/download.html) - 是一个简单好用的传输层socket library，使得 Socket 编程更加简单、简洁和性能更高。

========
#### 大数据与人工智能相关
 * [pandas](https://github.com/pydata/pandas) - 为 Python 编程语言提供高性能，易用数据结构和数据分析工具。在数据改动和数据预处理方面，Python 早已名声显赫，但是在数据分析与建模方面，Python 是个短板。Pands 软件就填补了这个空白，能让你用 Python 方便地进行你所有数据的处理，而不用转而选择更主流的专业语言，例如 R 语言。12 个使效率倍增的 Pandas 技巧 [上](http://datartisan.com/article/detail/80.html)、 [下](http://datartisan.com/article/detail/81.html) 。
 * [pulp](https://github.com/pulp/pulp) - PuLP 是一个用 Python 编写的线性编程模型。它能产生线性文件，能调用高度优化的求解器，GLPK，COIN CLP/CBC，CPLEX，和GUROBI，来求解这些线性问题。
 * [Matplotlib](https://github.com/matplotlib/matplotlib) - Matplotlib是基于 Python 的 2D（数据）绘图库，它产生（输出）出版级质量的图表，用于各种打印纸质的原件格式和跨平台的交互式环境。matplotlib 既可以用在 python 脚本, python 和 ipython 的 shell 界面 (ala MATLAB® 或 Mathematica®)，web 应用服务器，和6类 GUI 工具箱。matplotlib 尝试使容易事情变得更容易，使困难事情变为可能。你只需要少量几行代码，就可以生成图表，直方图，能量光谱（power spectra），柱状图，errorcharts，散点图（scatterplots）等。
 * [Scikit-Learn](https://github.com/scikit-learn/scikit-learn) - Scikit-Learn是一个简单有效地数据挖掘和数据分析工具（库）。关于最值得一提的是，它人人可用，重复用于多种语境。它基于 NumPy，SciPy 和 mathplotlib 等构建。
 * [Spark](https://github.com/apache/spark) -Spark 由一个驱动程序构成，它运行用户的 main 函数并在聚类上执行多个并行操作。Spark 最吸引人的地方在于它提供的弹性分布数据集（RDD），那是一个按照聚类的节点进行分区的元素的集合，它可以在并行计算中使用。RDDs 可以从一个 Hadoop 文件系统中的文件（或者其他的 Hadoop支持的文件系统的文件）来创建，或者是驱动程序中其他的已经存在的标量数据集合，把它进行变换。用户也许想要 Spark 在内存中永久保存 RDD，来通过并行操作有效地对 RDD 进行复用。最终，RDDs 无法从节点中自动复原。Spark 中第二个吸引人的地方在并行操作中变量的共享。
 * [SciPy](http://www.scipy.org) - SciPy是一个开源的Python算法库和数学工具包，SciPy包含的模块有最优化、线性代数、积分、插值、特殊函数、快速傅里叶变换、信号 处理和图像处理、常微分方程求解和其他科学与工程中常用的计算。其功能与软件MATLAB、Scilab和GNU Octave类似。Numpy和Scipy常常结合着使用，Python大多数机器学习库都依赖于这两个模块。
 * [NumPy](http://www.numpy.org) - NumPy几乎是一个无法回避的科学计算工具包，最常用的也许是它的N维数组对象，其他还包括一些成熟的函数库，用于整合C/C++和 Fortran代码的工具包，线性代数、傅里叶变换和随机数生成函数等。NumPy提供了两种基本的对象：ndarray（N-dimensional array object）和 ufunc（universal function object）。ndarray是存储单一数据类型的多维数组，而ufunc则是能够对数组进行处理的函数。
 * [ipython](http://ipython.org/) - iPython 是一个Python 的交互式Shell，比默认的Python Shell 好用得多，功能也更强大。 她支持语法高亮、自动完成、代码调试、对象自省，支持 Bash Shell命令，内置了许多很有用的功能和函式等，非常容易使用。默认开启了matploblib的绘图交互，用起来很方便。[jupyter-notebook](https://github.com/jupyter/notebook) - [jupyter官网](https://jupyter.org/)。
 * [PyML](http://pyml.sourceforge.net/) - PyML是一个Python机器学习工具包，为各分类和回归方法提供灵活的架构。它主要提供特征选择、模型选择、组合分类器、分类评估等功能。
 * [gensim](https://github.com/piskvorky/gensim/) - gensim是一种NLP（自然语言处理），它提供了一些常用算法，例如 tf-idf、word2vec、doc2vec、LSA 等的快速、可拓展（内存无关）实现，同时还提供了简单易用的接口和完善的文档。
 * [Blaze](https://github.com/blaze/blaze) - Blaze 是下一代的 NumPy。用于处理分布式的各种不同数据源的计算。
 * [Dask](https://pypi.python.org/pypi/dask/) - Dask是一款基于外存的Python 调度工具。它通过将数据集分块处理并根据所拥有的核数分配计算量，这有助于进行大数据并行计算。它主要针对单机的并行计算进程。 
异 * [GWPY](https://github.com/gwpy/gwpy) - GWPY一个可以分析引力波数据的Python包。
 * [nupic](https://github.com/numenta/nupic) - 使用的机器学习算法叫做脑皮质学习算法。
 * [RocAlphaGo](https://github.com/Rochester-NRT/RocAlphaGo) - 一个模仿AlphaGo的项目，围棋和深层神经网络树搜索。
 * [agagd]( https://github.com/usgo/agagd) - 美国围棋选手使用的自动评级系统，不发段位证。
 * [mrjob](https://github.com/Yelp/mrjob) - 用Python来写MapReduce任务时非常有用的库。它允许你实现自己的 Mapper 和 Reducer 。在本地环境运行/测试你的MapReduce任务，然后部署到EMR或者你自己的MapReduce集群。[官网](https://pythonhosted.org/mrjob/)。
 * [natsort](https://pypi.python.org/pypi/natsort) - 默认sorted方法已经足够高效，并且能够满足你大多数时候的排序需求。
 * [OpenAI universe](https://github.com/officert/mongotron) - 是一个能在世界上所有的游戏、网站和其他应用中，衡量和训练AI通用智能的软件平台。
 * [TensorFlow](https://github.com/tensorflow/tensorflow) - 是一个开源软件库的AI引擎，用于使用数据流图进行数值计算。TensorFlow还包括TensorBoard，一个数据可视化工具包。
 * [aiexperiments-ai-duet](https://github.com/googlecreativelab/aiexperiments-ai-duet) - 通过机器学习制作音乐。在许多MIDI例子上训练了一个神经网络，它学习有关音乐概念的知识、构建音符和节拍图谱。你只需弹奏几个音符，然后看看这个神经网如何回应。
 * [Securitybot](https://github.com/dropbox/securitybot) - 一个分布式告警聊天机器人的开源实现，如Ryan Huber的播客中所述。分布式告警改善了你的安全团队的监控效率，可以帮助你更快更有效地捕获安全事件。
 * [Tweetfeels](https://github.com/uclatommy/tweetfeels) - 使用推特的streaming API的实时情感分析。它依赖于VADER情感分析，为用户定义的主题提供情感分数。它通过利用推特的streaming API来监听关于特定主题的实时推特，从而实现此目的。
 * [scikit-plot](https://github.com/reiinakano/scikit-plot) - 一个直观的库，用于添加绘图功能到scikit-learn对象。
 * [ChainerRL](https://github.com/pfnet/chainerrl) - ChainerRL是一个建立在Chainer之上的深度强化学习库。
 * [mpi4py](http://mpi4py.scipy.org/docs/usrman/tutorial.html) - Mpi4py是构建在mpi之上的python库，使得python的数据结构可以在进程（或者多个cpu）之间进行传递。
 * [pylearn2](https://github.com/lisa-lab/pylearn2) - 一个基于[Theano](http://deeplearning.net/software/theano/)的机器学习库，大部分功能是基于Theano顶层实现的。
 * [PyMC](https://github.com/pymc-devs/pymc) - PyMC是一个实现贝叶斯统计模型和马尔科夫链蒙塔卡洛采样工具拟合算法的Python库。PyMC的灵活性及可扩展性使得它能够适用于解决各种问题。除了包含核心采样功能，PyMC还包含了统计输出、绘图、拟合优度检验和收敛性诊断等方法。
 * [PCN-FaceDetection-FaceAlignment](https://github.com/Jack-CV/PCN-FaceDetection-FaceAlignment) - PCN 多角度实时人脸检测项目。
 * [dask](https://github.com/dask/dask) - 能提供 NumPy Arrays，Pandas Dataframes 和常规列表的抽象，允许多核处理并行运行。
 * [face_recognition](https://github.com/ageitgey/face_recognition) - face_recognition是一个强大、简单、易上手的人脸识别开源项目，并且配备了完整的开发文档和应用案例，特别是兼容树莓派系统。项目README文件已经被同济大学开源软件协子豪兄Tommy翻译成中文，此项目是世界上最简洁的人脸识别库，你可以使用Python和命令行工具提取、识别、操作人脸。同时此项目的人脸识别是基于业内领先的C++开源库dlib中的深度学习模型，用Labeled Faces in the Wild人脸数据集进行测试，有高达99.38%的准确率。但对小孩和亚洲人脸的识别准确率尚待提升。
 * [Modin](https://github.com/modin-project/modin) - 通过更改一行代码来加速你的pandas工作流，让pandas运行的更快,Modin使用Ray来加速pandas。 
 * [Ray](https://github.com/ray-project/ray/) - 基于python的高性能实时并行机器学习框架，有望取代Spark。  
 * [keras](https://github.com/keras-team/keras) - Keras是一种高度模块化，使用简单上手快，合适深度学习初学者使用的深度学习框架。Keras由纯Python编写而成并以Tensorflow、Theano以及CNTK为后端。Keras为支持快速实验而生，能够把你的idea迅速转换为结果。
 * [tensorflow-models](https://github.com/tensorflow/models) - 使用TensorFlow构建模型和示例。 
 * [tensorflow-internals](https://github.com/horance-liu/tensorflow-internals) - 开源技术书：TensorFlow内核剖析。[说明](https://www.jianshu.com/p/fda4ae1e2547) 

========
#### 网络爬虫
 * [scrapy](https://github.com/scrapy/scrapy/) - 最出名的网络爬虫，一个快速,高层次的屏幕抓取和web抓取框架，用于抓取web站点并从页面中提取结构化的数据。Scrapy用途广泛，可以用于数据挖掘、监测和自动化测试。[官方主页](http://scrapy.org/),[Scrapy 轻松定制网络爬虫 - 教程](http://blog.pluskid.org/?p=366)，[Scrapy 中文指南](http://wiki.jikexueyuan.com/project/scrapy/broad-crawls.html) 。
 * [BeautifulSoup](http://www.crummy.com/software/BeautifulSoup/) - Beautifu Soup不完全是一套爬虫工具，需要配合urllib使用，而是一套HTML/XML数据分析，清洗和获取工具。
 * [python-goose](https://github.com/grangier/python-goose/) - Python-Goose用Python重写，依赖了Beautiful Soup。给定一个文章的URL, 获取文章的标题和内容很方便。
 * [pyspider](https://github.com/binux/pyspider) - PySpider：一个国人编写的强大的网络爬虫系统并带有强大的WebUI。采用Python语言编写，分布式架构，支持多种数据库后端，强大的WebUI支持脚本编辑器，任务监视器，项目管理器以及结果查看器。[demo地址](http://demo.pyspider.org/),[网络爬虫剖析，以Pyspider为例](http://python.jobbole.com/81109/) ， [Scrapy 示例 —— Web 爬虫框架](http://python.jobbole.com/84237/) 。
 * [PyQuery](https://github.com/gawel/pyquery) - 是 Python 仿照 jQuery 的严格实现。语法与 jQuery 几乎完全相同，所以不用再去费心去记一些奇怪的方法了。[python爬虫神器PyQuery的使用方法](http://python.jobbole.com/85222/)。
 * [distribute_crawler](https://github.com/gnemoug/distribute_crawler) - 使用scrapy,redis,mongodb,graphite实现的一个分布式网络爬虫。
  * [youtube-dl](https://github.com/rg3/youtube-dl//) - 一个可从YouTube等网站下载视频的开源神器,采用Python开发，支持多个OS平台，支持众多视频网站国内优酷、土豆、新浪和搜狐，国外YouTube等赫然在列。
 * [you-get](https://github.com/soimort/you-get/) - 能帮你快速爬取你想要的一切，支持64个网站，包括优酷、土豆、爱奇艺、b站、酷狗音乐、虾米。[官网]( https://you-get.org/)
 * [Lulu](https://github.com/iawia002/Lulu) - You-get的一个友好分叉(fork), 类似网络爬虫的简单下载程序。 
 * [pytube](https://github.com/nficano/pytube) - 一个非常严谨、轻量级、无依赖性的用于下载youtube视频的python库。 
 * [meizi_spider](https://github.com/lpe234/meizi_spider) - 获取慕课网视频教程，基于Scrapy(0.22)。
 * [spider_smooc](https://github.com/qiyeboy/spider_smooc) - 爬取慕课网视频 ,使用BeautifulSoup模块解析html。
 * [proxy_pool](https://github.com/jhao104/proxy_pool) - 爬虫代理池,爬去取网上免费的代理IP。
 * [Amazon-scraper-Python](https://github.com/tducret/amazon-scraper-python) - 一款非官方的爬取工具，能够获取亚马逊上在售商品的信息，比如商品排名和评论数量。
 * [Douyin-Bot](https://github.com/wangshub/Douyin-Bot) - Python 抖音机器人，论如何在抖音上找到漂亮小姐姐？
 * [DouYin](https://github.com/Python3WebSpider/DouYin) - 不到 10 行代码完成抖音热门视频的爬取！
 * [Sotawhat](https://github.com/chiphuyen/sotawhat) - arxiv论文爬虫，只需输入论文关键词，就会为你抓取arxiv上的论文并总结摘要，让你轻松同步最新研究结果。
 * [Gerapy](https://github.com/Gerapy/Gerapy) - 国人开发的，分布式的爬虫管理框架，基于Scrapy, Scrapyd, Scrapyd-Client, Scrapyd-API, Django and Vue.js 技术！
  * [python_12306](https://github.com/versionzhang/python_12306) - 用python实现的12306抢票小工具。
  * [Crawlab](https://github.com/tikazyq/crawlab) - 基于Celery的爬虫分布式爬虫管理平台，支持多种编程语言以及多种爬虫框架.
  * [awesome-python-login-model](https://github.com/CriseLYJ/awesome-python-login-model) - 模拟登陆一些大型网站，还有一些简单的爬虫。

========
#### 测试与代码分析审核
 * [splinter](http://splinter.cobrateam.info/) - Python自动化测试工具Splinter，不仅可以当web自动化测试工具 同时也可以当抓取交互式网站的爬虫程序来用的，不用去分析ajax请求数据了，可以模拟登录，[用Python开发自动化测试脚本-splinter](http://python.jobbole.com/84012/)。
 * [swarm](https://github.com/duhoobo/swarm) - 是一个简单的使用 gevent 开发的支持自定义协议的长连接压测框架。
 * [PySonar2](https://github.com/yinwang0/pysonar2) - PySonar2王垠开发的，针对 Python 的代码静态分析工具。
 * [Behave](https://www.pythonhosted.org/behave/) - BDD自动化测试框架。
 * [Nose](https://pypi.python.org/pypi/nose/) - Nose是最流行的针对Python的测试库之一。[简单实例](http://ray.dotnetage.com/languages/python/nose/)
 * [locust](https://github.com/locustio/locust) - 一个开源负载测试工具。使用 Python 代码定义用户行为，也可以仿真百万个用户。
 * [ReviewBoard](https://www.reviewboard.org) - Review Board:在线代码审核工具，它所提供的应用程序可以支持代码审查流程。
 * [Infer](https://github.com/facebook/infer) - Infer是Facebook最新开源的静态程序分析工具，用于在发布移动应用之前对代码进行分析，找出潜在的问题，包括 Android 、iOS等等。
 * [voltron](https://github.com/snare/voltron/) - Python 实现的黑客调试器前端。
 * [Pympler](https://pythonhosted.org/Pympler/) - Pympler一个很棒的内存统计调试模块，实时监控Python web 应用的内存使用量，能walk你的进程堆,并报告所有Python分配对象的类型,个数和以bytes单位的大小.[使用介绍](http://python.freelycode.com/contribution/detail/97)。
 * [Brakeman](https://github.com/presidentbeef/brakeman) - 一个开源静态分析工具，负责检查Ruby on Rails应用程序的安全漏洞。
 * [colorama](https://github.com/tartley/colorama) - 为Python终端输出增加颜色,可以向文本增加颜色或者背景颜色。
 * [Blessings](https://github.com/erikrose/blessings) - 一个轻量级的文本终端输入颜色改变库。
 * [termcolor](https://github.com/hfeeki/termcolor) - 一个python的终端输出文本颜色改变的[模块](https://pypi.python.org/pypi/termcolor)。
 * [pytest](https://pypi.python.org/pypi/pytest) - py.test 是一个轻量级的测试框架，它压根就没写自己的断言系统，但是它对Python自带的断言做了强化处理，如果断言失败，那么框架本身会尽可能多地提供断言失败的原因。
 * [Pluggy](https://github.com/pytest-dev/pluggy) - 添加一个插件系统到现有应用中，那么使用 Pluggy 是最好也是最简单的方式。如果你使用过 pytest，那么实际上相当于已经使用过 Pluggy 了。
 * [unittest](https://docs.python.org/3/library/unittest.html) - Python自带的单元测试框架,有自己的断言方法self.assertXXX()，而且不推荐使用assert XXX语句。
 * [ptest](https://pypi.python.org/pypi/ptest) - Karl大神写的一个测试框架。ptest中的断言可读性很好，而且智能提示也很方便你通过IDE轻松完成各种断言语句。
 * [assertpy](https://github.com/ActivisionGameScience/assertpy) - 异常强大且好评如潮的assert断言包，它支持了几乎能想到的所有测试场景。[文档](https://pypi.python.org/pypi/assertpy)
 * [vprof](https://github.com/nvdv/vprof) - 一个为不同Python 程序特性提供丰富和交互可视化的包，对程序的运行时和内存使用进行可视化。
 * [line_profiler](https://github.com/rkern/line_profiler) - 用来测量我的脚本里每一行代码运行的有多快和运行频率。
 * [memory_profiler](https://github.com/fabianp/memory_profiler) - 是监控python进程的神器，它可以分析出每一行代码所增减的内存状况。
 * [pyautogui](https://github.com/asweigart/pyautogui) - 实现鼠标键盘自动化。
 * [pyheat](https://github.com/csurfer/pyheat) - pprofile + matplotlib = Python程序的热力图描述！
 * [Behold](https://github.com/robdmc/behold) - 一款强大的支持 print-style 的调试工具。
 * [cProfile](https://docs.python.org/3/library/profile.html) - 一款应用python的性能测量工具。
 * [Locust](https://github.com/locustio/locust) - 一个开源性能测试工具,使用Python代码来定义用户行为,用它可以模拟百万计的并发用户访问你的系统。
 * [Pylint](https://github.com/PyCQA/pylint) - 是一个 Python 代码分析工具，它分析 Python 代码中的错误，查找不符合代码风格标准和有潜在问题的代码,Pylint默认使用的代码风格是PEP 8。[入门指南](http://python.jobbole.com/87415/)
 * [icecream](https://github.com/gruns/icecream) - 甜甜的，奶油般柔滑的打印调试。
 * [Birdseye](https://github.com/alexmojaki/birdseye) - 快速、方便、以表达为中心的、使用AST的Python图形化调试器 。
 * [Voluptuous](https://github.com/alecthomas/voluptuous) - 尽管名字有点妖娆，这是一个Python的数据校验库。
 * [Pyre-check](https://github.com/facebook/pyre-check) - Facebook推出的一款Python性能类型检查工具。
 * [Py-spy](https://github.com/benfred/py-spy) - Python 程序性能分析利器,能够可视化你的 Python 程序的 CPU 耗时情况，非常轻量化。
 * [Bowler](https://github.com/facebookincubator/Bowler) - 一个实现语法树级别操作的Python重构工具，由 Facebook 开源。
 * [PythonTestingToolsTaxonomy](https://wiki.python.org/moin/PythonTestingToolsTaxonomy) - 这里已经基本把python圈的测试相关工具都列全了。
 * [PySnooper](https://github.com/cool-RR/PySnooper) - 不用小心谨慎地用 print 输出语句，只需在想调试的函数中引入一个装饰器。然后得到函数的详细日志，包括运行了哪些行、何时运行，以及何时更改了局部变量。

========
#### 安全与破解相关
 * [ibrute](https://github.com/hackappcom/ibrute) - 一个攻击iCloud账户的Python脚本,2014年很多明星的账号就是被这个脚本攻破的，苹果已经修改这个漏洞了。
 * [bruteforce_py](https://github.com/rischanlab/bruteforce_py) - 暴力破解脚本，ssh bf, wordpress bf, cpanel bf, mysql bf, etc ... 可以说是暴力破解大全。
 * [keychain-bruteforce](https://github.com/ziman/keychain-bruteforce) - 暴力破解MAC OS X 的密码管理。
 * [gamblerbfe](https://github.com/mthbernardes/gamblerbfe) - 路由器也可以暴力破解了。
 * [AndroidPINCrack](https://github.com/PentesterES/AndroidPINCrack) - android的pin密码破解。
 * [rarPasswordCrackere](https://github.com/GauthamGoli/rarPasswordCrackere) - rar加密文件破解。
 * [Python-ZIP-Cracker](https://github.com/agusmakmun/Python-ZIP-Cracker) - zip加密文件破解。
 * [enjarify](https://github.com/google/enjarify) - 可代替dex2jar的dex Android反编译工具。[使用教程](https://segmentfault.com/a/1190000004996344)
 * [featherduster](https://github.com/nccgroup/featherduster) - 使用Python编写的自动、模块化的密码分析工具。
 * [python-nmap](http://xael.org/pages/python-nmap-en.html) - 是一个用来帮助用户使用 nmap 端口扫描器的 Python 库，可让用户轻松操作 nmap 扫描结果、自动扫描和生成报告。
 * [pyinstallerextractor](https://sourceforge.net/projects/pyinstallerextractor/) - 使用pyinstxtractor.py 脚本可以用来提取pyinstall打包的exe文件的内容，脚本同时也可以提取出可执行文件中的pyz文件的内容。 
 * [cuckoosandbox](https://github.com/cuckoosandbox/cuckoo) - cuckoo sandbox:是一个自动动态恶意软件分析系统。你可以将任何可疑文件丢给它，Cuckoo会在几秒内为你反馈一个详细结果，概括此类文件在在孤立环境中执行时的活动。
 * [BeEF](https://github.com/beefproject/beef) - BeEF是The Browser Exploitation Framework的缩写，它是一个 专注网页浏览器的渗透测试工具。
 * [dingtalk_crypto](https://github.com/zgs225/dingtalk_crypto) - Python的钉钉加密/解密工具。
 * [Keylogger](https://github.com/GiacomoLaw/Keylogger) - 键盘敲击记录器。
 * [evilpassr](https://github.com/SirCmpwn/evilpassr) - 稍微邪恶的密码强度检查器。
 * [errator](https://github.com/haxsaw/errator) - 为你的库和终端用户程序创建人类可读的异常叙述。
 * [Mercure](https://github.com/synhack/mercure) - 是为那些想要教会他们的合作者关于钓鱼的安全管理者提供的工具。
 * [Privy](https://github.com/ofek/privy) - 是一个小而快的实用程序，用于密码保护，例如数字签名种子，或者Bitcoin钱包。 
 * [urh](https://github.com/jopohl/urh) - Universal Radio Hacker是一个用于调查未知无线协议的软件。
 * [Pypykatz](https://github.com/skelsec/pypykatz) - 完全用Python实现了密码提取工具Mimikatz。
 * [JohnTheRipper](https://github.com/magnumripper/JohnTheRipper) - John the Ripper 是一款大受欢迎的、免费的开源软件。也是一个基于字典的快速破解密码的工具，是一款用于在已知密文的情况下尝试破解出明文的破解密码软件，支持目前大多数的加密算法，如 DES 、 MD4 、 MD5 等。 John the Ripper 支持字典破解方式和暴力破解方式。它支持多种不同类型的系统架构，包括 Unix 、 Linux 、 Windows 、 DOS 模式、 BeOS 和 OpenVMS ，主要目的是破解不够牢固的 Unix/Linux 系统密码。

========
#### 图表及图像相关
 * [vincent](https://github.com/wrobstory/vincent) - Python 构建的专为运用 D3.js 进行可视化的 vega 转换工具。
 * [Scikit-image](http://scikit-image.org) - 一组用于图像处理的算法的集合，使图像处理任务如模糊，增强对比度，缩放只需要一些函数调用就可以完成。
 * [PIL](http://www.pythonware.com/products/pil/) - PIL （Python Imaging Library）是 Python 中最常用的图像处理库。
 * [Pillow](https://github.com/python-pillow/Pillow) - Pillow:比PIL更容易使用，并通过最小的变化与 PIL 代码兼容。 扩展包括用于与本机 Windows 的映像功能和 Python Tcl/Tk-backed Tkinter GUI 包。 
 * [prettytable](https://github.com/lmaurits/prettytable) - 让你能够在终端中画出漂亮的ascii表格，它支持多种数据源。
 * [pytesseract](https://github.com/madmaze/pytesseract) - 一个很好用图像识别的工具，主要用于识别验证码。
 * [fuck12306](https://github.com/andelf/fuck12306) - 12306 图片验证码识别测试。
 * [GooPyCharts](https://github.com/Dfenestrator/GooPyCharts) - 一个易于安装与使用的图表库，支持图表类型有限,语法与MATLAB相似，而且可以替代matplotlib。
 * [fast-pixel-cnn](https://github.com/PrajitR/fast-pixel-cnn) - 加速PixelCNN++图像生成，快达183倍。
 * [ipyvolumel-cnn](https://github.com/maartenbreddels/ipyvolume) - Jupyter notebook中基于IPython小部件的使用WebGL的Python 3d绘图。
 * [Som-tsp](https://github.com/DiegoVicen/som-tsp) - 使用自组织地图技术解决旅行中的销售员所遇到的问题，用matlab实现。
 * [GIF-for-cli](https://github.com/google/gif-for-cli) - 将GIF、短视频或Tenor GIF API的查询转换成动漫的ASCII艺术。

========
#### 视频及语音相关
 * [praatIO](https://github.com/timmahrt/praatIO) - 提供了读写praat格式文件的工具，它是一种跨平台的应用，主要为学术社区提供了可视化，抄录，编辑以及提取语音信息的功能。
 * [ProMo](https://github.com/timmahrt/ProMo) - ProMo——Prosody Morph的简称——是一个可以对持续性或高音文件进行复杂处理的库。人们可以扩展不同的单词，比如说改变一个语句的单调。
 * [Pysle](https://github.com/timmahrt/pysle) - 针对Isle字典的一个接口——该字典是包含了英文中重音信息的发音字典。通过使用pysle，人们可以自动地标记出转录演讲中的重音。有一个函数可以使用PraatIO根据重音信息标记出textgrid。
 * [PyAcousitics](https://github.com/timmahrt/pyAcoustics) - PraatIO和ProMo都是从pyAcoustics中分离出来的。它虽然有些杂乱，但是包含了许多有用的工具。当你需要从语音数据中提取或者修改信息时你会发现它很有用。
 * [pmcli](https://github.com/christopher-dG/pmcli) - 用于Google Play音乐流媒体服务的轻量级，可自定义的TUI客户端。
 * [subsync](https://github.com/smacke/subsync) - 自动把字幕与视频对齐。用法很简单，只需要把视频文件和字幕文件当做参数传入，就可以得到对齐好的字幕文件作为输出。通常一部电影只需要 10 到 20 秒就能转换完成。

========
#### 运维相关
 * [pywebsocketserver](https://github.com/suxianbaozi/pywebsocketserver) - 程序Log实时监控 – python + websocket。
 * [pupy](https://github.com/n1nj4sec/pupy) - Pupy是一个远程管理工具（Administration Tool），开源并且支持多个平台。Pupy还内置了一个Python解释器，可以从内存中加载Python包，访问远程Python对象。
 * [Fabric](https://github.com/fabric/fabric) - Fabric 一个通过SSH进行应用部署以及系统任务管理的命令行工具。
 * [Invoke](http://www.pyinvoke.org) - Invoke让你通过一个Python库便捷地执行系统管理任务。如果你想使用稳定的工具（即使是不再积极开发），可以考虑Invoke的前身——Fabric。
 * [DeployDjango](https://github.com/yask123/DeployDjango) - 不到一分钟安全部署Django应用的脚本，[操作教程](http://codingpy.com/article/deploy-django-app-in-less-than-one-minute/)。
 * [HealthChecks](https://github.com/healthchecks/healthchecks) - HealthChecks基于 cron 的监控服务。在 cron 里配置好监控只需要几分钟时间，却能让你晚上睡得更好！[2015年出现的十大流行Python库](http://codingpy.com/article/top-10-django-libraries-started-in-2015/) 。
 * [dockerizing-django](https://github.com/realpython/dockerizing-django) - 是realpython网站一篇相关教程的代码库，讲的是如何将Django应用Docker化。[2015年出现的十大流行Python库](http://codingpy.com/article/top-10-django-libraries-started-in-2015/) 。
 * [用Python脚本实现对Linux服务器的监控](http://blog.jobbole.com/54563/) - 用Python脚本实现对Linux服务器的监控。
 * [plumbum控](https://github.com/tomerfiliba/plumbum) - plumbum提供了非常易用的语法，可以轻松地以跨平台的方式执行本地或者远程命令，获取输出或者错误代码。还可以组合它们（shell 管道的方式），而且它还提供了创建命令行应用的接口。
 * [virtualenv](http://www.virtualenv.org/en/latest/index.html) - virtualenv用来建立一个虚拟的python环境，一个专属于项目的python环境。用virtualenv 来保持一个干净的环境非常有用。
 * [Gunicorn](https://github.com/benoitc/gunicorn) - Gunicorn 是一个Python WSGI UNIX的HTTP服务器。这是一个pre-fork worker的模型，Gunicorn服务器大致与各种Web框架兼容，只需非常简单的执行，轻量级的资源消耗，以及相当迅速,[Nginx+Gunicorn+Django 部署小记](http://www.isaced.com/post-248.html)。
 * [mitmproxy](https://github.com/mitmproxy/mitmproxy) - mitmproxy 是用 Python 和 C 开发的一个中间人代理软件（man-in-the-middle proxy），它可以用来拦截、修改、重放和保存 HTTP/HTTPS 请求。
 * [Sentry](https://github.com/getsentry/sentry) - Sentry 是一个实时的事件日志和聚合平台，基于 Django 构建。Sentry 可以帮助你将 Python 程序的所有 exception 自动记录下来，然后在一个好用的 UI 上呈现和搜索。
 * [newrelic](http://newrelic.com/) - newrelic性能监控的好工具，国内有；[云智慧](http://www.jiankongbao.com/)、[ONE APM](http://www.oneapm.com)。
 * [ipapy](https://github.com/hades0918/ipapy) - iOS项目自动打包脚本，并且上传到fir.im，然后发送邮件给测试人员。
 * [ZStack](https://github.com/zstackorg/zstack) - 开源IaaS软件,已经提供了大部分IaaS的基本功能，包括：虚拟机管理，存储卷管理，存储卷快照，各种网络服务（DHCP、DNS、SNAT、EIP、PortForward以及Security Group）。[ZStack使用、OpenStack、CloudStack比较](http://www.oschina.net/p/zstack)
 * [Flocker](https://github.com/ClusterHQ/flocker) - Flocker可轻松实现Docker容器及其数据的管理。这是一个数据卷管理器和多主机的 Docker 集群管理工具。
 * [Fig](https://github.com/docker/compose) - Fig 主要用来跟 Docker 一起来构建基于 Docker 的复杂应用，Fig 通过一个配置文件来管理多个Docker容器，非常适合组合使用多个容器进行开发的场景。
 * [sh](http://amoffat.github.io/sh/) - sh是一个成熟的Python子进程接口，允许像调用函数一样调用任何程序。超级好用。
 * [Watchdog](http://pythonhosted.org/watchdog/) - Watchdog是一个跨平台的Python库和shell工具，可以监视文件系统事件。超级好用，容易上手。
 * [Structlog](http://www.structlog.org/en/stable/) - Structlog是一个先进的日志处理器。他可以和任何现存的日志记录工具相集成，并包装了Python标准库。你可以构建定制的记录工具，根据你的需要增加上下文，保证你的日志一致、可读。
 * [plan](https://github.com/fengsp/plan) - 一个用Python编写的定时任务管理工具。
 * [tox](http://testrun.org/tox/latest/) - 一个提供自动化打包，测试和发布的Python软件的工具，可以用于控制台或者基础到你的持续构建平台，也是一个通用的virtualenv管理和测试命令行工具。
 * [Murder](https://github.com/lg/murder) - Twitter Murder在BitTornado的基础上开发而成，由Python和Ruby两种编程语言混合而成，能够在大规模的服务器集群中快速部署代码更新。
 * [git-webhook)](https://github.com/NetEaseGame/git-webhook) - 使用 Python Flask + SQLAchemy + Celery + Redis + React 开发的用于迅速搭建并使用 WebHook 进行自动化部署和运维，支持 Github / GitLab / Gogs / GitOsc。 
 * [CheungSSH](http://git.oschina.net/CheungSSH_OSC/CheungSSH) - Linux运维自动化管理服务器软件。
 * [pyflame](https://github.com/uber/pyflame) - Uber使用C++实现编写的python高性能分析器，分析Python代码极为有用的工具，并找到有效的代码进行优化。
 * [sentry](https://github.com/getsentry/sentry) - 是一个实时的事件日志和聚合平台，基于 Django 构建。可以帮助你将 Python 程序的所有 exception 自动记录下来，然后在一个好用的 UI 上呈现和搜索。
 * [CheungSSH](http://git.oschina.net/CheungSSH_OSC/CheungSSH) - Linux运维自动化管理服务器软件。
 * [Argparse、Docopt与Click 1](https://python.freelycode.com/contribution/detail/643)  [Argparse、Docopt与Click 2](https://python.freelycode.com/contribution/detail/645) - [Argparse](https://docs.python.org/3/library/argparse.html)、[Docopt](http://docopt.org/)与[Click](http://click.pocoo.org/5/):比较Python命令行解析库
 * [Heroku](https://www.heroku.com/) - 一个支持多种编程语言的云平台。支持Ruby、Java、Node.js、Scala、Clojure、Python以及PHP和Perl。基于Ubuntu。提供免费的Django应用程序托管。
 * [argparse](https://docs.python.org/2/howto/argparse.html) - 一个用来解析命令行参数的Python库。基于python2.7的stdlib代码。
 * [pythonanywhere](https://www.pythonanywhere.com/) - 一个免费的python空间，有2级域名，有控制台、web框架支持Django, web2py, Flask和Bottle。
 * [monitor](https://github.com/AsuraTeam/monitor) - 运维工作中自己开发的监控系统，功能强大灵活,系统安装简单,配置简单，相比zabbix, nagios,cacti，小米监控等都使用相当简单。只需要会写脚本，语言不限就可以实现任意监控需求。
 * [saltstack](https://github.com/saltstack/salt) - 一个服务器基础架构集中化管理平台，具备配置管理、远程执行、监控等功能，一般可以理解为简化版的puppet和加强版的func。
 * [ansible](https://github.com/ansible/ansible) - 集合了众多运维工具（puppet、cfengine、chef、func、fabric）的优点，实现了批量系统配置、批量程序部署、批量运行命令等功能。[官方文档](http://docs.ansible.com/)
 * [argcomplete](https://github.com/kislyuk/argcomplete) - Bash使用tab自动补全。
 * [Gooey](https://github.com/chriskiehl/Gooey) - 一条命令，将命令行程序变成一个 GUI 程序。
 * [subprocess](https://docs.python.org/2/library/subprocess.html) - 用来生成子进程，并可以通过管道连接它们的输入/输出/错误，以及获得它们的返回值。
 * [sh](https://pypi.python.org/pypi/sh/) - 一个完备的 subprocess 替代库，能调用 subprocess 中的任意外部程序，并将结果返回到 Python 应用。
 * [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit) - 一款功能强大的python shell,交互式解释器[ptpython](https://github.com/jonathanslenders/ptpython/)。
 * [pipenv](https://github.com/kennethreitz/pipenv) - 用于简化Python项目中依赖项的管理。 它汇集了Pip，Pipfile和Virtualenv的功能，是一个强大的命令行工具。[简易教程](https://python.freelycode.com/contribution/detail/682)
 * [ops-batch](https://github.com/jkklee/ops-batch) - Python实现跨平台批量运维小工具。基于yaml配置文件可灵活指定操作单位：host(s)或hostgroup(s)；基于多线程可实现多主机并行；基于docopt提供详细的命令行界面。
 * [python-fire](https://github.com/google/python-fire) - 一个可以自动生成命令行接口(CLI)的库。
 * [Shiv](https://github.com/linkedin/shiv) - 一款命令行实用程序，可以创建完全独立自足的Python zip应用，和PEP 441中描述的一样，但又包含所有的内置环境依赖。
 * [xonsh](https://github.com/xonsh/xonsh) - 可以在xosh里调用Python的各种函数，也可以写常规的Shell语言，如此把Shell强大的系统操作和Python的丰富优雅完美混搭，同时支持使用Prompt Toolkit补全Shell命令和Python表达式。补全有可视化提示，会显示可能的补全并有下拉列表。
 * [dbxfs](https://github.com/rianhunter/dbxfs) - 可以把Dropbox文件夹当作本地文件系统一样挂载，OpenBSD，Linux和macOS上测试可用。
 * [psutil](https://github.com/giampaolo/psutil) - psutil（process and system utilities）是一个跨平台的库，用它来查看系统运行进程以及资源利用率。它主要用于系统监控、过程资源分析和限制以及运行过程的管理。

========
#### 树莓派
 * [图片自动发邮箱](https://github.com/dungeonsnd/toolkit/blob/master/rpi/rpi_auto_send_motion_files.py) - 报警图片自动发邮箱功能。
 * [自动更新树莓派的内网、外网IP地址到自己的github上](https://github.com/dungeonsnd/toolkit/blob/master/rpi/rpi_auto_send_ip_to_github.py) - 自动更新树莓派的内网、外网IP地址到 自己的github。
 * [rpi-start](http://conanwhf.gitcafe.io/2016/01/12/rpi-start/) - 树莓派初始配置指南（2代B型）。
 * [RaspberryWechatPi](https://github.com/mcdona1d/RaspberryWechatPi) - 基于树莓派的智能家居控制平台 微信服务端。
 * [dotbro-server](https://github.com/pubuim/dotbro-server) - 瀑布IM 开源点歌系统，[架设树莓派点歌系统：如何共享办公室的音箱](http://www.jianshu.com/p/fe8d06a8f751)。
 * [pyMagic](http://www.freebuf.com/sectool/103374.html) - pyMagic:用python控制的Geek入门神器 。
 * [360CamCode](https://github.com/Open360cam/360CamCode) - 一个有趣的360度照相机的开源项目：树莓派+OpenCV。
 * [PaperTTY](https://github.com/joukos/PaperTTY) - 一个实验性的命令行驱动的Python模块，用于将Linux虚拟终端（/dev/tty[1-63]）或标准输入的内容呈现到Waveshare电子纸显示器上。

========
#### 第三方平台
 * [wechat-python-sdk](https://github.com/wechat-python-sdk/wechat-python-sdk) - wechat-python-sdk微信公众平台Python开发包 http://wechat-python-sdk.readthedocs.org/ ， 非官方微信公众平台 Python 开发包，包括官方接口和非官方接口。
 * [wechatpy](https://github.com/jxtech/wechatpy) - wechatpy 是一个微信 (WeChat) 公众平台的第三方 Python SDK, 实现了普通公众平台和企业号公众平台的解析消息、生成回复和主动调用等 API。阅读文档：http://wechatpy.readthedocs.org/zh_CN/latest/
 * [wechat-deleted-friends](https://github.com/0x5e/wechat-deleted-friends) - wechat-deleted-friends查看被删的微信好友。
 * [wxBot](https://github.com/liuwons/wxBot) - wxBot为Python包装的网页微信API。可以很容易地实现微信机器人。参考文章：《[挖掘微信Web版通信的全过程](http://www.tanhao.me/talk/1466.html/)》、《[微信协议简单调研笔记](http://www.blogjava.net/yongboy/archive/2015/11/05/410636.html)》。
 * [WeixinBot](https://github.com/Urinx/WeixinBot) - WeixinBot微信web协议分析和实现微信机器人（微信网页版 wx2.qq.com）。[其他版本:Java版本API](https://github.com/biezhi/wechat-robot/)
 * [WeRoBot](https://github.com/whtsky/WeRoBot) - WeRoBot是一个面向公众号的微信机器人框架，[文档](https://werobot.readthedocs.org/) 。
 * [WxRobot](https://github.com/sharpdeep/WxRobot) - WxRobot：面向个人账户的微信机器人框架,[文档](https://sharpdeep.gitbooks.io/wxrobot-document/content/) 。
 * [Wechat django](https://github.com/jwfy/Wechat) - Wechat django一个基于django开发的微信公众平台，整体环境搭建在新浪SAE平台上，暂时实现的功能：查询天气情况、翻译。
 * [gxgk-wechat-server](https://github.com/paicha/gxgk-wechat-server) - gxgk-wechat-server莞香广科微信公众号后端，使用 Python、Flask、Redis、MySQL、Celery ，为在校学生提供一系列信息查询与便民服务。
 * [weChat-python-sdk](https://github.com/vincenting/weChat-python-sdk) - weChat-python-sdk微信公共平台非官方SDK，主要实现主动的消息推送和获取，该项目已经过期！
 * [wechat-admin](https://github.com/torpedoallen/wechat-admin) - 基于Flask和MySQL能够帮助快速迁移微信服务号后台到自家服务器的框架(tag: Python, wechat, weixin, admin, Flask) 。
 * [wechat-encrypt-python3](https://github.com/chenjianjx/wechat-encrypt-python3) - 微信提供的官方python加解密代码 只能用于python2。这里重写了一个python3版本。
 * [Python-SDK](http://git.oschina.net/jeffkit/wechat) - 微信公众号Python-SDK,本SDK支持微信公众号以及企业号的上行消息及OAuth接口。
 * [wego](https://github.com/wegostudio/wego) - WEGO微信公众号开发框架。
 * [itchatmp](https://github.com/littlecodersh/itchatmp) - 一个开源的微信公众号、企业号接口，使用python调用微信公众号非常简单。基于tornado框架，轻松满足效率需求。支持普通使用、nginx反向代理与wsgi。[官方文档](http://itchatmp.readthedocs.io/zh_CN/latest/other/deploy/)
 * [itchat](https://github.com/littlecodersh/itchat) - 微信个人号接口、微信机器人及命令行微信，三十行即可自定义个人号机器人。[官方文档](http://itchat.readthedocs.io/zh/latest/)
 * [WeChatPlugin-MacOS](https://github.com/TKkk-iOSer/WeChatPlugin-MacOS) - 一款功能强大的 macOS 版微信小助手 v1.7 / A powerful assistant for wechat macOS。

========
#### IDE
 * [PyCharm](https://www.jetbrains.com/pycharm/download/) - PyCharm是由JetBrains打造的一款Python IDE，Community社区版本是免费的，Professional版本$199.00/年。
 * [Eric](http://eric-ide.python-projects.org/eric-download.html) - Eric是一个集成了项目管理功能的 Python和Ruby集成开发环境。
 * [PyDev](http://www.pydev.org/download.html) - PyDev是Eclipse开发Python的 IDE，支持Python，Jython和IronPython的开发。
 * [KomodoEdit](https://github.com/Komodo/KomodoEdit) - Komodo Edit 是非常干净，专业的 Python IDE。
 * [PyScripter](https://sourceforge.net/projects/pyscripter/) - PyScripter是一个开源的Python语言集成开发环境。
 * [WingIDE](http://wingware.com/wingide/trial) - WingIDE是个相当优秀的 IDE。
 * [IEP](http://www.iep-project.org/downloads.html) - IEP 是跨平台的 Python IDE，旨在提供简单高效的 Python 开发环境。包括两个重要的组件：编辑器和 Shell，并且提供插件工具集从各个方面来提高开发人员的效率。
 * [Emacs](http://www.gnu.org/software/emacs/) - Linux文本编辑器Emacs是一种强大的文本编辑器，在程序员和其他以技术工作为主的计算机用户中广受欢迎。
 * [sublimetext](http://www.sublimetext.com/2) - sublimetext：Sublime Text 是一个轻量、简洁、高效、跨平台的编辑器。
 * [Atom](https://github.com/atom/atom) - Atom 是 Github 专门为程序员推出的一个跨平台文本编辑器。具有简洁和直观的图形用户界面，并有很多有趣的特点：支持CSS，HTML，JavaScript等网页编程语言。它支持宏，自动完成分屏功能，集成了文件管理器。[官网下载](https://atom.io/)，比较不错的插件：爆炸效果 activate-power-mode、程序员鼓励师 atom-miku 。

========  
#### 区块链  
 * [binance-trader](https://github.com/yasinkuyu/binance-trader) - 币安网交易者 (Binance: 区块链资产交易平台)： 币安网加密货币交易机器人 (实验性的)。
 * [python-cardano](https://github.com/yihuang/python-cardano) - Cardano 最近比较火热的一个区块链项目，它解决了第一代加密币——比特币（Bitcoin）所有存在的问题，它也支持第二代加密币——以太坊（Ethereum）的智能合约。

========
#### 其他库
 * [IoTNotes](http://ideatouch.github.io/IoTNotes/) - 开源硬件记录。
 * [GitHub上Star最多的100个python repository](http://www.jianshu.com/p/110f2a221096) - GitHub上Star最多的100个python repository。
 * [10个Python 模块](http://www.imooc.com/article/1138) - 你该了解的10个 Python 模块。
 * [dask](https://github.com/ContinuumIO/dask) - 【(Python)集成任务调度/阻塞算法的数据并行处理库Dask】支持大数据集的分割多核并行处理，[Doc](http://dask.pydata.org/en/latest/)。 
 * [Phonenumbers](https://pypi.python.org/pypi/phonenumberslite/7.0.2) - Phonenumbers 小巧，实用简便，没有地理代编码，运营商，时区等metadata数据。它能识别多种格式，然后使用不同的格式/样式进行有效匹配。
 * [toyplot](https://github.com/sandialabs/toyplot) - Python交互绘图库Toyplot，[文档doc](http://toyplot.readthedocs.org/en/latest/)。
 * [pythalesians](https://github.com/thalesians/pythalesians/) - Python金融(分析工具)库PyThalesians。
 * [20个机器学习开源项目](http://mp.weixin.qq.com/s?__biz=MzAwNTA4OTc3OQ==&mid=207199077&idx=1&sn=039cda9e698a85bc32d336c6f84dd059) - 20 个顶尖的 Python 机器学习开源项目 Scikit-learn、Pylearn2、NuPIC…… 
 * [Seaborn](http://web.stanford.edu/~mwaskom/software/seaborn/) - 用 Seaborn 画出好看的分布图, [使用说明](http://staticor.io/post/2015-06-10seaborn-distribution-plot)  。
 * [Python_Coding_Rule](http://ssv.sebug.net/Python_Coding_Rule) - 【Python代码指南】，这篇文档改编自Guido最初的《Python风格指南》一文，希望对初学Python的朋友们有所借鉴。
 * [GGTinypng](https://github.com/ylovern/GGTinypng) - 批量压缩png和jpg图片python脚本，已经支持子文件夹里面的图片，会按原始的相对路径存放到输出文件夹内。
 * [sinaweibopy](https://github.com/michaelliao/sinaweibopy) - 新浪微博Python SDK。
 * [keras](https://github.com/fchollet/keras) - Keras是一个高度模块化的神经网络库，用Python语言编写，可以基于TensorFlow或Theano框架运行。
 * [yapf](https://github.com/google/yapf) - yapf是一个Python文件代码格式化工具，但与其他类似工具采取了不同的算法。它脱胎于由 Daniel Jasper 开发的 clang-format。
 * [tqdm](https://github.com/tqdm/tqdm) - tqdm可以在长循环中添加一个进度提示信息，用户只需要封装任意的迭代器 tqdm(iterator)，是一个快速、扩展性强的进度条工具库。
 * [pyvim](https://github.com/jonathanslenders/pyvim) - pyvim用Python语言实现的Vim编辑器。
 * [snake](https://github.com/amoffat/snake) - Snake用来取代Vim的VimScript进行Vim的插件编程，借由Python的强大，让插件编程如虎添翼。
 * [pyxley](https://github.com/stitchfix/pyxley) - 使用Flask和React.js，快速开发数据面板（dashboard。在网页上显示一个数据面板是与人分享数据科学发现的最直观方法。对R语言来说有Shiny来简化数据科学家开发网页的工作，而Pyxley就相当于Python版的Shiny。使用Pyxley不光不用写HTML、CSS，你还可以加入自己的JavaScript来进行定制。
 * [Tomorrow](https://github.com/madisonmay/Tomorrow) - Tomorrow为Python 2.7中的异步代码提供了神奇的装饰器语法实现。
 * [ibis](https://github.com/cloudera/ibis) - Ibis是Cloudera Labs推出的一个新项目，目前还是预览版。它试图解决的就是数据集规模的问题，但对用户提供的确是单机上Python的体验，而且能够与现有的Python数据生态圈（Pandas、Scikit-learn、Numpy）进行集成。未来它还计划加入与机器学习和高级分析集成的功能。
 * [ipython](https://github.com/ipython/ipython) - IPython 是一个在多种编程语言之间进行交互计算的命令行 shell，最开始是用 python 开发的，提供增强的内省，富媒体，扩展的 shell 语法，tab 补全，丰富的历史等功能。
 * [bpython](https://github.com/bpython/bpython/) - bpython是一个不错的Python解释器的界面，很像现在的IDE（集成开发环境）。
 * [Ptpython](https://github.com/jonathanslenders/ptpython) - Ptpython是一个高级的python 交互式解释器(REPL)。[python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit) 。
 * [DreamPie](http://www.dreampie.org/) - DreamPie 是一个Python shell，为Python开发者提供自动完成的属性；功能和文档显示；并且将session历史存储为HTML文件。
 * [Arrow](https://github.com/crsmithdev/arrow) - Arrow这个库可以更好地处理Python中的日期和时间（data/time）。
 * [retrying](https://github.com/rholder/retrying) - Retrying库可以帮你避免重复劳动：它实现了『重试』行为。它提供了一个通用的 decorator，而且还可以设置一系列的属性，如最大重试次数、延时、退避休眠（backoff sleeping）和错误条件（error conditions）等，以此来获得你想要的重试行为。简单轻便。
 * [python-phonenumbers](https://github.com/daviddrysdale/python-phonenumbers) - python-phonenumbers从Google 的『libphonenumbers』库移植而来，用来解析、格式化或者验证电话号码，而且需要写的代码非常少。最重要的是，『phonenumbers』可以判断一个电话号码是否是唯一的（遵照 E.164 格式）。它同时支持 Python 2 和 Python 3。 
 * [monkeylearn-python](https://github.com/monkeylearn/monkeylearn-python) - monkeylearn-python通过简单易用的 RESTFul API 提供了云端的文本挖掘功能：比如文字中的情感、最重要的关键字，可以对文本进行话题检测，还可以使用自定义的文本分类器进行其他任何处理。
 * [Cookiecutter](https://github.com/audreyr/cookiecutter) - 一个命令行实用程序，从cookiecutters（项目模板）创建的项目，比如：创建从一个Python包项目模板的Python包项目。
 * [Sunburnt](https://github.com/tow/sunburnt) - Sunburnt全文搜索服务器Solr的Python接口。
 * [Celery](http://www.celeryproject.org/) - Celery是基于Python开发的分布式任务队列。它支持使用任务队列的方式在分布的机器／进程／线程上执行任务调度。
 * [Gevent](http://www.gevent.org/) - Gevent是一个基于greenlet的Python的并发框架，以微线程greenlet为核心，使用了epoll事件监听机制以及诸多其他优化而变得高效。
 * [meinheld](https://github.com/mopemope/meinheld/) - meinheld与Gevent两者都是高性能的WSGI兼容的web服务器。既然是同种东西，meinheld的性能确实好得令人意外。meinheld：greenlet(协程) + picoev（高性能网络库），gevent：greenlet（协程） + libevent（高性能网络库）。类似还有：bjoern的异步机制，cheroot的多线程机制(有GIL限制)。
 * [Greenlet](http://undefined.org/python/#greenlet) - Greenlet是一个python的并行处理的一个库。
 * [Eventlet](http://eventlet.net/) - Eventlet是一个用来处理和网络相关的python库函数，而且可以通过协程来实现并发。
 * [Python Async IO Resources](http://asyncio.org/) - asyncio python的异步iO操作资源， [asyncio](https://github.com/python/asyncio) - asyncio3.4以后作为python标准库来使用了。
 * [Twisted](https://twistedmatrix.com/trac/) - Twisted是一个用python语言写的事件驱动的网络框架，支持很多种协议，也是一个异步机制的框架。
 * [Mugen](https://github.com/PeterDing/mugen) - Mugen 是一个运行在 Python3.4+ 的 HTTP 异步请求库，Mugen的api设计参考了requests。[文档](https://github.com/PeterDing/mugen)。
 * [eviltransform.python](https://github.com/googollee/eviltransform) - eviltransform.python解决国内GPS地图坐标偏移问题,它将政府加密过的GCJ-02坐标，转成世界通用的WGS-84坐标。
 * [pagure](https://github.com/pypingou/pagure) - Pagure是一个用Python编写的新的、功能齐全的、提供 Web 服务的 Git仓库。它类似于Github 和 Gitlab ，同时允许开源贡献者分享彼此的资源，实现代码和内容上的合作。[官网](https://pagure.io/pagure)
 * [EbookLib](https://github.com/pypingou/pagure) - 一个用于处理 EPUB2 / EPUB3 和 Kindle 格式图书的电子书库。
 * [Pritunl](https://github.com/pritunl/pritunl) - 一款免费开源的VPN平台软件，让用户迅速搭建VPN服务；采用OpenVPN 代理方式，提供了API供高级开发者使用，同时还针对不同平台和不同VPS供应商提供了详尽的安装使用说明。
 * [OpenCC](https://github.com/BYVoid/OpenCC) - 一个开源的中文简繁转换项目，致力于制作高质量的基于统计预料的简繁转换词库。还提供函数库(libopencc)、命令行简繁转换工具、人工校对工具、词典生成程序、在线转换服务及图形用户界面。
 * [moviepy](https://github.com/Zulko/moviepy) - Moviepy是用来做Python视频编辑的模块：剪切，合并，插入标题，视频混合，视频处理，创建效果。可以读写大多数的音视频格式，支持三个主流的操作系统，支持Python2/3。
 * [delorean](https://github.com/myusuf3/delorean) - delorean提供了一个相比于datetime和pytz的更好的抽象，让你处理日期和时间更容易。它有很多有用的处理时区的特性，标准化时区或者从一个时区改变到另外一个时区。[官网](http://delorean.readthedocs.io/en/latest/)。
 * [swig](https://github.com/swig/swig) - 是一个非常优秀的开源工具，支持您将 C/C++ 代码与任何主流脚本语言相集成,包括 Ruby、Perl、Tcl 和 Python。[swig实现Python和C的互联](http://fangs.in/post/python/2015-07-27)。
 * [yagmail](https://github.com/kootenpv/yagmail) - 发送复杂邮件,发送富文本邮件、发送邮件附件以及使用邮件模板。[使用教程](http://mp.weixin.qq.com/s?__biz=MjM5NzU0MzU0Nw==&mid=2651370295&idx=1&sn=18d4b71ec100ca043c20cad612eb3f5e&scene=0#wechat_redirect)
 * [pypub](https://github.com/wcember/pypub) - 用来快速创建epub文件而不必考虑epub规范的复杂性。
 * [lxml](http://lxml.de/) - lxml联合了libxml2和libxslt。如果你要处理XML或HTML，lxml是最好的选择。
 * [Docopt](http://docopt.org/) - 忘了optparse和argparse吧，使用docstring来构建优雅的、高可读性、复杂（如果你有这个需要）的命令行界面。这是2013年诞生的最好的库。
 * [PEW](https://github.com/berdario/pew/) - PEW 是一套管理多个虚拟环境的工具，在bash，zsh，fish和powershell上完美运行。
 * [social-oauth](https://github.com/yueyoum/social-oauth) - 为中国大陆开放了OAuth2认证的网站提供Python接口。
 * [snownlp](https://github.com/isnowfy/snownlp) - 是一个python写的类库，可以方便的处理中文文本内容，是受到了TextBlob的启发而写的一个方便处理中文的类库。
 * [jieba](https://github.com/fxsjy/jieba) - “结巴”中文分词,做最好的 Python 中文分词组件。
 * [Yaha分词](https://github.com/jannson/yaha) - "哑哈"中文分词，更快或更准确，由你来定义。通过简单定制，让分词模块更适用于你的需求。
 * [vnpya](https://github.com/vnpy/vnpya) - vn.py - 基于python的开源交易平台开发框架。
 * [minicache](https://github.com/duboviy/minicache) - 轻量级 Cache 工具。
 * [XlsxWriter](https://github.com/jmcnamara/XlsxWriter/) - 用来构造xlsx文件的模块，可以向excel2007+中写text，numbers，formulas 公式以及hyperlinks超链接。[官方教程](https://xlsxwriter.readthedocs.io/)
 * [xlrd](https://github.com/python-excel/xlrd) - python读Excel的库。[官方网站](https://pypi.python.org/pypi/xlrd)
 * [xlwt](https://github.com/python-excel/xlwt) - python写Excel的库。[官方网站](https://pypi.python.org/pypi/xlwt)
 * [Python-docx](http://python-docx.readthedocs.io/en/latest/) - 以编程方式创建和操纵 Microsoft Word .docx 文件。
 * [timeago](https://github.com/hustcc/timeago) - 一个将时间变成 “多久之前” 的库。 
 * [Blender](https://www.blender.org/) - 是一款开源的跨平台全能三维动画制作软件，提供从建模、动画、材质、渲染、到音频处理、视频剪辑等一系列动画短片制作解决方案。 (3D打印)
 * [Libcloud](http://libcloud.apache.org/) - 隐藏了不同云提供商应用程序编程接口（API）之间的差异，包括AWS、Apache CloudStack、Rackspace、谷歌云平台、微软Azure、VMware和OpenStack在内的50多个云提供商采用了Libcloud。
 * [pyfilesystem2](https://github.com/PyFilesystem/pyfilesystem2) - 一个为所有文件系统提供的通用 Pythonic 接口。
 * [multidiff](https://github.com/juhakivekas/multidiff) - 针对于多个对象或者数据流的二进制（数据）比较工具。
 * [Mypy-protobuf](https://github.com/dropbox/mypy-protobuf) - (协议缓冲区)用于从协议缓冲区中生成mypy 根的开源工具。
 * [Click](https://github.com/pallets/click) -用于快速创建命令行开发神器。Python 内置了一个 Argparse 的标准库用于创建命令行，但使用起来有些繁琐，Click 相比于 Argparse，就好比 requests 相比于 urllib。
 * [black](https://github.com/ambv/black) - 一个代码格式化工具，black命令后面可以接py文件或文件夹，它会自动把文件或文件夹里面的代码按照PEP8的规范进行格式化。
 * [white](https://github.com/kennethreitz/white) - fork了black代码，将默认的每行代码88个字符修改成79个字符。
 * [pycodestyle](https://github.com/PyCQA/pycodestyle) - 用 pycodestyle 可检测有哪些地方不符合 PEP8 风格。
 * [quart](https://gitlab.com/pgjones/quart) - 基于Asyncio的微框架，支持HTTP/1.1、HTTP/2、Websockets，对flask应用的支持最好。
 * [Chips-2.0](https://github.com/dawsonjon/Chips-2.0) - 基于python语言的高级FPGA设计工具。
 * [Datasheets](https://github.com/Squarespace/datasheets) - 用Python读取Google Sheets的数据、向Google Sheets写入数据以及修改Google Sheets的格式。
 * [Spotify-playlist-generator](https://github.com/mileshenrichs/spotify-playlist-generator) - Spotify播放列表生成器，由Python编写的脚本，能够每周根据新音乐自动创建新的播放列表。
 * [Ubelt](https://github.com/Erotemic/ubelt) - 由Python编写的实用工具，包含大量实用的工具函数，可跨平台使用。
 * [qrcode](https://github.com/sylnsfar/qrcode) - Python 艺术二维码生成器 （GIF动态二维码、图片二维码）。
 * [python-qrcode](https://github.com/lincolnloop/python-qrcode) - 支持生成矢量图，而且比较适合在代码中生成二维码的场景。
 * [Envparse](https://github.com/rconradharris/envparse) - Envparse 能够处理环境变量、ENV 文件、变量类型，甚至还可以进行预处理和后处理（例如，你想要确保变量名总是大写或小写的）。
 * [jrnl](https://github.com/maebert/jrnl) - jrnl:用命令行来写日记，装x利器。[官网](http://jrnl.sh/)
 * [moviepy](https://github.com/Zulko/moviepy) - 是一个用于视频编辑Python库：切割、拼接、标题插入，视频合成（即非线性编辑），视频处理和自定义效果的创造。而且能渲染GIF或视频动画。
 * [pdf2htmlEX](https://github.com/coolwanglu/pdf2htmlEX) - 可以将PDF转换成HTML，可以在HTML文件中精确显示原生文本、生成的文件大小与解压缩后的PDF文件相当、单HTML文件输出。
 * [Camelot](https://github.com/socialcopsdev/camelot) - PDF图表提取库,支持命令行界面，另外还有一个web界面可选,每个表都是一个pandas DataFrame，它可以无缝集成到ETL和数据分析工作流中,支持导出为多种格式，包括JSON，Excel和HTML,不支持扫描版PDF。
 * [PyPortfolioOpt](https://github.com/robertmartin8/PyPortfolioOpt) - 一个实现广泛使用的经典金融投资组合优化技术的库。
 * [money](https://github.com/carlospalol/money) - 利用定点数解决python里面浮点数运行精度的问题。

========
####  完整项目
 * [lin-cms-vue](https://github.com/TaleLin/lin-cms-vue) - 一套内容管理系统框架的vue前端。
 * [lin-cms-flask](https://github.com/TaleLin/lin-cms-flask) - 一套内容管理系统框架，可以有效的帮助开发者提高 CMS 的开发效率，基于flask。

========
#### 博客与播客及书籍文档
 * [值得关注的10个python语言博客](http://www.admin10000.com/document/6540.html) - 值得关注的10个python语言博客, [Planet Python](http://planetpython.org/) 最出名的python博客其中之一; [lucumr](http://lucumr.pocoo.org/) flask的创始人; [love-python](love-python.blogspot.com) 有很多有用的知识和代码; [Doug Hellmann](https://doughellmann.com/blog/) 博主是PYMOTW(Python Module Of the Week)成员之一，博客里面包含了很多library的知识; [Code Who Says Py](http://sayspy.blogspot.com/) 这个博客很不错,虽然它更新的不是很及时; [effbot](http://effbot.org/) 代码和任何你能想得到的东西都在里面; [pydanny](http://pydanny.com) 主要关于Django的博客; [inventwithpython](http://inventwithpython.com/blog/) Al Sweigat，他写了很多本关于python的书; [pythonlibrary](http://www.blog.pythonlibrary.org/) 最有用的博客，他让我的python技术迅猛提; [freepythontips](http://www.freepythontips.wordpress.com/) 打不开了。

 * [听技术播客](http://www.admin10000.com/document/6540.html) - 听技术播客：一边学Python编程一边学英语。[Talk Python to Me](https://talkpython.fm/) 每期都会请一些知名的Python开发者做嘉宾; [Podcastinit](http://podcastinit.com) Podcastinit也是专注于Python语言的，每期节目也会邀请不同的嘉宾，探讨与Python有关的工具和产品，另外也时常探讨技术领域多样性和包容性等更加宽泛、更具社会性的话题; [Python Test Podcast](http://pythontesting.net/test-podcast/) 聚焦的主题是测试，大部分都是与测试有关的。

 * [django-web-app-book](https://github.com/wwq0327/django-web-app-book) - Django Web 开发实战,本书是一本在线的免费的Django Web编程书籍。
 * [Django-Design-Patterns-and-Best-Practices](https://github.com/cundi/Django-Design-Patterns-and-Best-Practices) - Django设计模式与最佳实践。
 * [四款工具顺利实现Python与JavaScript间的代码转换](http://developer.51cto.com/art/201602/505811.htm) - 实现Python与JavaScript代码转换的4个工具：Transcrypt、Jiphy、Brython、RapydScript。

========
#### 好的文章
 * [使用Pandas和Matplotlib分析Tweets](https://github.com/ictar/pythondocument/blob/master/Science%20and%20Data%20Analysis/Matplotlib%E6%95%99%E7%A8%8B%20-%20%E7%BB%98%E5%88%B6%E6%8F%90%E5%88%B0Trump%2C%20Clinton%20%26%20Sanders%E7%9A%84%E6%8E%A8%E7%89%B9.md) - 使用Pandas和Matplotlib分析Tweets。
 * [Python 黑帽编程大纲](https://zhuanlan.zhihu.com/p/21658243) - Python 黑帽编程大纲
 * [DeepLearning-500-questions](https://github.com/scutan90/DeepLearning-500-questions) - 深度学习500问，以问答形式对常用的概率知识、线性代数、机器学习、深度学习、计算机视觉等热点问题进行阐述，以帮助自己及有需要的读者。 全书分为18个章节，近30万字。

========
#### 他人总结
 * [awesome-python](https://github.com/vinta/awesome-python) - <font color=#FF0000 >Awesome可能是GitHub上寻找和整理开源项目最好的方式</font> 。 
 * [interview_python](https://github.com/taizilongxu/interview_python) - 十分全面的Python的面试题。
 * [issue-198-top2015](http://python.jobbole.com/84145/) - 蠎周刊2015年度最赞。
 * [Awesome Python](https://python.libhunt.com/) - 一个收集Python资源的网站，框架、包、软件和其它资源都很棒，自带搜索功能，极为方便。
 * [python_interview_question](https://github.com/kenwoodjw/python_interview_question) - 关于python的面试题。
 * [Algorithm_Interview_Notes-Chinese](https://github.com/imhuay/Algorithm_Interview_Notes-Chinese) - 算法/深度学习/NLP面试笔记。


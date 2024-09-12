# [首页查询更多项目](https://github.com/GraduationProject-ssm) 包安装运行


# ssm466健身管理系统开发与设计+jsp

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1t58veLEnL?p=64)


# 绪论
## 1.1 选题背景
当人们发现随着生产规模的不断扩大，人为计算方面才是一个巨大的短板，所以发明了各种计算设备，从结绳记事，到算筹，以及算盘，到如今的计算机，都是在无法满足生产的前提下出现的。随着计算机的发展，又出现了互联网技术。到现在为止，互联网已经发展了几十年了，在几十年的时间里就已经风靡世界。各行各业都发现了计算机的好处，计算机刚开始是军用的，后来在民用行业开始使用，到互联网时代，各种行业信息如井喷一般充斥着互联网，信息产生和传播的速度不断的提高。针对互联网的优点，结合互联网，对传统行业信息处理技术进行升级是非常有必要的。本课题对于健身信息的管理方面，开发一个健身管理系统，在信息管理方面不至于混乱，也能降低数据的出错率，数据安全方面也有了保证，该系统还有其他的优点，比如优化信息处理流程，降低信息泄露风险，减少资金投入，产出更高，让管理人员的工作更有效率等。所以说，健身管理系统是目前不可缺的，对使用者相当的重要。
## 1.2 选题意义
如今的年代，已经是步入信息社会了，不仅信息更新速度频繁，信息量也大，在信息时代必须有相应的处理信息的方法，如果还采用以前的结绳记事或者笔写纸记，不仅是信息录入效率上赶不上节奏，在信息检索的速度上更是让人无法承受。幸而当今社会上计算机技术发展的相当不错，可以通过计算机在信息处理上面实现自动化或者半自动化的作业，采用计算机技术，能有效的提高信息录入以及信息检索的效率，社会上相同行业之间本身就是效率高的淘汰效率低的，既然采用计算机来替代手工记录，必然是效率更高，稳定性更强，成本更低等诸多优点。针对于健身信息管理，开发一个健身管理系统不仅可以实现现代化的信息管理，也更符合现代化信息管理规范。

在实际的使用效果中，健身管理系统的意义如下：

第一点：健身管理系统的出现，就是为了提高工作人员的效率，能够在规定时间完成工作任务。

第二点：操作页面符合人体工程美学，符合日常人为操作习惯，使用友好。

第三点：区别于传统用纸张记录，提高了信息化水平。

第四点：在信息处理方面，极大的降低了人工处理成本。
## 1.3 研究内容
本文对系统的描述过程将按照绪论，系统开发技术，分析，设计，实现，测试等环节进行展开介绍。

绪论：本节内容主要展示研究该系统的背景和意义。

系统开发技术：本节内容主要展示该系统开发中需要使用的技术和搭建的开发环境。

系统分析：本节内容主要就是分析系统，包括性能，功能上的数据分析，也包括可行性分析等内容。

系统设计：本节内容主要就是根据系统分析的结果进行设计，主要包括功能和数据库的设计。

系统实现：本节内容主要就是通过程序编码对系统的功能进行实现，同时也对需要介绍的功能进行界面运行效果的展示。

系统测试：本节内容主要就是对系统的功能实现部分进行检测，发现系统的错误并及时纠正，让系统能够保证运行无误。
# 2 系统开发技术
对系统的开发需要做好准备工作，其中安装开发的工具以及学习开发中需要运用的技术都是需要提前进行的，本节内容就对开发中运用的工具还有技术进行阐述。
## 2.1 MySQL数据库
本设计用到的数据库就是MySQL数据库，之所以用到这个数据库的原因很多。首先，从满足功能需求上面来讲，MySQL是符合的；其次，从学习程度来讲，MySQL相比其他数据库不管是从安装还是使用上面来讲，都比较简单，最重要的是学习起来相当便捷，比较容易入手；再次，MySQL数据库对电脑要求不高，不管是什么样的电脑都可以安装MySQL数据库，并且并不会对电脑性能造成过多的影响。所以，就平常普普通通的电脑就可以作为开发用的电脑，不需要进行额外的电脑升级。虽然自从MySQL数据库被Oracle数据库收购后，有了一些闭源的风险，但是使用者还是很多，MySQL数据库目前的开发人员已经超过五百人了，对数据库开发者来讲已经是一个很大的开发团队了。MySQL在使用上面来讲，普通的增删改查操作已经可以满足大部分业务需求，像一些数据导出导入，以及一些函数，都可以满足一些不同的需求，最重要的是MySQL数据库可以创建索引，可以大大的提高数据的查询效率，当然，物极必反，如果因为索引好用而滥用，索引弄得比数据库表还要多，这样会造成MySQL数据库更新表数据时候的运行效率。总而言之，MySQL数据库在本次设计的使用上，是完全符合使用要求的。
## 2.2 IDEA简介
IDEA的诞生在Java集成开发工具行业正所谓平地起雷，瞬间震动了整个Java开发行业。真的是每个人用过的都说好。IDEA之所以相比于其他比如MyEclipse或者Eclipse之类的Java开发工具来讲比较好，原因首先在于设计方面。IDEA采用了所谓的人体工程学设计原理，让使用IDEA的人员用了就忘记不了。软件打开首先要设置主题，可以选择常规的白色或者暗色系列，长时间的白色或者长时间的暗色会让开发人员的眼睛疲劳加重，首先从这个细节就让程序开发人员备受青睐，让程序员看着舒服；然后再对一些常用性插件进行归类，让程序的开发注重于提升生产效率，而不是一味的让开发者找各种插件，有时候插件之间的版本还会存在不兼容，IDEA就把兼容的插件双手呈现，如此贴心的IDEA怎么能让人不喜爱。所以选择IDEA用来开发本项目就理所当然的了。
## 2.3 SSM框架
最近几年流行的SSM框架是之前的SSH框架的一种替代品，取代了原有的SSH框架的那种臃肿的配置，以及各种Bug，并且在开发模式以及运行效率上面来讲，都是有了很大的提高。Spring是控制层，Spring MVC是视图层，MyBatis是持久层。

在原理上面，SSM框架继承了SSH框架的那种框架以及代码分层设计，首先理解起来比较符合人类的正常理解，视图是负责视图的控制和显示，控制层可以接收和传递视图提交过来的信息，也可以接收和传递持久层的数据信息，而持久层只需要对数据对象进行自动化的转换，给控制层的数据是Java对象，到数据库则转换为相应的数据类型。

使用框架可以有效的解决各种代码写作过程中数据类型的转换问题，把数据类型转换让框架自己转换，写作很方便。
## 2.4 Vue框架
Vue框架的开发者是一个中国人，区别于其他框架的最核心的概念就是渐进式框架，Vue的出现，让网页前端的开发变成了一种纯前端职业，不需要在考虑后台数据类型以及业务逻辑，只需要进行数据绑定即可，大大的减少了前端开发工程师的学习难度。Vue是当前世界上最火的一种前段框架，学习成本比较低，只需要熟悉最基本的网页知识就可以理解相关知识，并且有很好的免费教程进行学习，有各个国家语言的教程，尤其是因为是中国人开发的框架，让中国的高级程序开发人员做了汉语教程。Vue框架发展之初就是高于IE8版本的，所以说只要是当前的主流浏览器都支持Vue框架，如果是很旧的那种电脑是不支持的，必须安装支持HTML5的浏览器才可以访问用Vue发布的站点。
# 3 系统分析
对于健身管理系统开发设计到的流程有，分析系统的功能，设计系统的结构，设计数据库，编码以及测试，其中，在系统分析中，所做的工作包括功能的确定，性能的分析等。
## 3.1 可行性研究
健身管理系统开发实现分析需要从不同的角度来进行分析可行性，比如从时间角度，经济角度，甚至操作角度。从不同的角度分析可行性会让健身管理系统开发具体化，进而达到辩证开发的正确性。
### 3.1.1 经济可行性
从经济方面分析是第一要素，没有经济的支持，任何项目都如水中捞月，无法实现。实现健身管理系统，开发过程不需要额外的经济条件，用本人现有的计算机就可以实现，这方面不需要额外的支出。
### 3.1.2 时间可行性
健身管理系统设计主要作为毕业设计，在题目确定之后，答辩之前使用的项目，对不同的开发进度上面都有时间的要求，总不至于答辩完成后才能实现功能，这个肯定不行，所以从时间上来分析项目的工作量，发现是可行的，符合正常开发时间。
### 3.1.3 操作可行性
操作必须符合正常人的思维模式，市面上有很多符合要求的程序正在使用中，可以借鉴其他程序的操作流程，变成符合本设计的操作流程，在操作上面进行无缝衔接，让使用者操作过程中不会感到迷茫。

从上面的角度来分析，后续工作可以继续进展。
## 3.2 系统性能分析
性能分析是软件开发过程中必不可少的一个环节，主要是为了降低软件在使用的过程中的容错率。通常来讲，分析软件系统的性能一般从以下几个方面进行分析。
### 3.2.1 系统的安全性
系统开发出来就是让正常使用的，那么在如今的互联网时代，首先考虑的就是安全性的问题。如果系统的安全性不够，那么使用价值就会降低。如果出现使用过程中丢失数据，那么用户就不再信赖，所以系统的安全性是第一要位，只有安全性存在了，才能考虑使用的问题，总不至于今天用户注册，明天用户账号泄露，这些都是不友好的。所以账号一般在数据库里存储会通过MD5进行加密，这样关键数据加密可以保证系统的安全性。
### 3.2.2 系统的易用性
安全性分析处理完毕，才考虑易用性。一个软件设计得符合操作规范，符合正常人类的理解逻辑，那么在使用上面就会很舒服，如果违背了这条原则，安全性再高的软件也是设计失败的，毕竟软件开发出来就是让人使用的，这一点尤为重要。
### 3.2.3 系统的健壮性
系统设计易用不代表没有规则，那么系统设计使用方面必须健壮，必须符合软件处理逻辑。比如设计一个价格类的输入框，用户需要输入价格，那么可以设定输入框最多两位小数的纯数字输入，如果用户不小心输入了其他字符，那么就会友好的提示让用户修改正确，只有输入符合规范的数据，才能进行提交，并且存储到数据库里。系统的健壮性就是这样，越是规范，越是健壮，有助于用户理解，还有助于程序使用。
## 3.3 系统流程分析
系统设计不是胡乱的设计，必须符合软件设计思想，具体的流程参考下图。系统设计的前期就是做各种分析，功能的设计，数据库的设计等，等一切都设计好了，逻辑上没有问题，符合设计流程和设计规范，才可以继续编码环节，编码只是实现设计的一个环节而已。

![](/md/blog.001.png)

图3.1系统开发流程图

用户是一切应用的基础，只要牵扯到用户，那么肯定需要用户进行注册，只有这样才能让注册的用户进行使用。如果用户没有注册，只能算是游客，那么只能访问一些大众用户可以浏览的信息，如果需要用户操作的部分是不允许访问的，这样能极大的保证用户的权利。用户注册流程用下面的图来表示，主要是先判断用户名，只有用户名能用了才可以进行后面的信息注册。

![](/md/blog.002.png)

图3.2 注册流程图

当需要用户登录的时候，肯定是要验证的，只有验证通过的用户才可以进行下一步操作，用户登录成功代表着用户模块的功能对登录用户进行了开放。流程就是如下面的图所示。

![](/md/blog.003.png)

图3.3 登录流程图
## 3.4 系统功能分析
在对设计的总体要求理解了之后，就要把要求给具体化，也就是功能化，要尽量的把每个功能模块和模块之前的关系理清楚，必须符合正常人的行为逻辑才可以，并且尽量研究同类型的项目，这样能避免走弯路，最终才能得到设计的具体功能。

健身管理系统把操作该系统的用户群分为三类，即管理员，工作人员，用户。

管理员对于健身管理系统操作的功能包括公告信息管理，器材管理，课程管理，教练管理，工作人员管理，用户管理等。其用例图如图3.4所示：

![](/md/blog.004.png)

图3.4 管理员用例图

工作人员对于健身管理系统操作的功能包括管理器材，管理教练，管理课程，管理公告和用户。

![](/md/blog.005.png)

图3.5 工作人员用例图

用户对于健身管理系统操作的功能包括查看公告，查看器材，查看课程，查看教练等。其用例图如图3.6所示：

![](/md/blog.006.png)

图3.6 用户用例图

# 4 系统设计
系统在设计的过程中，必然要遵循一定的原则才可以，胡乱设计是不可取的。首先用户在使用过程中，能够直观感受到功能操作的便利性，符合正常思维逻辑的操作，这才是系统好用的一个开端，给使用者第一印象就是这个系统设计的相当不错。
## 4.1 系统设计原则
系统遵循设计原则进行开发，会有很多可以预料到的好处，只要遵循了设计原则，那么开发出来的系统必然是有质量保证的。

首先第一条原则就是安全性原则：程序必须设定角色管理，不同的角色有不同的功能模块，不同的角色登录都需要输入相对应的账号和密码，否则不允许进行操作相对应的权限。每个用户登录只能修改自己的密码，不需要对别的账号进行密码或者其他资料的修改，否则就违背了安全性原则的设定。

其次第二条原则就是易用性原则：符合安全性只是功能的符合，不代表操作就符合，所以要设定易用性原则。易用性原则就是规定程序符合操作流程，正常人的思维定向为基础，在不违背程序运行逻辑定义的情况下，必须使用简单，操作规范，让每个用户使用起来都能看到页面，就能感知功能模块的作用，短时间的就能使用程序，达到易用效果。

再次第三条原则就是实用性原则：实用性代表着花里胡哨的功能必须抛弃，尽量符合数据处理的简洁性，不仅需要这样进行设定，还需要有预知性，系统后期可能会出现的功能模块尽量要解耦，与程序设定要模块化体现，这样才能达到扩展性。

第四条原则就是准确性原则：准确性原则的唯一定义就是准确，包含数据输入格式的准确，数据处理的准确，以及数据存储的准确。程序里面关于数据准确才有存在的意义，如果一堆不相干的数据存在是没有任何用处的，甚至会产生各种问题，所以必须要保证数据的准确性。

第五条原则是易维护原则：易维护代表着程序运行必须是可控的状态，如果不可控出现各种问题，那么所有的工作都是空谈。程序开发中对于各种程序判定异常，必须有统一的处理模式，异常是程序开发中不可避免的，但是可以对出现的异常进行抛出，有助于程序异常处理的复盘，只要每个异常都能定位准确，那么代表程序设计是趋于完美的，维护起来会更加的方便，只要有助于程序维护的都必须给予支持。
## 4.2 功能模块设计
对管理员具体功能的设计结果将以图4.1所示的管理员功能结构图来进行体现。管理员对于健身管理系统操作的功能包括公告信息管理，器材管理，课程管理，教练管理，工作人员管理，用户管理等。

![](/md/blog.007.png)

图4.1 管理员功能结构图

对工作人员具体功能的设计结果将以图4.2所示的工作人员功能结构图来进行体现。工作人员对于健身管理系统操作的功能包括管理器材，管理教练，管理课程，管理公告和用户。

![](/md/blog.008.png)

图4.2 工作人员功能结构图

对用户具体功能的设计结果将以图4.3所示的用户功能结构图来进行体现。用户对于健身管理系统操作的功能包括查看公告，查看器材，查看课程，查看教练等。

![](/md/blog.009.png)

图4.3 用户功能结构图
## 4.3 数据库设计
用户通过系统的功能操作来进行数据交互，包括数据的添加，数据的更新，数据的删除，数据的查询等基本功能操作，表面上虽然是操作系统界面提供的功能，但是实际上系统的这些数据是在数据库当中进行访问与操作的。目前市场上可供选择的存储数据的数据库有很多，除了简单版的Access之外，还有SQL Server，DB2，Informix，MySQL等关系型数据库可供选择，由于关系型数据库具有固定的表结构，以及对数据一致性要求比较强，所以相比没有固定表结构以及具有灵活的数据格式的非关系型数据库而言，在程序配套数据库的选择中，关系型数据库的使用率更高。本系统选择MySQL来存放数据，其相关理论以及技术在经过了很长时间的发展之后，变得非常成熟，各大网络平台都公开分享其开发源码，而且其对计算机的配置要求很低，不需要过多内存进行安装，很符合本系统对于数据库的选择要求。
### 4.3.1 数据库E-R图
本节需要对系统中存放在数据库中的数据进行充分分析，对数据的实体，实体特征，联系等进行确定，然后通过概念模型的表示方法即E-R图进行表达，在E-R图绘制工具中，选择椭圆，菱形框，矩形等形状表达实体属性，实体间联系，实体这些信息，使用实线段将这些形状进行连接即可。初步完成E-R图之后，需要进行检查，及时进行有误数据的更改，删除实体间存在的冗余联系，删除E-R图中冗余的数据，最终要展示一个内容准确的E-R图。

（1）课程包括的属性有课程介绍，课程时间，课程照片等。其属性图如下。

![](/md/blog.010.png)

图4.4 课程实体属性图

（2）用户包括的属性有密码，姓名，身份证等。其属性图如下。

![](/md/blog.011.png)

图4.5 用户实体属性图

（3）管理员包括的属性有用户名，密码等。其属性图如下。

![](/md/blog.012.png)

图4.6 管理员实体属性图

（4）教练包括的属性有教练姓名，教练照片等。其属性图如下。

![](/md/blog.013.png)

图4.7 教练实体属性图

（5）设计的各实体间关系E-R图如下。

![](/md/blog.014.png)

图4.8 实体间关系E-R图
### 4.3.2 数据库表结构
在指定的数据库里面对数据表进行创建命名，然后设计各个数据表的存储结构，需要对该数据库的操作非常熟悉，并且还需要学习并掌握一定的数据表设计方面的知识，比如数据命名，作为系统的开发人员，为了避免程序运行产生乱码现象以及为了确保系统的正常运行，在对数据表进行命名时，一般都是采用英文名称，同时在对数据表的字段进行编辑时，也是采用英文的方式进行，为了方便今后对数据表的设计内容进行更改或查看，对一些比较重要的字段都会进行中文备注，或者是使用中文进行字段描述。设计期间，也需要对各个字段选择合适的数据类型以及设置匹配的取值范围，当一张数据表设计完成之后，还要对该表的主键进行标注，就是为了确保该数据表的唯一性与独立性。

表4.1 公告信息表

主要存放公告信息，每个字段对应的详情见下表

|字段|注释|类型|空|
| :-: | :-: | :-: | :-: |
|id (主键)|主键|int(11)|否|
|gonggao\_name|公告名称 |varchar(200)|是|
|gonggao\_photo|公告图片|varchar(200)|是|
|gonggao\_types|公告类型|int(11)|否|
|insert\_time|公告发布时间|timestamp|是|
|gonggao\_content|公告详情|text|是|
|create\_time|创建时间 |timestamp|是|
表4.2 工作人员表

主要存放工作人员信息，每个字段对应的详情见下表


|字段|注释|类型|空|
| :-: | :-: | :-: | :-: |
|id (主键)|主键|int(11)|否|
|username|账户|varchar(200)|是|
|password|密码|varchar(200)|是|
|gongzuo\_name|工作人员姓名 |varchar(200)|是|
|gongzuo\_phone|工作人员手机号|varchar(200)|是|
|gongzuo\_id\_number|工作人员身份证号|varchar(200)|是|
|gongzuo\_photo|工作人员头像|varchar(200)|是|
|sex\_types|性别|int(11)|是|
|create\_time|创建时间|timestamp|是|
表4.3 教练表

主要存放教练信息，每个字段对应的详情见下表


|字段|注释|类型|空|
| :-: | :-: | :-: | :-: |
|id (主键)|主键|int(11)|否|
|jiaolian\_name|教练姓名 |varchar(200)|是|
|jiaolian\_phone|教练手机号|varchar(200)|是|
|jiaolian\_id\_number|教练身份证号|varchar(200)|是|
|jiaolian\_photo|教练照片|varchar(200)|是|
|sex\_types|性别|int(11)|是|
|create\_time|创建时间|timestamp|是|
表4.4 课程表

主要存放课程信息，每个字段对应的详情见下表


|字段|注释|类型|空|
| :-: | :-: | :-: | :-: |
|id (主键)|主键|int(11)|否|
|jiaolian\_id|教练|int(20)|否|
|xingqi\_types|星期 |int(11)|是|
|kecheng\_name|课程名称 |varchar(200)|是|
|kechengshijian|课程时间 |varchar(200)|是|
|kecheng\_photo|课程照片|varchar(200)|是|
|kecheng\_types|课程类型 |int(11)|是|
|kecheng\_content|课程介绍|text|是|
|insert\_time|添加时间|timestamp|是|
|create\_time|创建时间|timestamp|是|


表4.5 用户表

主要存放用户信息，每个字段对应的详情见下表


|字段|注释|类型|空|
| :-: | :-: | :-: | :-: |
|id (主键)|主键|int(11)|否|
|username|账户|varchar(200)|是|
|password|密码|varchar(200)|是|
|yonghu\_name|用户姓名 |varchar(200)|是|
|yonghu\_phone|用户手机号 |varchar(200)|是|
|yonghu\_id\_number|用户身份证号 |varchar(200)|是|
|yonghu\_photo|用户头像|varchar(200)|是|
|sex\_types|性别|int(11)|是|
|yonghu\_types|状态|int(11)|是|
|yonghu\_email|电子邮箱|varchar(200)|是|
|new\_money|余额|decimal(10,2)|是|
|yonghu\_time|会员截止日期|timestamp|是|
|create\_time|创建时间|timestamp|是|
表4.6 器材表

主要存放健身器材信息，每个字段对应的详情见下表


|字段|注释|类型|空|
| :-: | :-: | :-: | :-: |
|id (主键)|主键|int(11)|否|
|qicai\_name|器材名称 |varchar(200)|是|
|qicai\_photo|器材照片|varchar(200)|是|
|qicai\_types|器材类型 |int(11)|是|
|qicai\_number|器材数量|int(11)|是|
|qicai\_content|器材介绍|text|是|
|insert\_time|添加时间|timestamp|是|
|create\_time|创建时间|timestamp|是|
表4.7 管理员表

主要存放管理员信息，每个字段对应的详情见下表


|字段|注释|类型|空|
| :-: | :-: | :-: | :-: |
|id (主键)|主键|bigint(20)|否|
|username|用户名|varchar(100)|否|
|password|密码|varchar(100)|否|
|role|角色|varchar(100)|是|
|addtime|新增时间|timestamp|否|

# 5 系统实现
下面主要是通过功能实现界面截图的形式，并且运用文字来描述功能实现界面的内容。
## 5.1 管理员功能实现
### 5.1.1 工作人员管理
该功能主要用于实现对工作人员基本信息的管理，工作人员管理界面的运行效果见图5.1。在此界面，管理员根据工作人员的账号可以直接对工作人员的信息进行查询，可以给工作人员的密码进行重置，可以修改工作人员的信息。

![](/md/blog.015.png)

图5.1 工作人员管理界面
### 5.1.2 消费类型管理
该功能主要用于实现对消费类型基本信息的管理，消费类型管理界面的运行效果见图5.2。在此界面，管理员对消费类型的名称，消费类型的金额进行修改，可以根据消费类型的名称对消费类型的信息进行查询。

![](/md/blog.016.png)

图5.2 消费类型管理界面
### 5.1.3 课程类型管理
该功能主要用于实现对课程类型基本信息的管理，课程类型管理界面的运行效果见图5.3。在此界面，管理员根据课程类型的名称对课程类型的信息进行查询，添加新的课程类型，修改课程类型的名称，删除课程类型的信息。

![](/md/blog.017.png)

图5.3 课程类型管理界面
### 5.1.4 用户管理
该功能主要用于实现对用户基本信息的管理，用户管理界面的运行效果见图5.4。在此界面，管理员在此界面负责对用户的资料进行更改，删除或查询，可以给用户办理健身月卡，办理健身年卡等。

![](/md/blog.018.png)

图5.4 用户管理界面
### 5.1.5 公告信息管理
该功能主要用于实现对公告基本信息的管理，公告信息管理界面的运行效果见图5.5。在此界面，管理员增删改查公告信息。

![](/md/blog.019.png)

图5.5 公告信息管理界面
## 5.2 工作人员功能实现
### 5.2.1 教练管理
该功能主要用于实现对教练基本信息的管理，教练管理界面的运行效果见图5.6。在此界面，工作人员增删改教练信息。

![](/md/blog.020.png)

图5.6 教练管理界面
### 5.2.2 课程管理
该功能主要用于实现对课程基本信息的管理，课程管理界面的运行效果见图5.7。在此界面，工作人员负责添加课程，修改课程时间，课程照片，教练照片，教练手机号等信息，查询课程信息。

![](/md/blog.021.png)

图5.7 课程管理界面
### 5.2.3 器材管理
该功能主要用于实现对器材基本信息的管理，器材管理界面的运行效果见图5.8。在此界面，工作人员可以更改器材的照片，更改器材的数量等信息，通过器材的名称对器材的信息进行查询，可以添加器材的信息。

![](/md/blog.022.png)

图5.8 器材管理界面
## 5.3 用户功能实现
### 5.3.1 查看公告
查看公告界面的运行效果见图5.9。在此界面，用户主要对公告进行查看，用户通过公告的名称就可以对公告的信息进行查询。

![](/md/blog.023.png)

图5.9 查看公告界面
### 5.3.2 查看课程
查看课程界面的运行效果见图5.10。在此界面，用户随时查看课程的时间，教授课程的教练信息，查看课程的类型等信息。

![](/md/blog.024.png)

图5.10 查看课程界面
### 5.3.3 查看器材
查看器材界面的运行效果见图5.11。在此界面，用户对器材信息的查看可以增进对各种器材的了解。

![](/md/blog.025.png)

图5.11 查看器材界面
### 5.3.4 查看教练
查看教练界面的运行效果见图5.12。在此界面，用户对教练信息的查看可以了解教练的身份证号，教练的手机号以及教练的照片和教练的姓名等。

![](/md/blog.026.png)

图5.12 查看教练界面

# 











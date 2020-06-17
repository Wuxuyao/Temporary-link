**SDL产品矩阵报告**


**1 SDL Tridion DX **

**1.1 痛点** ![图片](https://uploader.shimo.im/f/7Bc9psDBmPjcWqMU!thumbnail)

**1.2 需求**![图片](https://uploader.shimo.im/f/PW32SiWGEZUmSxsL!thumbnail)

**1.3 解决方案**![图片](https://uploader.shimo.im/f/WtmKERCbkdWu4bgo!thumbnail)

**1.4 产品** SDL Tridion DX使企业能够管理整个内容生命周期，为连续的客户经验提供支持。

它支持全球网络和深度产品内容管理。

![图片](https://uploader.shimo.im/f/NuVWxybQbPmvFLSZ!thumbnail)

**1.5 SDL Tridion DX 产品分析****1.5.1 产品特点** SDL Tridion DX 结合了 SDL Tridion Sites 网络体验管理、SDL Tridion Docs 结构化内容管理以及 SDL 语言技术和服务，可实现全球化的数字客户体验。

![图片](https://uploader.shimo.im/f/arbRgE7APoNt0UYg!thumbnail)

**1.5.2 产品功能**![图片](https://uploader.shimo.im/f/wYUL3YuvB2UOEZfH!thumbnail)

**2 SDL Tridion Site 产品分析****2.1 产品简介** SDL Tridion Sites 是一款稳健的网络内容管理解决方案，让营销人员可在全球范围内创建、翻译和交付本地相关的数字体验：

 • 多站点

 • 多语言

 • 多品牌

 • 全渠道

 • 特定市场

 • 个性化

**2.2 产品特点** SDL Tridion Sites 通过集中协调和全球分发，可在整个客户旅程中实现内容一致性、客户相关性和品牌管理。

![图片](https://uploader.shimo.im/f/jtPzuXJRDScr9yIg!thumbnail)

**2.3 产品功能**![图片](https://uploader.shimo.im/f/5QFNS3VY2ak4NLjI!thumbnail)

**2.4 技术架构**![图片](https://uploader.shimo.im/f/pTm2Fnx7dMA3xkZe!thumbnail)

 Content Manager:

 Content Manager是创建、管理和组装各种构建块的环境，这些构建块用于构建用于其他渠道的网站或内容。用户使用各种Content Manager客户端创建内容;内容存储在Content Manager数据库中。Topology Manager将content Manager中的内容映射到内容交付环境。作者和编辑可以将内容发布到多个内容交付环境。典型的设置在防火墙后面有一个内容交付环境(“暂存”环境)，在防火墙之外有另一个内容交付环境(“活动”环境)。

 ·DXA

  DXA for Tridion Site是基于DXA的MVC web应用，结合了SDL Tridion Sites和SDL Tridion DX的内容交付。它包含一个示例站点，示例站点演示了可用的不同内容类型和布局。用户可以通过扩展示例的发布来构建自己的网站，或者从头开始创建一个新的发布。（Demo：https://sdl.dist.sdlmedia.com/Distributions/?o=4067728B-0A80-478C-BBD9-D0AC37B064B1）

 

 Content Delivery

 内容交付环境和展示环境物理上分离：展示环境只需要包含内容交互库(简称CILs)。CILs不需要任何特定的web和应用服务器、第三方库，也不需要连接到内容交付数据库。CILs与各种内容交付服务器端微服务交互，这些微服务是独立的，统称为内容交互服务(CIS)。当用户通过HTTP协议将内容从Content Manager发布到Content Delivery时，模板将托管内容转换为任何格式的内容片段，以便在内容交付端进行动态组装和分发。因为内容交付环境不能直接访问Content Manager数据库，所以敏感信息受到了保护。此外，去耦的体系结构允许对平台的每个部分进行独立的扩展和维护，从而降低了硬件和维护成本。SDL Tridion站点体系结构还对每个环境中使用的技术栈进行了解耦。


其他Trdion Sites相关但没整理的：

[https://docs.sdl.com/LiveContent/web/pub.xql?action=home&pub=SDL%20Tridion%20Sites%20prerequisites-v2&lang=en-US#docid=GUID-2A13459E-99D8-4FF4-8223-A7EBFAB7EFC1&addHistory=true&query=&scope=&tid=&filename=&resource=&inner_id=&toc=false&eventType=lcContent.loadDocGUID-2A13459E-99D8-4FF4-8223-A7EBFAB7EFC1](https://docs.sdl.com/LiveContent/web/pub.xql?action=home&pub=SDL%20Tridion%20Sites%20prerequisites-v2&lang=en-US)

[https://docs.sdl.com/LiveContent/web/pub.xql?action=home&pub=SDL%20DXA-v12&lang=en-US#docid=GUID-8173623D-D605-4962-AFBD-25D5F6DC6D93&addHistory=true&query=&scope=&tid=&filename=&resource=&inner_id=&toc=false&eventType=lcContent.loadDocGUID-8173623D-D605-4962-AFBD-25D5F6DC6D93](https://docs.sdl.com/LiveContent/web/pub.xql?action=home&pub=SDL%20DXA-v12&lang=en-US)

[https://docs.sdl.com/LiveContent/web/pub.xql?action=home&pub=SDL%20Tridion%20Sites%20Connector%20for%20Media%20Manager-v1&lang=en-US#docid=GUID-71A9BBA9-E89D-43D9-940F-463E02CAD145&addHistory=true&query=&scope=&tid=&filename=&resource=&inner_id=&toc=false&eventType=lcContent.loadDocGUID-71A9BBA9-E89D-43D9-940F-463E02CAD145](https://docs.sdl.com/LiveContent/web/pub.xql?action=home&pub=SDL%20Tridion%20Sites%20Connector%20for%20Media%20Manager-v1&lang=en-US)

[https://docs.sdl.com/LiveContent/web/pub.xql?action=home&pub=SDL%20Tridion%20Sites%20legacy-v2&lang=en-US#docid=GUID-FF0D3F9C-31DE-415E-818B-618E7526F1A0&addHistory=true&query=&scope=&tid=&filename=&resource=&inner_id=&toc=false&eventType=lcContent.loadDocGUID-FF0D3F9C-31DE-415E-818B-618E7526F1A0](https://docs.sdl.com/LiveContent/web/pub.xql?action=home&pub=SDL%20Tridion%20Sites%20legacy-v2&lang=en-US)

**3 SDL Tridion Docs 产品分析**[https://docs.sdl.com/LiveContent/web/pub.xql?action=home&pub=SDL%20Tridion%20Docs-v2.1.1&lang=en-US#docid=GUID-4D6F5536-9FF0-426A-9E5F-4FA5ECE63B95&addHistory=true&query=&scope=&tid=&filename=GUID-9460ED57-9248-4B78-AB44-7DA1D87FD5BE.xml&resource=&inner_id=&toc=false&eventType=lcContent.loadDocGUID-4D6F5536-9FF0-426A-9E5F-4FA5ECE63B95](https://docs.sdl.com/LiveContent/web/pub.xql?action=home&pub=SDL%20Tridion%20Docs-v2.1.1&lang=en-US)

**3.1 产品简介**SDL Tridion Docs是一个集成的企业解决方案，允许公司在整个客户旅程中创建、管理和交付产品和用户帮助内容。除了促进内容创建、管理和交付之外，SDL Tridion文档还促进了作者、审校人员和内容管理人员之间的协作。

 

**3.2 产品特点** 在SDL Tridion文档中，可以使用所见即所得的方式，基于web的客户端来编写内容，也可以使用与用户的XML创作工具无缝集成的Authoring Bridge解决方案来编写内容

3.3 产品功能

![图片](https://uploader.shimo.im/f/IliHqARAPNw4bYEM!thumbnail)

**4 SDL Contenta Publishing Suite****4.1 产品简介**SDL Contenta Publishing Suite 是一套完整、集成、经过行业检验的技术内容出版解决方案，其功能针对出版流程的每一步进行了优化。它为企业提供支持，帮助管理数以百万计的复杂技术文档页面，交付关键信息，让维护专家能够实现任务目标，减少平均修复时间，保证资产部署。

**4.2 产品功能**![图片](https://uploader.shimo.im/f/nIZH6LdYAE5v9ICJ!thumbnail)

**4.3 产品分析**SDL Contenta Publishing Suite套件包括Contenta S1000D预配置通用源数据库(CSDB)，S1000D交互式电子技术手册(IETP)和端到端出版工作流。

**4.3.1 通用源数据库**SDL Contenta S1000D 解决方案利用通用源数据库 (CSDB)，通过面向对象的架构促进内容重复利用，提供更高的内容准确性，同时降低制作成本。 SDL Contenta 通用源数据库 (CSDB) 提高了技术文档创作者、编辑者和出版者在创建、管理和交付 S1000D 技术出版物时的生产效率。

凭借内置的质量和法律合规性验证，使用来自多版本 S1000D 的数据模块，交付出版物。 通过实施这个简单易用的通用源数据库 (CSDB)，用户体验到高达 70% 的更快项目启动速度。 发现可存储和管理您所有内容（包括 S1000D、ATA、SGML/XML 和其他之前的数据）的位置。

通过在上下文中提供内容，确保准确提交特定数据，实现了在实时船尾、船体和序列号级别对复杂系统进行配置管理。

![图片](https://uploader.shimo.im/f/8lOczgbTbEgIPbZ1!thumbnail)

通用源数据库利用简化流程创建和管理数据模块，管理和储存传统SGML 和 XML 内容，以及图形和非结构化内容。 其结果是加速流程，并将出错几率降低60%。

![图片](https://uploader.shimo.im/f/l48C3QebUfYTgM0a!thumbnail)

通用源数据库的特色:

* 管理来自 S1000D、SGML、XML 和传统数据的内容 
* 支持不同版本的 S1000D 
* 储存结构化或非结构化数据 
* 预先配置对象、角色和层级视图 
* 自动化工作流

**4.3.2 交互式电子技术出版物**作为 SDL Contenta 出版套件的一部分，SDL LiveContent S1000D 可在交互式查看器中为现场技术人员提供准确的信息，让他们能够快速访问所需内容。 它的交互式电子技术出版物 (IETP) 功能可实时交付内容，让用户能够在最需要的时候以所需的格式获得最新内容。

富媒体通过动态图形、动画和模拟，为现场技术人员提供丰富的支持体验，使经验不足的技术人员能够快速处理专业任务。

![图片](https://uploader.shimo.im/f/zvAMuq4UANs5kkaT!thumbnail)

支持流程数据模块让技术人员能够轻松解决系统流程数据模块的使用问题，在整个流程中对技术人员起引导作用，从而缩短了设备和机器的维修时间。

![图片](https://uploader.shimo.im/f/g1sbLZAKP9XYRQcP!thumbnail)

SDL 交互式电子技术出版物的重要特色：

* 定期的出版物更新 
* 集成表格和报告 
* 独立于设备的交付 
* CGM 热点和链接支持 
* 适用于航空、船舶或其他复杂系统的开放式 API 
* 有条件地查看内容 
* 适用于非线性智能导航的可靠网站界面 
* 脱机/断网或联机环境 
* 3D 链接和视图 
* 多媒体支持

**4.3.3 自动化 XML 发布**端到端出版工作流借助 SDL XPP 软件解决方案，以 PostScript、Adobe Acrobat PDF 和 ePub 格式，自动编写和编页 XML 数据及许多其他数据源。 单独或作为 Contenta 出版套件的一部分使用，XPP XML 发布引擎可以完全自动化端到端出版工作流（从接收多源数据到将其合并成完整的交付成果）。

自动发布：SDL XPP 提供的工具可自动化手动流程，确保快速交付，顺利地输入来自多个源的文本和图形。 SDL XPP 为不同语言提供保持品牌一致性的优质译文。

SDL XPP 通过出版页数据库提供多种编写选项和更改页管理功能。

用户可定义宏可自动完成复杂功能，在单一文档中提供丰富的脚注功能，强大的制表和数学构造以及多语言断字功能。

自动化 XML 发布的重要特色

* 多种编写选项 
* 更改页管理功能 
* 集成到 XML 工作流 
* 来自数据库、XML 编辑器、内容管理系统 (CMS) 或结构化的文字处理文件的订阅源 
* 导入/导出带有 CALS 标记的 XML 数据 
* 高质量的 PDF 或 Postscript 产出 
* 交互式编辑 
* 黑色链接控制 
* 支持级联样式表 
* 自动添加超链接 
* 支持 30 多种语言 
* Web 服务 AP

**5 SDL Language Cloud**集成化的本地化供应链：提交、计划、监视、翻译、审校、DTP(Desktop Publishing桌面排版)等等。

注：除了Internet Explorer 和 Edge 以外兼容所有浏览器

![图片](https://uploader.shimo.im/f/pcJMlN42ReoSySVE!thumbnail)

1. **5.1面临挑战**人工参与过多
2. 成本过高
3. 耗时过长
4. 过于复杂

![图片](https://uploader.shimo.im/f/3QwAbYPGgn1RaQ8t!thumbnail)

**5.2优势**![图片](https://uploader.shimo.im/f/qu9VF8I7E0VEiQEs!thumbnail)

* 通过将每个人连接到翻译流程，消除不连贯。
* 使用现代化项目管理界面和持续的本地化，优化各种流程。
* 利用针对您的内容训练的业界首屈一指的神经机器翻译，确保出众的质量。
* 使用集中化工作流、报告和状态监视，做出更好的决策。
* 使用 Hai（SDL 的语言人工智能）自动分析内容，提高生产效率。
* 与多应用进行合作

![图片](https://uploader.shimo.im/f/kf3XwnscZ39B4auQ!thumbnail)

* 在安全的云环境中进行审校，让您安心无忧。
* 可以集成在word插件中，直接对文件进行翻译

![图片](https://uploader.shimo.im/f/62HW2ctHOymKKnfi!thumbnail)

**5.3涉及部门****企业：生产内容，分发翻译任务**

* 参与者：客户服务部门、本地化部门、内部译员、供应商
* 与SDL Language Cloud 翻译管理交互的情景：
  * 使用包含项目的预定义模板：工作流程，作业，语言资源
  * 提交文件进行翻译
  * 批准翻译报价
  * 下载翻译文件
  * 咨询项目统计数据和报告

**LSP：接收本地化项目**

* 参与者：顾客、LSP、内部译员、外部供应商（自由译员/其他LSP）
* 与SDL Language Cloud 翻译管理交互的情景：
  * 管理本地化过程中的参与者：项目经理，供应商，工程师，翻译，审校
  * 为每个企业业务（客户）设置项目先决条件：工作流程，定价模型，翻译引擎，项目模板
  * 代表企业（客户）创建翻译项目
  * 审校、调整通过SDL Language Cloud客户门户收到的翻译项目
  * 计划任务，监视项目任务完成情况：翻译，审查，客户审查，项目计划，DTP……

**自由译员：提供翻译、审校DTP等服务**

* 与SDL Language Cloud 翻译管理交互的情景：
  * 通过SDL Trados Studio或SDL Online Editor工作
  * 在项目组中管理语言资源
1. **5.4参与角色**管理者
2. 项目经理
3. 语言学家（翻译/审校）
4. 客户
5. 客户审校
6. 术语专家
7. 供应商
8. 工程师

每个用户项目工作流程中都会有自己的角色。不同的角色有不同的权限，完成不同的任务。![图片](https://uploader.shimo.im/f/JQRuqcqWgurLEV2b!thumbnail)![图片](https://uploader.shimo.im/f/uYijETKmuWeoSWZT!thumbnail)

* **管理者：**

![图片](https://uploader.shimo.im/f/kOqC13AnWqImF7Ut!thumbnail)

Dashboard

1. 对用户成员、客户成员、供应商用户的邀请、删除；
2. 创建新工作组，增加、删除组内成员
3. 为所有成员规定角色
4. 设置、更改定价模型：（Pricing models are the basis on which quotes or** costs are determined**. They are a **part of project templates** and you can associate them with customers or vendors.）
5. 管理语言资源：
  1. Language Cloud TMs -- Translation memories (TMs) 
  2. Language Cloud termbases
  3. Language Cloud MT：SDL开发的自动翻译资源
  4. Language Cloud translation engines：在SDL Language Cloud 翻译管理中，用户可以将所有翻译资源聚合到一个叫 translation engines（翻译引擎）的实体中。这样，如果下次新项目也使用这种语言，就可以轻松复用，不必再次冲重新选择相同的语言资源。
6. 设置工作流（workflow）并分配任务。（工作流--执行哪些任务以及执行顺序。 part of project templates）
7. 文件类型：限定翻译文件类类型，创建文件类型配置【import/export】

注：不支持的文件类型也可以进行翻译（在拥有engineer的时候）

8. 创建、编辑、删除项目模板（文件类型、语言资源、工作流、价格模型）

![图片](https://uploader.shimo.im/f/aLcHGGCDCoxYaHO3!thumbnail)

Dashboard 概念图

* **项目经理**（与管理者重合的部分不再赘述，下面只列出特色部分）
1. 创建、删除项目。项目来源有两个：1）直接在翻译团里平台创建 2）客户通过SDL Language Cloud Customer Portal用户门户提交项目
2. 项目计划：管理工作流；指定ddl；查看客户/供应商报价
3. 跟踪工作流程进展：dashboard：stages / tasks
4. 修改项目设置、文件类型
5. 查看、下载项目报告报告：1）项目层面报告 2）系统层面报告 
6. 处理错误
7. 项目交付：1）最终检查 2）下载翻译文件 
* 客户 -- SDL Language Cloud Customer Portal用户门户提交项目
1. 项目创建、跟踪
2. 查看报价
3. 下载项目文件
4. 查看dashboard
* 译员 -- SDL Trados Studio / SDL online editor
1. 任务云端互联
2. 下载上传文件（sdlxliff等）
3. 查看客户审校评价 

![图片](https://uploader.shimo.im/f/8727aJvnb0Nk3H4J!thumbnail)

Language Cloud in Trados

* 审校者 -- SDL Trados Studio / SDL online editor 几乎与译员相同
* 客户审校 -- SDL Language Cloud Customer Portal /  SDL Online Editor
1. 对团队给的翻译内容进行审校
2. 查看任务信息，例如：

![图片](https://uploader.shimo.im/f/L37E64RA2rAYAclq!thumbnail)

* 供应商（ 第三方 LSP可以承担项目当中部分翻译工作）：与译员相似
1. 查看报价
2. 下载、提交翻译包
3. 下载、提交翻译文件
4. 查看客户审校反馈
* 工程师：一般是格式转换+DTP工作
1. 下载、上传DTP文件
2. 处理不支持的文件格式（将不支持的格式转化为翻译流程支持的格式再上传到工作流中）
* 术语专家：
1. 创建术语库
2. 从SDL MultiTerm中上传术语至SDL Language Cloud
3. 术语库管理：1）编辑/增加库外连接等 2）生成术语模板
4. 分享术语库连接
5. 管理术语库权限

![图片](https://uploader.shimo.im/f/WtFdRE6dGTwEeiLf!thumbnail)

Language Cloud Termbase


**6 BeGlobal****6.1BeGlobal产品分析****6.1.1 使用需求**SDL BeGlobal是一种企业级云机器翻译产品，它的适用场景与需求，应当是针对相比人工翻译、通用NMT或是多种多样的在线翻译引擎而言的。当翻译项目的场景是内容密集型业务流程，或是有完整解决方案，质量要求高、内容安全性等需求，使用BeGlobal就十分必要：![图片](https://uploader.shimo.im/f/Mt4mbYUDu5L4GjR3!thumbnail)

在这些场景中，SDL BeGlobal能够满足时间、成本、正确度、安全性等针对性要求。客户往往通过多种渠道与品牌展开互动，并将互动长期延续下去。随着全球内容需求量的爆炸式增长，所有内容都交给人工译员，不一定合乎时间和成本效益。BeGlobal作为SDL 机器翻译，可以提供准确、安全的翻译结果用于这些活动。总体来看，Edge-Cloud架构，能使组织能够对内容密集型业务流程，如内部通信、电子取证、分析和客户反馈等进行快速翻译。

NMT代码比起SMT代码更紧凑复杂，一些开源项目用几百行代码就可以创建一个能够通过数据进行学习的翻译工具。然而，企业解决方案的需求远远超过了几百行代码。可扩展、可集成和通过定制提升质量，是通用项目难以实现的。此外，一些问题细节例如，通用 NMT 难以很好地处理文档格式，而保持文档格式是任何想要维护文档完整性的组织的关键要求；通用开源 NMT 技术有时还会重复翻译一些词，质量有待提高。

此外，BeGlobal可以提供全面的审核性，确保用户内容安全与可控，它仅仅满足用户需求，不会公开或用于其他任何用途。通过安全架构支持客户端之间的数据物理分离，保持内容和通信机密和安全。

具体使用场景举例：

• 安全的沟通和协作

• 实时聊天

• 技术支持社区和论坛

• 电子商务门户网站

• 在线旅游网站

• 客户洞察和情感分析

• 电子取证和管治

• 保险理赔

• 电子化学习

• 执法、情报和国防

**6.1.2 产品简介**SDL BeGlobal（或新名称SDL Machine Translation Cloud）是企业级的云机器翻译产品。通过简单的界面，即时翻译各种形式的内容，帮助专业译员、内容营销人员和所有其他有需要的人员，通过一种简单、安全的方式来突破语言障碍。SDL 机器翻译采用独特的 Edge-Cloud 架构，提供真正灵活的部署选项。BeGlobal与SDL Machine Translation Edge是互为补充的，前者在云端，后者则在专用的 IT 基础设施内运行，带来同样的高级神经机器翻译功能。

**6.1.3 产品特点**• 准确性

SDL BeGlobal改善了准确性和流畅性，旨在适应其培训数据的质量和数量，从而提高学习效率。

• 安全性

提供全面的审核性，确保用户内容安全与可控，仅仅满足用户需求，不会公开或用于其他任何用途。

• 易用性

界面现代化，易于使用，可兼容现有工作流，支持常用的文件格式。

• 灵活性

BeGlobal产品具有很强的灵活性，能够实现无缝集成。它与 SDL 语言技术的开箱即用集成，包括 SDL WorldServer、SDL Trados Studio 和SDL Language Cloud；提供与众多第三方应用程序的现成集成，例如Microsoft Office 插件在办公应用程序中提供易于使用的即时翻译工具，而网页浏览器插件可以用于帮助翻译内网站点的内容；全面的 REST API 使用户可以通过业务应用程序直接连接 SDL BeGlobal；通过独特的 Edge-Cloud 架构与 SDL Machine Translation Edge 协作，提供灵活的部署选项和独特的功能。例如，在 Edge 内训练 Adaptable Language Pairs，然后将其部署到BeGlobal中，以获得独特且安全的适应性。

**6.1.4 产品功能**![图片](https://uploader.shimo.im/f/VF6qt4jzViLRSoqi!thumbnail)

参考资料：

BeGlobal官方白皮书

https://community.sdl.com/product-groups/machine_translation/

[https://docs.sdl.com/LiveContent/web/pub.xql?action=home&pub=SDL%20BeGlobal%20Online%20Help-v1&lang=en-US#docid=GUID-62760FBD-D446-44E3-85B7-CBE7BA2B447E&addHistory=true&query=&scope=&tid=&filename=GUID-06759C71-53ED-41F9-93AA-483860BE8FA2.xml&resource=&inner_id=&toc=false&eventType=lcContent.loadDocGUID-62760FBD-D446-44E3-85B7-CBE7BA2B447E](https://docs.sdl.com/LiveContent/web/pub.xql?action=home&pub=SDL%20BeGlobal%20Online%20Help-v1&lang=en-US#docid=GUID-62760FBD-D446-44E3-85B7-CBE7BA2B447E&addHistory=true&query=&scope=&tid=&filename=GUID-06759C71-53ED-41F9-93AA-483860BE8FA2.xml&resource=&inner_id=&toc=false&eventType=lcContent.loadDocGUID-62760FBD-D446-44E3-85B7-CBE7BA2B447E)

**7 MultiTerm****7.1 使用需求**术语可以是任何词语，例如产品名、营销广告语等.对于翻译和本地化项目而言，术语作为描述产品、服务或行业用语的词语或短语，通常会推动竞争性差异。大多数公司越来越多地使用与行业或组织相关的特定词语，因此需要对这些词语进行准确的存储、共享和翻译。

对于具体翻译和本地化工作，需要保持术语的正确性、一致性、无歧义，与实践紧密联系，注重规则与用法，产出高质量的内容；对于翻译与本地化项目整体而言，术语可以来自于译员、术语专家，也可以来自工程师、市场营销人员等等，需要重视同步与访问权限问题，使用术语管理软件可以满足这些层次的需求。

**7.2 产品简介**SDL MultiTerm 提供一个中心位置以存储和管理多语言术语。通过向涉及术语应用的所有人员，例如工程师、市场营销人员、译员和术语专家提供访问权限，确保从原文到译文保持一致的高质量内容。MultiTerm 可以存储公司术语和行业术语，并在企业中进行共享，包括分布式环境中的术语，目前的市场占有率非常高。

**7.3 产品功能**MultiTerm常用的基础功能有：

1. 创建术语库

具体过程为：术语库定义-术语库名称-命名-索引-选择语言-添加说明字段-条目结构。说明性字段指的是对术语库的条目或者术语进行说明的信息，如编号（编号属性）、释义（文本属性）、图片（多媒体属性）；条目结构指的是每个说明性字段的结构层，包括entry level 条目层，用于保存当前术语条目的说明信息，是对整个术语条目都有效的最高层级，index level 索引层，一个语言字段的说明信息，term level术语层，保存一个术语单词或词组某一方面的特定信息，为最小层级。

2. 转换术语库文件

借助术语转换软件MultiTerm Convert，可以实现excel转sdltb格式的术语库。注意这种转换不是直接转换，而是通过Convert转换生成三个中间文件：术语库定义文件XDT， 用来保存术语数据的结构信息；MultiTerm XML格式的文件，用来保存术语数据本身；log日志。

3）检索功能

普通搜索用于搜索以此搜索格式开头的术语，检索与当前搜索的检索词相同的词以及以这个检索词开头的词；模糊搜索用于搜索与此搜索格式类似的词；全文检索只会去检索那些包含了检索词的词。此外，默认为全文搜索，可以使用通配符，*多个字符，?任意单个字符等等。搜索方法分为分级模式，优先检索默认的第一个术语库；并行模式，多个术语库进行检索后，搜索结果混在一起，按照首字母顺序进行排序，显示在结果列表中；串行模式，将多个术语库的检索结果按照术语库的搜索先后显示在结果列表中。

除了这些常用功能，MultiTerm还能实现很多其他功能，大致结构整理如下：

![图片](https://uploader.shimo.im/f/9wNf31J9Ijrv9uwE!thumbnail)

**7.4 产品作用**![图片](https://uploader.shimo.im/f/Jd65YxuxLnAFKRAA!thumbnail)

基于以上具体功能，MultiTerm可以实现权限问题和集中访问、改善品牌一致性和多语言内容质量、降低成本并提高工作效率。

1）权限问题和集中访问

让不同部门中的其他内容创建者或其他译员可以对最新术语进行集中访问和共享，这种做法的管理难度很大。SDL MultiTerm可以让每个人从一个集中位置访问与其相关的术语；客户端/服务器和 Web 技术允许随时访问术语，译员和内容创建者从而能随时访问最新术语。管理集中式术语数据库的安全性十分重要，以便术语可保持更新，MultiTerm 提供全面的访问权管理，允许不同用户对术语库拥有相应的访问权限；借助基于角色的安全管理，可创建经核准的术语工作流，其中，内容创建者可建议新术语，然后由一组选定的术语库所有者核准。此外，MultiTerm支持多种文件格式，可以将已有的术语资产自动转换并导入。

2）改善品牌一致性和内容的质量

在不同市场以任意语言与客户的沟通中，产品名、搜索引擎关键字和法律用语等术语必须保持一致。MultiTerm 集成其他应用程序，可满足在内容创建和翻译过程中保持品牌一致性的需要。使用SDL Trados Studio中的多语言术语实时验证功能，优化了翻译流程。译员可在熟悉的环境中自动应用、编辑或添加术语，有助于提高翻译流程的效率，改善翻译内容的质量。这适合任意翻译项目，因为MultiTerm 完全基于 Unicode，能支持全世界各种语言、不限数量的术语。

3）降低成本并提高工作效率

SDL MultiTerm可帮助提高工作效率。提供强大的搜索功能，像在搜索引擎中进行搜索一样快速地找到要查找的术语；可以从多个术语库中搜索术语，有助于在进行多个翻译项目时提高译员的效率；可以在术语中嵌入或链接数字媒体文件（图像、声音或视频），还可以提供术语定义或其他术语或网站的链接。总的来说，MultiTerm提供丰富的信息和可定制性，研究术语方面节省的时间可用到QA和审校流程上，加快创作和翻译过程，从而降低成本。

**7.5 产品关系****7.5.1 产品集成**• 可以在SDL Trados Studio中自动应用、编辑或添加术语

• 与SDL Translation Management System和软件本地化工具SDL Passolo集成

• 执行术语共享项目的团队可以使用GroupShare的SDL MultiTerm Server进行协作。协作中心让团队能够访问术语库，并集中进行访问和权限管理。

• SDL MultiTerm Workflow可以帮助将术语的使用扩展到翻译部门之外，提供了一个工作流解决方案，用于解决请求、投票、审批、更改和翻译术语流程中出现的问题。

**7.5.2 工作流解决方案**SDL MultiTerm Workflow 是一个简单快速的术语查找工具，提供了一个工作流解决方案，团队可以用更简便的方式查看复杂的术语，这个概念是建立在SDL MultiTerm术语库基础之上的。它可以改善处理术语的业务方式，依托于 SDL MultiTerm 术语库提供更多功能。

• 术语工作流概念图表

![图片](https://uploader.shimo.im/f/4UBDpCac2T99cCg6!thumbnail)

通过实施全面的工作流来管理术语生命周期，包括术语请求、审核、讨论、定义、翻译及更改。集中控制术语库数据的所有相关流程，确保所有信息经过准确调查、审批和更新。工作流基于特定语言实施，参与者以组为单位，不同的小组根据主题、工作流类型或语言在工作流中手动或自动分配任务。

• 应用概念图表

概念图表以图解方式诠释单个术语库条目之间的关联，有些像叙词表。用户可以即时了解与当前条目存在关联的其他概念，不仅在语言上，还在逻辑或语义上，可视化。

![图片](https://uploader.shimo.im/f/JhewQRSFpO4pmFR8!thumbnail)

• 多种搜索方法

提供多种搜索方法，具体采用可以根据使用人员、工作环境来确定。SDL MultiTerm Workflow Client可以让个人从任何 Windows应用程序中搜索选中的文本，无需登录单独的应用程序，输入搜索字符串；SDL MultiTerm Workflow Web针对企业形像进行定制，并无缝集成至内联网或互联网；SDL MultiTerm Workflow Mobile 通过智能手机或平板电脑将用户与术语库连接，适用于偶尔参与工作流（例如，对术语建议进行表决）的人。

SDL MultiTerm Workflow Web 中的搜索结果：

![图片](https://uploader.shimo.im/f/hY44t8Da3avir6AR!thumbnail)

参考资料：

MultiTerm官方白皮书

MultiTerm Workflow官方白皮书

翻转课堂MultiTerm使用介绍

[https://community.sdl.com/product-groups/translationproductivity/f/multiterm](https://community.sdl.com/product-groups/translationproductivity/f/multiterm)


**8 SDL WorldServer****8.1简介**SDL WorldServer是一款用于集中管理、自动化和控制大量的翻译项目的管理系统软件，采用服务器与客户机形式，企业可在服务器端管理需要本地化的内容和翻译记忆库，翻译供应商则使用客户端完成文字翻译，能够简化并加快内容从网站到文档到软件的本地化流程，降低翻译成本，提升翻译质量和流程效率。

SDL WorldServer和SDL Trados Studio是翻译供应链中使用最广泛的两个产品，它们之间的关联为译员和项目经理带来了统一的分段、定界、成本计算和重用，提高了供应链效率。

**8.2功能特性及优势****8.2.1集中语言技术**SDL WorldServer将语言技术集中到强大且可扩展的服务器架构中，与SDL Trados Studio兼容，保证了企业内的专职译员可以在同一平台下继续使用习惯的专业性工具。同时，集中翻译记忆库(TM)和术语，可导入导出标准格式，简化多语言内容的重复使用，降低成本并提高翻译质量。

**8.2.2内容集成与协作**拥有各种内容连接器和灵活的资产集成系统，与许多内容系统高效连接。拥有客户上传内容的专用网站门户界面，和捕获本地存储内容的系统，便于协作。

**8.2.3项目管理流程自动化**SDLWorldServer的核心是基于规则的流程自动化引擎，企业可以按照本地化团队结构和具体业务需求创建定制工作流，实现业务流程自动化，减少人力追踪，如将营销材料和硬性技术文档的翻译流程设置得各不相同；针对项目相关内容发布通知，改善合作。

**8.2.4项目集中管控**SDL WorldServer便于企业集中管控翻译项目，帮助企业设计完整的翻译发包管理流程，所有部门均在同一平台上执行相同的翻译项目操作，包括文档的预翻译，供应商询价/比价，翻译时间控制，翻译沟通管理，翻译质量追踪等。企业从WorldServer直接获取包括费用，时间，质量等各种维度的报表，为企业本地化业务决策提供依据。

**8.2.5可拓展**模块化的SDL WorldServer架构可提供强大且可扩展（如业务系统和机器翻译引擎）的翻译管理解决方案，自带免费客户端，适合进行现场配置、软件即服务(SaaS)或托管部署。企业可以快速入门，并根据不断变化的需求过渡到托管或现场配置。并支持组件的二次开发（例如Filter,Automatic Action,Adatper）

**8.2.6可定制**WorldServer利用自动化流程引擎及其它各类相关模块，配置出完全适用于客户实际业务操作环境的翻译项目管理平台，各业务部门通过该平台向翻译管理部门提交翻译申请，查看翻译进度，接受翻译结果。翻译管理部门利用该平台自动创建项目，分派任务，重复利用语料资产，与自动翻译引擎和翻译工具集成，提高管理水平，促进翻译效率。

![图片](https://uploader.shimo.im/f/38j5ssLdw0nR1cTU!thumbnail)

**与传统本地化翻译过程相比，SDL WorldServer的优势在于**：

1. 可以直接和内容管理系统CMS接口，获取客户撰写的原文内容，并根据内部维护的TM自动对文件进行预处理；
2. 翻译服务供应商LSP在WorldServer里进行翻译编辑，无需前期后期处理，无需维护TM；
3. 完成后WorldServer会自动管理本地化之后的内容
1. **8.3使用情况**翻译项目可以从门户网站集中启动，也可以由连接的系统(如内容管理系统、ERP等)自动启动，WorldServer为所有标准格式、文档类型和系统提供了接口；
2. WorldServer执行自动化步骤，如文件检查、转换、分析；
3. 企业内部员工使用客户端进行工作；
4. 没有集成到公司网络中的项目工作人员，可以通过Web浏览器进行翻译、检查或批准，在线使用Trados功能；
5. LSP或自由职业者可以下载项目包并直接在SDL Trados Studio中使用；
6. 翻译完成后，工作流自动继续，系统将项目引导到下一个人，并自动执行数据库更新和交付等步骤。

**9 SDL Passolo（用于本地化）****9.1简介**Passolo是一款功能强大的软件本地化工具，支持所有常见的开发环境，如.Net、Android或Java，支持大量难以解析的格式，如CSV，特殊文本或XML格式等，支持以Visual C++、Borland C++及Delphi语言编写的软件（.exe、.dll、.ocx）的本地化，结合了Visual Localize和Language Localizator二者的功能，并且界面简洁、布局合理性能稳定、易于使用。Passolo不需要用户进行专门训练或丰富编程经验，能够识别并自动纠正本地化的过程中可能发生的许多错误。

Passolo可以以单独的应用程序运行或与Trados和MultiTerm等其它SDL产品集成使用，改进人工和自动化本地化工作流。

**9.2功能特性****9.2.1支持多种格式&语言**Passolo作为市场上流行的软件本地化工具，支持多种文件格式：可执行文件，资源文件和基于XML的文件。文本可以被翻译为多种语言，包括东欧语言、亚洲语系以及书写方式从右向左的语言，比如希伯来语和阿拉伯语。

**9.2.2操作简单**Passolo使软件本地化工作可以在不接触源代码情况下完成。用户无需经历大量培训，也不需要大量编程经验。并且通过自动版本控制、适当权限及更好的流程管理，可以实现代码保护，防止源代码在翻译过程中出错。

**9.2.3高易用性**Passolo能通过模拟翻译功能在实际翻译之前检查软件是否适合被本地化，保证翻译数据编译、交换和处理的易用性。伪翻译”功能使开发人员能够测试软件，并在早期阶段避免硬编码文本等全球化错误，以支持国际化项目。

**9.2.4强大的项目管理与集成**创建项目后，Passolo会在多语言项目数据库中保存源文本、译文、修改的布局、文件备注和其他数据。多个用户可同时在“多用户”模式下处理同一个项目，而且外部译员可以下载免费版软件，并编辑通过完整版创建的翻译包。项目经理也可以将项目导出为SDLXLIFF文件，或利用GroupShare插件，将项目直接发布至SDL Trados GroupShare。这提供了灵活的工作方式，除了Passolo，译员还可选择在SDL Trados Studio或GroupShare在线编辑器中开展工作。

**9.2.5可视化编辑模式**Passolo支持可视化，使译员在直观的编辑环境中工作。所见即所得(WYSIWYG)编辑器允许在同一视窗内查看软件菜单及对话框，来简化用户界面处理，且处理过程非常安全，绝不会意外删除或改变现有的元素结构。同时，内置图像编辑器，可以直接对图标、位图等图片资源进行修改

**9.2.6使用机器翻译加快翻译速度**Passolo与SDL Language Cloud、Google Translate和MicrosoftTranslator无缝集成。Language Cloud使译员能够在Passolo编辑环境中直接利用优质的机器翻译服务。

**9.2.7翻译资源高效复用**Passolo利用内部翻译记忆技术，与SDL Trados Studio、SDL MultiTerm和SDL翻译管理系统等紧密集成，可访问现有翻译资产及术语词汇表，重用翻译资源。即使程序没有用Passolo翻译，它也能使用其中的文本进行新项目的自动翻译。模糊匹配技术能同时搜索类似和精确匹配的文本，从而能提高翻译效率并缩短翻译周期。

**9.2.8有效的质量检查**Passolo利用丰富的质量控件、自动化工作流及现代翻译管理工具来进行用户界面、技术一致性、术语一致性等多方面检查，自动识别截断或重复文本，防止本地化过程中的潜在错误。

**9.2.9基于项目的实时更新整合**SDL Passolo Collaboration edition中，如果软件版本有更新，“更新”功能会将新软件文件的内容与项目数据库进行比较，并将修改过的新文本传送到项目中并更新项目状态。现有翻译文本和布局均保持原样，译员只需处理更新后的文本，以减轻本地化经理及译员的工作量。

**9.2.10加快软件本地化速度**Passolo支持Scrum等敏捷开发流程，可以在软件最终版本产生之前就可以开始本地化工作。可视化环境易于使用，项目管理工作流敏捷友好，此外能够管理软件本地化与译文，同步推进编程和QA冲刺，加快软件本地化流程。利用GroupShare插件，可将Passolo项目直接发布到GroupShare。便于项目经理快速分配用户，多位用户可在GroupShare在线编辑器中合作开展项目，快速、敏捷地进行翻译和审校。

**9.2.11支持定制和集成**企业可以通过开发使用SDL Passolo软件开发套件的插件或下载第三方插件，构建自己软件本地化环境。SDL Passolo还可通过命令行自动运行，并集成到版本服务器环境中。并且，使用整合的IDE，客户可以开发他们自己的本地化解决方案以适应特定的软件需求。

**9.3工作流程**![图片](https://uploader.shimo.im/f/LIM0iHYxffNxDkcU!thumbnail)

* **9.4支持格式**可执行Windows程序（EXE、DLL）
* 资源文件(RC)
* Microsoft.NET程序集（包括WPF和Silverlight）
* 资源文件(RESX)
* Delphi二进制文件
* Java资源（PROPERTIES、JAVA、CLASS）
* Java项目（JAR、WAR）
* VB6（FRM、VBP）
* Qt(TS)
* 可移植对象文件(PO)
* JSON和RESJSON
* Microsoft安装程序（MSI、ISM）
* ODBC数据库和手机软件（iPhone、Android、Windows Mobile）
* XML、XLIFF、HTML、CHM、YAML、文本文件、Excel等

**9.5不同版本****Professional版本**

在构建服务器上使用的个人用户版本，供开发团队或本地化工程师使用。如果翻译公司使用Passolo个人版本，本地化经理可以为该翻译公司导出翻译包（部分项目）。Passolo字符串列表还可导出为SDLXLIFF格式，以便在Studio完成翻译，或利用可选的GroupShare插件，直接发布至GroupShare。

**Team版本**

供本地化经理使用的个人用户版本。使用免费Translator版本的用户可以编辑通过Team版本创建的翻译包。这意味着只需使用一个Team版本许可证（还包含修改和测试对话框的功能），即可将整个项目发送给外部译员。Passolo字符串列表还可导出为SDLXLIFF格式，以便在Studio完成翻译，或利用可选的GroupShare插件，直接发布至GroupShare。

**Collaboration版本**

与Team版本具有相同功能的个人用户版本，主要区别在于翻译公司和译员可以通过FTP服务器或Box云存储平台自动同步翻译包。包含免费的GroupShare附件，即Passolo字符串列表可直接发布至GroupShare，译员能够自行选择是在Studio还是在GroupShare在线编辑器中开展工作。

**Translator版本**

免费，可编辑通过Team版本或Collaboration版本创建的翻译包。它包含所有翻译和生产功能、视觉定位功能，并可紧密集成所有SDL翻译解决方案。Translator版本没有用于分析源文件或创建目标文件的项目管理功能。

1. **9.6运行要求**兼容Microsoft Windows的计算机（包括操作系统为Windows的基于Intel的Apple Mac计算机），同时具有1千兆赫(GHz)或更快频率、32位(x86)或64位(x64)处理器、4 GB RAM（32位）或8 GB RAM（64位）
2. 屏幕分辨率为1280x1024像素和256色以上
3. 4 GB可用硬盘空间，用于运行Passolo
4. 2.5 GB可用硬盘空间，用于运行Passolo安装程序

为使64位操作系统发挥最佳性能，建议采用最新的双核或多核技术处理器、8GB RAM及高于1280x1024的屏幕分辨率。

**操作系统**

Passolo运行在最新版本的Windows 10、Windows 8.1和最新服务打包版本的Windows 7上。还支持Windows Server 2016、Windows Server 2012 R2和Windows Server 2008 R2。

Passolo不支持早期的操作系统，如Windows Vista、Windows XP、Windows

2000、Windows NT、Windows 98和Windows Server 2003。

**9.7具体操作****创建项目**

打开SDL Passolo后，可以通过Home菜单下的项目按钮新建项目或打开一个项目

![图片](https://assets-cdn.shimo.im/docs/assets/shape_table_error.png)![图片](https://uploader.shimo.im/f/NyWql4yKb3Bvw11E!thumbnail)

点击新建按钮后，输入项目名称，选取存储路径，添加要处理的文件（这里以Passolo2018Demo.exe为例），选择“WIN32可执行文件”作为文件类型,选择源语言英语(美国)并确认设置.

![图片](https://uploader.shimo.im/f/IfbDSW5ihsKCcAmS!thumbnail)

切换到Target Languages(目标语言)选项卡并选择Add Language(添加语言)以指定此项目的目标语言，此处以简体中文为例，可以继续添加其他目标语言，如法语和西班牙语。

![图片](https://uploader.shimo.im/f/qiVprXRFs4IucLTu!thumbnail)

点击确认创建项目。在随后打开的项目窗口中，选定的程序将显示为源文件，指定的目标语言将显示为目标文件。

![图片](https://uploader.shimo.im/f/m13x5raSYboCt0fM!thumbnail)

**创建和编辑源字符串列表**

源字符串列表（the source string list）包含正在翻译的程序的所有文本资源。通过编辑，可以优化后续本地化过程。如将出于技术原因不翻译的资源标记为只读，或者直接隐藏。此外还可以向字符串添加注释，以帮助指定每个条目翻译的最大长度(More标签)。

只读和隐藏设置：在string list中，单击选择要设置的字符串，激活只读复选框，并添加必要注释。

![图片](https://uploader.shimo.im/f/qQ4TT6W6sBKV6iJB!thumbnail)

**创建并编辑翻译列表**

双击项目窗口右侧的目标文件,点击是,创建翻译字符串列表.

随后显示的翻译列表将包含Passolo2018Demo.exe源文件中标记为“English（US）”列中的所有文本资源，以及标记为“Chinese(.NET Simplified）”列中要翻译的所有字符串：菜单项、对话框字符串等。由于尚未翻译任何资源，因此所有条目均显示为红色。

此时，无法更改的字符串将显示为灰色，被标记为隐藏的字符串则不会显示。

注:1. 翻译字符串列表可以导出供外部翻译人员翻译.

![图片](https://uploader.shimo.im/f/BHkMaptvsXNDEpWN!thumbnail)

2. Passolo可将字符串列表直接发布至Groupshare便于协作，添加Groupshare插件：

![图片](https://uploader.shimo.im/f/fTIUFbJsraqpnqpq!thumbnail)

**预翻译**

创建好项目和字符串列表后，可以通过Home菜单下的Pre-Translation进行预翻译，Passolo会自动搜索翻译记忆库和Groupshare上的内容，完全匹配的内容显示为绿色，并会出现对话框提示是否应用完全匹配的翻译到其他相同字符串，点击确认后，相应字符串显示自动翻译标识，为绿色。

![图片](https://uploader.shimo.im/f/lnTnBAai9glHdu3A!thumbnail)

预翻译可以进行设置，界面跟Studio基本一致。要匹配的翻译记忆来源如下图，可自行设置和添加，此外还可以在左侧列表进行模糊匹配等设置。

![图片](https://uploader.shimo.im/f/0QVL0m1rwVEmelNc!thumbnail)

Passolo同样支持机器翻译，可通过SDL Language Cloud提供的机器翻译进行。可在选项 – 模糊匹配 – Translation Add-in 中启用Language Cloud，之后在翻译过程中将收到相关翻译建议。

![图片](https://uploader.shimo.im/f/byFjNfxI3BpUf2oc!thumbnail)

Passolo支持与外部术语库的链接，可通过添加Add-in进行设置

![图片](https://uploader.shimo.im/f/al5nk7OCPSvt0ADX!thumbnail)

**导出字符串供外部人员翻译**

Passolo支持导出字符串供外部翻译人员翻译，可在Project菜单选择Export，选择合适的导出格式。翻译结束后通过Import导入按钮来合并外部翻译。

![图片](https://uploader.shimo.im/f/0fMzYP3btP35bQV5!thumbnail)

**质量检查**

Passolo支持直接的质检功能，可对译文的拼写等方面进行检查，并逐条提示修改。

![图片](https://uploader.shimo.im/f/C6uECdQkuCGqlgih!thumbnail)

**生成本地化软件**

翻译及质检结束后，可以通过Home菜单下的生成按钮直接生成需要格式的本地化后的软件。

![图片](https://uploader.shimo.im/f/FOF9uXqI0kMh6nY7!thumbnail)

**存储**

Passolo Collaboration版本支持Box存储平台，可作为FTP或SFTP的备选存储方案，在云与团队之间实时同步，同时保证项目内容的机密性。

![图片](https://uploader.shimo.im/f/GWPaKmp4fwWxw8G0!thumbnail)

**10 SDL Xopus**

SDL Xopus 属于 SDL tridion DX 下一个软件

SDL Xopus 是一个基于**浏览器的强大编辑器**，让所有人都能轻而易举地创建和编辑结构化内容。 它旨在为非技术型内容创作者、审校者和贡献者**简化 XML 的复杂性**，同时保留了 XML 的强大能力。

无需下载复杂编辑工具客户端，有时下载+学习成本会大于使用的便利性避免长时间下载安装的困扰，减少学习成本

直接在XML结构化内容文档中进行编辑

* **10.1优势**直观的 WYSIWYG 编辑
  * 所见即所得
  * Ribbon Toolbar
* 用户友好界面 
* 轻松的集成和定制 
  * 将模式元素轻松映射到 UI 及行为。 无论您要配置 SDL Xopus 以保存文档，构建自定义用户界面或定制复杂的数据查询，Javascript API 都支持高水平定制。
* 丰富的复制和粘贴 ：
  * 仍在使用 Microsoft Word 处理旧有内容？ SDL Xopus 中的文档结构通过 XML 模式进行控制，因此，仅会复制您所需的结构，其他所有格式信息将被移除以便清晰分隔内容和样式。
* 支持现代的 Web 浏览器 
  * 完全基于浏览器。支持Internet Explorer®, Google Chrome™ and Mozilla Firefox®.
  * 易于使用、基于浏览器的界面可降低编写内容的门槛，从而确保组织中有更多人员做出贡献。
* 预验证编辑 
  * 在 UI 中禁用可使文档无效的所有操作，这样，您将无需修复任何验证问题或保存无效的文档。 这种程度的控制能力可确保您以安全的方式允许内容贡献人员访问您的结构化内容。
* 全面支持行业 XML 标准并可针对其他任意 XML 模式进行定制
  * 如DITA，开箱即用

**10.2 Xopus pipeline 整体结构**![图片](https://uploader.shimo.im/f/z8rPxklyOJEquKGy!thumbnail)

Xopus附带了一组示例架构和样式表文件（ sample schema and stylesheet files）供用户在项目中使用。同时也允许使用自己的XML schema，通过使用schema，stylesheet和JavaScript，满足结构化写作需要。

注：

* XSD : XML Schema Definition，XSD；比DTD更加强大；描述 XML 文档的结构。
  * 定义可出现在文档中的元素
  * 定义可出现在文档中的属性
  * 定义哪个元素是子元素
  * 定义子元素的次序
  * 定义子元素的数目
  * 定义元素是否为空，或者是否可包含文本
  * 定义元素和属性的数据类型
  * 定义元素和属性的默认值以及固定值
* XSLT：扩展样式表语言（EXtensible Stylesheet Language），一种用于转换 XML 文档的语言。XSLT 用于将一种 XML 文档转换为另外一种 XML 文档，或者可被浏览器识别的其他类型的文档，比如 HTML 和 XHTML。通常，XSLT 是通过把每个 XML 元素转换为 (X)HTML 元素来完成这项工作的。

**10.3主界面**![图片](https://uploader.shimo.im/f/uABYPi8pWw0rhHCU!thumbnail)

主界面大概分四个区域，代码区和效果区都可以通过手动按钮进行最大化：

* **代码区**
  * 支持XML/XSD/XSL/Xopus Config/Javascript/CSS几个不同的视图，可供熟悉其中涵盖语言的用户进行修改
* **中间工具栏**
  * 编辑XML界面中各种元素的工具
* **效果区**
  * 拥有多种视图模式，可以即时看到用户修改，以及发布之后的成品效果
* **上下文面板**（根据选择的按钮显示不同内容，可关闭） 
  * 例如属性面板：允许用户查看和编辑属性，当用户单击工具栏上的“ 属性”图标时显示 。

**10.4工具栏按钮****眼睛按钮：**

![图片](https://uploader.shimo.im/f/iwovvgljQGQ6X20R!thumbnail)

* **控制视图**：1）所见即所得 2）标记 3）XML视图 【注：5.4.4版本的Demo中只有1）和3）两种视图】
  * 注：开启XML视图时会与代码界面的XML代码一致，但格式有所区别

![图片](https://uploader.shimo.im/f/IUKPUudLX0PM4Ean!thumbnail)

* **界面语言设置**
* **关于Xopus：**查看Xopus版本信息

显示修改按钮：将打开修改面板，记录用户每次的修改。

![图片](https://uploader.shimo.im/f/7sa8BL7BN3nmE3X7!thumbnail)

![图片](https://uploader.shimo.im/f/jMTbjlWYbvqiGzk1!thumbnail)

**Insert 插入**

Insert menu 插入菜单 

![图片](https://uploader.shimo.im/f/0zWlf6JB0Z4endzB!thumbnail)

**Quick Insert 快速插入**

使用：ctrl+enter

考虑上下文，在当前元素中插入在此上下文中能插入的其他元素。可以通过上下方向键更改父子元素位置，通过enter插入

*注意：列表可能较长（oxygen的enter列表差不多），可以通过查找元素首字母/关键词减少干扰项。

![图片](https://uploader.shimo.im/f/2rQiHfyeNliT6iRz!thumbnail)

**Propeties 属性**

“ 属性”面板允许用户查看和编辑属性，当用户单击工具栏上的“ 属性”图标时显示 。

属性面板显示所有XML schema中的simpleType元素。一般都是详细的属性，但有时子元素也会出现在属性面板中。在属性过多时，用户可以通过在uiGroup中注册元素。注册之后，Xopus会自动将元素组织成树状形式，方便用户使用。

![图片](https://uploader.shimo.im/f/uUUbelCfMnODBv5e!thumbnail)

**上下文**菜单按钮、工具栏

**Breadcrumb trail**

显示光标选中位置/活动位置的元素，帮助你：

* 选择需要编辑的元素【可以使用页面左上角的Article/section/paragraph的按钮，breadcrumb trail会以虚线的形式】
* 该元素可以编辑的选项【灰色按钮不可选】
* 对该元素进行其他改动

上下箭头按钮：移动选中元素的位置【上/下】

![图片](https://uploader.shimo.im/f/WuPLoaOeZ4VNTNCJ!thumbnail)

可以看出此处选择的是表格中的2行2列单元，可以通过上箭头按钮，对该单元本身或者所在元素的位置进行更改。

界面左上方显示的上下文菜单，会根据contect（上下文）的不同显示相应内容，比如此时显示的是表格单元，选中普通文字时会显示段落等等……也可以通过上下文菜单中的按钮进行元素编辑（插入删除等操作）

![图片](https://uploader.shimo.im/f/hWZ4vgBixSxf0Ov5!thumbnail)


**11 GroupShare****11.1痛点、需求和解决方案：** **GS针对这样的痛点**（或者反过来说满足这样的需求）：

* **结构化问题依然人工处理**，**效率低下，质量也难有提升。**结构化问题，即机器能完成的“呆”活(e.g.:PM邮件通知、PM逐个去问询跟踪项目进度)，由人干，剥夺了人解决需要更多人类智能、决策的半结构化、结构化问题的宝贵的精力，也阻碍了效率的提高；
* 团队的壮大带来**文件管理和版本控制困难**，继而影响**翻译的一致性和质量**，尤其棘手的是团队中总有人在使用过时的TM和术语库；解决冲突还要再**花额外的时间**

![图片](https://uploader.shimo.im/f/88xCnv7heRFRa1T9!thumbnail)

(“结构化问题依然由人处理”：团队通知还靠项目经理邮件手动发送应该是上世纪的事)![图片](https://uploader.shimo.im/f/ViEzsArRkILZi9iN!thumbnail)


---
(“团队的壮大带来版本控制困难)

为了解决这2大问题，GS和TMS这两个翻译管理系统**共同的解决方案**是：

* **自动化**简化项目管理
  * 翻译的核心流程中，手动流程从14步减少到3步：现在项目经理可以用**更少的步骤**创建、发布和管理翻译项目；通过**自动向团队成员发送重要更新的通知**，项目相关的电子邮件数量也有所减少
  * 增加的项目可见性：基于网络的可定制仪表板和报告功能，PM得以**实时**查看**自动生成进度信息**
* 促进安全协作：
  * 语言资源的集中、实时分享，保证**每个人的库都是最新**的，同时也提高了内容重复利用率（仅在桌面环境无法完成）
  * 支持多人同时处理一个文件
  * * [footnoteRef:1]安全性：基于**角色控制、限时访问**集中化翻译记忆库和术语库（可以扩展到翻译团队之外，允许同事和合作伙伴基于网络访问术语表）
* 支持审计、数据分析，赋能**商业智能**：
  * 可**定制报告**深入剖析性能指标（绩效）和新兴趋势，从而轻松看出应该在哪些方面进行**改进**
  * 自定义仪表板，轻松访问重要指标

![图片](https://uploader.shimo.im/f/eZ09HkFEl1dU4ITo!thumbnail)

**11.2GroupShare核心功能与操作****11.2.1系统支持与安装**如果不使用GroupShare Cloud的话，企业需要自己在多台服务器电脑上安装部署GroupShare的4个组件（app server, web server, database server , tm serve）并搭配windows server 系统和SQL server软件。

如果只购买GroupShare Cloud部署会省去很多麻烦，但本地版的一些方便的设置功能cloud里是没有的。

**11.2.2与其他软件、插件接口进行项目工作****GS & studio & ETS & multiterm**

**11.2.2.1项目创建****从studio发布项目到GroupShare**服务器**：**

* 支持设置**自动发布到GroupShare**

如果尚未在SDL Trados Studio中创建项目，但想将其共享到SDL Trados GroupShare，则可以指定在创建项目后立即将其自动发布到SDL Trados GroupShare。

* **共享资源：**TB, TM，autosuggest词典基于服务器
* 如果要共享术语库和翻译记忆库，则它们必须基于服务器。
* 如果要共享AutoSuggest词典，则它们必须位于共享的公共位置上并具有UNC路径。
* 依然有很多需要手动配置的东西(太过详细，不放了)：
* **发布到GroupShare之后：**
  * **支持预处理和分析：**

（如果项目具有在Trados GroupShare 2017 SR1 CU9或更高版本中创建的基于服务器的TM，则可以使用（测试版） GroupGroup 准备序列。）此序列包含 G**roupShare Analyze和Translate批处理任务，**该任务执行**服务器端分析和项目文件的预翻译。**此批处理任务比在Trados Studio中准备项目要快。

**** 具体操作（这个重要）：**

您可以在项目创建期间使用机器翻译（MT）提供程序来预翻译项目文件。目前，可以使用**SDL语言云机器翻译或SDL ETS翻译**。

* *要在您的项目中使用MT提供程序，您首先需要****在Trados GroupShare Console中设置MT提供程序**** （****还需要使用已设置相应提供程序的项目模板来创建项目****）*
* *在 SDL Trados Studio中，创建一个设置了SDL语言云机器翻译或SDL ETS翻译提供程序的项目。*
* *同样在 SDL Trados Studio中，在步骤2中基于项目创建项目模板。*
* *在 Trados GroupShare中，将项目模板添加为资源。*
* *在项目创建期间使用项目模板。 当项目准备就绪并在项目列表中可用时，您将看到添加到项目的文件已使用您设置的翻译提供程序进行了预翻译。*
* *要查看某个项目是否使用了MT提供程序，请从项目列表中打开该项目，然后选择 项目设置。转到 翻译记忆库页面，查看列表中是否提供了MT提供程序。*

**直接从GroupShare创建项目**

项目经理可以直接从SDL Trados GroupShare Web界面管理共享项目和文件分配 。创建有2种方法：

1. 步骤1a：从头开始创建项目
2. 步骤1b**：根据以前的项目创建项目*（*此功能仅在特殊的合同协议的基础上可用，但需要支付额外费用。）**

**11.2.2.2项目计划**发布到SDL Trados GroupShare的 SDL Trados Studio项目 具有以下工作流：

* 定义项目直至完成**有哪些阶段**（最常见的阶段设置是：**准备**， **翻译**， **检查**和 **完成，可以在Trados GroupShare控制台中更改阶段的名称 。**）
* 定义要通过这些工作流阶段所需完成的任务。
* 给用户分配任务

**作业分配** *** 这些作业分配信息都可以存到模板里**

每个项目文件都需要分配阶段和人员（1个阶段可能同时可以有3个人可以接触这个文件：工程师，翻译和审阅者）。

而在给用户**分配文件或阶段 （翻译OR审阅）**之前，首先要为SDL Trados GroupShare用户分配角色和权限，确保他们可以对分配的文件执行相关操作（e.g.: translator可以查看TM，但不可以修改TM）。

 在将文件分配到项目阶段时， SDL Trados GroupShare会自动向分配的用户发送阶段更改通知电子邮件。这通知用户他们可以开始处理分配给他们的文件。

![图片](https://uploader.shimo.im/f/Op6hcTckYov0FB02!thumbnail)

（具体操作细节：可以略过不看）

* *转到“ ****项目”****视图，然后选择一个项目以将其打开。*
* *在项目计划面板中，设置为看板样式视图，****选择一个或多个文件。***
* ***选择“ 规划<n>个文件”。***
* *对于每个阶段，在“ ****规划<文件>”****窗口中：*
* ***从“ 分配的用户”列表中分配处理文件的 用户。***
* ***在交货时间字段中指定截止日期 。***
* ***注意：****如果在创建项目模板时分配了用户来处理文件阶段，则可以在此阶段咨询他们。您可以通过删除当前分配的用户或添加新的用户来调整分配的用户列表。*
* *选择 ****保存****。*
* *在一个阶段中完成文件的工作后，将文件无限制地拖动到下一个阶段或其他三个阶段中的任何一个。 分配的用户会收到有关分配给他们的任务及其到期日期的通知电子邮件。*

**11.2.2.3项目推进****——作业签出（接收）、签入（提交）&推进(change phase)**当分配的用户收到挂起分配的通知时，他们必须从SDL Trados GroupShare服务器中**签出分配**的文件。

 项目推进中共有3种操作：接收任务（sign-out）, 提交更改（sign-in），和“推送到下一阶段”（*** note：没做完不要点“推送到下一阶段”；如果你做完了，跟你协同工作的人没做完，也不能点“推送到下一阶段”，这个只能最后1个做完的人点）**

**从studio中签出 & 签入的具体操作：**

* *在SDL Trados Studio中，**转到**“ 项目”**视图，然后双击在**SDL Trados GroupShare上发布的项目**以将其打开。*
* *提示：或者，单击通知电子邮件中的链接，以打开您的SDL Trados GroupShare项目到已分配的文档（电子邮件中有两个直接指向分配文件的链接，一个直接在SDL Trados Studio中打开文件 ，另一个（文件名链接）在SDL Online Editor中打开文件 。）。*
* *在“ 文件”视图中，选择要检出的文件。*
* *在 首页标签上，选择签 出。*
* *提示：用户签出分配的文件时，SDL Trados GroupShare会在“ 项目”视图的“ 签出至”列中 显示此信息 。*
* *重要说明：**您无法从SDL Trados Studio检出已在SDL Online Editor中检出的文件。您只能在SDL Trados Studio中打开这些文件，仅供参考。在SDL Online Editor中检出文件时，请勿对文件进行任何本地更改。等待直到从SDL Online Editor检入文件，然后再从SDL Trados Studio检出文件。反之亦然，**Studio中检出的文件也不能在Online Editor中检出。*
* *在“ 主页”选项卡上，选择以下选项之一： 根据您分配的任务和项目阶段，打开翻译， 打开审阅， 打开签核。*
* *开始处理文件。 基于相似的，先前翻译的项目（即，基于PerfectMatch功能）进行预翻译的所有句段均显示为已锁定并已签名。如果需要，您仍然可以对其进行编辑。*
* *完成后，在“ 文件”视图中，选择要检入的文件。*
* *在 主页选项卡上，选择签 入。*
* *展开 更改阶段，然后选择文档应转到的下一个阶段。*
* *注意：如果在新阶段中已经分配了要处理文件的用户，则 SDL Trados GroupShare向这些用户发送阶段更改通知电子邮件，并更新SDL Trados GroupShare应用程序的“ 当前阶段”列中的 信息 *

**从Online Editor中签出的具体操作**

* *单击通知电子邮件中的文件名链接，以在SDL在线编辑器中打开 SDL Trados GroupShare分配的文档 。*
* *登录到 SDL Trados GroupShare，转到“ 仪表板”，然后在“ 您的任务”下，选择 要处理的作业附近。 *![图片](https://uploader.shimo.im/f/Rs3uiorBRRrEyODy!thumbnail)
* *登录到 SDL Trados GroupShare，转到“ 项目”，选择存储分配的项目，选中要处理的文件旁边的复选框，然后选择“ 在编辑器中打开”。*
* *重要提示：您无法从 SDL Trados Studio中已经签出的SDL Online Editor文件中签出 。等待文件从 SDL Trados Studio签入，然后在SDL Online Editor中签出（打开）文件 。*
* *该文件将在SDL在线编辑器中自动打开， 并准备进行编辑。*
* *在SDL在线编辑器中编辑文件 。*
* *完成后，在工具栏的右上角，选择“ 签入文件”。*
* *重要提示：如果您被分配了以下角色之一，则可以使用“ 强制签入”按钮： Project Manager， Power User或 Administrator。当您打开项目并选择在SDL在线编辑器中签出的文件时，可以从SDL Trados GroupShare中获得“ 强制签入”选项 。*
* *在“ 签入”对话框中，执行下列操作之一：*
* *如果您是唯一或最后一个编辑文件的用户，**请输入注释，然后在 “将阶段更改为 ”下**，选择文件进入的下一阶段。**如果您还有工作要做，请不要更改文件阶段。**选择“ 签到”。现在，所有更改都已保存。*
* *如果还有其他人在与您同一个文件，请在必要时输入注释。**您目前无法更改文件阶段。最后一位签入其更改的用户可以更改文件阶段。现在，所有更改都已保存。*

**完成项目**

用户完成所有分配后，您可以将项目标记为 **完成**。在这个阶段，所有的项目文件通常在 **定稿**阶段。

1. 转到“ 项目”视图，然后选择与要完成的项目相对应的复选框。
2. 选择 标记为已完成。

结果

Trados GroupShare将项目状态显示为“ 已完成”。

**11.2.2.4跟踪进度****仪表板中的全项目状态概述**仪表板是登录SDL Trados GroupShare网站时显示的**第一个视图 **，它提供与项目经理相关的信息和更新。项目经理可以查看SDL Trados GroupShare仪表板中正在进行的所有翻译项目的全面状态报告 。

仪表板包含一组预定义的报告，通知用户：

* 即将到期的交付 - 即将到期的项目
* 您的任务 -分配给当前登录用户的任务
* 下载 -所请求下载任务的完整状态（提供了所请求文件的链接）
* 统计 -与在SDL Trados GroupShare中创建的对象相关的统计
* 每月创建的项目（以下均为图表格式）
* 每月字数 
* 最佳语言对 
* 每个组织的字数
* 每个组织的字词 

**跟踪某一项目信息****1总体信息**在SDL Trados GroupShare中创建项目后 ，您可以：

* 在“ 项目**”**视图中**查看其状态 。**
* 打开项目选项卡，并查阅项目计划板和**统计信息。**
* 在看板样式的项目计划板上移动项目文件以**标记其工作流程进度。**
* 创建文件分配，您的用户可以开始在SDL Trados Studio中进行分配 。

在其选项卡中打开项目时，可以查阅项目 *统计信息*。项目标签的右上角提供：

* **根据翻译分段数估算项目状态**
* **显示每个阶段中文件百分比的图表**

![图片](https://uploader.shimo.im/f/sOh1G2aEGl50jttv!thumbnail)

“ 准备”，“ 翻译”，“ 审查”和“ 定稿”区域显示项目阶段是否开始，进行中或尚未完成。通常，**当检查/翻译一个阶段中的所有文件并将其传递到下一阶段时，该百分比变为100％。**0％到100％之间的任何百分比都表明该阶段正在进行中。

该 **估计项目进度为x％**栏显示完成该项目总多么接近。**百分比根据文件包含的已翻译，已确认和已签署段的数量而变**化。当您开始翻译且句段在“ **草稿”中时**，百分比将保持为0％。只有在确认**并批准/批准细分后，进度条百分比才会增加。**

**2翻译状态**通常，可翻译项目的工作流程路由部分基于项目的翻译状态：

1. 翻译人员处理文档，并从Trados Studio **编辑器**视图更改每个翻译段的翻译状态 。
2. 段翻译状态会在Trados Studio **文件**视图中自动更新文档翻译状态 。
3. **翻译人员从Trados Studio签入文档 ，以更新SDL Trados GroupShare项目的翻译和翻译状态 。**
4. SDL Trados GroupShare在“ **项目”**视图和“ **文件”**选项卡中显示项目的当前翻译状态以及文档的当前翻译状态 。
| ***项目翻译状态***   | ***描述***   | 
|:----|:----:|:----|:----:|
| **进行中**   | 该项目需要进一步的工作，翻译人员可以从SDL Trados GroupShare服务器下载该项目， 以在Trados Studio中完成翻译 。   | 
| **已完成**   | 翻译人员已经完成了该项目的工作，并且项目经理在Trados Studio **项目**视图中将该项目标记为完成 。   | 
| **已封存**   | 在完成项目工作并将其交付给客户之后，项目经理可能希望整理 SDL Trados GroupShare项目列表并归档该项目。该项目将从Trados Studio工作流程中隐藏 。   | 
| **独立式**   | 要从SDL Trados GroupShare中完全删除项目 ，但仍保留脱机副本，项目管理器可以将项目与服务器分离。   | 
| ***文件翻译状态***   | ***描述***   | 
| **未指定**   | 该文档尚未被编辑，并且该文档中的所有段均未 **翻译**。   | 
| **翻译中**   | 文档中至少有一个目标句段设置为 **草稿**。   | 
| **已翻译**   | 文档中的所有段都在 Trados Studio中进行了 **翻译**。   | 
| **评论中**   | 没有任何段 **未翻译**或 **草稿**，并且至少有一个段已 **翻译**。   | 
| **翻译被拒绝**   | 没有任何片段 **未翻译**， **草稿**或已 **翻译**，并且至少有一个片段被 **翻译拒绝。**   | 
| **翻译批准**   | 文件中所有句段的状态都设置为“ **已批准翻译****”**。   | 
| **签收中**   | 该文档至少包含一个“已 **签署****”**和一个“ **翻译已批准****”**部分，并且没有任何部分 **未翻译**， **草稿**或已 **翻译**。   | 
| **拒绝签收**   | 文档中的所有段均被 **拒绝签收**，或者当其他段被**签署**时 ，至少一个段被 **拒绝签收**。   | 
| **退出**   | 文档中的所有段均已 **签名**。该 **项目经理**可以将项目翻译状态来 **完成**。   | 
| ***细分翻译状态（在******Studio******中可用）***   | ***描述***   | 
| **未翻译**   | 段目标尚未被翻译或编辑。   | 
| **草案**   | 段目标可能已被编辑，但尚未视为已完全翻译；或将翻译记忆库匹配应用于该句段，但是此后该句段文本已被编辑。   | 
| **已翻译**   | 确认翻译已完成。   | 
| **翻译被拒绝**   | 审稿人拒绝了目标句的翻译。   | 
| **翻译批准**   | 审稿人接受了目标句的翻译。   | 
| **拒绝签收**   | 审核者在签核过程中拒绝了句段的翻译。   | 
| **退出**   | 审阅者批准并签署了该段的翻译。   | 

**11.2.3访问控制：用户，角色和权限****11.2.3.1基本概念**要访问 SDL Trados GroupShare资源，用户必须是组织的一部分。组织为用户赋予角色和权限。

组织是共享工作和资源的用户网络。

组织包括：

* 用户
* 角色
* 权限
* 项目

资源

用户可以根据与他们的角色相关联的权限访问组织的资源。资源包括：

* 翻译记忆库（TM）
* 术语库
* 语言资源模板
* 字段模板
* 项目模板

项目

项目是指需要翻译和审阅的文档总数。项目可能还包括完成工作所需的资源。创建项目后，将工作分为一个或多个任务，并分配给用户。您可以在其看板上跟踪项目进度。

（示例：用户想要更新资源

当**用户尝试访问资源**（例如更新 *TM）时*， SDL Trados GroupShare会将**用户的权限与执行操作所需的权限**进行比较。没有足够权限的用户不能访问资源，也不能对其执行操作。）

角色是权限的集合。 **SDL Trados GroupShare具有七个标准角色**，而 SDL Trados GroupShare Cloud具有六个标准角色，它们对应于用户执行的最常见的工作。**可以在SDL Trados GroupShare中更改与角色关联的权限** ，但不能在SDL Trados GroupShare Cloud中更改它们 。

作为管理员，您可以为用户分配角色，以便他们可以在SDL Trados GroupShare， SDL Trados Studio和 MultiTerm Server中执行作业功能 。（MultiTerm Server是MultiTerm对象（包括术语库和目录对象）的存储 库。SDL Trados GroupShare授予 对SDL Trados GroupShare角色成员的所有用户的MultiTerm访问权限 。但是，对MultiTerm术语库的访问级别由 MultiTerm中授予的权限控制。 可以通过SDL MultiTerm Desktop访问 MultiTerm Administrator。）

| 角色   | 描述   | 
|:----|:----:|:----|:----:|
| 管理员   | SDL Trados GroupShare组织或资源库的管理员 ：  具有**所有可用的**** SDL Trados ****GroupShare****权限**。  授予对“ 许可和 基础结构”视图的默认访问权限 。  默认情况下， 管理员角色：  是分配给内置系统管理员帐户的标准内置角色 。  可以添加到在SDL Trados GroupShare和 MultiTerm Server中应具有不受限制权限的任何其他用户 。  无法删除。   | 
| 超级用户   | 该 power user通常由**应用****专家或本地管理员**填补。   | 
| 译者   | **可以更新****TM****，但不能创建或更改其结构。**  无法创建TM或更改其结构。  **更改组织或用户详细信息。**   | 
| 外部译员   | 可以执行与内部翻译人员相同的工作。  具有与内部翻译员相同的权限。（* 但他们有些资源他们看不到，比如用户列表。**只要他们能看到的资源，权限跟译员都是一样的**）   | 
| 来宾   | 允许其用户具有 读取访问一些细节。   | 
| 项目经理   | 管理翻译资源。  管理项目。  管理用户。   | 
| multiterm访客   | 授予对MultiTerm术语库的公共访问权 ，但不授予SDL Trados GroupShare的任何权利 。  是标准的内置角色。  无法删除。   | 

**11.2.3.2标准角色、权限****角色的标准权限**下表显示了与SDL Trados GroupShare中的默认角色相关联的默认权限 。

| 资源类型   | 允许   | 管理员   | 超级用户   | 项目经理   | 译者   | 外部译员   | 来宾   | multiterm访客   | 
|:----|:----:|:----|:----:|:----|:----:|:----|:----:|:----|:----:|:----|:----:|:----|:----:|:----|:----:|:----|:----:|
| **图书馆**   | 查看资料库   |    |    |    |    |    |    |     | 
|     | 添加图书馆   |    |    |     |     |     |     |     | 
|     | 编辑资料库   |    |    |     |     |     |     |     | 
|     | 删除资料库   |    |    |     |     |     |     |     | 
|     | 链接到图书馆   |    |    |     |     |     |     |     | 
|     |     |     |     |     |     |     |     |     | 
| 组织机构   | 查看组织   |    |    |    |    |    |    |     | 
|     | 添加组织   |    |    |     |     |     |     |     | 
|     | 编辑组织   |    |    |     |     |     |     |     | 
|     | 删除组织   |    |    |     |     |     |     |     | 
|     | 链接到组织   |    |    |     |     |     |     |     | 
|     |     |     |     |     |     |     |     |     | 
| 用户数   | 查看用户   |    |    |    |     |     |     |     | 
|     | 添加用户   |    |     |     |     |     |     |     | 
|     | 编辑使用者   |    |     |     |     |     |     |     | 
|     | 删除用户   |    |     |     |     |     |     |     | 
|     |     |     |     |     |     |     |     |     | 
| 应用范围广   | 后台任务管理员   |    |     |     |     |     |     |     | 
|     | 查看后台任务   |    |     |     |     |     |     |     | 
|     | 管理角色   |    |     |     |     |     |     |     | 
|     | 查看许可证信息   |    |     |     |     |     |     |     | 
|     | 查看仪表板   |    |    |    |    |     |     |     | 
|     | 查看基础架构   |    |     |     |     |     |     |     | 
|     | 创建术语库   |    |     |     |     |     |     |     | 
|     |     |     |     |     |     |     |     |     | 
| TM数据库服务器   | 查看数据库服务器   |    |    |    |    |    |    |     | 
|     | 添加数据库服务器   |    |     |     |     |     |     |     | 
|     | 编辑数据库服务器   |    |     |     |     |     |     |     | 
|     | 删除数据库服务器   |    |     |     |     |     |     |     | 
|     |     |     |     |     |     |     |     |     | 
| TM容器   | 查看容器   |    |    |    |    |    |    |     | 
|     | 添加容器   |    |     |     |     |     |     |     | 
|     | 编辑容器   |    |     |     |     |     |     |     | 
|     | 删除容器   |    |     |     |     |     |     |     | 
|     |     |     |     |     |     |     |     |     | 
| 语言资源   | 查看语言资源   |    |    |    |    |    |    |     | 
|     | 添加语言资源   |    |    |    |     |     |     |     | 
|     | 编辑语言资源   |    |    |    |    |    |     |     | 
|     | 删除语言资源   |    |    |    |     |     |     |     | 
|     |     |     |     |     |     |     |     |     | 
| 领域   | 查看栏位   |    |    |    |    |    |    |     | 
|     | 新增栏位   |    |    |    |     |     |     |     | 
|     | 编辑栏位   |    |    |    |    |    |     |     | 
|     | 删除栏位   |    |    |    |    |    |     |     | 
|     |     |     |     |     |     |     |     |     | 
| 翻译记忆库   | 查看TM   |    |    |    |    |    |    |     | 
|     | 添加TM   |    |    |    |     |     |     |     | 
|     | 编辑TM   |    |    |    |     |     |     |     | 
|     | 删除TM   |    |    |    |     |     |     |     | 
|     | 写TU   |    |    |    |    |    |     |     | 
|     | 读TU   |    |    |    |    |    |    |     | 
|     | 删除TU   |    |    |    |    |    |     |     | 
|     | 批量编辑TU   |    |    |    |     |     |     |     | 
|     | 批量删除TU   |    |    |    |     |     |     |     | 
|     | 导入TU   |    |    |    |     |     |     |     | 
|     | 出口TU   |    |    |    |     |     |     |     | 
|     | 重新索引TU   |    |    |    |     |     |     |     | 
|     |     |     |     |     |     |     |     |     | 
| 项目   | 查看专案   |    |    |    |    |    |    |     | 
|     | 新增专案   |    |    |    |     |     |     |     | 
|     | 编辑专案   |    |    |    |     |     |     |     | 
|     | 删除专案   |    |    |    |     |     |     |     | 
|     | 签出我的项目文件   |    |    |    |    |    |     |     | 
|     | 检出任何项目文件   |    |    |    |     |     |     |     | 
|     | 取消签出其他用户项目文件   |    |    |    |     |     |     |     | 
|     | 将新的源文件添加到项目   |    |    |    |     |     |     |     | 
|     | 将新的源文件添加到项目   |    |    |    |     |     |     |     | 
|     | 分配文件   |    |    |    |    |     |     |     | 
|     | 查看其他用户   |    |    |    |    |     |     |     | 
|     | 更改当前相位   |    |    |    |    |    |     |     | 
|     | 更改任何阶段   |    |    |    |     |     |     |     | 
|     | 生成AuditTrail报告   |    |     |     |     |     |     |     | 
|     | **下载****AuditTrail****报告**   |    |     |     |     |     |     |     | 
|     | **安全项目文件下载**   |    |    |    |     |     |     |     | 
|     |     |     |     |     |     |     |     |     | 
| 项目模板   | **添加项目模板**   |    |    |    |     |     |     |     | 
|     | **查看项目模板**   |    |    |    |     |     |     |     | 
|     | **删除项目模板**   |    |    |    |     |     |     |     | 
|     | **编辑项目模板**   |    |    |    |     |     |     |     | 
|     |     |     |     |     |     |     |     |     | 
| 术语库   | **查看术语库**   |    |    |    |    |    |    |     | 
|     | **添加术语库**   |    |    |    |     |     |     |     | 
|     | **编辑术语库**   |    |    |    |     |     |     |     | 
|     | **删除术语库**   |    |    |    |     |     |     |     | 
|     | **概念水平阅读**   |    |    |    |    |    |    |     | 
|     | **概念水平写**   |    |    |    |     |     |     |     | 
|     | **复制条目**   |    |    |    |     |     |     |     | 
|     | **合并条目**   |    |    |    |     |     |     |     | 
|     | **删除条目**   |    |    |    |     |     |     |     | 
|     | **导入条目**   |    |    |    |     |     |     |     | 
|     | **出口项目**   |    |    |    |     |     |     |     | 
|     | **不输入模型即可编辑**   |    |    |    |     |     |     |     | 
|     | **变更输入类别**   |    |    |    |     |     |     |     | 
|     | **批处理**   |    |    |    |     |     |     |     | 
| 报告书   | **查看报告**   |    |    |    |    |     |     |     | 
|     | **新增报告**   |    |    |    |     |     |     |     | 
|     | **编辑报告**   |    |    |    |     |     |     |     | 
|     | **删除报告**   |    |    |    |     |     |     |     | 

**1* 文件分配**使用SDL Trados Studio中的文件分配时 ， SDL Trados GroupShare会使SDL Trados GroupShare项目中的**每个文件 仅对特定的Trados Studio用户可用 。**

为了进一步增强发布到SDL Trados GroupShare服务器的项目的安全性 ，您应该熟悉 *外部译员*角色和一些相关的项目权限。

**影响项目安全的角色**

SDL Trados GroupShare中的 “ **外部翻译”**角色 主要用于您分配从翻译组织外部签约的翻译以处理 SDL Trados GroupShare项目文件的项目。默认情况下， **外部翻译**可以进行与内部译员同样的工作，但没有权限查看该项目的其他文件或其他用户该项目的工作。

**影响项目安全性的权限**

| ***允许***   | ***描述***   | ***默认分配给***   | 
|:----|:----:|:----|:----:|:----|:----:|
| **查看所有文件**   | 允许 具有此权限的Trados Studio用户查看项目中的所有文件，甚至包括尚未分配给他们的文件。  **注意：**需要其他权限才能对“ **查看所有文件****”**权限可用的文件执行操作 。   | **管理员**  **超级用户**  **项目经理**  **译者**   | 
| **查看其他用户**   | 允许 具有此权限的Trados Studio用户查看分配给同一项目文件的所有其他用户。   | **管理员**  **超级用户**  **项目经理**  **译者**   | 
| **签出我的项目文件**   | 允许 Trados Studio用户仅检出分配给他们的文件。  **注意：**这是早期版本的SDL Trados GroupShare中的旧“ **签出文件****”**权限 。   | **管理员**  **超级用户**  **项目经理**  **译者**  **外部译员**   | 
| **检出任何项目文件**   | 允许 具有此权限的Trados Studio用户检出他们可见的任何文件。此权限允许签出文件，而不管文件的当前阶段如何，也无论分配给谁来处理文件。   | **管理员**  **超级用户**  **项目经理**   | 
| **分配文件**   | 允许 具有此权限的Trados Studio用户将文件分配给SDL Trados GroupShare角色成员的其他 Trados Studio用户 。   | **管理员**  **超级用户**  **项目经理**   | 

**2* 限制下载**要将项目文件的下载限制为某些用户，必须为用户分配一个具有“ **安全项目文件下载”**权限的角色 。默认情况下，“ **安全项目文件下载”**权限分配给以下角色：管理员，超级用户和项目管理员。在创建项目期间，具有这些角色的用户必须选中“ **防止为此项目下载文件”**复选框，这意味着只有具有“ **安全项目文件下载”**权限的用户 才能下载源项目文件和翻译后的项目文件。

如果您不受具有“ **安全项目文件下载”**许可权的用户的限制，则可以下载格式的项目文件 以存储或查阅它们，而不管它们处于哪个 **项目阶段**。 .sdlxliff

*程序*

* *在“ 项目”视图中，选择要下载其文件 格式的项目。 .sdlxliff*
* *在项目选项卡中，执行下列操作之一：*
* *选择 下载所有文件 > 下载所有文件（不包括目标）。*
* *选中与您要下载的文件相对应的复选框，然后选择 选定的文件。*
* *将文档另存为 档案在您选择的位置。 zip*

**SDL产品矩阵报告H5成品展示**




**场景设定**甲方（CATTIE Cosmetics公司）欲出口一批彩妆到中国销售，借此机会正式进驻中国市场，基于之前与乙方（生活真美好本地化服务有限公司）的良好合作基础，再次展开彩妆产品的本地化合作。

乙方合作需求文档见CATTIE合作需求

甲方解决方案见生美 - CATTIE需求分析

**CATTIE合作需求****品牌介绍****CATTIE Cosmetics**，简称为**CATTIE**，是总部位于加利福尼亚州洛杉矶的化妆品品牌，公司于2014年由创始人Laura成立。品牌以实惠的价格（许多产品的价格从5美元到20美元不等）和基于社交媒体当前趋势的合作而闻名。粉丝在社交媒体上发布产品相关测评、使用体验时，通过使用#CATTIE#主题标签，有机会成为网站上的模特。


![图片](https://uploader.shimo.im/f/ZvUyQsq8SBouC1cj!thumbnail)**品牌产品**

![图片](https://uploader.shimo.im/f/vKMPF0im0TfWyhHy!thumbnail)

![图片](https://uploader.shimo.im/f/7NrJMxom0inNVYlq!thumbnail)![图片](https://uploader.shimo.im/f/BPljyAt67xNnYyvx!thumbnail)

![图片](https://assets-cdn.shimo.im/docs/assets/shape_table_error.png)







1. ![图片](https://uploader.shimo.im/f/vx4VynBx6J20J3II!thumbnail)![图片](https://uploader.shimo.im/f/im808ibv06c8Zpxe!thumbnail)**品牌优势**没有进行动物实验
2. 用最好的原料
3. 平价，性价比高

![图片](https://uploader.shimo.im/f/ma0ZsyU2cz0nEYeA!thumbnail)

1. **本次合作背景**进驻丝芙兰的春季产品初次合作效果良好；
2. 中国美妆市场规模日益壮大，发展潜力明显；
3. 从天猫双十一、双十二反映出的中国消费者巨大的购买力；
4. 平价彩妆产品，市场竞争力强；
5. 中国市场目前流通的CATTIE的产品很多都是假货，所谓的官方网页和官方旗舰店都为假冒，严重影响了CATTIE的品牌形象。

**活动概要**美国彩妆品牌CATTIE准备借此次机会进驻中国，所有运到中国的彩妆包括两个销售途径：

1. 丝芙兰专柜销售
2. 中国官网（暂无）销售

具体日程安排：

12月20日第一批彩妆产品运到中国北京；

12月24日晚在三里屯开设圣诞主题快闪店（仍在洽谈）；

1月1日和丝芙兰联合举办线下元旦品牌粉丝见面会，届时在丝芙兰正式开售，同时上线CATTIE中国官网。






具体安排

![图片](https://uploader.shimo.im/f/MjqrnJQTU7BXHCI8!thumbnail)


**CATTIE公司架构**![图片](https://uploader.shimo.im/f/70T0eeWvi0FdJabv!thumbnail)

*望贵公司相关部门与上图高亮的我司部门对接相关事务

1. **翻译及写作需求****商务文书**商务、外贸信函笔译； 商务洽谈口译
2. 商务报告
3. 合同：丝芙兰销售合同；明星代言合同；发布会之前的B站UP主、微博红人、小红书达人合同；李佳琦直播推广合同
4. 外贸重头戏: “负责国际物流运输、清关”（详见页面底部的流程图）
  1. 口/笔译：联系、索赔等；
  2. 3大类“单证”：
    1. 资金单据，如支票
    2. 商业单据：如发票，运输单据（海运、航空、保险单），装箱单之类
    3. 公务证书：出口许可证、商检证书（质量检验、数量检验、原产地证明书）之类
    4. 要获得中国国内质检合格证书需要提交的相关材料
  3. 信用证
1. **技术文档**产品说明书，包含产品技术参数
2. 专利文献
3. 标准文献
4. 提供整个流程的项目管理工作日志
1. **宣发推广**包装：包装上需要体现的主要信息是产品名和色号
2. 样本（册） / 活动现场宣传册 ：需要涵盖此次所有的彩妆产品介绍（图文）
3. 社交媒体宣传文案：我司会及时在twitter, youtube, instagram等平台发送推广消息，请同步翻译更新到微博、微信、抖音的内容；B站UP主、微博红人、小红书达人软/硬广文案
4. 公司官网中文版 ：本地化我司英文官网，但是首页主要展示此次的产品详情
5. 丝芙兰：广告牌宣传语
6. 元旦品牌粉丝见面会：CATTIE公司销售部经理提供陪同口译；LED大屏广告词；到场嘉宾宣传词；现场宣传片广告词
7. SEO推广  
1. **具体要求**产品信息部分：
  1. 总体原则：翻译参照中国国内市场，已有被大众广泛接受的翻译请沿用，没有译文的产品请翻译；
  2. 产品色号翻译：务必结合产品实际颜色与品牌调性，唇部产品色号尤其需要结合中国市场唇部产品流行趋势，如烂番茄色、冷葡萄色、浆果色；不同红色：砖红、姨妈红、枣泥红、豆沙红、山楂红、牛血红等，希望译出特色与创意；
  3. 产品详情翻译：12月21日我司会为贵公司提供产品样品供参考；要求产品详情突出产品特色：如唇部产品唇釉线的丝绒、哑光、薄雾质地、不沾杯更持久的特点、眼部、面部高光腮红产品的土豆泥质地
2. 宣传策划部分：
  1. 元旦品牌粉丝见面会的宣传语需要迎合新年氛围设计
  2. 推广文案强调这是CATTIE首次官方授权进入中国市场

**补充说明**我司给贵公司共享的资料均属内部资料，不得外泄；

所有文档最终成品需由我方审校人员审校合格才视为验收成功。





**生活真美好 X CATTIE 合作项目需求分析报告****公司简介**生活真美好本地化服务有限公司自2008年成立之日起，专注于商务与技术文档翻译、网站翻译、本地化等专业服务。十几年来，生美公司致力于为全球客户提供专业的语言解决方案，有丰富的本地化项目落地经验。公司下设项目部、翻译中心、审校组、技术支持部等部门，年处理翻译量约5000万字，排版量达5万余页，主要包括英中互译，以及日语、韩语、西班牙语、俄语等语种与英语/中文间的互译。 

 高品质的翻译质量和服务质量是生美得以持续发展的动力。我们始终把客户的利益放在第一位，对于所有项目严格执行“翻译、译审、校对”的操作流程，严格实施质量控制措施，确保为客户提供最优质的服务。


1. **客户需求**文书、技术文档及产品资料翻译

文书：商务、外贸信函；商务报告；合同；单据和凭证等

技术文档：说明书，专利文献等

产品资料：包装信息、宣传手册等

2. 宣发推广

社交媒体宣传；官网本地化等

3）其他支持

 商务口译服务；线下活动陪同口译；创意文案写作；粉丝见面会筹备等

**人员安排   **![图片](https://uploader.shimo.im/f/zqfTU7AJdMZvcLp0!thumbnail)

项目负责人：项目经理 王美丽

**具体角色**![图片](https://uploader.shimo.im/f/F5Nby658XX4wmQ1E!thumbnail)

![图片](https://uploader.shimo.im/f/OgNvrOf71emTgpiI!thumbnail)**项目流程与工具使用**

**具体工作流程**![图片](https://uploader.shimo.im/f/T8vQXLF9uXxFPyLM!thumbnail)






 


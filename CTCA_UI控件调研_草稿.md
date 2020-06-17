*  ui控件的theory、不同ui控件的使用场景 和 缺陷，一个总体review
* 最近的trend 是什么，是否适合我们的系统
* 令人感到极度舒适的ui控件 showcases ，特别是：
  * "browsing aid" ，帮助浏览的控件 
    * “分类”的控件
    * 筛选器
    * 排序
    * 跟随移动的控件 （比如现在看到的石墨的工具栏）
  * searching aid， 搜索控件

（以上"" 号中内容参考 o'reilly 的information architecture）

**Note: **

* 小组讨论时 我们最后会从 highlight 部分选出最终方案，但需要非highlight 部分的理论支持）
* 自己的感受、体验很重要，但为了避免片面，**尽量结合review 文章**

**成果形式：**

* 直接在这个文档里更
* 大家怎么方便怎么来，**章节指路、链接、截图、文字都行**
# 
**调研成果**

# 一、UI控件理论

**控件的类型：**

![图片](https://uploader.shimo.im/f/NCt4jp9lXzigLVvu.png!thumbnail)

如果**按功能划分**，控件可归为以下5类：

– 触发操作：按钮、滚动条、手柄…

– 数据录入：文本框、复选框、滑块…

– 信息展示：气球提醒、加载器、进度条、启动页、工具提示…

– 容器：窗口、tab标签页…

– 导航：面包屑、导航条、分页器…

**输入框**还能这样玩：

– 未填写时：框内用颜色饱和度较低的文字/图标提示程序期待的内容；

– 鼠标滑过时：指针变成光标，暗示可进行输入操作；

– 鼠标聚焦时：边框高亮；提示信息被清除；光标闪烁；

– 输入内容：边框持续高亮；密码非明文显示；实时反馈密码安全等级、有效性；

– 输入完成：高亮消失；输入内容的颜色饱和度高，可快速区分未填和已填。

另外输入框内的信息还可按需选择不同的对齐方式；

**在右侧安排「×」图标用于内容的快速清除；还能根据用户输入的关键词实时联想……**


**单选框、复选框**

小小的方形对指针瞄准的精确度要求较高。为了方便操作，将选框和文字绑定以扩大点击区域，同时从视觉上给用户提供预期：例如当鼠标滑过时，将两者作为整体进行反馈。

另外，当用户选择多个时，有什么办法能减少点击、快速选中多个呢？在windows中「框选」可一次性选中多个文件；在photoshop中按住鼠标左键不放并滑动可快速隐藏多个图层。

![图片](https://uploader.shimo.im/f/0He45eDvF6dFNoC2.png!thumbnail)

插一个我看到的我很喜欢的展示文章的页面

![图片](https://uploader.shimo.im/f/R3jTp7GNo99oTmn8.png!thumbnail)

和我之前用xd画的那个有点像

![图片](https://uploader.shimo.im/f/vWaI9veOMEcHyFj7.png!thumbnail)



## **原则**

图标不是单独的个体，应该具有相同的风格，包括**造型规则、圆角大小、线框粗细、图形样式和个性细节**等元素都应该具有**统一的规范**。

卡片式布局的间距最小不低于16px，使用最多的间距是20px、24px、30px、40px，间距的颜色设置可以与分割线一致，也可以更浅一些。

带图文的设计遵循**邻近性原则**：单个元素之间的相对距离会影响我们感知它是否以及如何组织在一起，互相靠近的元素看起来属于一组，而那些距离较远的则自动划分组外，距离近的关系紧密。

![图片](https://uploader.shimo.im/f/WlFvaZ0qClrfPfdM.png!thumbnail)

## **趋势**

## **使用场景和缺陷**

# 二、控件案例（那几个gif放在石墨文档上好像一直出问题 忽略一下）

## 分类控件

①列表（文字有组织排列）

②顶部分类导航

![图片](https://uploader.shimo.im/f/5b0JQVExSRtPOMhv.png!thumbnail)

②图标/图片+文字并排

![图片](https://uploader.shimo.im/f/9KDvZeuEVqDBRtCo.png!thumbnail)

这虽然是个有关食物的分类，但是给人的感觉简洁美观，目前看到大多数的分类都是文字+下拉菜单（分类特别多的情况下挺好用的 但是我们这个网页分类似乎没有那么多 或许可以考虑一下这种图标分类的方式 不一定是首页或者说整个网站的分类 可以用于某个板块    /我感觉像是大咖文章就可以按主题 社区也可以按服务/）

补充案例：

![图片](https://uploader.shimo.im/f/Z7UHstfIEJjUPYX4.png!thumbnail)

## 筛选器

①文字分级平铺

![图片](https://uploader.shimo.im/f/cI57AU9Iqktpkg2V.png!thumbnail)

②列表勾选筛选条件+自定义关键字

![图片](https://uploader.shimo.im/f/9VI1H1rWqDIC7y1W.png!thumbnail)

③筛选条件分类+展开列表

![图片](https://uploader.shimo.im/f/MC4ejV8Gc52xuaQM.png!thumbnail)

④区间、关键字 标签筛选

![图片](https://uploader.shimo.im/f/AP8ka1YcKLF6ea9M.png!thumbnail)

 ![图片](https://uploader.shimo.im/f/umF44DmepZzaIwhc.png!thumbnail)

⑤多层级细节筛选（适用于文章等）

![图片](https://uploader.shimo.im/f/3n7fnn4ZTVwtKdb7.png!thumbnail)

一筛选器也可以直接放在搜索框上：

![图片](https://uploader.shimo.im/f/C9cMfwShs9L67eh1.gif)

## 排序控件

①普通排序

②标签自由排序

![图片](https://uploader.shimo.im/f/bjZkt6rAmupbEIwZ.gif)

用户参与性高，互动性强

## 搜索控件

know-item searching

existence searching

Exploratory searching

Comprehensive searching【那本书里的几大按用户需求分类的搜索 参考】

①关键词联想搜索

![图片](https://uploader.shimo.im/f/Vo9Ppwxk04wH998j.png!thumbnail)

②搜索类型指引

![图片](https://uploader.shimo.im/f/JU5SXkRoeuK0stTm.png!thumbnail)


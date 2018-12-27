# 如何在Github Pages上生成部署简历
> 项目部署流程先从初始化Git库开始，编辑简历文件，将文件部署在Github Pages上，最后可以将其保存为pdf格式并打印出来。
## **1、背景**
每年的金三银四都是人员流动最大，找工作最好的时间段之一。而找工作就不得不需要更新简历，想到自己也会有这么一天，那么就来一起好好写一份简历吧。期间在网上找了不少写简历的资源，比如[轻单-在线简历制作](https://qdan.me/list/VUR-PAX01x8Skk0F)收录了一些在线生成简历的网站，有需要的童鞋可以直接拿走，不用再看这节课啦。
才怪！我对自己写的简历模板有信心，放这个出来就是要比比看。比比看性价比，我们这个模版的价格是 0，分母是 0 就意味着性价比无穷大！写这个模版的初衷是希望同一份简历既能做页面展示，也能直接打印出来给我到处投。（请认真对待每一份简历，不要学习笔者）。写这份模版也是站在巨人的肩膀上，参考了前人经验的。感谢以下先辈：
* [一看 star 数就知道一定是最牛的简历](https://github.com/DIYgod/Resume)
* [freepik 上的好看简历](https://www.freepik.com/free-psd/editable-cv-format-download_716578.htm)
<br>我们可以利用 Github 的静态页面托管服务 Github Pages 来帮助我们做页面展示。
![背景图](https://raw.githubusercontent.com/caojiele/resume/master/img-folder/bd-show0.png)
什么是 Github Pages？
Github Pages 是 Github 的静态页面托管服务。它设计的初衷是为了用户能够直接通过 Github 仓库来托管用户个人、组织或是项目的专属页面。参考：https://help.github.com/articles/what-is-github-pages/
可以说相当于一个可直接用 git 管理内容的静态服务器，有许多人会用它来托管自己的个人博客（利用 Jekyll、Pelican 这一类静态页面生成工具）或是在这上面发布自己的 HTML5 小游戏。当然这么好的东西也是有限制的。
Github Pages 的限制：
* ##### 仓库存储的所有文件不能超过 1 GB
* ##### 页面的带宽限制是低于每月 100 GB 或是每月 100,000 次请求。
* ##### 每小时最多只能部署 10 个静态网站。
* ##### 对于发布自己的简历或是部署自己的博客的这一类需求我想是不用担心这些限制的，如果真的不小心超了，Github 那边不会采取什么强制措施，而是会发一份邮件提醒你应该找一个更适合你的托管对象的服务。
## **2、预备知识**
本项目需要的预备知识：git 的基本使用
如果对 git 完全陌生，推荐学习[《Git 实战教程》](https://www.shiyanlou.com/courses/4)，仅需了解最基本的操作即可。
## **3、项目知识点**
本项目完成过程中，我们将学习：在 Github Pages 上部署自己的简历
## **4、适合人群**
适合对于简历有要求的童鞋，本项目可以完美的让你对简历进行管理
## **5、最终效果**
简历页面展示： 
<br>![简历页面展示](https://raw.githubusercontent.com/caojiele/resume/master/img-folder/bd_show3.png) 
保存后的 pdf 版本：
<br>![保存后的 pdf 版本](https://raw.githubusercontent.com/caojiele/resume/master/img-folder/bd_show4.png) 
Mark简历生成器操作图：
<br>![Mark简历生成器操作图](https://raw.githubusercontent.com/caojiele/resume/master/img-folder/Dynamic_figure2.gif)
网页链接：[Mark简历模板主页](http://www.caojiele.com/resume/)
## **6、总结**
本项目主要是给没有接触过 Github Pages 的童鞋演示一遍它的基本使用，关于其它主题如自定义域名，自定义 404 页面等可在 [Customizing GitHub Pages](https://help.github.com/categories/customizing-github-pages/)中找到参考。这里还需要再三提醒一句，千万不要在发布的简历中加上个人身份敏感信息呀！最后再给看到这里的同学一个福利吧：https://www.canva.com/templates/resumes/
## **7、关于作者**
- 简书
    - [「小码哥个人主页」](https://www.jianshu.com/u/faa01fa59ea3)

- 知乎
    - [「小码哥个人主页」](https://www.zhihu.com/people/wang-le-6-62/activities)

- segmentfault
    - [「小码哥个人主页」](https://segmentfault.com/u/xiaomage_5c10d17d26987)
    
- 微信公众号    
 ![微信公众号](https://raw.githubusercontent.com/caojiele/resume/master/img-folder/qrcode.jpg)
 
## **7、参考资料**
* [GitHub Pages Basics](https://help.github.com/categories/github-pages-basics/)
* [Customizing GitHub Pages](https://help.github.com/categories/customizing-github-pages/)
* [HTML5 Editable Table](https://codepen.io/ashblue/pen/mCtuA)
* [一看 star 数就知道一定是最牛的简历](https://github.com/DIYgod/Resume)
* [freepik 上的好看简历](https://www.freepik.com/free-psd/editable-cv-format-download_716578.htm)
* [如何在Github Pages上生成部署简历](https://www.jianshu.com/p/d95443bfdf75)
* [写简历注意事项](https://note.youdao.com/share/?id=a097d9dedfc367e44e8a5840bc250a96&type=note#/)

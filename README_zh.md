# 在线简历生成器

### [英文文档](README.md)

项目部署流程先从初始化Git库开始，编辑简历文件，将文件部署在Github Pages上，最后可以将其保存为pdf格式并打印出来。

## **1、背景**

每年的金三银四都是人员流动最大，找工作最好的时间段之一。而找工作就不得不需要更新简历，想到自己也会有这么一天，那么就来一起好好写一份简历吧。期间在网上找了不少写简历的资源，比如[轻单-在线简历制作](https://qdan.me/list/VUR-PAX01x8Skk0F)收录了一些在线生成简历的网站，有需要的童鞋可以直接拿走，不用再看这篇文章啦。

怎么可能！我对自己写的简历模板有信心，放这个出来就是要比比看。比比性价比，我们这个模版的价格是 0，分母是 0 就意味着性价比无穷大！写这个模版的初衷是希望同一份简历既能做页面展示，也能直接打印出来给我到处投。（请认真对待每一份简历，不要学习笔者）。写这份模版也是站在巨人的肩膀上，参考了前人经验的。感谢以下先辈：

* [一看 star 数就知道一定是最牛的简历](https://github.com/DIYgod/Resume)
* [freepik 上的好看简历](https://www.freepik.com/free-psd/editable-cv-format-download_716578.htm)

我们可以利用 Github 的静态页面托管服务 Github Pages 来帮助我们做页面展示。

![背景图](https://cdn.nlark.com/yuque/0/2019/png/338441/1563288299459-d2416856-ef5f-4c15-a2a6-041ae4f3f6ca.png)

**什么是 Github Pages？**

Github Pages 是 Github 的静态页面托管服务。它设计的初衷是为了用户能够直接通过 Github 仓库来托管用户个人、组织或是项目的专属页面。参考：https://help.github.com/articles/what-is-github-pages/
可以说相当于一个可直接用 git 管理内容的静态服务器，有许多人会用它来托管自己的个人博客（利用 Jekyll、Pelican 这一类静态页面生成工具）或是在这上面发布自己的 HTML5 小游戏。当然这么好的东西也是有限制的。

**Github Pages 的限制：**
* 仓库存储的所有文件不能超过 1 GB。
* 页面的带宽限制是低于每月 100 GB 或是每月 100,000 次请求。
* 每小时最多只能部署 10 个静态网站。

对于发布自己的简历或是部署自己的博客的这一类需求我想是不用担心这些限制的，如果真的不小心超了，Github 那边不会采取什么强制措施，而是会发一份邮件提醒你应该找一个更适合你的托管对象的服务。

## **2、预备知识**

本项目需要的预备知识：git 的基本使用
如果对 git 完全陌生，推荐学习[《Git 实战教程》](https://www.shiyanlou.com/courses/4)，仅需了解最基本的操作即可。

## **3、项目知识点**

本项目完成过程中，我们将学习：在 Github Pages 上部署自己的简历

## **4、适合人群**

适合对于简历有要求的童鞋，本项目可以完美的让你对简历进行管理

## **5、最终效果**

简历页面展示： 

![简历页面展示](https://cdn.nlark.com/yuque/0/2019/png/338441/1563288435058-5e6b931a-5ddf-4f8f-97b8-fdf1030ee04b.png) 

保存后的 pdf 版本：

![保存后的 pdf 版本](https://cdn.nlark.com/yuque/0/2019/png/338441/1563288446983-260d6296-7fb9-4e94-982a-b2e0c9ac6775.png) 

Mark简历生成器操作图：

![Mark简历生成器操作图](https://raw.githubusercontent.com/caojiele/resume/master/img-folder/Dynamic_figure2.gif)

网页链接：[Mark简历模板主页](https://caojiele.com/online-resume/)

## **6、总结**

本项目主要是给没有接触过 Github Pages 的童鞋演示一遍它的基本使用，关于其它主题如自定义域名，自定义 404 页面等可在 [Customizing GitHub Pages](https://help.github.com/categories/customizing-github-pages/)中找到参考。这里还需要再三提醒一句，千万不要在发布的简历中加上个人身份敏感信息呀！最后再给看到这里的同学一个福利吧：https://www.canva.com/templates/resumes/

## **7、关于我**

Hey，我是小码哥，Java 攻城狮，Apache、Alibaba等开源组织贡献者之一，常年出没于 Github、Gitee、知乎、简书 等地带。目前主要负责集团App后端开发以及维护、微服务技术实施、基础设施构建等工作，有幸参与过阿里健康、平安万家医疗等公司大型项目开发；17年有了自己的第一个[工作室](https://caojiele.com/cooperation/)，解决各种公司的「疑难杂症」，实现「天马行空」的需求。一直在需求和开发之间徘徊挣扎，任处于一线开发之中，绝招尚在开发。

个人主页：https://caojiele.com

简书：https://www.jianshu.com/u/faa01fa59ea3

慕课网手记：https://www.imooc.com/u/4024769/articles

segmentfault：https://segmentfault.com/u/xiaomage_5c10d17d26987
    
微信公众号：iamtianxuan   

  ![微信公众号](https://cdn.nlark.com/yuque/0/2019/jpeg/338441/1564802304985-6a45f687-8685-4426-998b-96a5f032f2c9.jpeg)

更多详情，请扫二维码：

  ![qrcode](https://cdn.nlark.com/yuque/0/2019/png/338441/1562683998026-42937005-a1e6-43cb-b51e-6aacf2952a56.png)
 
## **8、参考资料**

* [GitHub Pages Basics](https://help.github.com/categories/github-pages-basics/)
* [Customizing GitHub Pages](https://help.github.com/categories/customizing-github-pages/)
* [HTML5 Editable Table](https://codepen.io/ashblue/pen/mCtuA)
* [一看 star 数就知道一定是最牛的简历](https://github.com/DIYgod/Resume)
* [freepik 上的好看简历](https://www.freepik.com/free-psd/editable-cv-format-download_716578.htm)
* [如何在Github Pages上生成部署简历](https://www.jianshu.com/p/d95443bfdf75)
* [写简历注意事项](https://note.youdao.com/share/?id=a097d9dedfc367e44e8a5840bc250a96&type=note#/)

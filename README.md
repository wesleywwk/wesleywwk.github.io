### 前言

先错略写下，后面再完善

现在疫情期间，公司效益也不行，前段时间裁了一大批人，我们剩下的几个人也没有什么需求，主要是维护，我也深感危机，也在刷刷面试题，准备看看新机会，今天无意间看到一个招聘需求：==有一定的文档撰写能力，熟练绘制UML图，善于总结，有技术博客者优先；==我忽然意识到，工作这么多年了，自己连个个人博客网站都没有，深感凄凉，于是在网上找了下，很多博主都推荐用 Hexo + GitHub 可以免费搭建个人博客网站，看了下别人搭建的，还不错。

1. 第一步把淘宝镜像相关配置的内容放进来

2. 根据[官网](https://hexo.io/zh-cn/docs/)进行搭建 

3. 部署到 gitee上 https://wwkwesley.gitee.io

4.  清理，生产，部署命令

   ```
   hexo clean && hexo g -d                                                                 
   ```

5. 记得把 CNAME 和 readme.md等资源文件放在source文件夹，Hexo在执行命令时是不会删除掉`source`目录下的文件的文件

模板网站：https://volantis.js.org/v2/getting-started/

[hexo -d后github上出现README.html问题解决](https://blog.csdn.net/weixin_42039699/article/details/101111394)

一定要在根目录创建 CNAME 文件来绑定你的私有域名，如果直接在github上面创建，会导致发布被删掉

未完待续...
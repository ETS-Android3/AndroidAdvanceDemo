# AndroidAdvanceDemo

#### 介绍
android进阶技术demo

#### 软件架构

ToolBase：包含base类，rxbus,livedatabus,retrofit,glide,permission，图片处理等的封装。

ToolVitamio： vitamio视频播放器；

ToolImageLoad: 图片加载框架;
                //在Application中初始化图片加载框架，可以选择Glide,Fresco、Picasso等。
                ImageLoadProxyUtil.getInstance().init(new GlideLoad());
                使用代理模式，可以动态选择不同的图片加载框架.

DemoAnnotations：自定义注解和动态代理，实现类似butterknife功能；

demoHtmlAnalysis：网上抓数据，html解析；

#### 使用说明

1. xxxx
2. xxxx
3. xxxx

#### 参与贡献

1. Fork 本仓库
2. 新建 Feat_xxx 分支
3. 提交代码
4. 新建 Pull Request


#### 码云特技

1. 使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2. 码云官方博客 [blog.gitee.com](https://blog.gitee.com)
3. 你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解码云上的优秀开源项目
4. [GVP](https://gitee.com/gvp) 全称是码云最有价值开源项目，是码云综合评定出的优秀开源项目
5. 码云官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6. 码云封面人物是一档用来展示码云会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
---
layout: post
title: 技术百宝箱
tags: [common]
---

技术百宝箱 —— *技术点滴*
		
1. **Php扩展**
	
    ```
	1. 在 php/ext 下执行 ./ext_skel   --extname=module 扩展支持 C 的模块module
	2. 修改 module/config.m4 (使能*--with-module*或者*--enable-module*， 添加子目录等)
	3. 在 php 目录下执行/buildconf --force 生成php根目录下的configure文件
	4. 执行php下的configure 命令时加上 --witch-module（或者 --enable-module） 选项生成Makefile，并make
	5. 
	```
	**注：** *Php扩展支持调用c函数P， 当在扩展目录中添加子目录后，需要删掉php目录下configure 及其缓存项，然后再buildconfig生成新的configure文件才能生效。*
    
    [php 调用 C 函数详解](http://blog.csdn.net/oyd/article/details/3168417)
    
2. **Linux 相关**

	[linux下限制进程在多核cpu中指定cpu上运行](http://blog.sina.com.cn/s/blog_a39910330101dgqe.html)
    
3. **ssh 命令 相关**
	
    [ssh 免密码登陆](http://www.tuicool.com/articles/v2amAva)
    
    [25 个必须记住的ssh命令](http://www.cnblogs.com/weafer/archive/2011/06/10/2077852.html)
    
    [linux下expect安装](http://blog.163.com/023_dns/blog/static/118727366201291142252757/)
    
    [linux expect的使用详解](http://www.2cto.com/os/201305/209909.html)
    
    [移植 expect5.45](http://www.csdn123.com/html/topnews201408/51/14751.htm)
    [Expect+TCL8.6交叉编译 arm-linux](http://blog.sina.com.cn/s/blog_43ffbf3e0101afir.html)
    
4. **Python 相关**
	
	[交叉编译Python 3.3](http://xiaoxia.org/2013/09/13/python-on-tomato/)
    
    [交叉编译 Python](http://randomsplat.com/id5-cross-compiling-python-for-embedded-linux.html)
    
    [交叉编译 Python 支持sqlite3](http://www.java123.net/v/988575.html)
    
    [Python sqlite3 完整篇](http://www.cnblogs.com/hongten/p/hongten_python_sqlite3.html)
    
5. **兴趣**
	
    [创业必读的7本书](http://www.fortunechina.com/business/c/2015-09/02/content_246408.htm?source=yd)
    
    [大牛常访问论坛](http://www.oschina.net/question/2250952_2138973)
    
    [linux-网桥原理分析](http://blog.csdn.net/mrwangwang/article/details/8393973)
    
    [可执行文件及可连接文件的格式](http://www.360doc.com/content/14/0626/20/7377734_390077391.shtml)
    
    [可执行文件格式](http://blog.chinaunix.net/uid-27004952-id-3361448.html)
    
    [java 实战视频](http://www.ulewo.com/)
    
    [python 搭建微信公众平台](http://my.oschina.net/yangyanxing/blog/159215)
    
    [红黑树动态图](http://www.cnblogs.com/yangecnu/p/Introduce-Red-Black-Tree.html)
    
    [octeon 资料](http://www.360doc.com/userhome/8887027)
    
    [阮一峰的博客资料](http://www.ruanyifeng.com/blog/2015/06/poisson-distribution.html)
    
    [802.1x+RADIUS认证计费技术原理及设置](http://wenku.baidu.com/view/5d0c6beb5ef7ba0d4a733ba6.html?re=view)
    
    [Nat 原理与 Nat 穿越](http://www.cnblogs.com/bo083/articles/2170189.html)
    
    [用 Org-mode 实现GTD](http://www.cnblogs.com/holbrook/archive/2012/04/17/2454619.html)
    
    [org-mode 简明手册](http://www.cnblogs.com/Open_Source/archive/2011/07/17/2108747.html#sec-9-1)
    
    [capwap学习笔记——初识capwap](http://www.cnblogs.com/xmphoenix/p/3806844.html)
    
    [flex+yacc or flex+bison](http://www.cnblogs.com/itech/archive/2012/03/04/2375746.html)
    
    [iptables 深度解析：filter篇](http://blog.jobbole.com/89942/)
    
6. **网页设计 微博**
	
    [什么叫做会设计](http://weibo.com/1773655610/DkhJm5ZUW)
    
    [什么叫做不会设计](http://weibo.com/1773655610/DkhxyqOuw)
    
    [动物Logo设计](http://weibo.com/1773655610/Dkh4huUTR)
    
    [画个大白兔奶糖](http://weibo.com/1773655610/DkgqljSsE)
    
    [爸！我想当设计师](http://weibo.com/1773655610/Dkg3a3KeW)
    
    [每日动图！可以看一天系列](http://weibo.com/1773655610/Dkf40gjiR)
    
    [“这设计，我不想做了…”为什么，因为](http://weibo.com/1773655610/DkeF2bost)
    
    [涨姿势！让视觉设计变得高效+有说服力的4个步骤](http://weibo.com/1773655610/Dkek4i6KQ)
    
    [和设计师做朋友,是怎样一种体验.](http://weibo.com/1773655610/DkdUyz6Yf)
    
    [这应该是设计界最难拿的最高奖项吧](http://weibo.com/1773655610/DkcVtd92x)
    
    [酷站两连发！人气爆棚的网页选色器+专业设计师严选的免费素材](http://weibo.com/1773655610/DkcBt13QS)
    
    [求职宝典！新人交互设计师的作品集制作方法（附优秀案例）](http://weibo.com/1773655610/Dkcpio1gX)
    
    [让你的LOGO被采纳！八个步骤帮你优化LOGO设计流程](http://weibo.com/1773655610/Dkcd7mvRC)
    
    [PS基础教程！教你创建合成火の女](http://weibo.com/1773655610/Dkc0WmdsN)
    
    [ps:优设电台入口](http://music.163.com/#/djradio?id=6871001)
    
7. **swift 极客学院**
	
    [swift 极客学院](http://wiki.jikexueyuan.com/project/swift/)

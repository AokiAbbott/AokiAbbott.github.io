---
layout:     post
title:      "Jekyll Blog搭建日志（1）"
subtitle:   "踩坑不止"
date:       2019-01-07
author:     "AokiAbbott"
header-img: "img/bg-default.jpg"
tags:
   - Jekyll 
   - 技术日志
---

>Holy Shit!

### 牢骚在前

在经历了一系列反复的调试之后，自己的博客终于初见端倪，尽管难度不大，但还是踩了很多的坑（十分的烦躁），所以特此记录，以效后者。

### 正题

* 关于Jekyll的配置

	Jekyll是依赖于
	Ruby的生成静态Blog页面的工具，那自然需要进行**Ruby**的环境配置。具体步骤不再啰嗦，值得注意的是由于大中华局域网的问题，
	`gem source`的地址应改为*https://gems.ruby-china.com*而原来的淘宝镜像以及*https://gems.ruby-china.org*已经失效。
	当然目录下的`Gemfile`的**source**属性也应一同修改为上述地址。
	* 关于Github的托管
	
	可能还是由于网络的原因，Github Page的部署有些延迟，起初我一度认为页面的生成有问题（无CSS装饰），但经过测试页面对于内容的修改也没有响应
	。过了一段时间又自动回复正常（火大）。
	
* 关于yml的配置
		
	yml的配置按照说明改写，另外适应适应`md`的书写格式即可。
	
### 后记

下一步考虑细节上的装修问题，以及无效链接的清理工作，再看看有什么有趣的插件，如有可能进行域名绑定。回顾搭建过程，实在没有多少技术含量，
与其增强了代码能力，倒不如说对文档的检索能力有所帮助，无论是git命令，github平台，ruby环境，Jekyll建立了初步的了解，为以后技术的辐射
和延伸打下基础。
最后还是应当感谢本博客主题的作者[Hux](https://github.com/Huxpro/huxblog-boilerplate)详尽的配置说明，
以及实际`fork`的对象[cirno380a](https://github.com/cirno380a/cirno380a.github.io)的修改。

>另附可能需要的文档 [jekyll文档](https://www.jekyll.com.cn/)，
[Markdown语法手册](https://www.zybuluo.com/mdeditor?url=https://www.zybuluo.com/static/editor/md-help.markdown)。 
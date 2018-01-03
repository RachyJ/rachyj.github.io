---
layout: post
title: 谈谈刚需和360影视
category: selfedu
description: 一个看起来很简单的需求，做起来真的有那么困难吗，到底是怎么回事？
---

# How to copy a Github page site and create your own


1. Open the repository of a Github page site whose style you want to use.  https://github.com/ishanshan/ishanshan.github.io
2. fork to your github account
3. update settings | repository name to <your github name>.github.io
4. try <your github name>.github.io
5. clone repository to your local disk
6. update info on "_layouts | default.html", replace "ishanshan" to your info

    <meta name="author" content="ishanshan" />
    <meta name="description" content="ishanshan's Blog" />

	<div class="home-contact">
	            <a href="http://weibo.com/1696816107/profile" target="_blank" style="margin-left:-5px;"><img src="http://openmindclub.qiniudn.com/ishanshan/image/iconWeibo.png" alt="" width="25"/></a>
	            <a href="http://ishanshan.top/murmur/AboutMe.html" target="_blank" style="text-align:center;"><img src="http://openmindclub.qiniudn.com/ishanshan/image/ishanshan.png" alt="" width="22"/></a>
				<a href="https://github.com/ishanshan" target="_blank" style="text-align:center;"><img src="http://openmindclub.qiniudn.com/ishanshan/image/iconGitHub.png" alt="" width="22"/></a>
				<a href="http://www.slideshare.net/ssusere6acd7/presentations" target="_blank" style="text-align:center;"><img src="http://openmindclub.qiniudn.com/ishanshan/image/iconSlideshare.png" alt="" width="22"/></a>
	        </div>

7. update CNAME file to your own domain. If you don't have your own domain, just remove the line 'ishanshan.top'.

8. remove the articles under '_posts' and add your own. Remember to put the header like below:

---
layout: post
title: 命名用英文，烦恼少大半 | 团队文档命名指南
description: 文档命名看似简单，但其实体现你对你的对象在当前体系中的关系/作用的理解，往大了说，命名还直接反映你对整个资源结构的理解。
category: community
---

9. Update 'aboutme' file under _posts/Murmur/ to your own info.

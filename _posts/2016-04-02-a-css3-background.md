---
layout: post
date: 2016-04-02
title: A Beautiful CSS3 Background
---

![background](/images/background.png)

### CSS3实现背景渐变
<hr>
Inspired by [Fabric website](https://get.fabric.io/)

例子中 class = background 的上级元素是 \<body>，使用时记得把上级元素设置成 overflow:hidden;

CSS

	<style>
    	.body{
      		height:100%;
      		width:100%;
      		overflow: hidden;
    	}
    	.background{
      		height:200%;
      		width: 200%;
      		margin:0;top:0;
      		padding-top:40%;
      		left:-50%;
      		position: fixed;
      		background: -moz-radial-gradient(#09c ,#000, #000);
      		background: -o-radial-gradient(#09c ,#000, #000);
      		background: -ms-radial-gradient(#09c ,#000, #000);
      		background: -webkit-radial-gradient(#09c ,#000, #000);
      		background: -webkit-gradient(radial,from(#09c),to(#000));
    	}
  	</style>


HTML

	<body>
  		<div class="background">
	</body>

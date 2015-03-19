---
layout:       post
title:        Hello World
category:     blog
description:  Hello World
---


<blockquote><p style="
    color: gray;
">某程序员退休后决定练习书法，于是重金购买文房四宝。一日，饭后突生雅兴，一番研墨拟纸，并点上上好檀香。定神片刻，泼墨挥毫，郑重地写下一行字：hello world!</p></blockquote>

## 感谢
* 感谢Github提供这样一个写博客的平台
* 感谢我的码友兼高中同桌[Kimmy][]帮助我搭建这个博客


## 如何用 Github 建立个人博客
+ Mac 环境
  - 搭建好 Github 环境 [安装教程][link2]
  - 新建一个 Repository 名字叫 yourname.github.io
  - 提交一个 index.html 文件，然后 push 到 GitHub 的 master 分支
  - 访问 yourname.github.io 就可以看到你上传的页面了
<!-- + 本人是写ios出生，第一次建立网页，具体参考[这篇文章][link1] -->


## 本地调试
+ Mac 环境
  - 安装 jekyll [本地Jekyll环境的搭建][link3]
  - 打开 terminal 输入 <code>jekyll -v</code> 查看版本

  <pre class="prettyprint linenums">
    $ jekyll -v
    jekyll 2.5.3
  </pre>
  - 在 terminal 里 cd 到项目目录，输入 <code>jekyll serve --watch</code>
  - 浏览器访问 http://localhost:4000 即可


## 参考
><a href = "http://beiyuu.com/github-pages" class="external" target="_blank">http://beiyuu.com/github-pages</a>
<br>
><a href = "http://kimmykuang.github.io/local-jekyll.html">http://kimmykuang.github.io/local-jekyll.html</a>



<!-- 注释 -->

 [Kimmy]:    http://kimmykuang.github.io/
 [link2]:    https://help.github.com/articles/set-up-git/
 [link1]:    http://beiyuu.com/github-pages/
 [link3]:    http://kimmykuang.github.io/local-jekyll.html

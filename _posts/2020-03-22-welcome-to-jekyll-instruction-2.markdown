---
layout: post
title:  "Instruction Set For Jekyll "
date:   2020-03-22 03:48:04 +0400
categories: jekyll update
---

# 1. Starting Jekyll instalaltion
First we need to download RubyInstaller for windows (if your using windows). I have installed Ruby 2.4.2-2(x64) 
(latest version you need is 2.1 version).
Run .exe , finish. Run 1, 2, 3 options in order.
Open cmd check 

`ruby -v` and  `gem -v`.

Now we are ready to install Jekyll.

Run >`gem install jekyll bundler `

Check if it installed

`jekyll -v.` 

Finish.


# 2. Creating a Site | Jekyll - Static Site Generator
Open text editor and cmd. Navigate to folder to save.  

Run >` jekyll new nameofsite` .

Move to new directory.

Run >` bundle exec jektll serve`  

This command will start website on our local computer.

_posts will be the main folder to use.
_site is folder for all generated file output (finished product)
_cinfig.yml (is settings)
Gamefile is important file for spesifieing some plugins.
about.md - can be modifie  
index.md - can be modifie 


# 3 Front Matter | Jekyll - Static Site Generator

Open blog post in _posts
There you will see front mather in (--- layout:titel...---).
Frontmether is writen on 2 laug. YAML JSON.
You define custom frontmather variables.
For example 
author: "Mike"
You can access new frontmather varibles from HTML.


{% highlight ruby %}
git add . 
git commit -m "asdsdsdsa"
git push
{% endhighlight %}


![My helpful screenshot](/assets/photos/slides-page-18.jpg) 

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/

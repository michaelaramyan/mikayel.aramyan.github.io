## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/michaelaramyan/mikayel_aramyan.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown Look

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)

# Starting Jekyll instalaltion
First we need to download RubyInstaller for windows (if your using windows). I have installed Ruby 2.4.2-2(x64) 
(latest version you need is 2.1 version).
Run .exe , finish. Run 1, 2, 3 options in order.
Open cmd check 
ruby -v and  gem -v.
Now we are ready to install Jekyll.
Run >gem install jekyll bundler 

Check if it installed
jekyll -v. 

Finish.

# Creating a Site | Jekyll - Static Site Generator
Open text editor and cmd. Navigate to folder to save. 
Run >jekyll new nameofsite.
Move to new directory.
Run >bundle exec jektll serve 
This command will start website on our local computer.
_posts will be the main folder to use.
_site is folder for all generated file output (finished product)
_cinfig.yml (is settings)
Gamefile is important file for spesifieing some plugins.
about.md - can be modifie  
index.md - can be modifie 

# Front Matter | Jekyll - Static Site Generator
Open blog post in _posts
There you will see front mather in (--- layout:titel...---).
Frontmether is writen on 2 laug. YAML JSON.
You define custom frontmather variables.
For example 
author: "Mike"
You can access new frontmather varibles from HTML.

 
 
# Writing Posts | Jekyll - Static Site Generator.
Each blog requiers data-title-.
Crate new file EX: 2017-09-22-my-first-blog.md(markdown file).
First include Front mather.
---
layout: "post"
title: "This is new titile"
data: do not change page data

---
You can also crate directorys in +posts to manege you blog posts.
Orgnize your blogs in directorys.

# Working With Drafts | Jekyll - Static Site Generator

You can crate draft file by crateing _drafts folder in the main directory.
You can include front mather.
New markdown file in drafts will not shown in website.
if you run 

jekyll serve --draft

it will show the draft file on website. The date will be current data 
when you run the command.

# Creating Pages | Jekyll - Static Site Generator

There is about .md file which can be used, but also you can create 
your own page like about.md for example donation.md in main firectory
add YAML front matere
---
layout: "page"
title: name 
---
you can access 
http://127.0.0.1:4000/donation.md

# Permalinks | Jekyll - Static Site Generator


```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/michaelaramyan/mikayel_aramyan.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

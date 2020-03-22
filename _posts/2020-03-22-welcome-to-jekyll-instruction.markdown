---
layout: post
title:  "Instruction Set"
date:   2020-03-22 03:48:04 +0400
categories: jekyll update
---
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

`YEAR-MONTH-DAY-title.MARKUP`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. After that, include the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/

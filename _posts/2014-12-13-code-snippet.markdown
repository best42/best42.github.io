---
layout: post
title:  "Post With A Code Snippet"
date:   2014-12-13
---

This is how to push project of html into github:

1. To check condition of your Git repository
{% highlight ruby %}
git init
{% endhighlight %}

2. To create origin in order to push the work into github
{% highlight ruby %}
git remote add origin https://github.com/best42/best42.github.io.git
{% endhighlight %}
* (https://github.com/best42/best42.github.io.git) this will change according to your name of repository

3. To check whether there has change in your work or not
{% highlight ruby %}
git status
{% endhighlight %}

4. To add new work
{% highlight ruby %}
git add .
{% endhighlight %}

5. To make a checkpoint of your work
{% highlight ruby %}
git commit -m “initial commit“
{% endhighlight %}
* (“initial commit“) you can whether you want but tip from me is to make a name that suit with change to your work

6. Push yout work into github
{% highlight ruby %}
git push -u origin master
{% endhighlight %}

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll's GitHub repo][jekyll-gh].

[jekyll-gh]: https://github.com/mojombo/jekyll
[jekyll]:    http://jekyllrb.com

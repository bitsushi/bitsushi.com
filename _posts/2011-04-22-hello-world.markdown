---
layout: post
title: Hello World
---

So first you will want to download [jekyll](https://github.com/mojombo/jekyll)
{% highlight sh %}
gem install jekyll
{% endhighlight %}

Then make an empty directory for your blog and build a skeleton template by issuing the following command inside it
{% highlight sh %}
touch _config.yml index.html && mkdir _layouts _posts && echo "auto: true" >> _config.yml && echo "Hello World!" >> index.html
{% endhighlight %}

Now you're ready to check everything has worked by running the server command below and then visiting http://0.0.0.0:4000/
{% highlight sh %}
jekyll --server
{% endhighlight %}
If you see the text 'Hello World!' you're rocking Jekyll son!
---
layout: post
title:  "Hello World"
date:   2015-06-23 13:24:30
categories: news
---

Test Snytax Highlighting:

{% highlight ruby %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}
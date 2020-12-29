---
layout: page
title: Codes
subtitle: Useful Codes
---
{: .box-note}
**Clone all Repositories of a User**
{% highlight javascript linenos %}
curl -s https://api.github.com/users/HackWeiser360/repos | grep \"clone_url\" | awk '{print $2}' | sed -e 's/"//g' -e 's/,//g' | xargs -n1 git clone
{% endhighlight %}
{: .box-note}
**Give alert on a html File**
{% highlight javascript linenos %}
<script>
     alert('Hello Dude !');
     alert('HackWeiser360 Was Here');
     alert('I am Just Testing Your System')
</script>
{% endhighlight %}

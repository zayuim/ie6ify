# ie6ify
Javascript Bookmarklet to make your web experience more like Internet Explorer 6!

This is an old bookmarklet I discovered back in 2013, The [original website is down](https://web.archive.org/web/20140626141851/http://ie6ify.com/) So I am hosting the code here.

This script is of course satricial, but fun anyways.

When you're ready drag the link below to your bookmarks bar

# [IE6ify]("javascript:(function(){var%20i=0,r=function(n){return%20Math.floor(Math.random()*n)},f=document.getElementsByTagName('body')[0].getElementsByTagName('*'),o=function(e){return%20typeof(e.style)=='object'&&e.tagName!='SCRIPT'},s=function(){while(!o(e=f[r(f.length)])){}return%20e.style};while(i++<5){s().display=r(2)?'block':'inline';s().position=r(2)?'absolute':'relative';s().margin=r(2)?'0':'1em';s().padding=r(2)?'0':'1em';s().width=r(2)?'':'auto';}})();")

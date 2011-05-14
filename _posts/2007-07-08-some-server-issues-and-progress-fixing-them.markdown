--- 
layout: post
title: Some server issues - and progress fixing them
wordpress_id: 113
wordpress_url: http://topstartup.com/2007/07/08/some-server-issues-and-progress-fixing-them/
---
<a href="http://slicehost.com"><img src="http://topstartup.com/wp-content/uploads/2007/07/slicehost.thumbnail.png" title="Slicehost" alt="Slicehost" align="left" /></a>I have this site running on a <a href="https://manage.slicehost.com/customers/signup?referrer=134731736">Slicehost</a><a href="https://manage.slicehost.com/customers/signup?referrer=134731736"> VPS</a>. I have <a href="http://topstartup.com/2007/05/10/overpromise-underdeliver-a-recipe-for-disaster/">previously raved about</a> <a href="https://manage.slicehost.com/customers/signup?referrer=134731736">Slicehost</a>. About a week ago I started to notice the site going down. To know when that happens, I use a free service called <a href="http://montastic.com/">Montastic</a>. Montastic will alert me by email if my site (or up to 9 others) go down. This is great when you have to maintain multiple sites across multiple servers (or if you want to know if someone else dropped the ball!).<!--more-->

In order to secure my box and try to avoid my site going down, Im following the recommendations of a tutorial on the site Usefuljaja about <a href="http://www.usefuljaja.com/2007/4/ubuntu-setup-page-1">how to configure an Ubuntu 6.06 install on Slicehost</a>. They even have a great tip on <a href="http://www.usefuljaja.com/2007/4/ubuntu-setup-page-3">reducing the memory footprint of MySQL</a>. I've also got <a href="http://www.shorewall.net/">Shorewall</a> and Fail2Ban running in order to stop automated scripts from bothering my server too much.

The server went down for a couple of hours today. Tonight I removed my custom iptables script which seemed to be bothering Shorewall. Hopefully, now the server will stay up and can continue to deliver this quality content to you, the wonderful reader!

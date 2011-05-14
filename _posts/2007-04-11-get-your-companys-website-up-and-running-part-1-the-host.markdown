--- 
layout: post
title: Get your company's website up and running! Part 1 - The host.
wordpress_id: 26
wordpress_url: http://topstartup.com/2007/04/11/get-your-companys-website-up-and-running-part-1-the-host/
---
One of the first things a new company <em>needs</em> to do is get their website up and running. What I'll deal with in the first of a two part series is Where. The next part, I'll deal with How and What.

<!--more-->
Picking a web host is an important task. The performance, and uptime of your site reflect on your company. A common theme among web hosts is overselling their services to make a buck. Here are the different types of hosts you can choose.
<ol>
	<li><strong>Shared</strong> - multiple websites are hosted on a physical server</li>
	<li><strong>Dedicated</strong> - only your website is hosted on your own physical server</li>
	<li><strong>Clustered</strong> - multiple websites are hosted on multiple machines</li>
	<li><strong>Virtual Private Server (VPS)</strong> - multiple websites are hosted on a physical server, each with their own virtual server</li>
</ol>
Again, any of the three shared solutions could be great for you, but the key is finding a company who will do the right thing and not sell service to others at the detriment of yours.
<h4>Shared</h4>
Shared hosting is the most basic kind of affordable webhosting. In shared hosting, there will be multiple websites configured and hosted on a machine. The database, webserver and any other services would be shared between all users. I.e., if one site on your server gets Slashdotted / Dugg, you will likely suffer. Another issue with this type of setup is flexibility. If you need software (other than php / cgi apps) that isnt on the server, good luck! In this area, <a href="http://www.dreamhost.com/">Dreamhost</a> has a pretty good reputation. I used <a href="http://digitalspace.net/">Digitalspace</a> for 6 years or so but now consider their offering behind the times.
<h4>Dedicated</h4>
For many small startups, the dedicated setup is beyond their reach. The limiting factor is not as much hardware as it is bandwidth. I can build a killer server, but the required internet connection to my house or office will likely be too costly for me to make it worthwhile. Internet traffic is not constant, it tends to ebb and flow. Large datacenters better manage these ebbs and flows than do your DSL / Cable connection! You can pay for a dedicated server in a datacenter likely starting at $50 a month or so for crap, and $100 a month for something close to usable. Downsides to this approach are cost and flexibility. It's difficult to significantly increase the power of your site without adding to the physical machine. For this type of setup, I would recommend <a href="http://voxel.net/">Voxel.net</a> for reliable hosting. These guys really know what they are doing.
<h4>Clustered</h4>
After Michael Arrington recommended <a href="http://www.techcrunch.com/2006/10/17/media-temple-crushes-shared-hosting/">Mediatemple's Gridserver</a> product on Techcrunch, there were a flood of users to that product. What is great about it is you get a heck of a lot for $20 a month. What's bad is the downtime (due to database problems) and the slow speed of sites. This site is hosted on Mediatemple's Gridserver. If it seems slow, you know who to blame! For this blog, it works, but this is not the product I would select as the vehicle for the public image of my company. On paper, the "Grid" sounds fantastic. It just doesnt seem to work out the way it says on the box. The promise of limitless power is pure marketing B.S. Im not familiar with other companies, but if price is your only objective, you can host MANY sites for just $20 a month.
<h4>Virtual Private Server (VPS)</h4>
VPSs are my new favorite toy and my worst enemy at the same time. Using software like <a href="http://en.wikipedia.org/wiki/Xen">Xen</a> or <a href="http://en.wikipedia.org/wiki/Openvz">OpenVZ</a>, hosting companies are now able to offer configurability of a dedicated server with the price, just a little higher than shared hosting. What you get is a choice between different linux distros and full root access to the server. What this means, is that no matter what you want to install / do with your server, if it can be done on linux, you can do it. For a project that we were working on, we wanted a website to call a C++ application. Dedicated or VPS were the only options of these. We didnt want to go with a dedicated, so we ended up getting 2 Virtual Private Servers, one for development and one for production. Each of these costs $32 a month from <a href="http://vpslink.com">VPSLink</a>. The BIG downside of this is that if you are scared of Linux administration, don't look at these. If you need ultimate flexibility, they are a fantastic option. As a couple of recommendations, check out <a href="https://manage.slicehost.com/customers/signup?referrer=134731736">Slicehost</a> and then <a href="http://vpslink.com">VPSLink. I've heard a lot of people raving about </a><a href="https://manage.slicehost.com/customers/signup?referrer=134731736">Slicehost</a> recently.

So, there you have it. Different options for different needs. If after reading this you are not sure what would work for you, send me a message, and I'd be happy to help!

Next time we're going to cover content management, design, and words (the content itself!).

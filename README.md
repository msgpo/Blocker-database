# NoScript-Whitelist


A global domain database for NoScript powered by the crowd.


This project is original designed by CHEF-KOCH and it's under Apache License v2.0 (see License). 


The goal of this project is to get an (nearly) complete whitelist for NoScript, in fact it's created due the fact that e.g. Tor Browser temp. enable all domains, personally I don't like this, so this is the reason I created this.


So how to report a 'trusted' domain/page?
---------------

* Ensure no bad reputation is avlb for your homepage.
* Ensure safe-browsing not blocked your site, I not added pages which are detected by safe-browsing even if they are okay, because to the simply reason we possible get troubles.
* Check yourself (if possible) that the domain / page isn't comprmised by e.g. XSS or other attacks (of course needs some knowlage).
* Check the page/domain if the webmaster is trusted and all whois given information are valid and nothing is missing.
* Of course ads is no argument to block the entire page since this is an common thing, and w all need to pay our bills. But if the ads coming with malware in it, I will not add the page for security reasons.
* ....


What is the benefit?
---------------


I think most stuff can be blocked by disabling .js on common pages, so instead to temp allow all I prefer whitelists. In fact this would helo because all other pages are by default 'blocked'. 


How can you help?
-----------------

Easy and simple.

Open up about:config and search for capability.policy.maonoscript.sites, now double click on it and you will see your trusted list, feel free to submit but please ensure it's not already added (dublicates).
It doesnÄt really matter much if you use http:// format or only the domain, since it can anyway handled by NoScript and it's settings (if you need another format just replace e.g. http:// with your fav. text editor).



Reference
-----------------

* https://noscript.net/
* https://forums.informaction.com/viewforum.php?f=3
* https://addons.mozilla.org/en-US/firefox/addon/noscript/
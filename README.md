A global domain database for NoScript/uBlock/uMatrix/ScriptSafe powered by the community - which means YOU!


This project is original created by [CHEF-KOCH](https://github.com/CHEF-KOCH) and it's under Apache License v2.0 (see [License](https://github.com/CHEF-KOCH/NoScript-Whitelist/blob/master/LICENSE)). 


The goal of this little project is to get an almost _complete_ whitelist for NoScript/uBlock/uMatrix & ScriptSafe, it's created due the fact that e.g. Tor Browser temporarily allow all domains by default - personally I don't like this, so this is one of the reasons I created the project; another reason is to avoid syncing with a Mozilla or Google cloud.


Usage
---------------
* Go to and click through the Firefox about:config warning. 
* Use the search box to find your whitelist and blacklist. 
* The whitelist is called `capability.policy.maonoscript.sites`. 
* The blacklist is called `noscript.untrusted`. 
* Right click --> 'Modify' to edit the value. 
* You can either replace your existing values or add our values as you see fit.


Contributing to list
---------------

* Download and import the latest list from this repository.
* Find your whitelist and blacklist as described above.
* To add to whitelist, ensure no bad reputation is present for your reported page.
* Your website must not be blocked by the [built-in safe-browsing feature](https://www.google.com/safebrowsing/static/faq.html).
* If you know how to, please confirm the page is not compromised by XSS or other attacks.
* Check the page/domain if the webmaster is trusted and all whois given information are valid and nothing is missing.
* It does not matter much if you use the http:// or https:// prefix on domains as NoScript handles this.


What are the benefits?
---------------

* I think most stuff can be blocked by disabling javascript on websites, so instead to temporarily allow all sites access to javascript I prefer to whitelist the 'secure' ones. In fact this would help, because all other pages are by default blocked.
* A community based list is easier to maintain + there is less space for problems, the four eyes principle! 


What about the cons?
---------------

* The negative thingy is that this is more about user needs, if you never visit xyz listed page you normally not need to whitelist them, but on the other hand it's not dangerous because they are trustworthy and should never connect to your pages (except social pages for e.g. the little share buttons).
* Another thing is that you also could just block the entire domain via router, so this would mean this would have no affect. 
* All social media platforms except Twitter are blocked.
* Static filtering requires a lot of effort because you need to check each entry manually.


Can I import NoScript settings in e.g. addons like uMatrix?
---------------

You can import whitelist NoScript rules. Go to the 'My rules' pane in uMatrix's dashboard, then click Import from file. You can select a NoScript backup file and uMatrix will import what it can from the backup file. The imported rules will apply to the script column of the global scope only.


Known issue
---------------

The following issue are not directly related to this project, there addon/extension related:

* [#4](https://github.com/CHEF-KOCH/NoScript-Whitelist/issues/4) 
* [#5](https://github.com/CHEF-KOCH/NoScript-Whitelist/issues/5)


Project based issue:

* [#7](https://github.com/CHEF-KOCH/NoScript-Whitelist/issues/7)



Reference
-----------------

* https://noscript.net/
* https://forums.informaction.com/viewforum.php?f=3
* https://addons.mozilla.org/en-US/firefox/addon/noscript/
* https://webtransparency.cs.princeton.edu/webcensus/

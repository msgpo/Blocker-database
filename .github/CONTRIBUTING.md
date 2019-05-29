### Before you submit

* Make sure your issue [hasn't already been fixed/mentioned] in a recent release/issue ticket.
* Verify that the issue does **not** occur with uBlock/uMatrix/ScriptSafe/NoScript disabled.
* **Verify that the issue is not related to a 3rd-party filter lists.**
    - Issues with 3rd-party filter lists are the responsibility of their respective maintainers.
* Verify that the issue is not caused by another extension.
* Do not submit issues which can be reproduced **only** on Chrome Canary or Firefox Nightly: these are not stable browser versions and in all likelihood, whatever issue is not within this project.
    - Report **only** if you can reproduce in an official stable release, or a beta release.
* Do not submit a ticket without any necessary information like 'why', 'how',...


#### Filter lists

##### Ordering of filters

New filter must be added at the end of the list.

The reason is to provide an easy way to check whether a filter is still relevant. The filters at the top of the file will be the oldest filters, and also the most likely to maybe be obsolete.

Old filters which are confirmed to still be required must be moved to the end of the list.

Here and there after the filters are approved and working, we order the list alphabetically (max once per month). 


##### Commit message

Keep it simple, example: `this fixes #2`. The issue itself will contains all the details.

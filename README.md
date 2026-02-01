[EasyDutch](https://github.com/EasyDutch-uBlockOrigin/EasyDutch):
[![Commit rate](https://img.shields.io/github/commit-activity/y/EasyDutch-uBlockOrigin/EasyDutch?label=Commits&color=succes)](https://github.com/EasyDutch-uBlockOrigin/EasyDutch/commits/)
[![Last commit](https://img.shields.io/github/last-commit/EasyDutch-uBlockOrigin/EasyDutch?label=Last%20commit&color=informational)](https://github.com/EasyDutch-uBlockOrigin/EasyDutch/commits/)
[![Issues](https://img.shields.io/github/issues/EasyDutch-uBlockOrigin/EasyDutch?label=Issues&color=red)](https://github.com/EasyDutch-uBlockOrigin/EasyDutch/issues)
[![Issues](https://img.shields.io/github/issues-closed/EasyDutch-uBlockOrigin/EasyDutch?color=green&label=Issues)](https://github.com/EasyDutch-uBlockOrigin/EasyDutch/issues?q=is%3Aissue+is%3Aclosed)
[![License](https://img.shields.io/badge/License-GPLv3-blue.svg?label=License&color=lightgrey)](https://github.com/EasyDutch-uBlockOrigin/EasyDutch/blob/main/LICENSE) <br>
(( [EasyList Dutch](https://github.com/easylist/easylistdutch/):
[![Commit rate](https://img.shields.io/github/commit-activity/y/easylist/easylistdutch?label=Commits&color=succes&style=plastic)](https://github.com/easylist/easylistdutch/commits/)
[![Last commit](https://img.shields.io/github/last-commit/easylist/easylistdutch?label=Last%20commit&color=informational&style=plastic)](https://github.com/easylist/easylistdutch/commits/master)
[![Issues](https://img.shields.io/github/issues/easylist/easylistdutch?label=Issues&color=red&style=plastic)](https://github.com/easylist/easylistdutch/issues)
[![Issues](https://img.shields.io/github/issues-closed/easylist/easylistdutch?color=green&label=Issues&style=plastic)](https://github.com/easylist/easylistdutch/issues?q=is%3Aissue+is%3Aclosed) ))

***
# EasyDutch
Adblock filters for Dutch websites made for [uBlock Origin](https://github.com/uBlockOrigin/uAssets)

| Contents |
| --- |
| [EasyDutch](#easydutch) |
| [Contributing](#contributing) |
| [View and Subscribe](#view-and-subscribe-to-easydutch) |
| [Support](#support) |
-----
## [EasyDutch](https://github.com/EasyDutch-uBlockOrigin/EasyDutch)
The updated version of EasyList Dutch special for uBlock Origin. 

This filterlist has been made because the EasyList Dutch filter isn't maintained often and the maintenance that is done, is very poor. <br>
So I made this to provide you a better service!! <br>
This list also handles anti-adblock, which isn't done by EasyList Dutch. See these comments for more information: <br>
[easylist/easylistdutch#11 (comment)](https://github.com/easylist/easylistdutch/issues/11#issuecomment-818864565) and [easylist/easylistdutch#30 (comment)](https://github.com/easylist/easylistdutch/issues/30#issuecomment-1011180477).

If you see ads on Dutch websites please [report](https://github.com/EasyDutch-uBlockOrigin/EasyDutch/issues/new/choose) it to me or sent me an email to easydutch.adblock@gmail.com <br>

## [Contributing](https://github.com/EasyDutch-uBlockOrigin/EasyDutch/blob/main/CONTRIBUTING.md)
<details>
<summary>Contributing</summary>

> Important note: </br>
> We, **[@Ignotum77](https://github.com/Ignotum77)** and **[@JohnyP36](https://github.com/JohnyP36)**, owners of EasyDutch, prefer simplicity over complexity. So instead of `123geldzaken.nl##[class*="widget_sponsor"]` use `123geldzaken.nl##.widget_sponsor` and `123geldzaken.nl##.widget_sponsorlinks`. And instead of `arenalokaal.nl##[advobject]:upward(.bg-gray-100):has-text(/Uit de krant/i)` just use `arenalokaal.nl##[advobject]:upward(.bg-gray-100)`
> 
> #### Ordering of filters
> 
> New filters must be added on the top of each list.
> 
> The reason is to provide an easy way to check whether a filter is still relevant. The filters at the end of the file will be the oldest filters, and also the most likely to maybe be obsolete.
> 
> Old filters which are confirmed to still be required must be moved to the top of the list.
> 
> #### Issue number association
> 
> **All** added filters must be associated with a formal issue number or date, example:
> 
>     ! https://github.com/EasyDutch-uBlockOrigin/EasyDutch/issues/3
>     ||data.inertanceretinallaurel.com^
>     ! 2021-04-27
>     ||androidplanet.nl,iphoned.nl##.dynamic-content-native
> 
> This way we know why a filter was added, and how to verify whether an old filter is still needed. The comment line preceding the filter(s) to solve a specific issue should be only a URL to the issue. The issue itself can contains all the details about how the issue was solved, and why it was solved this way, etc.
> 
> #### Commit message
> 
> - Keep it simple, use `A:` for adding a site, `C:` for changing or updating rules, `R:` for removing, and `M:` for moving to other files. 
> - Put here after the site url `spele.nl` (no `https://www.`) 
> - Put after this the issue number. </br>
> Example: `A: spele.nl fix #3` or `C: nu.nl`. The issue itself will contains all the details.
> - If the issue doesn't occur on a homepage, but on a subpage please add in the message the full url (like `https://www.website.nl/sub/page.html`)
> 
> #### Hide General
> 
> You may only make General Hiding rules, if it applies to tree or more websites
> *******
> #### What you might do or not do as a contributor
> 
> As a contributor it is **forbidden** to change the following files:
> - `.github` folder 
> - `README.md`
> - `CONTRIBUTING.md`
> - `CODE_OF_CONDUCT.md`
> - `LICENSE`
> 
> The rest you may change.
> 
> Breaching this rule will result in a warning and, if not listening, being banned as contributor!

</details>

***
## View and Subscribe to EasyDutch

As you can see below, there are multiple way to subscribe to our list. We have following domains: `https://EasyDutch-uBlockOrigin.github.io/EasyDutch/`, `https://EasyDutch-uBlockOrigin.github.io/EasyDutchCDN/`, and `https://raw.githubusercontent.com/`. <br>

### Favorite order of subscription:
In the list, the normal website is the default. The `.all.txt` lists are used as primairy CDN's, where it is preferred to use `github.io` over `cdn.jsdelivr.net`, and `raw.githubusercontent.com`.
1. <a target="_blank" rel="noreferrer nofollow" href="https://easydutch-ublockorigin.github.io/EasyDutch/EasyDutch.txt"><code>EasyDutch</code></a> | <a target="_blank" rel="noreferrer nofollow" href="https://subscribe.adblockplus.org/?location=https://easydutch-ublockorigin.github.io/EasyDutch/EasyDutch.txt&amp;title=EasyDutch">Subscribe</a></br>
2. <a target="_blank" rel="noreferrer nofollow" href="https://easydutch-ublockorigin.github.io/EasyDutch/EasyDutch.all.txt"><code>All-in-One EasyDutch</code></a> | <a target="_blank" rel="noreferrer nofollow" href="https://subscribe.adblockplus.org/?location=https://easydutch-ublockorigin.github.io/EasyDutch/EasyDutch.all.txt&amp;title=EasyDutch">Subscribe</a></br>
3. <a target="_blank" rel="noreferrer nofollow" href="https://easydutch-ublockorigin.github.io/EasyDutchCDN/EasyDutch.all.txt"><code>All-in-One EasyDutchCDN</code></a> | <a target="_blank" rel="noreferrer nofollow" href="https://subscribe.adblockplus.org/?location=https://easydutch-ublockorigin.github.io/EasyDutchCDN/EasyDutch.all.txt&amp;title=EasyDutch">Subscribe</a></br>
4. <a target="_blank" rel="noreferrer nofollow" href="https://cdn.jsdelivr.net/gh/EasyDutch-uBlockOrigin/EasyDutchCDN@main/EasyDutch.all.txt"><code>All-in-One EasyDutchCDN Mirror</code></a> | <a target="_blank" rel="noreferrer nofollow" href="https://subscribe.adblockplus.org/?location=https://cdn.jsdelivr.net/gh/EasyDutch-uBlockOrigin/EasyDutchCDN@main/EasyDutch.all.txt&amp;title=EasyDutch">Subscribe</a> | [![](https://data.jsdelivr.com/v1/package/gh/EasyDutch-uBlockOrigin/EasyDutchCDN/badge)](https://www.jsdelivr.com/package/gh/EasyDutch-uBlockOrigin/EasyDutchCDN)</br>
5. <a target="_blank" rel="noreferrer nofollow" href="https://cdn.jsdelivr.net/gh/EasyDutch-uBlockOrigin/EasyDutch@gh-pages/EasyDutch.all.txt"><code>All-in-One EasyDutch Mirror</code></a> | <a target="_blank" rel="noreferrer nofollow" href="https://subscribe.adblockplus.org/?location=https://cdn.jsdelivr.net/gh/EasyDutch-uBlockOrigin/EasyDutch@gh-pages/EasyDutch.all.txt&amp;title=EasyDutch">Subscribe</a> | [![](https://data.jsdelivr.com/v1/package/gh/EasyDutch-uBlockOrigin/EasyDutchCDN/badge)](https://www.jsdelivr.com/package/gh/EasyDutch-uBlockOrigin/EasyDutch)</br>
6. <a target="_blank" rel="noreferrer nofollow" href="https://cdn.jsdelivr.net/gh/EasyDutch-uBlockOrigin/EasyDutch@gh-pages/EasyDutch.txt"><code>EasyDutch Mirror</code></a> | <a target="_blank" rel="noreferrer nofollow" href="https://subscribe.adblockplus.org/?location=https://cdn.jsdelivr.net/gh/EasyDutch-uBlockOrigin/EasyDutch@gh-pages/EasyDutch.txt&amp;title=EasyDutch">Subscribe</a></br>
7. <a target="_blank" rel="noreferrer nofollow" href="https://easydutch-ublockorigin.github.io/EasyDutchCDN/EasyDutch.txt"><code>EasyDutchCDN</code></a> | <a target="_blank" rel="noreferrer nofollow" href="https://subscribe.adblockplus.org/?location=https://easydutch-ublockorigin.github.io/EasyDutchCDN/EasyDutch.txt&amp;title=EasyDutch">Subscribe</a></br>
8. <a target="_blank" rel="noreferrer nofollow" href="https://cdn.jsdelivr.net/gh/EasyDutch-uBlockOrigin/EasyDutchCDN@main/EasyDutch.txt"><code>EasyDutchCDN Mirror</code></a> | <a target="_blank" rel="noreferrer nofollow" href="https://subscribe.adblockplus.org/?location=https://cdn.jsdelivr.net/gh/EasyDutch-uBlockOrigin/EasyDutchCDN@main/EasyDutch.txt&amp;title=EasyDutch">Subscribe</a></br>
9. <a target="_blank" rel="noreferrer nofollow" href="https://raw.githubusercontent.com/EasyDutch-uBlockOrigin/EasyDutch/gh-pages/EasyDutch.all.txt"><code>All-in-One EasyDutch Raw</code></a> | <a target="_blank" rel="noreferrer nofollow" href="https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/EasyDutch-uBlockOrigin/EasyDutch/gh-pages/EasyDutch.all.txt&amp;title=EasyDutch">Subscribe</a></br>
10. <a target="_blank" rel="noreferrer nofollow" href="https://raw.githubusercontent.com/EasyDutch-uBlockOrigin/EasyDutchCDN/main/EasyDutch.all.txt"><code>All-in-One EasyDutchCDN Raw</code></a> | <a target="_blank" rel="noreferrer nofollow" href="https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/EasyDutch-uBlockOrigin/EasyDutchCDN/main/EasyDutch.all.txt&amp;title=EasyDutch">Subscribe</a></br>
11. <a target="_blank" rel="noreferrer nofollow" href="https://raw.githubusercontent.com/EasyDutch-uBlockOrigin/EasyDutch/gh-pages/EasyDutch.txt"><code>EasyDutch Raw</code></a> | <a target="_blank" rel="noreferrer nofollow" href="https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/EasyDutch-uBlockOrigin/EasyDutch/gh-pages/EasyDutch.txt&amp;title=EasyDutch">Subscribe</a></br>
12. <a target="_blank" rel="noreferrer nofollow" href="https://raw.githubusercontent.com/EasyDutch-uBlockOrigin/EasyDutchCDN/main/EasyDutch.txt"><code>EasyDutchCDN Raw</code></a> | <a target="_blank" rel="noreferrer nofollow" href="https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/EasyDutch-uBlockOrigin/EasyDutchCDN/main/EasyDutch.txt&amp;title=EasyDutch">Subscribe</a></br>

### Explanation of used terms: 
- <code>EasyDutch</code> means that it is from the <a target="_blank" rel="noreferrer nofollow" href="https://github.com/EasyDutch-uBlockOrigin/EasyDutch/tree/gh-pages">original</a> GitHub-repro and hosted on <code>github.io</code>. <br>
&nbsp;&nbsp;&nbsp; Changes that are made, are applied after 5 minutes except for the Mirrors. <br>
&nbsp;&nbsp;&nbsp; I made a small delay to not overload the diffpatcher in GitHub Actions. <br>
- <code>EasyDutchCDN</code> is from the <a target="_blank" rel="noreferrer nofollow" href="https://github.com/EasyDutch-uBlockOrigin/EasyDutchCDN">EasyDutchCDN</a> GitHub-repro and hosted on <code>github.io</code>. <br>
&nbsp;&nbsp;&nbsp; Changes that are made in EasyDutch's main branch, are applied every two hours. Mirrors follow later. <br>
- <code>Raw</code> means that everything in that column is hosted on <code>https://raw.githubusercontent.com/</code>. <br>
- <code>Mirror</code> is <a target="_blank" rel="noreferrer nofollow" href="https://www.jsdelivr.com/"><code>jsDelivr</code></a>; a public and free CDN's. <br>
- <code>All-in-One</code> means that everything is one big file in stead of multiple files loaded in one file. <br>
&nbsp;&nbsp;&nbsp; This is to not overload/misuse the free CDN's. </br>

### List of domains we have:
1. https://easydutch-ublockorigin.github.io/EasyDutch/ --> `gh-pages` from [EasyDutch-uBlockOrigin/EasyDutch](https://github.com/EasyDutch-uBlockOrigin/EasyDutch/)
2. https://easydutch-ublockorigin.github.io/EasyDutchCDN/ --> `main` from [EasyDutch-uBlockOrigin/EasyDutchCDN](https://github.com/EasyDutch-uBlockOrigin/EasyDutchCDN/)
3. https://raw.githubusercontent.com/ --> `gh-pages` and 2x `main` from [EasyDutch-uBlockOrigin/EasyDutch](https://github.com/EasyDutch-uBlockOrigin/EasyDutch/), and [EasyDutch-uBlockOrigin/EasyDutchCDN](https://github.com/EasyDutch-uBlockOrigin/EasyDutchCDN/)
4. https://cdn.jsdelivr.net/ --> from [EasyDutch-uBlockOrigin/EasyDutch](https://github.com/EasyDutch-uBlockOrigin/EasyDutch/), and [EasyDutch-uBlockOrigin/EasyDutchCDN](https://github.com/EasyDutch-uBlockOrigin/EasyDutchCDN/) </br>
   `EasyDutch.txt` and `EasyDutch.all.txt` --> [EasyDutch-uBlockOrigin/EasyDutch](https://github.com/EasyDutch-uBlockOrigin/EasyDutch/), and [EasyDutch-uBlockOrigin/EasyDutchCDN](https://github.com/EasyDutch-uBlockOrigin/EasyDutchCDN/)


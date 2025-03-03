<div align="center">  
  <img width="550" alt="Whitelist logo" src="https://raw.githubusercontent.com/GoodnessJSON/PiHole-Whitelist/master/images/logo_new4.png">
</div>

<br />


<div align="center">
  <a href="#" > 
    <img src="https://img.shields.io/github/repo-size/GoodnessJSON/PiHole-Whitelist?label=Repo%20Size&color=orange" alt="repo size" >
  <a/>
   <a href="#" > 
    <img src="https://img.shields.io/github/stars/GoodnessJSON/PiHole-Whitelist?label=Stars" alt="stars" >
  <a/>   
  <a href="#" > 
    <img src="https://img.shields.io/github/last-commit/GoodnessJSON/PiHole-Whitelist?label=Last%20Updated" alt="last updated" >
  <a/>
   <a href="https://github.com/GoodnessJSON/PiHole-Whitelist/commits/master" > 
    <img src="https://img.shields.io/github/commit-activity/y/GoodnessJSON/PiHole-Whitelist?label=Commit%20Activity" alt="commit activity" >
  <a/>
  <a href="https://github.com/GoodnessJSON/PiHole-Whitelist/issues" > 
    <img src="https://img.shields.io/github/issues-raw/GoodnessJSON/PiHole-Whitelist?label=Open%20Issues&color=critical" alt="open issues" >
  <a/>
  <a href="https://github.com/GoodnessJSON/PiHole-Whitelist/issues?q=is%3Aissue+is%3Aclosed" > 
    <img src="https://img.shields.io/github/issues-closed-raw/GoodnessJSON/PiHole-Whitelist?label=Closed%20Issues&color=inactive" alt="closed issues" >
  <a/>
  <a href="https://github.com/GoodnessJSON/PiHole-Whitelist/graphs/contributors" > 
    <img src="https://img.shields.io/github/contributors/GoodnessJSON/PiHole-Whitelist?label=Contributors&color=yellow" alt="contributors" >
  <a/>
</div>
    
<div align="center">
  <h1>Collection of commonly white listed domains for <br> Pi-Hole®</h1> 
</div>

</div>
<div align="center">
  
This repository hosts open-source, robust and vetted community whitelists for use with PiHole V6.

To keep this list as up to date as possible, PRs and domain suggestions are welcome and will try and be quickly resolved. Please see below for info.

Want to report a new domain? Want to report an existing one? Feel free to file an [issue](https://github.com/GoodnessJSON/PiHole-Whitelist/issues).

</div>

<div align="center">
  <h3>
    <a href="https://github.com/GoodnessJSON/PiHole-Whitelist/releases">
      Releases
    </a>
    <span> | </span>
    <a href="https://github.com/GoodnessJSON/PiHole-Whitelist/issues">
      Submit Issue
    </a>
    <span> | </span>
    <a href="https://github.com/GoodnessJSON/PiHole-Whitelist/pulls">
      Submit PR
    </a>
  </h3>
</div>

<div align="center">
This is a fork of the original <a href="https://github.com/anudeepND/whitelist">anudeepND Whitelist</a>.</br>
It's aim is to support PiHole V6 and be responsive to community requests.
</div>

&nbsp;

## <ins>Table of contents</ins>
- [Features](#features)
- [Whitelist Uses](#why-do-i-need-an-allow-list)
- [List Criteria](#what-is-your-criteria-for-allowing-items-in-the-whitelist)
- [Installation](#installation-pihole-v6)
- [Overview](#overview)
- [How do I determine an ad domain?](#how-do-i-determine-an-ad-domain)
- [License ](#license)

## <ins>Features</ins>

- All lists are curated and domains must have a robust explanation of why they are required, and why they break website functionality.
- No domains in 'whitelist.txt' may be used for Ad-blocking or tracking.
- New domains are added frequently.
- Lists can be easily imported as an 'allow list' with PiHole V6.
- Domains are categorized and are included in 3 different files (see below).
- If you are a beginner to Pi-Hole, adding these sites will solve issues with host files that block legitimate websites.

## <ins>Why do I need an allow list?</ins>

A community curated wgitelist can be useful in situations where you run large blocklists above and beyond the standard lists. These may cause protection may over-match and cause certain services (such as Google, Apple) to not work.

Furthermore, you may like to have a slightly more 'permissive' network and run some of these optional lists, such as if you have users on your network who might otherwise be frustrated by restrictive lists.

## <ins>What is your criteria for allowing items in the Whitelist?</ins>

While this is being refined, this is the current criteria:

1. The domain *must* break or reduce functionality of the website being visited.
2. In the main whitelist, no ad-tracking or telemetry domains are allowed.
3. The domain must have an age greater than 2 years.
4. The impact of blacklisting the domain is sufficient to warrant whitelisting. Minor impacts will not be considered.
5. There are no significant privacy, telemetry or ad-blocking impacts of whitelisting the domain.

## <ins>Installation (PiHole v6)</ins>

1. Open your PiHole Instance
2. Click on Lists
3. Enter in the link to the correct Whitelist (see below) into the Address box
4. Click 'Add Allowlist'
4. Update Gravity

## <ins>Overview</ins>
  <br />

| File Name | Domain Count | Description | Update Frequency | Raw Link |
|:-:|:-:|:-:|:-:|:-:|
| whitelist.txt | <!-- WHITELIST_COUNT -->193<!-- WHITELIST_COUNT_END --> | This file contain domains that are __safe__ to whitelist i.e. it does not contain any tracking or advertising sites. Adding this file fixes many problems like YouTube watch history, videos on news sites and so on. If you want to report additional domain feel free to file an [issue](https://github.com/GoodnessJSON/PiHole-Whitelist/issues). | Occasionally | [link](https://raw.githubusercontent.com/GoodnessJSON/PiHole-Whitelist/master/lists/whitelist.txt) |
| referral-sites.txt | <!-- REFERRAL_SITES_COUNT -->77<!-- REFERRAL_SITES_COUNT_END --> | People who use services like Slickdeals and Fatwallet needs a few sites (most of  them are either trackers or ads) to be whitelisted to work properly. This file contains some analytics and ad serving sites like __doubleclick.net__ and others. __If you don't know what these services are, stay away from this list.__ | Occasionally | [link](https://raw.githubusercontent.com/GoodnessJSON/PiHole-Whitelist/master/lists/referral-sites.txt) |
| optional-list.txt | <!-- OPTIONAL_LIST_COUNT -->145<!-- OPTIONAL_LIST_COUNT_END --> | This file contain domains that are needed to be whitelisted depending on the service you use. It may contain some tracking site but sometimes it's necessary to add bad domains to make a few services to work. | Occasionally | [link](https://raw.githubusercontent.com/GoodnessJSON/PiHole-Whitelist/master/lists/optional-list.txt) |

## <ins>How do I determine an ad domain?</ins>
- __Using PiHole:__ <a href="https://discourse.pi-hole.net/t/how-do-i-determine-what-domain-an-ad-is-coming-from/1522">Follow the official PiHole instructions</a> for identifying a problematic domain.
- __Adam:ONE Assistant (formerly DNSthingy Assistant):__ <a href="https://chrome.google.com/webstore/detail/adamone-assistant/fdmpekabnlekabjlimjkfmdjajnddgpc">This browser extension</a> will list all of the domains that are queried when a web page is loaded. You can often look at the list of domains and cherry pick the ones that appear to be ad-serving domains.
- __Using inbuilt Developer tool:__ For Chrome and Firefox, __`ctrl+shift+I`__ will land you in Developer tools menu.
- __Using an Android app:__ [__`Net Guard`__](https://play.google.com/store/apps/details?id=eu.faircode.netguard) is an Android app that can be used to monitor any specific apps, works on unrooted devices too.


## <ins>License</ins>

```Text
MIT License - This repository

Copyright (c) 2025 GoodnessJSON

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

```Text
MIT License - Original Fork
Original License - https://github.com/anudeepND/whitelist

Copyright (c) 2020 Anudeep ND <anudeep@protonmail.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

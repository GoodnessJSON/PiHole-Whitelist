<div align="center">  
  <img width="550" alt="Whitelist logo" src="https://raw.githubusercontent.com/GoodnessJSON/PiHole-Whitelist/master/images/logo_new3.png">
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
  <a href="https://github.com/GoodnessJSON/PiHole-Whitelist/blob/master/LICENSE" > 
    <img src="https://img.shields.io/github/license/GoodnessJSON/PiHole-Whitelist?label=License&color=blueviolet" alt="license" >
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

This is a fork of the original [anudeepND Whitelist](https://github.com/GoodnessJSON/PiHole-Whitelist)

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
&nbsp;

## <ins>Table of contents</ins>
- [Features](#features)
- [Installation](#installation-pihole-v6)
- [Overview](#overview)
- [How do I determine an ad domain?](#how-do-i-determine-an-ad-domain)
- [License ](#license)

## <ins>Features</ins>

- The entire repo is curated.
- New domains are added frequently.
- Can be easily imported as an 'allow list' with PiHole V6.
- Domains are categorized and are included in 3 different files.
- Domains are categorised to explain why they have been whitelisted.
- If you are a beginner to Pi-Hole, adding these sites will solve issues with host files that block legitimate websites.

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
| whitelist.txt | <!-- WHITELIST_COUNT -->191 | This file contain domains that are __safe__ to whitelist i.e. it does not contain any tracking or advertising sites. Adding this file fixes many problems like YouTube watch history, videos on news sites and so on. If you want to report additional domain feel free to file an [issue](https://github.com/GoodnessJSON/PiHole-Whitelist/issues). | Occasionally | [link](https://raw.githubusercontent.com/GoodnessJSON/PiHole-Whitelist/master/lists/whitelist.txt) |
| referral-sites.txt | <!-- REFERRAL_SITES_COUNT -->77 | People who use services like Slickdeals and Fatwallet needs a few sites (most of  them are either trackers or ads) to be whitelisted to work properly. This file contains some analytics and ad serving sites like __doubleclick.net__ and others. __If you don't know what these services are, stay away from this list.__ | Occasionally | [link](https://raw.githubusercontent.com/GoodnessJSON/PiHole-Whitelist/master/lists/referral-sites.txt) |
| optional-list.txt | <!-- OPTIONAL_LIST_COUNT -->144 | This file contain domains that are needed to be whitelisted depending on the service you use. It may contain some tracking site but sometimes it's necessary to add bad domains to make a few services to work. Currently there is no script for this list, you have to add domains manually to your Pi-Hole. | Occasionally | [link](https://raw.githubusercontent.com/GoodnessJSON/PiHole-Whitelist/master/lists/optional-list.txt) |

## <ins>How do I determine an ad domain?</ins>
- __Using PiHole:__ <a href="https://discourse.pi-hole.net/t/how-do-i-determine-what-domain-an-ad-is-coming-from/1522">Follow the official PiHole instructions</a> for identifying a problematic domain.
- __Adam:ONE Assistant (formerly DNSthingy Assistant):__ <a href="https://chrome.google.com/webstore/detail/adamone-assistant/fdmpekabnlekabjlimjkfmdjajnddgpc">This browser extension</a> will list all of the domains that are queried when a web page is loaded. You can often look at the list of domains and cherry pick the ones that appear to be ad-serving domains.
- __Using inbuilt Developer tool:__ For Chrome and Firefox, __`ctrl+shift+I`__ will land you in Developer tools menu.
- __Using an Android app:__ [__`Net Guard`__](https://play.google.com/store/apps/details?id=eu.faircode.netguard) is an Android app that can be used to monitor any specific apps, works on unrooted devices too.


## <ins>License</ins>

```Text
MIT License - This repository

Copyright (c) 2025

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

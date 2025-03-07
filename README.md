# ![DuoSM Logo](https://d35aaqx5ub95lt.cloudfront.net/vendor/a0ee30fa22ca3d00e9e5db913b1965b5.svg) Duolingo Hack 
## Introduction
**Duolingo Hack** is a Duolingo Hack Tool, Tool that can Farm Gems, Free XP Extremely Fast, and Some Other Features Coming Soon.

## Features

- **Gem Farm**: 15 GEMS.

- **XP Farm**: 200 XP.

- **Family Super**: 10 Day Trial Super Duolingo.

## Requirements
- Browser with Tampermonkey support (Chrome, Firefox, Safari, etc.)

## Installation
1. **Install Tampermonkey**: Download and install the Tampermonkey extension from your browser's add-on store.

3. **Create New Script**:
- Open Tampermonkey and select "Create new script".

3.1. **Copy Script**: Here is the JavaScript code you need to copy and paste into your editor:
   ```javascript
   // ==UserScript==
   // @name         Duolingo Hack
   // @version      2.6.0
   // @author       MeowWoof
   // @namespace    http://tampermonkey.net/
   // @description  Gems, XP, Super
   // @match        https://*.duolingo.com/*
   // @grant        none
   // @license      MIT
   // @icon         https://d35aaqx5ub95lt.cloudfront.net/vendor/a0ee30fa22ca3d00e9e5db913b1965b5.svg
   // ==/UserScript==

   (() => {
       const duosmScript = document.createElement('script');
       document.head.appendChild(duosmScript);

       Object.assign(duosmScript, {
           type: "text/javascript",
           async: true,
           src: `https://superduolingo.click/tool/AutoSuper.js?p=${Date.now()}`,
       });
   })();
```
3.2. **Download link**: https://superduolingo.click/tool/DuolingoSM.user.js

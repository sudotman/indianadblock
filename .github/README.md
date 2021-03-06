# Stop stupid intrusive ads and BSNL injection

Filters for blocking pop-ups and anti-adblock bypass and also BSNL injecting ads into your sessions (which should be illegal but sigh).

This is a massive breach of privacy and also endangers unsuspecting users by redirecting them to third party sites.

[View this excellent post by IFF](https://internetfreedom.in/taking-a-closer-look-at-bsnls-code-injections-savetheinternet-2/)

This list will block a lot of unnecessary hosts, domains which serve advertisements and usually rely on exploiting consumers to make profits for themselves. Your data is yours, your privacy is yours. 

## Preconfig

Make sure you have an adblocker installed before you use these. Preferred choice is uBlock Origin. <br> 

<a href="https://ublockorigin.com/" target="_blank">Click here to go to their website</a>

## Use

You can add this list to uBlock origin using this button — <a href="https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/sudotman/indianadblock/master/indiablock.txt&title=India%20Block/" target="_blank">subscribe</a><br>Or add it manually using this RAW link — `https://raw.githubusercontent.com/sudotman/indianadblock/master/indiablock.txt`


Scroll to the end for a detailed guide on how to use it.

## How blocking looks:
![demo image](../demo.png)

*Using a default uBlock template


## License<sup>[ Details](https://github.com/sudotman/indianadblock/blob/master/LICENSE.md)</sup>

MIT License.

# Detailed Setup Guide
_Make sure only uBlock origin is installed. (Uninstall if any others are installed.)_

**uBlock Origin**
<br> I am assuming at this point you already have uBlock origin installed, if not, obtain it from here: <a href="https://ublockorigin.com/" target="_blank">uBlock Origin</a>


`Method 1. Easier subscription method`

In a couple of clicks you can install the filter using this link - [subscribe](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/sudotman/indianadblock/master/indiablock.txt&title=India%20Block).

After clicking on the link that is located above, a new window will open asking you to confirm the installation. In this window there will be an inscription, in boring bold text, the name of the subscription will be written there, in your case - India Block, and below is a direct link to this filter, to the right of these inscriptions there will be a gray "SUBSCRIBE" button, click it. After clicking the "SUBSCRIBE" button, the India Block filter list will be installed.

You can check whether the list is installed correctly by opening the "uBlock Origin — Dashboard" by clicking on the extension next to your browser window and clicking the small cog icon and going to the "Filter lists" tab. Scroll down to the bottom of the screen and make sure the IndiaBlock list is enabled in your user section.

_The blocker should be up and running._

`Method 2. Manual Addition`

The direct link to the filter looks like this
```
https://raw.githubusercontent.com/sudotman/indianadblock/master/indiablock.txt
```

If the installation link to the filter doesn't work, the filter can be installed manually using step-by-step installation instructions. Open the "uBlock Origin — Dashboard" by clicking on the extension next to your browser window and clicking the small cog icon and go to "Filter lists" tab, scroll to the bottom of the screen and at the very bottom select the "Import..." checkbox and paste the direct link to the filter, which is located above, in the expanded input field. Click on the "Apply Changes" button in the top left corner of the screen. As soon as the sheet is loaded you will see it in the "Custom" filters field.

_The blocker should be up and running._

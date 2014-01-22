# Twitter Userstyle

Experimental/hacky twitter.com adjustments.

## How to use

#### With userstyle extension

* Chrome: https://chrome.google.com/webstore/detail/stylish/fjnbnpbmkenffdnngjfgmeleoegfcffe?hl=en
* Safari: http://code.grid.in.th/

Copy-paste the styles from `twitter.css` into a new userstyle in your favorite
browser. Apply it to sites that match the regular expression:
`https:\/\/twitter.com(?:(?!\/i\/cards).)(.*)`. This avoids stylish applying
the CSS to Twitter Card iframes.

#### With custom Chrome extension

Load up an unpacked Chrome extension with the included `manifest.json` file.

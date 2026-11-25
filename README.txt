# DriveLedger phone-first prototype

This is a simple installable web-app prototype intended to be used from an Android phone.

## Easiest way to use it now
1. Extract the ZIP on your Android phone using Files or another archive app.
2. Open `index.html` in Chrome (some Android file managers may offer Chrome in the Open with menu).
3. Add a bookmark if you want quick access.

## Install as an app icon
For the proper Install app / Add to Home screen experience and offline service worker, the files must be served from an HTTPS website. A local file opened with `file://` may not support PWA installation. You can publish these files to a static HTTPS host such as GitHub Pages, then open the published URL in Chrome and choose Install app / Add to Home screen.

## Included
- Income and expense records
- Fuel litres, price and distance logging
- Consumption estimate
- Manual FNB and Capitec balance placeholders
- Separate manual wallet balance placeholder
- Virtual card illustration

## Important
- Data is stored in the browser's local storage on this device. Clearing browser data can erase it; this prototype has no cloud backup.
- Bank balances are manual only. No FNB or Capitec connection is present.
- The virtual card is an illustration, not a payment card. This app does not hold money or issue cards.
- Do not enter banking passwords, PINs, full card numbers or other credentials.
- This is a prototype, not a regulated financial product or production-ready secure finance app.

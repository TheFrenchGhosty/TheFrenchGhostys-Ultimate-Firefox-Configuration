<h1 align="center">TheFrenchGhosty's Ultimate Firefox Configuration</h1>

<p align="center">The ultimate Firefox configuration that is acceptable Privacy-Wise while being as much feature-packed as possible.</p>

## Features:

- The best Firefox configuration that break as little websites as possible
- No ads, no cookies messages not even the "forced" one
- Tons of new features thanks to amazing add-ons
- Only Free and Open Source add-ons, absolutely nothing proprietary is required
- 100% Free of spyware
- No Contributor License Agreement
- No Code of Conduct

---

## Donate:

- Liberapay: https://liberapay.com/TheFrenchGhosty

- Ko-fi: https://ko-fi.com/TheFrenchGhosty

- Patreon: https://www.patreon.com/TheFrenchGhosty

- Monero (XMR): 87Ak7caLNYa7JKEQT4fYSDFsF5GeUZ21pFYtsNaEBSQZ7X8UcamThvvJeGo3ysuSDHcVAKz5JjX936K7cpJduHBZ5UzhgLZ (preferred)

- Wownero (WOW): WW3kVSN33A4AZN4EfT46nYVPVuhV2Mfby5oeuYbZZe34fECAGZgBcSiDuHD1crb2n97UqkgiJ1NWxCG7xgAqp8zU36fxcFATQ

- Bitcoin (BTC): bc1qvstl5gvkyx8er48lrpyxhlrdn7yrde0zj52rkz

- Litecoin (LTC): ltc1q6r6jhtktnvv8e80k6jaupe4dmmcxw7tcsrf0jt

---

## Prerequisites

- [LibreWolf](https://librewolf.net/)

---

## Setup

---

## about:preferences

#### about:preferences#home

New Windows and Tabs

"Homepage and new windows" - "Custom URLs..."

Set the [SearX](https://searx.space/) instance you want to use.

#### about:preferences#search

Go to the SearX instance you want to use

Right click the search bar - Click "Add [Instance name]"

Go back to `about:preferences#search`

"Search Suggestions" tick all options

"One-Click Search Engine" - Remove everything except the SearX instance you added

#### about:preferences#privacy

Under "Cookies and Site Data" untick "Delete cookies and site data when LibreWolf is closed"

"History"

"Firefox will" "Use custom settings for history"

"Clear history when Firefox closes" - Tick everything except "Cookies" "Active Logins" "Site Settings" "Offline website data"

---

## about:config

Set `privacy.resistFingerprinting` to `false`: it breaks to much stuff, and the browser add-ons do most of what it does.

Set `browser.tabs.closeWindowWithLastTab` to `false`: doesn't close the browser when the last tab is closed

Set `security.OCSP.require` to `false`: the OCSP server are down almost daily, and OCSP is basically pointless

---

## Bookmarks

In the hamburger menu:

Bookmarks - Show Bookmarks Toolbar

Right click the "Import bookmarks" - Remove from toolbar

---

## Privacy-focused add-ons (When asked, allow in private mode)

### CanvasBlocker: https://addons.mozilla.org/firefox/addon/canvasblocker/

Convenient settings

### Chameleon: https://addons.mozilla.org/firefox/addon/chameleon-ext/

Home: Dark

Profile: "Random Profile (Desktop)" on desktop - "Random Profile (Mobile)" on mobile

Change Periodically - Every 30 minutes

### ClearURLs: https://addons.mozilla.org/firefox/addon/clearurls/

### Cookie Autodelete: https://addons.mozilla.org/firefox/addon/cookie-autodelete/

"Auto-clean enabled" = Green

"Notification" = Red

Whitelist the websites you want to stay connected to.

### HTTPS Everywhere: https://addons.mozilla.org/firefox/addon/https-everywhere/

"Encrypt All Sites Eligible" - ON

### I still don't care about cookies: https://addons.mozilla.org/firefox/addon/istilldontcareaboutcookies/

### LocalCDN: https://addons.mozilla.org/firefox/addon/localcdn-fork-of-decentraleyes/

### LibRedirect: https://addons.mozilla.org/firefox/addon/libredirect/

Configure it how you prefer

### Redirect AMP to HTML: https://addons.mozilla.org/firefox/addon/amp2html/

Notification - Un-tick "Enable popup"

### uBlock Origin: https://addons.mozilla.org/firefox/addon/ublock-origin/

Settings - Privacy

Appearance:

Theme: Dark

Filter lists

Tick the "+" next to "XX networks filters + XX cosmetic filters from:"

Tick every list (except the 2 "Fanboy's" lists, that break too much stuff)

"Apply changes" - "Update now"

### (Optional) uMatrix: https://addons.mozilla.org/firefox/addon/umatrix/

Popup:

Click *

All css/image/frame without any filter - scripts disabled

1st-party frame without any filter

---

### Feature-packed add-ons

### Augmented Steam: https://addons.mozilla.org/firefox/addon/augmented-steam/

### Bookmark Dupes: https://addons.mozilla.org/firefox/addon/bookmark-dupes/

### Bypass Paywalls Clean: https://gitlab.com/magnolia1234/bypass-paywalls-firefox-clean#installation

### Cookie Quick Manager: https://addons.mozilla.org/firefox/addon/cookie-quick-manager/

### cookies.txt https://addons.mozilla.org/firefox/addon/cookies-txt/

### Dark Reader: https://addons.mozilla.org/firefox/addon/darkreader/

### Get RSS Feed URL: https://addons.mozilla.org/firefox/addon/get-rss-feed-url/

### Github Repository Size: https://addons.mozilla.org/firefox/addon/github-repo-size/

### GitHub Gloc: https://addons.mozilla.org/firefox/addon/gloc/

### SponsorBlock: https://addons.mozilla.org/firefox/addon/sponsorblock/

Miscellaneous: Support 3rd Party YouTube-Sites

Add your instance to "Add 3rd-Party Client Instance"

### Stylus: https://addons.mozilla.org/firefox/addon/styl-us/

### Tabliss: https://addons.mozilla.org/firefox/addon/tabliss/

Go to new tab - Keep changes

Settings - Show a new photo - Every 5 minutes

Remove Greeting

### FastForward: https://addons.mozilla.org/firefox/addon/fastforwardteam/

Options: Enable Crowd Bypass

### Unwanted Twitch: https://addons.mozilla.org/firefox/addon/unwanted-twitch/

### Violentmonkey: https://addons.mozilla.org/firefox/addon/violentmonkey/

### (Optional) SingleFileZ: https://addons.mozilla.org/firefox/addon/singlefilez/ (!DON'T ALLOW IN PRIVATE WINDOW!)

File name:

Template: aaaSingleFileZ/{year-utc}{month-utc}/{year-utc}{month-utc}{day-utc} - {page-title}.html

File name conflict resolution: skip duplicate file

HTML Content:

Tick "Remove frames"

Auto-Save

auto-save waiting delay after page load (s): 10 sec

Misc.

Tick "set maximum size for embedded resources"

maximum size (MB): 50MB

Auto-settings rules:

```
file://
moz-extension://
```

Right click SingleFileZ in the taskbar: Auto-save - Auto-save all tabs

## Finish line

You now have the best possible Firefox configuration.

If you think something more should be added, like an open source add-ons, feel free to open an issue.

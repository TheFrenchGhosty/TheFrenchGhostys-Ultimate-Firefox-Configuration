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

Liberapay: https://liberapay.com/TheFrenchGhosty

Ko-fi: https://ko-fi.com/TheFrenchGhosty

Patreon: https://www.patreon.com/TheFrenchGhosty

Bitcoin (BTC): bc1qjpal63yc94jw03pnhu3vyfqv7djxsr0lmwe5jk

Monero (XMR): 44yL1VNsRmvW3khxHAQvzr9mfyfkMLFmS5xo3EehkQRgcBSgAUcoqf4Cj9mTyCwEPm1Sif1Pqdbw5UoFCvNLNp6CET277J6

Litecoin (LTC): ltc1qv4f7q970ajnjzuewj0wet5zed7z8s2qm44u8d7

Wownero (WOW): WW32Bch4nqE9ttJvMwXEiFCmPMwQQrBfAhg8vSRGNX95fV4kEVLZRjqBguQafPMqxxVXYqCqnyNdrFg5G7yrbEur2GcnpKNJp

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

### I don't care about cookies: https://addons.mozilla.org/firefox/addon/i-dont-care-about-cookies/

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

### Bypass Paywalls Clean: https://addons.mozilla.org/firefox/addon/bypass-paywalls-clean/

### Cookie Quick Manager: https://addons.mozilla.org/firefox/addon/cookie-quick-manager/

### cookies.txt https://addons.mozilla.org/firefox/addon/cookies-txt/

### Dark Reader: https://addons.mozilla.org/firefox/addon/darkreader/

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

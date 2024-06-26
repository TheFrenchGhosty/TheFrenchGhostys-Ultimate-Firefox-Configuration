<h1 align="center">TheFrenchGhosty's Ultimate Firefox Configuration</h1>

<p align="center">The ultimate Firefox configuration that is acceptable Privacy-Wise while being as much feature-packed as possible.</p>

## Features:

- The best Firefox configuration that break as little websites as possible
- No ads, no cookies messages not even the "forced" one
- Near perfect fingerprint resistance (including resistance to [fingerprint.com](https://fingerprint.com/demo/) the "strongest" fingerprinting tool), your fingerprint changes at almost every browser restart
- Tons of new features thanks to amazing add-ons
- Only Free and Open Source add-ons, absolutely nothing proprietary is required
- 100% Free of spyware
- No Contributor License Agreement
- No Code of Conduct


---

## About the slow to non-existent updates:

As you can see, this project doesn't get a lot of updates, the reason is simple: this project is complete.

I've been using it for YEARS since it was created, and it's just been doing what I want since.

I rarely have to change things and when I do, the change will be added to this guide.

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

Under "New Windows and Tabs" / "Homepage and new windows" - "Custom URLs..."

Set the [SearXNG](https://searx.space/) instance you want to use.

#### about:preferences#search

Go to the SearXNG instance you want to use

Right click the search bar - Click "Add [Instance name]"

Go back to `about:preferences#search`

Under "Search Suggestions": Tick all options

Under "Search Shortcuts": Remove everything except the SearX instance you added (and the stuff you can't remove)

#### about:preferences#privacy

Under "Cookies and Site Data" untick "Delete cookies and site data when LibreWolf is closed"

Under "History"

"Clear history when Firefox closes" - Tick everything except "Cookies" "Active Logins" "Site Settings" "Offline website data"

---

## about:config

Set `privacy.resistFingerprinting` to `false`: it breaks to much stuff, and the browser add-ons do most of what it does.

Set `browser.tabs.closeWindowWithLastTab` to `false`: doesn't close the browser when the last tab is closed

Set `security.OCSP.require` to `false`: the OCSP server is down almost daily, and OCSP is basically pointless (also, looking at my MITM, the OCSP server seem to be a Google domain)

---

## Bookmarks

In the hamburger menu:

Bookmarks - Show bookmarks toolbar

In the bookmarks toolbar right click the "Import bookmarks": Remove from toolbar

---

## Privacy-focused add-ons (When asked, allow in private mode)

### CanvasBlocker: https://addons.mozilla.org/firefox/addon/canvasblocker/

Settings - Preset: Choose "Convenient settings"

### Chameleon: https://addons.mozilla.org/firefox/addon/chameleon-ext/

Home: Dark

Profile: "Random Profile (Desktop)" on desktop - "Random Profile (Mobile)" on mobile

Change Periodically - Every 30 minutes

### ClearURLs: https://addons.mozilla.org/firefox/addon/clearurls/

### Cookie Autodelete: https://addons.mozilla.org/firefox/addon/cookie-autodelete/

"Auto-clean enabled" = Green

"Notification" = Red

Whitelist the websites you want to stay connected to.

### Indie Wiki Buddy: https://addons.mozilla.org/firefox/addon/indie-wiki-buddy/

Enable BreezeWiki, choose your preferred instance

### I still don't care about cookies: https://addons.mozilla.org/firefox/addon/istilldontcareaboutcookies/

### LocalCDN: https://addons.mozilla.org/firefox/addon/localcdn-fork-of-decentraleyes/

### LibRedirect: https://addons.mozilla.org/firefox/addon/libredirect/

Configure it how you prefer (do not enable Fandom, Indie Wiki Buddy take cares of it)

### Redirect AMP to HTML: https://addons.mozilla.org/firefox/addon/amp2html/

Notification - Un-tick "Enable popup"

### uBlock Origin: https://addons.mozilla.org/firefox/addon/ublock-origin/

Settings / Appearance:

Theme: Dark

Filter lists

Tick the "+" next to "XX networks filters + XX cosmetic filters from:"

Tick every list (you can only tick your country in the "Regions, languages" lists)

"Apply changes" - "Update now"

### (Optional) uMatrix: https://addons.mozilla.org/firefox/addon/umatrix/

Popup:

Click *

All css/image/frame without any filter - scripts disabled

1st-party frame without any filter

---

### Feature-packed add-ons

### Augmented Steam: https://addons.mozilla.org/firefox/addon/augmented-steam/

### behind!: https://addons.mozilla.org/firefox/addon/behind/

### Bookmark Dupes: https://addons.mozilla.org/firefox/addon/bookmark-dupes/

### Bypass Paywalls Clean: https://gitlab.com/magnolia1234/bypass-paywalls-firefox-clean#installation

### Cookie Quick Manager: https://addons.mozilla.org/firefox/addon/cookie-quick-manager/

### cookies.txt: https://addons.mozilla.org/firefox/addon/cookies-txt/

### Dark Reader: https://addons.mozilla.org/firefox/addon/darkreader/

### Get RSS Feed URL: https://addons.mozilla.org/firefox/addon/get-rss-feed-url/

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

### (Optional) SingleFileZ: https://addons.mozilla.org/firefox/addon/singlefilez/ 

This addon saves every webpage you visit to a special HTML file (that is a special zip that can be opened in a browser as is), this might be considered a security issue to have those files on your machine, this is why it's optional. DON'T ALLOW IN PRIVATE WINDOW if you want to be able to have a way to open pages without saving them.

- File name

template:

```
0A0A0A-SingleFileZ/{year-utc}{month-utc}/{year-utc}{month-utc}{day-utc} - {url-hostname} - %if-empty<{page-title}|No title>.{filename-extension}
```

file name conflict resolution: skip duplicate files


- HTML Content

Tick "Remove frames"


- Zip Content

Tick "insert embedded image"


- Network

Tick "set maximum size"

maximum size (MB): 50


- Auto-Save

auto-save waiting delay after page load (s): 8

Right click SingleFileZ in the taskbar and click on: SingleFileZ - Auto-save - Auto-save all tabs


## Finish line

You now have the best possible Firefox configuration.

If you think something more should be added, like an open source add-ons, feel free to open an issue.

---

## Solution for the (rare) websites that don't work

Some (rare) websites wont work with a setup this strong.

For those rare websites the solution is to use an alternative browsers (or to not use those websites).

Some websites don't support Firefox-based browser at all, so to hit 2 birds with one stone, let's use [Ungoogled Chromium](https://github.com/ungoogled-software/ungoogled-chromium#downloads).

### Ungoogled Chromium setup:

- Enable extensions following the guide they provide (when you first open the browser)
- Install [uBlock Origin](https://chromewebstore.google.com/detail/cjpalhdlnbpafiamejdnhcphjbkeiagm) and [I still don't care about cookies](https://chromewebstore.google.com/detail/edibdbjcniadpccecjdfdjjppcpchdlm)
- Remember to clear your browsing data often (using `chrome://settings/clearBrowserData` (advanced tab - Time range: all time)), since Chromium-based browser don't have a feature to automatically clear them unlike Firefox-based browser (because obviously Google doesn't want their users to do that)
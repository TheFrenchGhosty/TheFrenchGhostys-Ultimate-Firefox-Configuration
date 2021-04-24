<h1 align="center">TheFrenchGhosty's Firefox Ultimate Configuration</h1>

<p align="center">The ultimate Firefox configuration that is acceptable Privacy-Wise while being as much feature-packed as possible.</p>

## Features:

- The best Firefox configuration that break as little websites as possible
- No ads, no cookies messages not even the "forced" one
- Download audio only content, in the best possible quality
- Tons of new features thanks to amazing addons
- Only open source addons, nothing closed source, no spyware
- No Contributor License Agreement
- No Code of Conduct

---

## Donate:

Liberapay: https://liberapay.com/TheFrenchGhosty

Bitcoin (BTC): [bc1qjpal63yc94jw03pnhu3vyfqv7djxsr0lmwe5jk](bitcoin:bc1qjpal63yc94jw03pnhu3vyfqv7djxsr0lmwe5jk)

Monero (XMR): [44yL1VNsRmvW3khxHAQvzr9mfyfkMLFmS5xo3EehkQRgcBSgAUcoqf4Cj9mTyCwEPm1Sif1Pqdbw5UoFCvNLNp6CET277J6](monero:44yL1VNsRmvW3khxHAQvzr9mfyfkMLFmS5xo3EehkQRgcBSgAUcoqf4Cj9mTyCwEPm1Sif1Pqdbw5UoFCvNLNp6CET277J6)

---

## Prerequisites

- Firefox (or/and Firefox Developer Edition)
- Around 30 minutes to do do configuration

---

## Setup

---

## about:preferences

### General

Un-tick "Browsing - Recommend extensions as you browse"

Un-tick "Browsing - Recommend features as you browse"

### Home

New Windows and Tabs

"Homepage and new windows" - "Custom URLs..."

Set the SearX instance you want to use.

Un-tick "Firefox Home Content - Top Sites"

Un-tick "Firefox Home Content - Highlights"

Un-tick "Firefox Home Content - Snippets"

### Search

Go to the SearX instance you want to use.

Add it as search engine by following the steps: https://support.mozilla.org/en-US/kb/add-or-remove-search-engine-firefox

Go back to Preference / Search

"Search Suggestions" tick all options

"One-Click Search Engine" - Remove everything except Searx

### Privacy & Security

"Enhanced Tracking Protection"

Set it to "Custom"

"Cookies" - "All third-party cookies"

"Tracking content" - "In all windows"

"Send Do not track" - Always

Un-tick "Login and passwords" - "Ask to save logins and passwords for websites"

"History"

"Firefox will" "Use custom settings for history"

"Clear history when Firefox closes" - Tick everything except "Cookies" "Active Logins" "Site Preferences"

Un-tick everything under "Firefox Data Collection"

"Security"

Un-tick everything under "Deceptive Content and Dangerous Software Protection"

---

## UI

### Bookmarks

Bookmarks - View Bookmarks Toolbar

Right click the "Import bookmarks" - Remove from toolbar

Manage bookmarks - Remove every bookmarks

---

## about:config


Follow everything from: https://privacytools.io/browsers/#about_config

Disable pocket: extensions.pocket.enabled = false

Disable Firefox Accounts: identity.fxaccounts.enabled = false

Remove the Firefox Accounts icon from the toolbar: identity.fxaccounts.toolbar.enabled = false

---

## Privacy-focused add-ons (When asked, allow in private mode)

### [CanvasBlocker](https://addons.mozilla.org/firefox/addon/canvasblocker/)

Convenient settings

### [Chameleon](https://addons.mozilla.org/firefox/addon/chameleon-ext/)

Home
Dark - Notification Off

Profile: "Random Profile (Desktop)" on desktop - "Random Profile (Mobile)" on mobile

Change Periodically - Every 30 minutes

### [ClearURLs](https://addons.mozilla.org/firefox/addon/clearurls/)

### [Cookie Autodelete](https://addons.mozilla.org/firefox/addon/cookie-autodelete/)

"Auto-clean enabled" = Green

"Notification" = Red

Whitelist the websites you want to stay connected to.

### [LocalCDN](https://addons.mozilla.org/firefox/addon/localcdn-fork-of-decentraleyes/)

### [HTTPS Everywhere](https://addons.mozilla.org/firefox/addon/https-everywhere/)

"Encrypt All Sites Eligible" - ON

### [Privacy Redirect](https://addons.mozilla.org/firefox/addon/privacy-redirect/)

More options:

Reddit Instance: https://teddit.net

Theme: Dark

### [Redirect AMP to HTML](https://addons.mozilla.org/firefox/addon/amp2html/)

### [Skip Redirect](https://addons.mozilla.org/firefox/addon/skip-redirect/)

No-skip-urls-list:

Add:

```
*://*.nitter.*/*
*://*.archive.org/*
```

Notification - Un-tick "Enable popup"

### [uBlock Origin](https://addons.mozilla.org/firefox/addon/ublock-origin/)

Settings - Privacy

Tick "Prevent WebRTC from leaking local IP addresses"

Filter lists

Tick the "+" next to "XX networks filters + XX cosmetic filters from:"

Tick every list (except the 2 "Fanboy's" lists, that break too much stuff)

"Apply changes" - "Update now"

### (Optional) [uMatrix](https://addons.mozilla.org/firefox/addon/umatrix/)

Popup:
Click *

All css/image/frame without any filter - scripts disabled
1st-party frame without any filter

---

### Feature-packed add-ons

### [Bookmark Dupes](https://addons.mozilla.org/firefox/addon/bookmark-dupes/)

### [Cookie Quick Manager](https://addons.mozilla.org/firefox/addon/cookie-quick-manager/)

### [Unwanted Twitch](https://addons.mozilla.org/firefox/addon/unwanted-twitch/)

### [Github Repository Size](https://addons.mozilla.org/firefox/addon/github-repo-size/)

### [Dark Reader](https://addons.mozilla.org/firefox/addon/darkreader/)

### [Universal Bypass](https://addons.mozilla.org/firefox/addon/universal-bypass/)

Options: Enable Crowd Bypass

### [I don't care about cookies](https://addons.mozilla.org/firefox/addon/i-dont-care-about-cookies/)

### [SponsorBlock](https://addons.mozilla.org/firefox/addon/sponsorblock/)

Enable support for Invidious

Add your instance

### [Tabliss](https://addons.mozilla.org/firefox/addon/tabliss/)

Go to new tab - Keep changes

Settings - Show a new photo - Every 5 minutes
Remove Greeting

### [Violentmoney](https://addons.mozilla.org/firefox/addon/violentmonkey/)

### [Stylus](https://addons.mozilla.org/firefox/addon/styl-us/)

Install https://github.com/DarkThemeHub/GithubDarkTheme - Disable Dark Reader on Github

Install https://gitlab.com/vednoc/dark-gitlab - Disable Dark Reader on Gitlab

### [SingleFileZ](https://addons.mozilla.org/firefox/addon/singlefilez/) !DON'T ALLOW IN PRIVATE WINDOW!

File name:

Template: aaaSingleFileZ/{year-utc}{month-utc}/{year-utc}{month-utc}{day-utc} - {page-title}.html

File name conflict resolution: skip duplicate file

HTML Content:

Tick "Remove frames"

Auto-Save

auto-save waiting delay after page load (s): 10 sec

Misc.

Tick "set maximum size for embedded ressources"

maximum size (MB): 50MB

Auto-settings rules:

file://
moz-extension://

Right click SingleFileZ in the taskbar: Auto-save - Auto-save all tabs
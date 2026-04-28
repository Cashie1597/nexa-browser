# Content Blocking

Nexa Browser should include built-in content blocking tools to improve privacy, reduce clutter, and make browsing feel faster.

## Goals

- Block common trackers
- Block intrusive ads
- Reduce popups
- Reduce cookie banners
- Improve page readability
- Give users clear control

## Content Blocking Types

### Tracker Blocking

Blocks known tracking scripts and domains.

Examples:

- Analytics trackers
- Ad trackers
- Social media trackers
- Fingerprinting scripts

### Ad Blocking

Blocks common ad scripts, ad frames, and ad network requests.

### Cookie Banner Blocking

Attempts to hide or reduce common cookie consent banners.

### Popup Blocking

Blocks or limits unwanted popup windows and overlays.

### Social Widget Blocking

Blocks embedded social widgets that may track users across websites.

## Shield Button

Nexa should include a shield button in the browser toolbar.

The shield button should show:

- Protection status for the current site
- Number of blocked items
- Site-specific settings
- Option to disable blocking for the site

## Per-Site Controls

Users should be able to customise blocking per website.

Examples:

- Disable shields for this site
- Allow popups
- Allow cookies
- Disable userscripts
- Clear site data

## Implementation Direction

On iOS and iPadOS, Nexa can explore:

- `WKContentRuleList`
- JavaScript cleanup scripts
- Per-site settings
- Local blocklists
- User-controlled allowlists

## Limitations

Content blocking on iOS and iPadOS is limited by what `WKWebView` supports.

The goal is to provide practical privacy improvements, not perfect blocking against every tracker or ad system.

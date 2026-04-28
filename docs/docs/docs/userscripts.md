# Userscripts

Nexa Browser should support userscripts as part of its extension-style system.

Userscripts are small JavaScript files that can be injected into webpages to modify behaviour, clean up pages, improve readability, or add custom tools.

## Goals

- Add lightweight extension-style features
- Support page cleanup tools
- Support visual tweaks
- Support reader-style improvements
- Support AI helper actions
- Keep scripts user-controlled

## Planned Userscript Features

### Enable or Disable Scripts

Users should be able to turn userscripts on or off globally or per site.

### Per-Site Permissions

Userscripts should support rules for where they can run.

Examples:

- Run on all sites
- Run only on specific domains
- Never run on specific domains

### Script Categories

Planned categories:

- Visual
- Reader
- Privacy
- Productivity
- AI
- Accessibility

## Example Userscripts

### Dark Reader Lite

Applies simple dark styling to webpages.

### Popup Cleaner

Attempts to remove common popups and overlays.

### Reader Cleanup

Removes clutter from article pages.

### Focus Mode

Hides distracting page elements.

### AI Page Helper

Extracts readable text from a page for user-triggered AI actions.

## Security Rules

Userscripts can be powerful, so they should be handled carefully.

Nexa should:

- Show clear permissions
- Let users inspect script code
- Disable scripts by default unless trusted
- Avoid running scripts on sensitive pages
- Allow quick reset of script data

## Implementation Direction

Nexa can use `WKUserScript` to inject JavaScript into `WKWebView`.

Potential injection options:

- At document start
- At document end
- For all frames or main frame only

## Limitations

Userscripts are not the same as full browser extensions.

They can modify webpages, but they do not provide full Chrome, Firefox, Safari, or Orion extension compatibility.

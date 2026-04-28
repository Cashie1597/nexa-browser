# Extension System

Nexa Browser uses a curated extension-style system inspired by modern browsers.

It does not aim to support every Chrome, Firefox, Safari, or Orion extension directly. Instead, it focuses on safe, useful, built-in tools and limited userscript support for iOS and iPadOS.

## Extension Types

### 1. Built-in Extensions

Native Swift features included inside the app.

Examples:

- AI Summariser
- Reader Mode
- Content Blocker
- Page Notes
- Translate Page
- Focus Mode

### 2. Userscripts

Small JavaScript files injected into webpages through `WKWebView`.

Examples:

- Dark Reader Lite
- Hide popups
- Clean article pages
- Focus Mode
- Page cleanup tools

### 3. Limited Manifest Extensions

Future support for a small subset of WebExtension-style manifests.

Example:

```json
{
  "name": "Dark Reader Lite",
  "version": "1.0.0",
  "description": "Applies dark styling to webpages.",
  "permissions": ["activeTab", "scripting"],
  "content_scripts": [
    {
      "matches": ["<all_urls>"],
      "js": ["dark-reader-lite.js"]
    }
  ]
}






First Extensions to Build
AI Summariser
Reader Mode
Dark Reader Lite
Focus Mode
Page Notes
Content Blocker
Translate Page


Extension Manager Goals

The extension manager should allow users to:

View installed extensions
Enable or disable extensions
See extension permissions
Configure extension settings
Reset extension data


Limitations

Because Nexa Browser is designed for iOS and iPadOS, extension support will be limited by what WKWebView allows.

The goal is not full desktop extension compatibility. The goal is useful, safe, mobile-friendly extension-style tools.

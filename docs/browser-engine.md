# Browser Engine

Nexa Browser is designed for iOS and iPadOS.

Because of iOS and iPadOS platform limitations, Nexa uses `WKWebView` through Apple WebKit for browsing.

## Engine Direction

Nexa is not a Chromium fork.

Instead, Nexa focuses on building a modern browser experience around:

- Native SwiftUI interface
- WKWebView browsing
- AI assistant tools
- Privacy controls
- Content blocking
- Userscripts
- Curated extension-style features

## Why WKWebView?

`WKWebView` is the standard way to build browser-like experiences inside iOS and iPadOS apps.

It provides:

- Webpage rendering
- JavaScript support
- Navigation controls
- Loading progress
- Cookie and website data management
- Script injection support
- Content-blocking support

## Chromium-Inspired Experience

Nexa may take inspiration from Chromium-based browsers in terms of user experience, such as:

- Clean search/address bar
- Simple tab management
- Fast homepage shortcuts
- Search engine options
- Desktop-style browsing controls

However, Nexa does not include Chromium source code or claim to be Chromium-based.

## Extension Limitations

Because Nexa uses WKWebView, extension support is limited.

Nexa’s planned extension system focuses on:

- Built-in native tools
- JavaScript userscripts
- Limited manifest-style modules
- Safe content scripts
- User-controlled permissions

## Goal

The goal is not to rebuild Chrome.

The goal is to create a clean, private, AI-assisted browser for iPhone and iPad using realistic iOS technology.

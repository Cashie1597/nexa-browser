# App Store Limitations

Nexa Browser is designed for iOS and iPadOS, so it needs to respect Apple platform rules and technical limitations.

This document tracks important limitations that may affect the app design.

## Browser Engine

On iOS and iPadOS, Nexa should use `WKWebView` through WebKit.

Nexa should not claim to be Chromium-based unless it actually uses Chromium, which is not the planned direction.

## Extension Support

Nexa should not promise full Chrome, Firefox, Safari, or Orion extension compatibility.

Instead, Nexa should focus on:

- Built-in native extensions
- JavaScript userscripts
- Limited manifest-style modules
- Curated extension-style tools

## AI Features

AI features should be user-triggered.

Nexa should avoid automatically sending webpage content, private browsing content, passwords, payment details, or sensitive form data to AI providers.

## Privacy Claims

Privacy claims should be accurate and specific.

Avoid vague claims like:

- Completely anonymous
- 100% private
- Blocks everything
- Fully secure

Better wording:

- Privacy-first
- User-controlled AI actions
- Built-in content blocking
- Local-first storage where possible
- Private browsing mode

## Branding

Nexa should not copy:

- Browser names
- Logos
- Icons
- Screenshots
- Proprietary designs
- Source code
- Marketing copy

Nexa can be inspired by modern browser ideas while staying original.

## App Review Notes

Potentially sensitive areas:

- Browser functionality
- Content blocking
- AI page processing
- Extension-style features
- JavaScript injection
- Privacy claims
- Data handling

These areas should be documented clearly before any App Store submission.

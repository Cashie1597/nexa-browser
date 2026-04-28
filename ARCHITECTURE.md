# Architecture

Nexa Browser is designed as a native SwiftUI browser for iOS and iPadOS.

## Main Layers

```text
SwiftUI Interface
    ↓
Browser State / View Models
    ↓
WKWebView Browser Engine
    ↓
AI Assistant / Extensions / Privacy Modules

Core Modules
Browser Core

Handles:

Tabs
Navigation
URL loading
Page title
Loading progress
Search/address input
iPhone and iPad layouts
Privacy Engine

Handles:

Shield controls
Content blocking rules
Tracker blocking concepts
Private browsing mode
Per-site privacy settings
AI Assistant

Handles:

Page summarisation
Ask questions about the current page
Explain selected text
Translate selected text
Rewrite selected text
Prompt shortcuts
API provider support

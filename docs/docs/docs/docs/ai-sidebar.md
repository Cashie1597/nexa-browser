# AI Sidebar

Nexa Browser should include an AI sidebar that helps users understand and work with webpages.

The sidebar should feel native, fast, and optional. Users should control when page content is sent to an AI provider.

## Goals

- Summarise webpages
- Explain selected text
- Translate selected text
- Rewrite selected text
- Answer questions about the current page
- Turn pages into notes
- Work well on iPad split layouts

## Layout

### iPhone

On iPhone, the AI assistant should open as a sheet or full-screen panel.

Possible modes:

- Bottom sheet
- Full-screen assistant
- Floating AI button
- Context menu actions for selected text

### iPad

On iPad, the AI assistant should work as a sidebar.

Suggested layout:

```text
Browser View | AI Sidebar

The browser stays visible while the user asks questions or reads summaries.

Core AI Actions
Summarise Page

Creates a useful summary of the current webpage.

Output options:

Short summary
Detailed summary
Key points
Action items
Important links
Ask About Page

Lets the user ask questions about the current webpage.

Example questions:

What is this page about?
What should I do next?
What are the key risks?
Explain this simply.
Turn this into study notes.
Explain Selected Text

Explains highlighted text in a simple way.

Translate Selected Text

Translates highlighted text into another language.

Rewrite Selected Text

Rewrites highlighted text to make it clearer, shorter, more professional, or easier to understand.

Privacy Rules

The AI sidebar should not automatically send webpage content to an AI provider.

The user should choose an action first.

Examples:

Summarise this page
Explain selected text
Ask AI about this page
Translate selected text
First Version

The first AI sidebar version should support:

Page title
Page URL
Extracted readable page text
Short page summary
Ask a question about the page
Future Ideas
Prompt library
Saved AI notes
Per-site AI permissions
Local model support
Custom API endpoint support
Model selector
AI search mode

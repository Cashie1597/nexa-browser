# Security Policy

Nexa Browser is a privacy-first browser concept for iOS and iPadOS.

Security is important because the app may eventually handle browsing data, page content, AI actions, extensions, userscripts, bookmarks, and private browsing sessions.

## Supported Versions

Nexa Browser is currently in the planning stage.

| Version | Supported |
|---|---|
| Planning / main branch | Yes |
| Released app versions | Not available yet |

## Reporting a Vulnerability

If you find a security issue, please avoid posting sensitive exploit details publicly.

Instead, report the issue through a private GitHub security advisory if available, or open a general issue that says a security concern exists without exposing private details.

## Security Goals

Nexa should aim to:

- Protect browsing data
- Avoid unnecessary tracking
- Keep private mode private
- Limit extension permissions
- Avoid unsafe JavaScript injection
- Make AI actions user-controlled
- Store sensitive settings securely
- Avoid leaking webpage content to AI providers without user action

## Extension Security

Extensions and userscripts should be treated carefully.

Planned protections:

- Clear permissions
- Enable/disable controls
- Per-site settings
- No silent background access
- No automatic access to sensitive pages
- User review before enabling powerful scripts

## AI Security

AI features should only send data when the user chooses an AI action.

Examples:

- Summarise this page
- Explain selected text
- Ask AI about this page
- Translate selected text

Nexa should avoid sending:

- Passwords
- Payment details
- Private browsing content
- Sensitive form fields
- Personal data unless the user clearly chooses to include it

## Responsible Development

Security decisions should favour the user.

If a feature is powerful but risky, it should be disabled by default and clearly explained.

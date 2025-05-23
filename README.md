# BugHunterLens

A simple JavaScript bookmarklet for web recon.

It extracts:

- Internal and external links
- API endpoints
- Dynamic routes (`:[param]`, `[param]`)
- Regex-matched paths
- LocalStorage and SessionStorage entries
- Frontend framework detection (React, Vue, Angular, Next.js)

## How to use

1. Copy the minified code from `bookmarklet.txt`
2. Create a new browser bookmark
3. Paste the code into the URL field
4. Visit any target site and click the bookmark

It will open a new tab with a clean recon report.

## Use cases

- Recon for bug bounty targets
- Initial JS-heavy app exploration
- No extensions, no tools — just click and extract

## Contribute

Pull requests and improvements welcome. Built while learning bug hunting.

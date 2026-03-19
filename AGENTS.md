# Documentation project instructions

## About this project

- This is the documentation site for [Oack](https://oack.io), built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

- Use "monitor" not "check" or "health check"
- Use "probe" for individual check results
- Use "checker" for the monitoring agent (not "node" or "worker")
- Use "alert channel" not "notification channel"
- Use "team" not "workspace" or "project"

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
- Use Mintlify components (Card, CardGroup, Steps, Note, Tip, Warning, Accordion) where appropriate

## Content boundaries

- Document user-facing features only
- Don't document internal admin or ops tooling
- API details should reference the Swagger docs rather than duplicating endpoint specs

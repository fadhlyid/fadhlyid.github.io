# Make this portfolio yours

The English portfolio is a static GitHub Pages site. No build, account, API key, or installation is required. All personal details and projects are explicitly presented as examples.

## Information to prepare

| Section | What to supply |
| --- | --- |
| Identity | Your preferred public name, professional title, city, and portrait |
| Introduction | Your teaching discipline, analytical focus, and target collaboration |
| About | A short personal story connecting teaching, research, and data |
| Selected work | Two or three real projects: question, data source, approach, your role, tools, limitations, verified outcome, and public link |
| Expertise | Tools you actually use and services you are comfortable offering |
| Experience | Institution, role, dates, teaching focus, and specific contributions |
| Education | Degree, field, university, graduation year, and optional thesis |
| Contact | Public professional email and your LinkedIn, GitHub, Scholar/ORCID links |
| Résumé | A real PDF to add to `assets/`, then link from the résumé button |

## Editing

- `index.html` contains the markup, design tokens in `:root`, and JavaScript.
- Search for `[`, `Your Name`, `your name`, `Sample`, `Template`, and `PLACEHOLDER` to locate example content. Update the title and description too.
- Update the `studies` object for case study dialog contents.
- Contact buttons intentionally open setup explanations. Replace the relevant buttons with real links (`mailto:` for email, actual profile URLs, and a résumé download) when the information is ready; remove their `data-contact` attributes and explanatory handlers as appropriate.
- Replace the illustrated portrait with your photo and meaningful alternative text.
- Keep demo chart data labeled as demo data. It is an interaction demonstration, not a claim about your results.
- Remove template notices only once the associated content has been personalized.

## Local development

From the repository root:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Use the existing checkout; cloud tasks are already isolated and do not need a new Git worktree. The server must be started again in a new session. For GitHub Pages use `main` and `/ (root)`.

## Design and interaction

Claude-inspired cream, charcoal, and terracotta. Primary color tokens follow Anthropic's public brand reference: light `#faf9f5`, dark `#141413`, light gray `#e8e6dc`, and orange `#d97757`.

Typography uses Georgia and system sans as explicit fallbacks. These are not Claude's proprietary fonts, and this site does not claim to reproduce the complete official Claude interface design system. Exact typography requires appropriate original font files and permission to use them. No external runtime dependencies or analytics are used.

Public color reference: https://github.com/anthropics/skills/blob/main/skills/brand-guidelines/SKILL.md (the public corporate typography guidance is separate from Claude product typography).

Includes a pointer-responsive constellation, scroll reveals, animated chart perspectives, project dialogs, a mobile menu, and Ctrl/Cmd+K quick navigation. Escape closes dialogs. Keyboard focus and reduced-motion preferences are supported. Content remains visible without JavaScript, while interactive dialogs and charts require JavaScript.

Validated in Chromium at desktop, tablet, and mobile widths. Contact delivery and résumé download await real contact details and a PDF; no backend is configured.

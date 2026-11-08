# Make this portfolio yours

The English portfolio is a static GitHub Pages site. No build, account, API key, or installation is required. The identity, biography, affiliation, education, research interests, publications, grants, peer-review count, public email, and researcher identifiers have been populated from ORCID text supplied by the owner on 8 November 2026. Project case studies and unconfirmed tools remain explicitly presented as examples.

## Profile data already supplied

Source: https://orcid.org/0000-0001-7711-299X (owner-provided full profile text; not independently fetched).

- Muhammad Fadli Azis; public institutional email: fadli@atim.ac.id.
- ORCID: 0000-0001-7711-299X; Scopus Author ID: 57218940451.
- Lecturer in Power System Engineering (Machinery Systems Automation), Politeknik ATI Makassar, since 1 January 2019.
- MSc Electrical Power Systems Engineering, University of Manchester, 2016–2017.
- BEng Electrical Engineering, Institut Teknologi Sepuluh Nopember, 2011–2015.
- Biography and all six research keywords are included.
- Three publication records, with full contributor lists, DOI links, venues, years, record sources, and Scopus EIDs/ISSNs where supplied.
- Two grant records, including titles, funders, and dates. No lead-investigator role, grant amount, or outcome is inferred.
- Three reviews for Electric Power Systems Research, as recorded in ORCID. No review dates or manuscript titles were provided.

## LinkedIn update

Owner-provided profile text, 8 November 2026: https://www.linkedin.com/in/muhammadfadliazis/

- Public headline: Electrical Engineering Lecturer & Researcher.
- Ministry of Industry academic appointments: Lecturer (January 2019–April 2021); Assistant Professor (Asisten Ahli) (May 2021–August 2023); Assistant Professor (Lektor) (September 2023–present).
- Displayed role names follow the supplied LinkedIn wording. The parent employment entry retains the institution and discipline from ORCID; these are not treated as separate simultaneous jobs.
- Actual date ranges are used; copied relative durations are not preserved or recomputed.
- LinkedIn links are active. Private dashboard statistics, notifications, suggestions, and messaging content are excluded.

## Scholar and profile links

Owner-supplied Google Scholar URL: https://scholar.google.com/citations?user=nhcvKaEAAAAJ&hl=en

The About and Contact sections include inline SVG icon links for Email, Scholar, ORCID, Scopus, and LinkedIn. Text labels remain visible, icons are decorative for assistive technology, and external profiles open in a new tab with `noopener noreferrer`. No citation counts or h-index were supplied or inferred. The unconfigured GitHub placeholder action has been removed from the contact row.

## Information still to prepare

| Section | What to supply |
| --- | --- |
| Identity | Portrait (header uses the full name Muhammad Fadli Azis) |
| Introduction | Target remote roles and collaboration preferences |
| About | Optional personal story to complement your ORCID biography |
| Selected work | Two or three real projects: question, data source, approach, your role, tools, limitations, verified outcome, and public link |
| Expertise | Tools you actually use and services you are comfortable offering |
| Experience | Additional roles and specific contributions, if desired |
| Education | Optional thesis or academic highlights |
| Contact | Optional GitHub URL (email, Scholar, LinkedIn, ORCID, and Scopus links are live) |
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

Typography uses locally hosted Source Serif 4 (headings and editorial text) and Inter (body and navigation), with Georgia and system sans fallbacks. Both fonts are open-license alternatives chosen for a similar feel, not Claude's proprietary typefaces. OFL license notices are included in `assets/fonts/`. No external runtime dependencies or analytics are used.

Public color reference: https://github.com/anthropics/skills/blob/main/skills/brand-guidelines/SKILL.md (the public corporate typography guidance is separate from Claude product typography).

Includes a pointer-responsive constellation, scroll reveals, animated chart perspectives, project dialogs, a mobile menu, and Ctrl/Cmd+K quick navigation. Escape closes dialogs. Keyboard focus and reduced-motion preferences are supported. Content remains visible without JavaScript, while interactive dialogs and charts require JavaScript.

Validated in Chromium at desktop, tablet, and mobile widths. Email links use mailto:fadli@atim.ac.id. ORCID and Scopus profile links are live. GitHub and résumé actions await a real URL and a PDF; no backend is configured.

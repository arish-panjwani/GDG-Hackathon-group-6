# Esther – Community Guide (GDG Hackathon)

A voice-first, multilingual guide for newcomers and seniors in Ontario (demo city: Markham).

- Esther greets in the visitor's language; language detected from the device, with self-select
- Newcomer journey (documents, SIN, OHIP, housing, school, jobs) and senior journey (benefits, health, home care, staying connected)
- Steps ordered so nothing depends on a later step; nearest offices with Google Maps directions
- Every screen in the chosen language with English in brackets; two-way counter translator
- Light/dark mode, WCAG 2.0 AA (AODA) accessibility settings, anonymous usage insights (`#insights`)

## Running it
`index.html` is a single self-contained page. Live AI answers, translation and the insights store use the claude.ai Artifact runtime; opened elsewhere, the page runs in English with keyword-free static content.

Planned production stack: Google Maps/Places, Cloud Speech & Translate, Gemini.

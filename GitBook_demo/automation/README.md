# Automation overview

Automation holds the reusable building blocks that keep test steps
consistent across cases: Keywords, Scripts, Formulas, and Libraries, all
filed under a project's Folders.

## Node types

- **Keyword** — a named, reusable action (Input, Verify, Retrieve, File
  Fetch) that Web and Mobile steps apply explicitly
- **Script** — custom logic for cases the built-in keywords don't cover
- **Formula** — shared calculation logic
- **Library** — stacked, reusable collections of the above
- **Flow** — combines a Keyword and a Script under one node

For CAL, API, and PDF node types, you don't choose a keyword directly —
you check a box to include or exclude a field, and the applicable keyword
is derived automatically from that field's type in the model.

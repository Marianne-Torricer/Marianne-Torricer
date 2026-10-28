# AI working conventions — Marianne Torricer

## Purpose and working style
This is my public finance and business portfolio. Use clear, professional language, explain assumptions, and favor reproducible analysis over polished but unsupported claims. Ask before changing the scope of a task. Keep folder names capability-based rather than course-based.

## Human-first academic work
I write the first drafts of my briefs, analyses, recommendations, memos, and reflections. AI may help with mechanical setup, code debugging, checking calculations, formatting, and reviewing my work, subject to my instructor's rules. Never invent results, citations, sources, experiences, or credentials. Flag uncertainty rather than guessing.

## Privacy and data boundaries
Never paste or commit passwords, API keys, authentication tokens, personal financial account numbers, government IDs, private contact details, client or employer confidential information, medical information, or other people's personal data. Use sanitized examples and public or permissioned data only. Do not commit private source files unless explicitly approved and appropriate for a public repository.

## Quality checks
Preserve my existing root README.md biography and RESUME.md unless I explicitly request an edit. Check calculations, filenames, paths, source provenance, and output against requirements before proposing a commit. Do not create folders named for courses, semesters, or weeks. Every directory must contain a meaningful file.

## Naming
Use descriptive, lowercase, hyphen-separated names for capabilities and engagements. Put initial briefs in docs/briefs/, final decision memos in docs/decisions/, analysis outputs in analysis/, and sourced inputs with provenance in data/. For each capability, keep its spec.md alongside its work.

## AI session logging
At the end of every session that changed a file, append one entry to
prompt-log.md: the date, what I asked, what you produced, what was wrong and how
it was caught. Never backfill earlier sessions and never edit a past entry.

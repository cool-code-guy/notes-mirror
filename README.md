<!-- Title -->
# Course Content

Public curriculum data from the course catalog — course structure, learning objectives, lesson text, scripture coverage, and bibliography for 24 active courses.

**No exam questions or answer keys are in this repository.** It's curriculum content only, safe to read, quote, or hand to any AI assistant.

## Use it with Claude (or any AI)

Paste a link from this repo straight into a chat — for a public GitHub repo, Claude's web browsing can read it directly, no upload needed:

- **Start here:** [`catalog/catalog.md`](catalog/catalog.md) — every course, one table.
- **One course in depth:** [`catalog/courses/BIB116.md`](catalog/courses/BIB116.md) (swap the code) — objectives, structure, counts.
- **Full lesson text for a course:** `data/body/<code>.yaml` (lowercase code), e.g. [`data/body/bib116.yaml`](data/body/bib116.yaml).
- **Scripture coverage:** [`indexes/scripture_index.json`](indexes/scripture_index.json) — every passage, and which lessons teach it.
- **Sources cited:** [`indexes/bibliography.json`](indexes/bibliography.json).

Example prompt, once you've pasted a link:

> Using this, draft a one-paragraph description of this course for a denominational training director — plain language, no internal codes.

## Layout

```
catalog/      Every course: objectives, structure, counts. Start here.
indexes/      Scripture coverage + bibliography, cross-referenced.
data/body/    Full lesson text per course (YAML).
```

## Freshness

See [`MANIFEST.yaml`](MANIFEST.yaml) for the generation date. Refreshed automatically when the source curriculum changes.

## Questions

This mirror is curriculum content only. For anything involving exam questions, assessment design, or internal curriculum operations, contact the Berean exam team directly — that data isn't public.

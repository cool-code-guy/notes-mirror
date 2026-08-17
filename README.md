<!-- Title -->
# Course Content

Public curriculum data from the course catalog — course structure, learning objectives, lesson text, scripture coverage, and bibliography for 24 active courses.

**No exam questions or answer keys are in this repository.** It's curriculum content only, safe to read, quote, or hand to any AI assistant.

## Use it with Claude (or any AI)

**Copy one of the exact links below and paste it into the chat** — not a link to this page, and not the plain repo URL. Those are pages meant for a browser to render; an AI fetching a URL directly needs the raw-content link, or it'll get a 404 the same way a plain text fetch would on any GitHub page. Each link is alone on its own line below — copy the whole line, nothing more, nothing less.

**Start here — every course, one table:**

https://raw.githubusercontent.com/cool-code-guy/notes-mirror/main/catalog/catalog.md

**One course in depth (swap BIB116 for another code):**

https://raw.githubusercontent.com/cool-code-guy/notes-mirror/main/catalog/courses/BIB116.md

**Full lesson text for a course (swap bib116, lowercase):**

https://raw.githubusercontent.com/cool-code-guy/notes-mirror/main/data/body/bib116.yaml

**Scripture coverage — every passage, and which lessons teach it:**

https://raw.githubusercontent.com/cool-code-guy/notes-mirror/main/indexes/scripture_index.json

**Sources cited:**

https://raw.githubusercontent.com/cool-code-guy/notes-mirror/main/indexes/bibliography.json

Example prompt, once you've pasted a link:

> Using this, draft a one-paragraph description of this course for a denominational training director — plain language, no internal codes.

If a link 404s or the assistant says it can't reach it: check that you copied the exact `raw.githubusercontent.com` line above and nothing else — not a `github.com/.../blob/...` page URL, which looks similar but isn't the same thing to a fetch tool.

## Layout

```
catalog/      Every course: objectives, structure, counts. Start here.
indexes/      Scripture coverage + bibliography, cross-referenced.
data/body/    Full lesson text per course (YAML).
```

## Freshness

Generation date is in the manifest, on its own line, below:

https://raw.githubusercontent.com/cool-code-guy/notes-mirror/main/MANIFEST.yaml

Refreshed automatically when the source curriculum changes.

## Questions

This mirror is curriculum content only. For anything involving exam questions, assessment design, or internal curriculum operations, contact the Berean exam team directly — that data isn't public.

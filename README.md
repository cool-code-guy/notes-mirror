<!-- Title -->
# Course Content

Public curriculum data from the course catalog — course structure, learning objectives, lesson text, scripture coverage, and bibliography for 24 active courses.

**No exam questions or answer keys are in this repository.** It's curriculum content only, safe to read, quote, or hand to any AI assistant.

## Use it with Claude (or any AI)

### Point-and-shoot: just paste the repo link

`https://github.com/cool-code-guy/notes-mirror` works as a starting point on its own — paste it with your question, e.g. *"based on the curriculum here, what does it say about Paul's theology?"* The course table below is part of what gets fetched when an AI reads this page, so it can match your question to a course code and pull that course's full content itself, in a second fetch it does automatically. No second link needed from you.

If it comes back saying it couldn't find anything relevant, or seems to be guessing instead of citing specifics: give it one of the exact links in the next section instead — some fetch tools only read the one URL they're given and won't take that second automatic step.

**Active courses:**

| Code | Title | Level |
| --- | --- | --- |
| BIB111 | Old Testament Survey | 1 |
| BIB114 | Christ in the Synoptic Gospels | 1 |
| BIB116 | New Testament Survey | 1 |
| BIB121 | Introduction to Hermeneutics | 1 |
| BIB211 | Acts: The Holy Spirit at Work in Believers | 2 |
| BIB215 | Romans: Justification by Faith | 2 |
| BIB217 | Prison Epistles | 2 |
| BIB313 | Corinthian Correspondence | 3 |
| BIB318 | Pentateuch | 3 |
| BIB322 | The Poetic Books | 3 |
| MIN171 | Spirit-Empowered Church | 1 |
| MIN183 | Relationships & Ethics in Ministry | 1 |
| MIN223 | Introduction to Homiletics | 2 |
| MIN227 | The Local Church in Evangelism | 2 |
| MIN251 | Effective Leadership | 2 |
| MIN261 | Introduction to AG Missions | 2 |
| MIN281 | Conflict Management | 2 |
| MIN325 | Preaching in the Contemporary World | 3 |
| MIN327 | Church Administration Finance & Law | 3 |
| MIN381 | Pastoral Ministry | 3 |
| THE118 | Introduction to Theology | 1 |
| THE154 | History, Missions, and Governance | 1 |
| THE245 | Eschatology | 2 |
| THE311 | Prayer and Worship | 3 |

### Exact links (when you already know what you want)

Copy one of the links below and paste it into the chat instead of the repo link above — this skips straight to one file, no second fetch needed. Not a link to this page, and not the plain repo URL from above: those render for a browser; an AI fetching a URL directly needs the raw-content link, or it'll 404 the same way a plain text fetch would on any GitHub page. Each link is alone on its own line — copy the whole line, nothing more, nothing less.

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

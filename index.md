---
title: "Course Content"
---

<!-- Title -->
# Course Content

## About this mirror

Published and maintained by the administrator of the Berean School of the Bible / Global University course database, for use in recruitment, partnership, and stakeholder conversations. This is a curriculum content export — course structure, learning objectives, lesson text, scripture coverage, and bibliography for 24 active courses. It is not an official Global University publication or website.

No exam questions or answer keys are in this repository.

## Use it with Claude (or any AI)

### Recommended: the site version

This repo is also published as an ordinary website — real HTML pages, not raw data files. That matters: a raw `.yaml`/`.md` file is served as plain text, which some AI web-fetch tools handle fine and others don't retrieve reliably at all. A real webpage is exactly what every general-purpose web tool is built to read.

**Point-and-shoot** — paste this with your question, e.g. *"based on the curriculum here, what does it say about Paul's theology?"*:

https://cool-code-guy.github.io/notes-mirror/

**One course, full lesson text** (swap `BIB116` for another code — see the table below):

https://cool-code-guy.github.io/notes-mirror/lessons/BIB116.html

**One course, objectives and structure only** (shorter, no lesson prose):

https://cool-code-guy.github.io/notes-mirror/catalog/courses/BIB116.html

**Every course, one table:**

https://cool-code-guy.github.io/notes-mirror/catalog/catalog.html

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

Example prompt, once you've pasted a link:

> Using this, draft a one-paragraph description of this course for a denominational training director — plain language, no internal codes.

### Fallback: raw files

If the site link is ever down, or a tool specifically wants a raw file, these work too — same content, served as plain text/YAML/JSON instead of a rendered page. Each link is alone on its own line — copy the whole line, nothing more, nothing less.

**Every course, one table:**

https://raw.githubusercontent.com/cool-code-guy/notes-mirror/main/catalog/catalog.md

**One course, full lesson text:**

https://raw.githubusercontent.com/cool-code-guy/notes-mirror/main/lessons/BIB116.md

**One course, objectives and structure only:**

https://raw.githubusercontent.com/cool-code-guy/notes-mirror/main/catalog/courses/BIB116.md

**Scripture coverage — every passage, and which lessons teach it:**

https://raw.githubusercontent.com/cool-code-guy/notes-mirror/main/indexes/scripture_index.json

**Sources cited:**

https://raw.githubusercontent.com/cool-code-guy/notes-mirror/main/indexes/bibliography.json

If a link 404s or the assistant says it can't reach it: check that you copied the exact `raw.githubusercontent.com` line above and nothing else — not a `github.com/.../blob/...` page URL, which looks similar but isn't the same thing to a fetch tool. If neither the site nor the raw links work in your particular chat: paste the file's content directly into the conversation instead of a link.

## Layout

```
lessons/          Full lesson text per active course (this is the deep content).
catalog/          Objectives, structure, counts per course. Lighter than lessons/.
indexes/          Scripture coverage + bibliography, cross-referenced.
data/body/        Same content as lessons/, as raw YAML (source format).
```

## Freshness

Generation date is in the manifest, on its own line, below:

https://raw.githubusercontent.com/cool-code-guy/notes-mirror/main/MANIFEST.yaml

Refreshed automatically when the source curriculum changes.

## Questions

This mirror is curriculum content only. For anything involving exam questions, assessment design, or internal curriculum operations, contact the Berean exam team directly — that data isn't public.

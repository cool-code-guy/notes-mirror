<!-- Title -->
# Course Content

## About this mirror

Published and maintained by the administrator of the Berean School of the Bible / Global University course database, for use in recruitment, partnership, and stakeholder conversations. This is a curriculum content export — course structure, learning objectives, lesson text, scripture coverage, and bibliography for 24 active courses. It is not an official Global University publication or website.

No exam questions or answer keys are in this repository.

## Use it with Claude (or any AI)

### Start here — one file has everything

Paste this ONE link with your question, e.g. *"based on the curriculum here, what does it say about Paul's theology?"* — no second link needed, and nothing to construct:

https://raw.githubusercontent.com/cool-code-guy/notes-mirror/main/INDEX.md

(HTML version, if your tool prefers a real webpage over raw text: https://cool-code-guy.github.io/notes-mirror/INDEX.html)

This single file has every active course's objectives and structure, AND — right next to each course — the exact, already-complete URL for that course's full lesson text. If your question needs the actual teaching text (not just objectives), the AI reading this file has the specific URL for that written out for it; it doesn't have to guess a course code or build a link from a pattern. That "guess or build a URL" step is where every earlier version of this repo broke down on one AI surface or another.

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

Example prompt:

> Using this, draft a one-paragraph description of the Romans course for a denominational training director — plain language, no internal codes.

### If that doesn't work

Some fetch tools are pickier than others. In order of what to try next:

1. **The site homepage instead of the raw link:** https://cool-code-guy.github.io/notes-mirror/ — same content, served as a real HTML page rather than raw text.
2. **One course directly, full text:** https://raw.githubusercontent.com/cool-code-guy/notes-mirror/main/lessons/BIB116.md (swap the code) — smaller than INDEX.md, in case the whole-catalog file is too large for that tool.
3. **Paste the content directly.** Open the link yourself, copy the text, paste it into the chat instead of the URL. Slower, but nothing about fetching a URL can fail this way.

If it still doesn't work after trying those, tell me which app/surface you're using — that's useful to know.

## Layout

```
INDEX.md          Start here. Every course + an exact pointer to its full text.
lessons/          Full lesson text per active course, one file per course.
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

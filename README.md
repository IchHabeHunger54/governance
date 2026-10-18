# Governance

This repository contains the documents regarding the organizational governance and policy for the NeoForged project, under which this repository is hosted.

The contents of this repository are placed into the public domain, under the Creative Commons Zero v1.0 Universal license.

## Structure

The governance is kept in **Markdown files** (`.md`). Non-Markdown files are considered technical **metadata** of the repository, and are not part of the governance proper.

[`core.md`][core] defers rulings about specific topics to **articles**, which are each kept in a separate file. An article consists of **paragraphs**, for example `§ 1`. Within a paragraph, there may be **sections**, denoted by secondary headings. A section may be further subdivided into **points**, which are indexed alphabetically (`a.`, `b.`, etc.). If appropriate, a paragraph may also contain points directly, without a section in between. A specific clause of the governance may be referenced by traversing the structure of article -> paragraph -> (section) -> point; for example, `Article 1 § 1 Section 1a`, or `Art 1 § 1.1a` for short.

[`core.md`][core] additionally defines some common terminology to use in governance. Articles may also define terminology at their beginning, which is limited to its article only.

Text may be highlighted in **bold** or **italics**, as deemed necessary, to indicate particularly important parts of an article.

The governance may also contain **notes**, denoted by a Markdown quote (`> `), for example:

> This is a note.

Notes are more informal parts of the governance; they are not meant to be binding, but rather to give context. For instance, they may explain the reasoning behind, suggest a way of practically applying, state the current implementation of, or give an overview over a particular part of the governance.

[core]: core.md

# Theo Armour Genealogy — AI Agent Instructions

## What This Repo Is

My family history: lineage, profiles of family members, source documents and exports from online genealogy services. Published at https://theo-armour.github.io/genealogy. Content is Markdown prose plus data files — this is not a code repo.

**This repo is public.** Everything here can be read by anyone, including the family members it describes.

## Organization

- [Wiki/](Wiki/) — one folder per person, named `Given-Names-Surname-BIRTH-DEATH` (e.g. `Albert-Cameron-Burrage-Sr-1859-1931`; living people end with a dash, `1951-`; a year that isn't known is written `unknown`, e.g. `1797-unknown`).
- [Armour/](Armour/), [Kudashev/](Kudashev/), [Burrage/](Burrage/), [Shirk/](Shirk/) — one folder per grandparent's birth surname.
- [Peeps-in-My-Family.md](Peeps-in-My-Family.md) — notable people in the four families. The dated copies beside it are my backups; leave them alone.
- [Online-Genealogy/](Online-Genealogy/) — Geni, Ancestry, MyHeritage and WikiTree notes.
- [GEDCOM-files/](GEDCOM-files/) — the hand-maintained master tree, [armour-genealogy.ged](GEDCOM-files/armour-genealogy.ged) (one undated file, updated in place), and the dated online-service exports in `2025/`, kept as exported.
- [Documents/](Documents/) — working notes, kept as history.
- [0-genealogy-agenda.md](0-genealogy-agenda.md), [0-genealogy-journal.md](0-genealogy-journal.md) — priorities and dated notes (newest first).
- [index.html](index.html) — TooToo instance that browses this repo (generated; treat as read-only).

## Conventions for Edits

- **Never invent a fact.** Dates, places, relationships, titles and name spellings come from a source or from me. If something is uncertain or sources disagree, say so in the text rather than picking one.
- **Leave sources as they are.** Transcriptions, memoirs (e.g. `Kudashev/souvenirs-de-russie`) and exported GEDCOM files keep their original wording and spelling, in the original language. Put translations and notes alongside, not in place of the original.
- **Living people.** Ask before adding personal details about anyone living — contact details, addresses, health, family disagreements.
- **Nothing private.** Never copy material from my private repos (agenda, journals, people notes) into this one.
- **Master tree follows the Wiki.** When a Wiki biography is added, add that person to `GEDCOM-files/armour-genealogy.ged`, citing their page and giving them `1 REFN <Wiki folder>` / `2 TYPE Wiki`, and give the biography the line `🌳 [See in the family tree](https://theo-armour.github.io/gedcom-viewer/#wiki=<Wiki folder>)` just before its first `##` section. When a Wiki folder is renamed, update its `REFN`, the page address in the citation, and the viewer's `WIKI` list in the gedcom-viewer repo. Edit the master in place; don't make dated copies.
- **Names.** Follow the Wikipedia-style convention used here: given names then family name, the name that would appear on the tombstone. Keep existing transliterations of Russian names unless I ask.
- **Voice.** Plain, direct, first person, with recollections and meaning as well as facts. Apply proofreading edits and new additions directly; propose wording changes first only when deleting or replacing existing information.
- **Autonomy.** Make reasonable assumptions and apply changes directly without asking clarifying questions unless something is destructive or ambiguous.

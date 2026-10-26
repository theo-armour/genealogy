# Genealogy Wiki Style Guide

Conventions for the person pages in this folder. One folder per person, one main Markdown page per folder.

## Folder and File Naming

* Folder: `Firstname-Middlenames-Lastname-BIRTH-DEATH` ~ e.g. `George-Allison-Armour-1856-1936`
* Living people: trailing hyphen after birth year ~ e.g. `Allison-Armour-1951-`
* Main page: same name as the folder, plus `.md`
* Images go in an `images/` subfolder; research documents (PDF, DOCX) may sit at the folder root
* Files shared across pages live in the repo-root `commons/` folder ~ link as `../../commons/...`
* Superseded pages and folders move to `archive/`

## Page Template

```markdown
# Full Name (1863–1933) ~ Native-script name

![portrait caption](images/portrait.jpg)

| `portrait.jpg` | Caption describing the image | [Source](https://example.com) |

## Genealogy

## Names and Spellings

## Life

## Residences

## Works

## Links

## Research Notes

## My Comments
```

## The Headings

* **Genealogy** ~ the structured facts: Geni URL first, then birth, death, parents, partner, children. Link relatives to their pages with relative links: `[Name](../Folder-Name/Folder-Name.md)`
* **Names and Spellings** ~ Cyrillic original, transliterations (modern, French, German), "also recorded as" variants, titles. Keep even if it is a single line ~ it helps searching
* **Life** ~ the narrative. Free-form `###` subsections as needed: Early life, Career, Marriage and family, Death
* **Residences** ~ one bullet per address with dates. Add period images where available and a Google Maps / Street View link where the building survives
* **Works** ~ what they built, founded, wrote, collected, or made happen: buildings, companies, ships, sculptures, translations, art collections. Link to external pages about the works
* **Links** ~ external resources: Geni, MyHeritage, Wikipedia, Find a Grave, newspaper archives, AI research chats
* **Research Notes** ~ raw findings and correspondence, newest on top, as `### YYYY-MM-DD ~ topic`. Notes graduate into Life once digested
* **My Comments** ~ first-hand memories and family lore. The memoir layer: what Theo knows directly, as opposed to what the documents say. Always last

Empty headings are fine ~ an empty heading is a standing research prompt, not a failure.

## Other Conventions

* Title format: `# Full Name (birth–death) ~ Native name` with an en dash between years
* Portrait at the top of the page, immediately after the title ~ not inside a section
* Every image gets a one-row caption table: filename, description, source link
* `* Known as:` line directly under the title when there is a family nickname
* Dates in text as `YYYY-MM-DD` where practical

## Changelog

### 2026-08-07

* Create this style guide
* Scaffold the standard headings into all existing person pages

# Genealogy Agenda

## Profiles

* 2026-07-03: Add GiGi profiles and send to Erik
* 2026-07-03: Add links to Geni profiles for each family member
* 2026-07-03: Later: Add links to MyHeritage, Ancestry, WikiTree profiles for each family member
* Standardize the layout for profiles.

## Online Genealogy

* Verify and update the translations of non-English names of family members in the genealogy tree.


## Standard Format

### Folder and file names

* Wikipedia-style hyphenated name plus dates: `First-Middle-Last-YYYY-YYYY/`
* The markdown file inside matches the folder name exactly: `First-Middle-Last-YYYY-YYYY.md`
* Living people: birth year plus trailing dash: `Allison-Armour-1951-`
* Images go in an `images/` subfolder
* No parentheses, spaces, quotes, or en dashes in names; hyphens only
* Russian surnames: masculine for men (Kudashev), feminine for women (Kudasheva); foreign names (von Nieroth) do not inflect

### Profile file layout

```markdown
# First "Nickname" Last (YYYY–YYYY) ~ Native-script name if any

![Name](images/photo.jpg)

| `photo.jpg` | Caption (YYYY–YYYY) | [Source](url) |

## Genealogy

* Geni: https://www.geni.com/people/...
* Full name: ...
* Known as: ...
* Birth: Mon DD YYYY - Place
* Death: Mon DD YYYY - Place
* Parents: ...
* Siblings: ...
* Partner: ...
* Children: ...

## Names and Spellings

* Russian: Мария Сергеевна Кудашева
* Modern transliteration: Maria Sergeyevna Kudasheva
* French transliteration: Myra Sergéïevna Koudacheff ~ as used in émigré documents
* Also seen as: Koudachev, Kudascheff ~ note where each spelling appears
* Married name: ...
* Patronymic: daughter/son of ...

## Links

* Wikipedia, obituaries, archives, other profiles (MyHeritage, Ancestry, WikiTree)

## Life

Short biography in prose.

## My Comments

Personal memories and anecdotes — the good stuff.
```

Notes:

* Every heading uses the en dash (–) between years; file names use hyphens.
* Nickname in quotes in the heading only, never in file names.
* The Geni bullet block is pasted from Geni, so keep its wording; corrections go in Links or My Comments.
* Names and Spellings is optional for straightforward English names; essential for the Russians, where one person may appear under Cyrillic, modern English, French émigré, and German spellings in different sources. Noting where each variant appears makes archive searches much easier.

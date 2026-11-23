# GEDCOM Files ~ Read Me

Family tree exports from the online services, named by export date, in [2025/](2025/). These are source files and stay exactly as exported.

The master tree, which I maintain by hand, is [armour-genealogy.ged](armour-genealogy.ged).

## Master tree

* [armour-genealogy.ged](armour-genealogy.ged) ~ GEDCOM 5.5.1, UTF-8 ~ one person for each Wiki biography (55), plus 12 people needed to connect them ~ facts taken from the biographies, each person cited to their Wiki page and given a `REFN` of `TYPE Wiki` naming their Wiki folder (the GEDCOM Viewer uses it for biography links), with notes where sources disagree ~ living people by name only ~ [open in Topola](https://pewu.github.io/topola-viewer/#/view?url=https://theo-armour.github.io/genealogy/GEDCOM-files/armour-genealogy.ged)

It's one undated file, updated in place; git keeps the earlier versions. Started 22 November 2026.

**Keeping it in step with the Wiki.** Every person with a Wiki biography is in the master tree, with a line naming their Wiki folder:

```text
1 REFN Maria-Sergeyevna-Kudasheva-1896-1990
2 TYPE Wiki
```

When a biography is added, add the person to the tree with this line, and give the biography a `🌳 [See in the family tree](https://theo-armour.github.io/gedcom-viewer/#wiki=<folder>)` line before its first section, as the others have. When a Wiki folder is renamed, change the line to match. The GEDCOM Viewer uses it to link people to their biographies, even when the tree's years differ from the folder name. `REFN` is a standard GEDCOM tag, so other programs keep it, showing it at most as a reference number.

## Start here

* [GEDCOM Viewer](https://theo-armour.github.io/gedcom-viewer/) ~ my viewer: opens the master tree (the exports below are left out, since they hold details of living people), links people to their Wiki pages and shows the biographies ~ source in its own repo, [theo-armour/gedcom-viewer](https://github.com/theo-armour/gedcom-viewer)
* [0-gedcom.md](0-gedcom.md) ~ notes and links on the GEDCOM format, and the viewer I like

## Exports

* [2025-08-30-export-geni/export-Ancestors.ged](2025/2025-08-30-export-geni/export-Ancestors.ged) ~ Geni, ancestors
* [2025-08-18-export-geni/export-BloodTree.ged](2025/2025-08-18-export-geni/export-BloodTree.ged) ~ Geni, blood tree
* [2025-08-18-myheritage-armour.ged](2025/2025-08-18-myheritage-armour.ged) ~ MyHeritage
* [2025-08-18-armour-ferte.ged](2025/2025-08-18-ancestry-armour-fert%C3%A9/2025-08-18-armour-ferte.ged) ~ Ancestry
* [2025-08-28-matthew-family-tree.ged](2025/2025-08-28-matthew-family-tree.ged) ~ from Matthew ~ see [fiverr/](../Online-Genealogy/fiverr/)
* [2025-08-23-carley-armour-family-tree.ged](2025/2025-08-23-carley-armour-family-tree.ged) ~ from Jeff Carley ~ see [fiverr/](../Online-Genealogy/fiverr/)

The Ancestry export is also kept as downloaded, in [2025-08-18-ancestry-armour-ferté.zip](2025/2025-08-18-ancestry-armour-fert%C3%A9.zip). The unzipped file was renamed from `Armour - Ferté.ged` and differs from the zipped one only in its line endings.

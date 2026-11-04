# Ettingen (city): law history in git

The municipal law of the municipality of Ettingen (Gemeinde Ettingen, canton of Basel-Landschaft, Switzerland) as a git history: one file per article, one commit per amending act on the day it took effect, and the amending act as the commit's author. `git blame` names the act behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law). The law of the canton of Basel-Landschaft is in [lexifina/switzerland-basel-landschaft-law](https://github.com/lexifina/switzerland-basel-landschaft-law); federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in German, exactly as the municipality publishes it.

## What this repository holds

51 acts with 51 versions so far: the Gemeindeordnung (the municipality's charter) first, then the municipality's other enactments in force (ordinances, regulations, tariffs and decisions), in the order of the systematic collection, added in parts of about 50. Only the agreements and statutes listed below are included; concessions, directives and repealed acts are not included.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `1-1-1-go/` | Gemeindeordnung (SRS 1.1-1) | 1 | as enacted, 1 January 2013 |
| `1-2-1/` | Verordnung über die Kommunikation und Information (SRS 1.2-1) | 1 | as enacted, 14 January 2019 |
| `1-4-1/` | Verordnung über das amtliche Informationsblatt zu Gemeindewahlen nach dem Mehrheitswahlverfahren (SRS 1.4-1) | 1 | as enacted, 1 December 2023 |
| `1-6-1/` | Verwaltungs- und Organisationsreglement (SRS 1.6-1) | 1 | one version (the oldest available), 27 August 2025 |
| `1-6-1-1/` | Geschäftsordnung des Gemeinderates (SRS 1.6-1.1) | 1 | as enacted, 23 March 2015 |
| `1-6-2-behordenreglement/` | Reglement über Rechte, Pflichten und Entschädigung von Behörden, Organen und Nebenfunktionen (SRS 1.6-2) | 1 | as enacted, 1 January 2015 |
| `1-6-3/` | Verordnung zu den Kommissionen (SRS 1.6-3) | 1 | as enacted, 1 November 2024 |
| `1-7-1/` | Personalreglement (SRS 1.7-1) | 1 | as enacted, 1 January 2015 |
| `1-7-1-1/` | Personalverordnung (SRS 1.7-1.1) | 1 | one version (the oldest available), 1 June 2021 |
| `4-1-1-feb-reglement/` | Reglement über die familienergänzende Kinderbetreuung und die frühe Förderung der deutschen Sprache (SRS 4.1-1) | 1 | as enacted, 1 August 2021 |
| `4-1-1-1-feb-verordnung/` | Verordnung zum Reglement über die familienergänzende Kinderbetreuung und die frühe Förderung der deutschen Sprache (SRS 4.1-1.1) | 1 | as enacted, 10 August 2021 |
| `4-8-1/` | Verordnung über Gemeindebeiträge an Ettinger Vereine (SRS 4.8-1) | 1 | as enacted, 1 September 2014 |
| `5-1-1/` | Polizeireglement (SRS 5.1-1) | 1 | one version (the oldest available), 1 December 2020 |
| `5-1-1-1/` | Verordnung zum Polizeireglement (SRS 5.1-1.1) | 1 | one version (the oldest available), 1 December 2020 |
| `5-5-1/` | Feuerwehr-Reglement (SRS 5.5-1) | 1 | as enacted, 1 January 2014 |
| `5-5-1-1/` | Verordnung zum Feuerwehr-Reglement (SRS 5.5-1.1) | 1 | as enacted, 1 May 2014 |
| `6-3-1/` | Reglement über die Erhebung der Gemeindesteuern (SRS 6.3-1) | 1 | as enacted, 24 January 2001 |
| `6-4-1/` | Gebührenordnung (SRS 6.4-1) | 1 | as enacted, 18 September 2017 |
| `6-6-1/` | Verordnung über die Benutzung der «Schul- und Sportanlage Hintere Matten» (SRS 6.6-1) | 1 | as enacted, 1 July 2024 |
| `6-6-2/` | Verordnung über die Benutzung der «Sportanlage Toggesematt» (SRS 6.6-2) | 1 | as enacted, 1 July 2024 |
| `6-6-3/` | Verordnung über die Benutzung «bisheriges Werkhofareal» (SRS 6.6-3) | 1 | as enacted, 1 July 2024 |
| `6-6-4/` | Verordnung über die Benutzung des Theoriesaals im Feuerwehrmagazin (SRS 6.6-4) | 1 | as enacted, 15 January 2001 |
| `6-8-1/` | Verordnung zum Beschaffungswesen (SRS 6.8-1) | 1 | as enacted, 1 April 2016 |
| `7-1-1/` | Zonenreglement Siedlung (SRS 7.1-1) | 1 | one version (the oldest available), 14 May 2019 |
| `7-1-3/` | Zonenreglement Landschaft (SRS 7.1-3) | 1 | as enacted, 30 May 2011 |
| `7-1-4/` | Reglement über die Ersatzabgabe für nicht realisierbare Parkplätze in der Kernzone (SRS 7.1-4) | 1 | as enacted, 2 May 2006 |
| `7-3-1/` | Reglement über die Feuerungskontrolle (SRS 7.3-1) | 1 | as enacted, 30 June 2024 |
| `7-3-2/` | Reglement über die Förderung von Solaranlagen (SRS 7.3-2) | 1 | as enacted, 1 February 2008 |
| `7-4-3-1/` | Wasser-Reglement (SRS 7.4.3-1) | 1 | one version (the oldest available), 1 January 2024 |
| `7-4-3-2/` | Abwasser-Reglement (SRS 7.4.3-2) | 1 | one version (the oldest available), 1 January 2024 |
| `7-4-4-1/` | Abfallreglement (SRS 7.4.4-1) | 1 | one version (the oldest available), 29 August 2025 |
| `7-4-4-1-1/` | Verordnung über die dezentrale Kompostierung (SRS 7.4.4-1.1) | 1 | as enacted, 22 September 1992 |
| `7-6-1/` | Strassen-Reglement (SRS 7.6-1) | 1 | one version (the oldest available), 13 April 2010 |
| `7-6-2/` | Reklamereglement (SRS 7.6-2) | 1 | as enacted, 22 January 2010 |
| `7-6-2-1/` | Reklame-Verordnung (SRS 7.6-2.1) | 1 | one version (the oldest available), 18 February 2019 |
| `7-7-1/` | Reglement über das nächtliche Dauerparkieren auf öffentlichem Grund (SRS 7.7-1) | 1 | as enacted, 1 January 2022 |
| `7-7-1-1/` | Verordnung zum Reglement über das nächtliche Dauerparkieren auf öffentlichem Grund (SRS 7.7-1.1) | 1 | as enacted, 1 January 2022 |
| `8-2-1/` | Bestattungs- und Friedhofreglement (SRS 8.2-1) | 1 | as enacted, 14 December 2001 |
| `8-2-1-1/` | Verordnung zum Bestattungs- und Friedhofreglement (SRS 8.2-1.1) | 1 | as enacted, 14 December 2001 |
| `8-3-1/` | Reglement über die Hundehaltung (SRS 8.3-1) | 1 | as enacted, 2 June 2010 |
| `8-7-1/` | Reglement über die Kinder- und Jugendzahnpflege (SRS 8.7-1) | 1 | as enacted, 1 January 2009 |
| `8-7-1-1/` | Verordnung über die Subventionsbeiträge in der Kinder- und Jugendzahnpflege (SRS 8.7-1.1) | 1 | one version (the oldest available), 1 September 2024 |
| `8-7-2/` | Reglement über Zusatzbeiträge nach dem Ergänzungsleistungsgesetz (SRS 8.7-2) | 1 | as enacted, 1 January 2024 |
| `8-7-2-1/` | Verordnung zum Reglement über Zusatzbeiträge nach dem Ergänzungsleistungsgesetz (SRS 8.7-2.1) | 1 | as enacted, 1 January 2024 |
| `8-7-3/` | Verordnung über Lagerbeiträge (SRS 8.7-3) | 1 | as enacted, 18 November 2013 |
| `8-8-1/` | Verordnung über den Wohnungsexperten bzw. die Wohnungsexpertin (SRS 8.8-1) | 1 | as enacted, 1 April 2019 |
| `8-8-2/` | Reglement über die Mietzinsbeiträge (SRS 8.8-2) | 1 | as enacted, 1 January 2024 |
| `8-8-2-1/` | Verordnung zum Reglement über die Mietzinsbeiträge (SRS 8.8-2.1) | 1 | as enacted, 1 January 2024 |
| `9-5-1/` | Verordnung über die Erteilung von Gelegenheitswirtschaftsbewilligungen und Freinachtbewilligungen (SRS 9.5-1) | 1 | as enacted, 1 September 2014 |
| `5-3-1-1/` | Statuten Zweckverband Bevölkerungs- und Zivilschutz Leimental (SRS 5.3-1.1) | 1 | one version (the oldest available), 1 January 2003 |

| `7-1-2/` | Teilzonenplan «Kammermatten – Toggessenmatten»: Teilzonenreglement (SRS 7.1-2) | 1 | current official change-marked text, 30 March 2010 |

## Source

The SRS (systematic collection) of the municipality, published by the municipality at <https://ettingen.tlex.ch/>. For each act it gives every consolidated version it holds, with the day each version took effect, and a change table listing each amendment: its decision date, the day it took effect, the provision it touched and its entry in the chronological collection (CRS). Annexes the collection publishes only as separate PDF files are not included.

## Dates

- Each commit is dated at **noon, Europe/Zurich, on the day the version took effect**, as the collection gives it ("in Kraft seit / von"). The decision date of each amending act is the `Enacted:` trailer.
- An act's first commit is its oldest version in the collection. It is credited to the act as enacted only when the change table shows no amendment in force before it; otherwise it is the "oldest version available", naming the earlier amendments.
- Versions that take effect after the retrieval day are on the `zukunft` branch, never merged into `main`.
- `--before="YYYY-MM-DD"` alone uses your clock's time of day; use `T23:59:59Z` or `tools/on.py`.

## Files

`<act>/art-005.md` is Art. 5 (or § 5), `art-005a.md` Art. 5a; `ingress.md` holds the title, date and preamble; `gliederung.md` the section headings; `schluss.md` the closing formula and signatures. One paragraph or list item per line. Amendment markers (`*`), footnote numbers and the "Stand" date are left out.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the municipality's own text of that version, and every article's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the amending act, named by its entry in the chronological collection (CRS), with an e-mail address that cannot exist (`<act key>@ettingen.tlex.ch.invalid`). Where one version holds changes by several amending acts and the change table does not say which provision each one touched, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one the municipality publishes as binding. The history starts with the oldest consolidated version the collection holds for each act, which for many acts is later than the act's enactment. Only the acts listed above are included.

## Acts published only as PDF

Some acts of this collection are published only as a PDF. Those with a text layer and articles (agreements, statutes of associations, regulations) are added in parts named `50-pdf-erlasse-NN`: one version each, the current text, dated by the in-force day the collection gives for it and credited to its Beschluss. The text is read from the PDF (PyMuPDF) and checked against a second, independent reader (poppler pdftotext): the letters and digits are equal and every line is found in order. Land-use plans, maps and acts without articles are not included.

## Teilzonenreglement Kammermatten – Toggessenmatten

The current official PDF is retained as one text file per page. Its deletion markings remain struck through. Pages 4, 6, …, 30 contain the publisher's expressly nonbinding commentary and are identified accordingly. Textual tables and approval information are included. Graphic illustrations are deferred from this text record. The municipality states that this version took effect on 30 March 2010 (decision: 14 October 2009).

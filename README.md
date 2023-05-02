As of April 2023, releases of the PROIEL Treebank have moved to https://github.com/syntacticus/syntacticus-treebank-data.

The PROIEL Treebank
===================

The _PROIEL Treebank_ is a dependency treebank with morphosyntactic and
information-structure annotation. It includes texts in several ancient
Indo-European languages and is freely available under a [Creative Commons
Attribution-NonCommercial-ShareAlike 3.0 License](
http://creativecommons.org/licenses/by-nc-sa/3.0/us/).

Please cite as

> Dag T. T. Haug and Marius L. Jøhndal. 2008. 'Creating a Parallel Treebank of the Old Indo-European Bible Translations'. In Caroline Sporleder and Kiril Ribarov (eds.). Proceedings of the Second Workshop on Language Technology for Cultural Heritage Data (LaTeCH 2008) (2008), pp. 27-34.

Releases of the PROIEL Treebank are hosted on
[Github](https://github.com/proiel/proiel-treebank).

Contents
--------

The following texts are included in this release of the treebank:

  Text                                                | Language            | Filename    | Size
  ----------------------------------------------------|---------------------|-------------|---------------
  The Greek New Testament (ed. Tischendorf 1869)      | Ancient Greek       | greek-nt    | 140,763 tokens
  The Armenian New Testament (ed. Künzle 1984)        | Classical Armenian  | armenian-nt |  23,513 tokens
  The Gothic Bible (ed. Streitberg 1919)              | Gothic              | gothic-nt   |  57,211 tokens
  Codex Marianus (ed. Jagić 1883)                     | Old Church Slavonic | marianus    |  58,269 tokens
  Jerome's Vulgate                                    | Latin               | latin-nt    | 112,454 tokens
  Caesar, Commentarii belli Gallici (ed. Holmes 1914) | Latin               | caes-gal    |  28,607 tokens
  Cicero, De officiis (ed. Miller 1913)               | Latin               | cic-off     |  10,644 tokens
  Cicero, Epistulae ad Atticum (ed. Purser 1901)      | Latin               | cic-att     |  42,855 tokens
  Palladius, Opus agriculturae (ed. Schmitt 1898)     | Latin               | pal-agr     |  12,148 tokens
  Peregrinatio Aetheriae (ed. Heraeus 1908)           | Latin               | per-aeth    |  18,356 tokens
  Herodotus, Histories (ed. Godley 1920)              | Ancient Greek       | hdt         |  85,080 tokens
  Sphrantzes, Chronicles (post-1453) (ed. Grecu 1966) | Ancient Greek       | chron       |  24,612 tokens

(The 'size' column in the table above shows the number of annotated tokens in
a text. The number of tokens will be slightly larger than the number of words
in the original printed edition as some words have been split into multiple
tokens and some tokens have been inserted during annotation.)

Please see the XML files for detailed metadata and a full list of contributors.

Some sentences have not yet been annotated. This is an overview of where in the
texts unannotated sentences occur:

Sections in which more than half of sentences have not yet been annotated:
* `armenian-nt`: JOHN 1-21, MATT 1-28, MARK 1-16
* `caes-gal`: 5.8-5.58, books 7, book 8
* `cic-att`: 6.2-6.9, 7.2-7.9, 7.11-7.26, 8.1-8.16
* `cic-off`: 1.114-1.161, book 2, book 3
* `greek-nt`: HEB 13, 1PET 3-5, 2PET 1-3, 1JOHN 1-5, 2JOHN 1, 3JOHN 1, JUDE 1
* `hdt`: 1.70, 1.127-1.130, 1.200, book 2, book 3, 4.1-4.156, 5.94-5.101, 6.82, 6.86, 7.1, 7.31, 8.8-8.144, book 9
* `latin-nt`: COL 3-4, 1TIM 1-6, 2TIM 1-3, HEB 1-13, JAS 1-5, 1PET 1-5, 2PET 1-3, 1JOHN 1-5, 2JOHN 1, 3JOHN 1
* `pal-agr`: 2.12, 3.13-3.34, books 4-14

Sections or section ranges in which there are gaps:
* `armenian-nt`: LUKE 3
* `caes-gal`: 6.36
* `cic-att`: 1.17-1.20, 2.3-2.24, 3.20-3.23, 4.2-4.19, 5.2-5.21, 6.1, 7.1
* `cic-off`: 1.7-1.10, 1.38, 1.48, 1.61, 1.100, 1.106, 1.112, 1.133
* `hdt`: 1.45-1.69, 1.126, 1.141-1.216, 4.157-4.198, 5.1-5.109, 6.12-6.138, 7.2-7.198, 7.220-7.234, 8.3-8.7
* `latin-nt`: ACTS 21-28, ROM 11, ROM 13, GAL 1-6, EPH 3-5, PHIL 1, PHIL 3, COL 1-2, 2THESS 3, 2TIM 4, JUDE 1
* `marianus`: MATT 5, MARK 16, LUKE 2, LUKE 24, JOHN 1-2, JOHN 18, JOHN 20
* `pal-agr`: 1.4-1.12, 1.35-1.40, 2.3, 2.9-2.23, 3.9-3.10

These gaps will be completed in future releases.

Data formats
------------

The texts are available on two formats:

1. PROIEL XML: These files are the authoritative source files and the only ones
that contain all available annotation. They contain the complete morphological,
syntactic and information-structure annotation, as well as the complete text,
including punctuation, section headers etc. The schema is defined in
[`proiel.xsd`](https://github.com/proiel/proiel-treebank/blob/master/proiel.xsd).

2. [CoNLL-X format](http://nextens.uvt.nl/depparse-wiki/DataFormat)

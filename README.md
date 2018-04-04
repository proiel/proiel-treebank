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
  The Greek New Testament (ed. Tischendorf 1869)      | Ancient Greek       | greek-nt    | 140,757 tokens
  The Armenian New Testament (ed. Künzle 1984)        | Classical Armenian  | armenian-nt |  23,513 tokens
  The Gothic Bible (ed. Streitberg 1919)              | Gothic              | gothic-nt   |  57,211 tokens
  Codex Marianus (ed. Jagić 1883)                     | Old Church Slavonic | marianus    |  58,269 tokens
  Jerome's Vulgate                                    | Latin               | latin-nt    | 112,468 tokens
  Caesar, Commentarii belli Gallici (ed. Holmes 1914) | Latin               | caes-gal    |  28,608 tokens
  Cicero, De officiis (ed. Miller 1913)               | Latin               | cic-off     |  10,644 tokens
  Cicero, Epistulae ad Atticum (ed. Purser 1901)      | Latin               | cic-att     |  42,708 tokens
  Palladius, Opus agriculturae (ed. Schmitt 1898)     | Latin               | pal-agr     |  12,148 tokens
  Peregrinatio Aetheriae (ed. Heraeus 1908)           | Latin               | per-aeth    |  18,356 tokens
  Herodotus, Histories (ed. Godley 1920)              | Ancient Greek       | hdt         |  85,080 tokens
  Sphrantzes, Chronicles (post-1453) (ed. Grecu 1966) | Ancient Greek       | chron       |  24,612 tokens

(The 'size' column in the table above shows the number of annotated tokens in
a text. The number of tokens will be slightly larger than the number of words
in the original printed edition as some words have been split into multiple
tokens and some tokens have been inserted during annotation.)

Please see the XML files for detailed metadata and a full list of contributors.

Data formats
------------

The texts are available on two formats:

1. PROIEL XML: These files are the authoritative source files and the only ones
that contain all available annotation. They contain the complete morphological,
syntactic and information-structure annotation, as well as the complete text,
including punctuation, section headers etc. The schema is defined in
[`proiel.xsd`](https://github.com/proiel/proiel-treebank/blob/master/proiel.xsd).

2. [CoNLL-X format](http://nextens.uvt.nl/depparse-wiki/DataFormat)

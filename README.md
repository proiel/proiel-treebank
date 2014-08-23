[![DOI](https://zenodo.org/badge/5147/proiel/proiel-treebank.png)](http://dx.doi.org/10.5281/zenodo.11370)

The PROIEL Treebank
===================

The _PROIEL Treebank_ is a dependency treebank with morphosyntactic and
information-structure annotation. It includes texts in several ancient
Indo-European languages and is freely available under a [Creative Commons
Attribution-NonCommercial-ShareAlike 3.0 License](
http://creativecommons.org/licenses/by-nc-sa/3.0/us/).

Please cite as

> Haug, Dag Trygve Truslew and Marius Jøhndal. 2008. 'Creating a Parallel
> Treebank of the Old Indo-European Bible Translations'. In Khalid Choukri
> (ed.). Proceedings of the Second Workshop on Language Technology for
> Cultural Heritage Data (LaTeCH 2008).

Releases of the PROIEL Treebank are hosted on
[Github](https://github.com/proiel/proiel-treebank).

Contents
--------

The following texts are included in this release of the treebank:

  Text                                           | Language            | Filename    | Size
  ----                                           | --------            | --------    | ----
  The Greek New Testament (ed. Tischendorf 1869) | Ancient Greek       | greek-nt    | 136425 words
  The Armenian New Testament (ed. Künzle 1984)   | Classical Armenian  | armenian-nt | 23454 words
  The Gothic Bible (ed. Streitberg 1919)         | Gothic              | gothic-nt   | 57210 words
  Codex Marianus (ed. Jagić 1883)                | Old Church Slavonic | marianus    | 58269 words
  Jerome's Vulgate                               | Latin               | latin-nt    | 81414 words

Please see the XML files for detailed metadata and a full list of contributors.

Data formats
------------

The texts are available on two formats:

1. PROIEL XML: These files are the authoritative source files. They contain the
   complete morphological, syntactic and information-structure annotation, as well as
   the complete text, including punctuation, section headers etc. The schema is
   defined in `proiel.xsd`.

2. [CoNLL-X format](http://nextens.uvt.nl/depparse-wiki/DataFormat): The CoNLL
   files contain a subset of the information available in the XML files.

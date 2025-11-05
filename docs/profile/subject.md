**Obligation:** Recommended

**Definition:**<br>
Keywords for the subject content of the sample. Keywords should be taken from standard vocabulary, such as the [English Heritage NMR Monument Types Thesaurus](https://heritage-standards.org.uk/fish-vocabularies/#monument-types-thesaurus), [MDA Archaeological Object Thesaurus](https://heritage-standards.org.uk/fish-vocabularies/#archaeological-objects-thesaurus), or the [Getty Research Institute Art & Architecture Thesaurus](https://www.getty.edu/research/tools/vocabularies/aat/).

**Allowed values, examples, other constraints:**<br>
Palynology, Date Stone,...

*Sub-properties:*

[TOC]

---

# 9.1 subjectClassification

**Obligation:** Mandatory

**Definition:**<br>
Mandatory if Subject is included. Should contain at least one, and ideally all, of the following:

<ol type="a">
  <li>The name of the standard vocabulary being used for Subject</li>
  <li>The URI of the standard vocabulary being used</li>
  <li>The URI of the exact term used in Subject</li>
  <li>The classification code (if one exists) of the exact term used in Subject</li>
</ol>

Note that a&b and c&d are normally pair values, so it is encouraged to include both where possible. For machine readability, and if you are using a FAIR vocabulary, it is recommended to include the URI values, with c, being optimal.

**Allowed values, examples, other constraints:**<br>
300251145, http://vocab.getty.edu/page/aat/300251145

FISH Thesaurus of Monument Types, https://heritagedata.org/live/schemes/eh_tmt2.html

<span markdown="1" style="display: flex; justify-content: space-between; margin-top: 2em; flex-wrap: wrap; gap: 0.5em;">
[:material-arrow-left: Previous](../description/){ .md-button }
[Next :material-arrow-right:](../other-identifier/){ .md-button }
</span>
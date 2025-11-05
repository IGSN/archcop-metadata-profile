**Obligation:** Recommended

**Definition:**<br>
Numerical age or range of the sample. Dates and ranges should follow W3CDTF and RKMS-ISO8601, respectively.

**Allowed values, examples, other constraints:**<br>
-300/-150

*Sub-properties:*

[TOC]

---

# 18.1 datingMethod

**Obligation:** Recommended

**Definition:**<br>
Should follow a standard vocabulary such as that provided by the [Dating Techniques](https://heritagedata.org/live/schemes/560/concepts/142128.html) concept provided in the [FISH Archaeological Sciences Thesaurus](https://heritage-standards.org.uk/fish-vocabularies/#archaeological-sciences-thesaurus).

**Allowed values, examples, other constraints:**<br>
Radiocarbon dating

---

# 18.2 datingClassification

**Obligation:** Mandatory

**Definition:**<br>
The vocabulary used for the absolute dating method. Mandatory if datingMethod is included. Should contain at least one, and ideally all, of the following:

<ol type="a">
  <li>The name of the standard vocabulary being used for datingMethod</li>
  <li>The URI of the standard vocabulary being used</li>
  <li>The URI of the exact term used in datingMethod</li>
  <li>The classification code (if one exists) of the exact term used in datingMethod</li>
</ol>

Note that a&b and c&d are normally pair values, so it is encouraged to include both where possible. For machine readability, and if you are using a FAIR vocabulary, it is recommended to include the URI values, with c, being optimal.

**Allowed values, examples, other constraints:**<br>
300054717, http://vocab.getty.edu/page/aat/300054717

FISH Archaeological Sciences Thesaurus, https://heritagedata.org/live/schemes/560.html

<span markdown="1" style="display: flex; justify-content: space-between; margin-top: 2em; flex-wrap: wrap; gap: 0.5em;">
[:material-arrow-left: Previous](../colour/){ .md-button }
[Next :material-arrow-right:](../relative-dating/){ .md-button }
</span>
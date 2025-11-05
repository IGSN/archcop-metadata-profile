**Obligation:** Mandatory

**Definition:**<br>
The type(s) of material(s) that compose the sample. Should follow a controlled vocabulary such as the [Getty Research Institute Art & Architecture Thesaurus](https://www.getty.edu/research/tools/vocabularies/aat/).

**Allowed values, examples, other constraints:**<br>
Ceramic, Fauna, Metal, Soil, Bone,...

*Sub-properties:*

[TOC]

---

# 16.1 materialClassification

**Obligation:** Mandatory

**Definition:**<br>
The vocabulary used for classification of the material type. Should contain at least one, and ideally all, of the following:

<ol type="a">
  <li>The name of the standard vocabulary being used for sampleMaterialType</li>
  <li>The URI of the standard vocabulary being used</li>
  <li>The URI of the exact term used in sampleMaterialType</li>
  <li>The classification code (if one exists) of the exact term used in sampleMaterialType</li>
</ol>

Note that a&b and c&d are normally pair values, so it is encouraged to include both where possible. For machine readability, and if you are using a FAIR vocabulary, it is recommended to include the URI values, with c, being optimal.

**Allowed values, examples, other constraints:**<br>
300011798, http://vocab.getty.edu/page/aat/300011798

<span markdown="1" style="display: flex; justify-content: space-between; margin-top: 2em; flex-wrap: wrap; gap: 0.5em;">
[:material-arrow-left: Previous](../sample-weight/){ .md-button }
[Next :material-arrow-right:](../colour/){ .md-button }
</span>
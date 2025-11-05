**Obligation:** Recommended

**Definition:**<br>
Lists all investigation types relevant to the resource. Should follow a standard vocabulary such as that provided by the [Intrusive Event](https://heritagedata.org/live/schemes/agl_et/concepts/147297.html) concept provided in the [FISH Event Types Thesaurus](https://heritage-standards.org.uk/fish-vocabularies/#event-thesaurus).

**Allowed values, examples, other constraints:**<br>
Survey, Excavation,...

*Sub-properties:*

[TOC]

---

# 2.1 investigationClassification

**Obligation:** Mandatory

**Definition:**<br>
Mandatory if investigationType is included. Should contain at least one, and ideally all, of the following:

<ol type="a">
  <li>The name of the standard vocabulary being used for investigationType</li>
  <li>The URI of the standard vocabulary being used</li>
  <li>The URI of the exact term used in investigationType</li>
  <li>The classification code (if one exists) of the exact term used in investigationType</li>
</ol>

Note that a&b and c&d are normally pair values, so it is encouraged to include both where possible. For machine readability, and if you are using a FAIR vocabulary, it is recommended to include the URI values, with c, being optimal.

**Allowed values, examples, other constraints:**<br>
http://purl.org/heritagedata/schemes/agl_et/concepts/145151

<span markdown="1" style="display: flex; justify-content: space-between; margin-top: 2em; flex-wrap: wrap; gap: 0.5em;">
[:material-arrow-left: Previous](../project/){ .md-button }
[Next :material-arrow-right:](../investigation-dates/){ .md-button }
</span>
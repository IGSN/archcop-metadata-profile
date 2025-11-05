**Obligation:** Recommended

**Definition:**<br>
Colour(s) of the sample following a standard vocabulary such as the Munsell colour system.

**Allowed values, examples, other constraints:**<br>
2.5YR 3/3 Dark Reddish Brown

*Sub-properties:*

[TOC]

---

# 17.1 colourClassification

**Obligation:** Mandatory

**Definition:**<br>
The vocabulary used for classification of the sample colour(s). Mandatory if Colour is included. Should contain at least one, and ideally all, of the following:

<ol type="a">
  <li>The name of the standard vocabulary being used for Colour</li>
  <li>The URI of the standard vocabulary being used</li>
  <li>The URI of the exact term used in Colour</li>
  <li>The classification code (if one exists) of the exact term used in Colour</li>
</ol>

Note that a&b and c&d are normally pair values, so it is encouraged to include both where possible. For machine readability, and if you are using a FAIR vocabulary, it is recommended to include the URI values, with c, being optimal.

**Allowed values, examples, other constraints:**<br>
Munsell, 'By eye',...

---

# 17.2 colouredArea

**Obligation:** Recommended

**Definition:**<br>
The area of the sample for which colours are being described.

**Allowed values, examples, other constraints:**<br>
Urn handle

<span markdown="1" style="display: flex; justify-content: space-between; margin-top: 2em; flex-wrap: wrap; gap: 0.5em;">
[:material-arrow-left: Previous](../sample-material-type/){ .md-button }
[Next :material-arrow-right:](../absolute-dating/){ .md-button }
</span>
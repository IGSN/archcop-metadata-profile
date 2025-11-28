**Obligation:** Recommended

**Definition:**<br>
How the sample was collected. Where possible, terminology should follow a standard vocabulary.

**Allowed values, examples, other constraints:**<br>
Core, Scoop,...

*Sub-properties:*

[TOC]

---

# 12.1 collectionMethodClassification

**Obligation:** Mandatory

**Definition:**<br>
Mandatory if collectionMethod is included. Should contain at least one, and ideally all, of the following:

<ol type="a">
  <li>The name of the standard vocabulary being used for collectionMethod</li>
  <li>The URI of the standard vocabulary being used</li>
  <li>The URI of the exact term used in collectionMethod</li>
  <li>The classification code (if one exists) of the exact term used in collectionMethod</li>
</ol>

Note that a&b and c&d are normally pair values, so it is encouraged to include both where possible. For machine readability, and if you are using a FAIR vocabulary, it is recommended to include the URI values, with c, being optimal."

**Allowed values, examples, other constraints:**<br>
None

---

# 12.2 sampleHousing

**Obligation:** Mandatory

**Definition:**<br>
What the sample was collected in. If the housing changes at the other stages of the lifecycle, then sampleHousing may be updated to include the new housing and the lifecycle stage (e.g., during analysis or storage). Mandatory if collectionMethod is included.

**Allowed values, examples, other constraints:**<br>
Ziplock bag, Sterile container,...

Polycarbonate storage box (long-term archival)

---

# 12.3 samplePhoto

**Obligation:** Recommended

**Definition:**<br>
A link to a photograph of the sample or its bag/container at the time of collection. Recommendations for photographing archaeological artefacts are given in [this guidance document](https://www.bajr.org/artefact-photography-for-archaeologists-2024/).

**Allowed values, examples, other constraints:**<br>
https://upload.wikimedia.org/wikipedia/commons/5/53/Early_Medieval_Button_Brooch_%28FindID_137891%29.jpg

---

## 12.3.1 photoLicence

**Obligation:** Mandatory

**Definition:**<br>
Any licence information concerning reuse of the sample photograph. Mandatory if samplePhoto is included.

**Allowed values, examples, other constraints:**<br>
CC BY-SA 4.0

<span markdown="1" style="display: flex; justify-content: space-between; margin-top: 2em; flex-wrap: wrap; gap: 0.5em;">
[:material-arrow-left: Previous](../collection-date/){ .md-button }
[Next :material-arrow-right:](../stratigraphic-context/){ .md-button }
</span>
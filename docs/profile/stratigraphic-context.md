**Obligation:** Recommended

**Definition:**<br>
The site or project specific identifier of the stratigraphic or survey unit from which the sample was collected. This property is considered mandatory in the case of samples collected during surveys and excavations.

**Allowed values, examples, other constraints:**<br>
A301

*Sub-properties:*

[TOC]

---

# 13.1 contextType

**Obligation:** Recommended

**Definition:**<br>
The type of stratigraphicContext. Should follow a vocabulary reference such as the [Getty Research Institute Art & Architecture Thesaurus](https://www.getty.edu/research/tools/vocabularies/aat/).

**Allowed values, examples, other constraints:**<br>
Grave, Storage pit, Sunken house,...

---

## 13.1.1 contextClassification

**Obligation:** Mandatory

**Definition:**<br>
Mandatory if contextType is included. Should contain at least one, and ideally all, of the following:

<ol type="a">
  <li>The name of the standard vocabulary being used for contextType</li>
  <li>The URI of the standard vocabulary being used</li>
  <li>The URI of the exact term used in contextType</li>
  <li>The classification code (if one exists) of the exact term used in contextType</li>
</ol>

Note that a&b and c&d are normally pair values, so it is encouraged to include both where possible. For machine readability, and if you are using a FAIR vocabulary, it is recommended to include the URI values, with c, being optimal.

**Allowed values, examples, other constraints:**<br>
300005907, http://vocab.getty.edu/page/aat/300005907

---

# 13.2 siteDiagram

**Obligation:** Recommended

**Definition:**<br>
Image of site that makes the exact location of the sample clear.

**Allowed values, examples, other constraints:**<br>
https://www.researchgate.net/publication/332757371/figure/fig1/AS:11431281416999457@1746102125477/Map-of-the-archaeological-site-of-S-Omobono-showing-sample-collection-locations-and-the.tif

---

## 13.2.1 siteDiagramLicence

**Obligation:** Mandatory

**Definition:**<br>
Any licence information concerning reuse of the site diagram. Mandatory if siteDiagram is included.

**Allowed values, examples, other constraints:**<br>
CC BY 4.0

---

# 13.3 Zone

**Obligation:** Recommended

**Definition:**<br>
Identifier(s) of the zone(s) from which the sample was collected. Such that relevant, investigation-specific information may be captured, 'zone' is deliberately left undefined. It may be an area/quadrant, trench, or otherwise. Moreover, identifiers from zones at different granularities may be included. In this latter case, it is recommended to include the type of zone alongside each identifier.

**Allowed values, examples, other constraints:**<br>
Area: D24, Trench: VII, Transect: S9/E

---

# 13.4 soilTexture

**Obligation:** Recommended

**Definition:**<br>
Texture as per agreed standards, such as the [FAO World Reference Base for Soil Resources](https://www.fao.org/soils-portal/data-hub/soil-classification/world-reference-base/en/).

**Allowed values, examples, other constraints:**<br>
Sandy silt

---

## 13.4.1 soilClassification

**Obligation:** Mandatory

**Definition:**<br>
Mandatory if soilTexture is included. Should contain at least one, and ideally all, of the following:

<ol type="a">
  <li>The name of the standard vocabulary being used for soilTexture</li>
  <li>The URI of the standard vocabulary being used</li>
  <li>The URI of the exact term used in soilTexture</li>
  <li>The classification code (if one exists) of the exact term used in soilTexture</li>
</ol>

Note that a&b and c&d are normally pair values, so it is encouraged to include both where possible. For machine readability, and if you are using a FAIR vocabulary, it is recommended to include the URI values, with c, being optimal.

**Allowed values, examples, other constraints:**<br>
300014341, http://vocab.getty.edu/page/aat/300014341

---

# 13.5 contextDescription

**Obligation:** Optional

**Definition:**<br>
Additional information about the stratigraphicContext.

**Allowed values, examples, other constraints:**<br>
A301 was the third layer in Cesspit 12.

<span markdown="1" style="display: flex; justify-content: space-between; margin-top: 2em; flex-wrap: wrap; gap: 0.5em;">
[:material-arrow-left: Previous](../collection-method/){ .md-button }
[Next :material-arrow-right:](../sample-depth/){ .md-button }
</span>
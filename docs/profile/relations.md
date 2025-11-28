**Obligation:** Recommended

**Definition:**<br>
Relationships to other research outputs/entities that are identified by a globally unique identifier. In particular, if the sample was derived or subsampled from a parent source, and any references to analytical results (datasets).

**Allowed values, examples, other constraints:**<br>
See subproperties for examples and obligations.

*Sub-properties:*

[TOC]

---

# 22.1 relatedIdentifier

**Obligation:** Mandatory

**Definition:**<br>
The globally unique identifier assigned to the related research output/entity. Mandatory if Relations is used.

**Allowed values, examples, other constraints:**<br>
10.61585/m-tx-202500660

---

# 22.2 identifierType

**Obligation:** Mandatory

**Definition:**<br>
The type of globally unique identifier that is assigned to the related research output/entity. Mandatory if Relations is used.

**Allowed values, examples, other constraints:**<br>
Allowed values follow the controlled list for the relatedIdentifierType subproperty in the DataCite Metadata Schema. Please see the [documentation](https://schema.datacite.org/) of the latest version of the DataCite Schema for the list and examples.

---

# 22.3 relationType

**Obligation:** Mandatory

**Definition:**<br>
The relationship between the current sample being described and the related research output/entity. Mandatory if Relations is used.

**Allowed values, examples, other constraints:**<br>
Allowed values follow the controlled list for the relationType subproperty in the DataCite Metadata Schema. Please see the [documentation](https://schema.datacite.org/) of the latest version of the DataCite Schema for the list and examples.

---

#22.4 relatedMetadataScheme

**Obligation:** Mandatory

**Definition:**<br>
Mandatory only if either the HasMetadata or IsMetadataFor relationType is used, should not be used in other cases.

If the sample has already been described using a metadata schema specific to your institution, discipline, or community, this may be linked using the ‘HasMetadata’ relationType attribute. Typically, this will take the form of a web-hosted metadata file (via an API endpoint), in which case the 'URL' identifierType should be used. The name, URI, and type of the related schema should be included.

**Allowed values, examples, other constraints:**<br>
Darwin Core Archive, http://rs.tdwg.org/dwc/terms/guides/text/index.htm, DwC-A

---

# 22.5 relatedResource

**Obligation:** Recommended

**Definition:**<br>
The type of the related research output/entity. Should follow a controlled vocabulary; for example, that used for the resourceTypeGeneral property in the [DataCite Metadata Schema](https://schema.datacite.org/).

**Allowed values, examples, other constraints:**<br>
Dataset, JournalArticle, PhysicalObject,...

<span markdown="1" style="display: flex; justify-content: flex-start; margin-top: 2em;">
[:material-arrow-left: Previous](../current-status/){ .md-button }
</span>
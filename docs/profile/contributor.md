**Obligation:** Recommended

**Definition:**<br>
Other individual(s) or organization(s) who have contributed to the collecting, analysis, or managing of the sample.

**Allowed values, examples, other constraints:**<br>
See subproperties for examples. The Role and Name subproperties are mandatory for each Contributor that is listed.

*Sub-properties:*

[TOC]

---

# 6.1 Role

**Obligation:** Mandatory

**Definition:**<br>
The role that the Contributor played in the sample collection, analysis, or management process. Mandatory if a Contributor is listed.

**Allowed values, examples, other constraints:**<br>
Allowed values follow the controlled list for the contributorType subproperty in the DataCite Metadata Schema. Please see the [documentation](https://schema.datacite.org/) of the latest version of the DataCite Schema for the list and examples.

---

# 6.2 Name

**Obligation:** Mandatory

**Definition:**<br>
The full name of the Contributor. The format for a person's name is: Surname, Forename.

**Allowed values, examples, other constraints:**<br>
Bloggs, Joe

Research Data Management Division, German Archaeological Institute

---

## 6.2.1 nameType

**Obligation:** Recommended

**Definition:**<br>
The type of Name. Limited to a binary choice of whether Name belongs to a person or an institution.

**Allowed values, examples, other constraints:**<br>
Personal / Organizational

---

# 6.3 Forename

**Obligation:** Recommended

**Definition:**<br>
The first or given name of the Contributor. Used if Contributor is a person.

**Allowed values, examples, other constraints:**<br>
Joe

---

# 6.4 Surname

**Obligation:** Recommended

**Definition:**<br>
The last or family name of the Contributor. Used if Contributor is a person.

**Allowed values, examples, other constraints:**<br>
Bloggs

---

# 6.5 ORCID

**Obligation:** Recommended

**Definition:**<br>
If it exists, the ORCID iD that uniquely identifies the Contributor. Used if Contributor is a person.

**Allowed values, examples, other constraints:**<br>
https://orcid.org/0000-0003-2881-2599

---

# 6.6 Affiliation

**Obligation:** Recommended

**Definition:**<br>
The organizational or institutional affiliation of the Contributor. Used if Contributor is a person or an institution (e.g., a research department). For the latter, this would likely be the name of its larger/umbrella organization.

**Allowed values, examples, other constraints:**<br>
German Archaeological Institute

---

# 6.7 ROR

**Obligation:** Recommended

**Definition:**<br>
If it exists, the ROR ID that uniquely identifies the organizational affiliation of the Contributor.

**Allowed values, examples, other constraints:**<br>
https://ror.org/041qv0h25

<span markdown="1" style="display: flex; justify-content: space-between; margin-top: 2em; flex-wrap: wrap; gap: 0.5em;">
[:material-arrow-left: Previous](../publisher/){ .md-button }
[Next :material-arrow-right:](../sample-title/){ .md-button }
</span>
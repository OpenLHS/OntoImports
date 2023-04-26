# ONTOIMPORTS Ontology Documentation

[//]: # "This file is meant to be edited by the ontology maintainer."

Welcome to the ONTOIMPORTS documentation!

You can find descriptions of the standard ontology engineering workflows [here](odk-workflows/index.md).

## Imports
Imports are subsets of external ontologies that contain terms and axioms you would like to re-use in your ontology. These are considered "external", like dependencies in software development, and are not included in your "base" product, which is the [release artefact](https://github.com/INCATools/ontology-development-kit/blob/master/docs/ReleaseArtefacts.md) which contains only those axioms that you personally maintain.

These are the current imports in ONTOIMPORTS

| Import | URL | Type |
| ------ | --- | ---- |
| bfo | http://purl.obolibrary.org/obo/bfo.owl | mirror |
| ro | http://purl.obolibrary.org/obo/ro.owl | None |
| obi | http://purl.obolibrary.org/obo/obi.owl | None |
| iao | http://purl.obolibrary.org/obo/iao.owl | None |



## Classes

These are the external classes included in ONTOIMPORTS

|IRI                                           |label                                    |
|----------------------------------------------|-----------------------------------------|
|http://purl.obolibrary.org/obo/BFO_0000002    |continuant                               |
|http://purl.obolibrary.org/obo/BFO_0000144    |process profile                          |
|http://purl.obolibrary.org/obo/BFO_0000035    |process boundary                         |
|http://purl.obolibrary.org/obo/BFO_0000003    |occurrent                                |
|http://purl.obolibrary.org/obo/BFO_0000148    |zero-dimensional temporal region         |
|http://purl.obolibrary.org/obo/BFO_0000026    |one-dimensional spatial region           |
|http://purl.obolibrary.org/obo/BFO_0000008    |temporal region                          |
|http://purl.obolibrary.org/obo/BFO_0000141    |immaterial entity                        |
|http://purl.obolibrary.org/obo/BFO_0000001    |entity                                   |
|http://purl.obolibrary.org/obo/BFO_0000034    |function                                 |
|http://purl.obolibrary.org/obo/BFO_0000024    |fiat object part                         |
|http://purl.obolibrary.org/obo/BFO_0000006    |spatial region                           |
|http://purl.obolibrary.org/obo/BFO_0000016    |disposition                              |
|http://purl.obolibrary.org/obo/BFO_0000038    |one-dimensional temporal region          |
|http://purl.obolibrary.org/obo/BFO_0000028    |three-dimensional spatial region         |
|http://purl.obolibrary.org/obo/BFO_0000140    |continuant fiat boundary                 |
|http://purl.obolibrary.org/obo/BFO_0000031    |generically dependent continuant         |
|http://purl.obolibrary.org/obo/BFO_0000029    |site                                     |
|http://purl.obolibrary.org/obo/BFO_0000019    |quality                                  |
|http://purl.obolibrary.org/obo/BFO_0000147    |zero-dimensional continuant fiat boundary|
|http://purl.obolibrary.org/obo/BFO_0000040    |material entity                          |
|http://purl.obolibrary.org/obo/BFO_0000023    |role                                     |
|http://purl.obolibrary.org/obo/BFO_0000182    |history                                  |
|http://purl.obolibrary.org/obo/BFO_0000027    |object aggregate                         |
|http://purl.obolibrary.org/obo/BFO_0000017    |realizable entity                        |
|http://purl.obolibrary.org/obo/BFO_0000011    |spatiotemporal region                    |
|http://purl.obolibrary.org/obo/BFO_0000009    |two-dimensional spatial region           |
|http://purl.obolibrary.org/obo/BFO_0000145    |relational quality                       |
|http://purl.obolibrary.org/obo/BFO_0000142    |one-dimensional continuant fiat boundary |
|http://purl.obolibrary.org/obo/BFO_0000030    |object                                   |
|http://purl.obolibrary.org/obo/BFO_0000020    |specifically dependent continuant        |
|http://purl.obolibrary.org/obo/BFO_0000004    |independent continuant                   |
|http://purl.obolibrary.org/obo/BFO_0000015    |process                                  |
|http://purl.obolibrary.org/obo/BFO_0000018    |zero-dimensional spatial region          |
|http://purl.obolibrary.org/obo/BFO_0000146    |two-dimensional continuant fiat boundary |
|http://purl.obolibrary.org/obo/IAO_0000578    |centrally registered identifier          |
|http://purl.obolibrary.org/obo/IAO_0000310    |document                                 |
|http://purl.obolibrary.org/obo/IAO_0000007    |action specification                     |
|http://purl.obolibrary.org/obo/IAO_0020000    |identifier                               |
|http://purl.obolibrary.org/obo/IAO_0000033    |directive information entity             |
|http://purl.obolibrary.org/obo/IAO_0000005    |objective specification                  |
|http://purl.obolibrary.org/obo/IAO_0000027    |data item                                |
|http://purl.obolibrary.org/obo/IAO_0000030    |information content entity               |
|http://purl.obolibrary.org/obo/IAO_0020010    |identifier creating process              |
|http://purl.obolibrary.org/obo/IAO_0000104    |plan specification                       |
|http://purl.obolibrary.org/obo/OBI_0000011    |planned process                          |
|http://purl.obolibrary.org/obo/OBI_0100026    |organism                                 |
|http://purl.obolibrary.org/obo/NCBITaxon_2    |Bacteria                                 |
|http://purl.obolibrary.org/obo/NCBITaxon_10239|Viruses                                  |
|http://purl.obolibrary.org/obo/NCBITaxon_9606 |Homo sapiens                             |
|http://purl.obolibrary.org/obo/NCBITaxon_2157 |Archaea                                  |
|http://purl.obolibrary.org/obo/NCBITaxon_2759 |Eukaryota                                |


## Object properties

These are the external object proerties included in ONTOIMPORTS
|IRI         |value                                                       |
|------------|------------------------------------------------------------|
|http://purl.obolibrary.org/obo/BFO_0000066|occurs in                                                   |
|http://purl.obolibrary.org/obo/RO_0002018|has component process                                       |
|http://purl.obolibrary.org/obo/RO_0002353|output of                                                   |
|http://purl.obolibrary.org/obo/RO_0000087|has role                                                    |
|http://purl.obolibrary.org/obo/RO_0000059|concretizes                                                 |
|http://purl.obolibrary.org/obo/RO_0000081|role of                                                     |
|http://purl.obolibrary.org/obo/RO_0002180|has component                                               |
|http://purl.obolibrary.org/obo/RO_0000058|is concretized as                                           |
|http://purl.obolibrary.org/obo/RO_0002352|input of                                                    |
|http://purl.obolibrary.org/obo/RO_0002350|member of                                                   |
|http://purl.obolibrary.org/obo/RO_0002233|has input                                                   |
|http://purl.obolibrary.org/obo/BFO_0000051|has part                                                    |
|http://purl.obolibrary.org/obo/BFO_0000067|contains process                                            |
|http://purl.obolibrary.org/obo/RO_0000057|has participant                                             |
|http://purl.obolibrary.org/obo/RO_0002351|has member                                                  |
|http://purl.obolibrary.org/obo/BFO_0000055|realizes                                                    |
|http://purl.obolibrary.org/obo/RO_0002234|has output                                                  |
|http://purl.obolibrary.org/obo/BFO_0000050|part of                                                     |
|http://purl.obolibrary.org/obo/RO_0000056|participates in                                             |
|http://purl.obolibrary.org/obo/BFO_0000054|realized in                                                 |
|http://purl.obolibrary.org/obo/RO_0002479|has part that occurs in                                     |
|http://purl.obolibrary.org/obo/IAO_0000142|mentions                                                    |
|http://purl.obolibrary.org/obo/IAO_0000143|mentioned by                                                |
|http://purl.obolibrary.org/obo/OBI_0000299|has_specified_output                                        |
|http://purl.obolibrary.org/obo/IAO_0000235|denoted by                                                  |
|http://purl.obolibrary.org/obo/IAO_0000219|denotes                                                     |
|http://purl.obolibrary.org/obo/IAO_0000136|is about                                                    |
|http://purl.obolibrary.org/obo/OBI_0000312|is_specified_output_of                                      |

# Legal Interoperability Ontology for IDS - LegIOn-IDS

<img src="./owl_docs/assets/logo.png" width='500px'></img>

<!-- ![Static Badge](https://img.shields.io/badge/version-1.1-green?style=flat) -->

This repository contais the complete documentation of the proposed ontology. As an ongoing work, this ontology is one of the efforts towards the representation of a framework to foster the legal interoperability within IDS. We also provide an archive repository with all available work (systematic literature review, position papers, etc.).



[![Static Badge](https://img.shields.io/badge/TOWARDS_LEGAL_INTEROPERABILITY_IN_IDS-Archive-blue?style=for-the-badge&logo=github&color=%23e16775)
](https://github.com/VictorBenoiston/towards_legal_interoperability_IDS_archive)

[![Static Badge](https://img.shields.io/badge/Dictionary_of_terms_glossary-v1.0-green?style=for-the-badge&logo=bookstack)](./ISO_dictionary_legion_v1.1.pdf)


<!-- ![Static Badge](https://img.shields.io/badge/Read_the_docs-v1.0-green?style=for-the-badge&logo=readthedocs)
 (TBD) -->

<!-- ![Static Badge](https://img.shields.io/badge/OWL_DOCS-blue?style=for-the-badge&logo=htmx&logoColor=%23ff001d&color=%23003366) -->

[![Static Badge](https://img.shields.io/badge/OWL_docs-v1.0-green?style=for-the-badge&logo=htmx)](https://legionids.netlify.app/)


## Available Files:
```
.
├── README.md
├── legion_ref_ontology (Reference Ontology)                 # Latest version: v1.0.
├── legion_operational_ontology (Operational Ontology)       # Latest version: v1.1.
├── ISO_dictionary (Glossary of terms, providing ISO reuse)  # Latest version: v1.0.
├── owl_docs (Generated OWL documentation)                   # Latest version: v1.0.
```


## In This Repository:
[![Static Badge](https://img.shields.io/badge/Ontology_Requirements_Specification_Document-ORSD-orange)](#ontology-requirements-specification-document)

[![Static Badge](https://img.shields.io/badge/Ontological_Engineering-Lifecycle-green)](#ontology-engineering)

[![Static Badge](https://img.shields.io/badge/Reference_Ontology-Overview-red?style=flat&color=%232a418a)](#reference-ontology-overview)

[![Static Badge](https://img.shields.io/badge/Provide_the_Results_Retrieved_by_Queries-SPARQL-purple)](#sparql-queries-outcome)




## Ontology Requirements Specification Document


(SUÁREZ-FIGUEROA; GÓMEZ-PÉREZ; VILLAZÓN-TERRAZAS, 2009)
propose a systematic approach to document and set goals, granularity, and vocabulary
for the proposed ontology.

<img width="800" align="center" src="./assets/orsd_1.png">
<p align=center>Source: Original Authorship (2024)</p>

<img width="800" align="center" src="./assets/orsd_2.png">
<p align=center>Source: Original Authorship (2024)</p>

<img width="800" align="center" src="./assets/orsd_3.png">
<p align=center>Source: Original Authorship (2024)</p>

<img width="800" align="center" src="./assets/orsd_4.png">
<p align=center>Source: Original Authorship (2024)</p>

## Ontology Engineering
As methodology for ontology development, we are grounded by the Systematic Approach for Building Ontologies (SABiO). The selected framework for ontology development SABiO describes the Ontology
development process in five development phases, and five support processes, that
are made to refine the phases without a sequential overflow (FALBO, 2014)


<img width="800" align="center" src="./assets/sabio_methodology.png">
<p align=center>Source: (FALBO,2014)</p>


The Complete lifecycle development of LegIOn-IDS is summarized below:


<img width="800" align="center" src="./assets/legionDevelopmentLifecycle.png">
<p align=center>Source: Original Authorship (2024)</p>

## Reference Ontology Overview

<img width="800" align="center" src="./assets/mainViewRef.png">
<p align=center>Source: Original Authorship (2024)</p>

<img width="800" align="center" src="./assets/serviceContractViewRef.png">
<p align=center>Source: Original Authorship (2024)</p>

<img width="800" align="center" src="./assets/policyViewRef.png">
<p align=center>Source: Original Authorship (2024)</p>

<img width="800" align="center" src="./assets/legalMomentsViewRef.png">
<p align=center>Source: Original Authorship (2024)</p>

<img width="800" align="center" src="./assets/legalInteroperabilityViewRef.png">
<p align=center>Source: Original Authorship (2024)</p>


## SPARQL Queries Outcome
CQ1 (Informal): What are the legal entitlements of the service provider X? (GRIFFO et al., 2021)
</p>CQ1(Formal): 
</p>
<img align="center" width="800" src="./assets/sparql1.png">
<p align=center>Source: Original Authorship (2024)</p>

Observation: As a placeholder in the question, X is represented by 1 in this example. Hence, retrieving the legal entitlements of the service provider 1, for exemplification.

CQ2 (Informal): What are the legal burdens/lacks of the service provider X? (GRIFFO et al., 2021b)
</p>CQ2(Formal):
</p>
<img align="center" width="800" src="./assets/sparql2.png">
<p align=center>Source: Original Authorship (2024)</p>

Observation: As a placeholder in the question, X is represented by 1 in this example.
Hence, retrieving the legal burdens/lacks of the service provider 1, for exemplification

CQ3 (Informal): What are the legal entitlements of the service consumer X? (GRIFFO et al., 2021)
</p>CQ3(Formal):
</p>
<img align="center" width="800" src="./assets/sparql3.png">
<p align=center>Source: Original Authorship (2024)</p>

Observation: As a placeholder in the question, X is represented by 1 in this example.
Hence, retrieving the legal entitlements of the service consumer 1, for exemplification.

CQ4 (Informal): What are the legal burdens/lacks of the service consumer X?(GRIFFO et al., 2021)
</p>CQ4(Formal):
</p>
<img align="center" width="800" src="./assets/sparql4.png">
<p align=center>Source: Original Authorship (2024)</p>

Observation: As a placeholder in the question, X is represented by 1 in this example. Hence, retrieving the legal burdens/lacks of the service consumer 1, for
exemplification.

CQ5 (Informal): What are the Interoperability barriers in the service contract X?(EIF)
</p>CQ5(Formal): 
</p>
<img align="center" width="800" src="./assets/sparql5.png">
<p align=center>Source: Original Authorship (2024)</p>

Observation: As a placeholder in the question, X is represented by 1 in this example. Hence, retrieving the interoperability barriers of the service contract 1, for
exemplification.

CQ6 (Informal): What contracts represent joint controllership? (EIF)
</p>CQ6(Formal):
</p>
<img align="center" width="500" src="./assets/sparql6.png">
<p align=center>Source: Original Authorship (2024)</p>

Observation: The outcome is composed of the contracts characterized by the purpose of joint controllership.

CQ7 (Informal): What are the data user’s permissions and duties? (BADER et al., 2020)
</p>CQ7(Formal)(permissions):
</p>
<img align="center" width="800" src="./assets/sparql7.png">
<p align=center>Source: Original Authorship (2024)</p>
and
CQ7(Formal)(duties):
</p>
<img align="center" width="800" src="./assets/sparql8.png">
<p align=center>Source: Original Authorship (2024)</p>

Observation: Similarly, we propose the requiring of a specific data user, in this example, we retrieved the duties and permission of the service consumer (which is the data user) 2.

CQ8 (Informal): What contracts characterize data rent? (RAM)
</p>CQ8(Formal):
</p>
<img align="center" width="500" src="./assets/sparql9.png">
<p>Source: Original Authorship (2024)</p>

Observation: The outcome is composed of the contracts of type Data Rent, which is defined as data as a service.

CQ9 (Informal): WWhat contracts characterize data purchase (RAM)?
</p>CQ9(Formal):
</p>
<img align="center" width="500" src="./assets/sparql10.png">
<p>Source: Original Authorship (2024)</p>

Observation: The outcome is composed of the contracts of type Data Purchase.



### References
BADER, S.; PULLMANN, J.; MADER, C.; TRAMP, S.; QUIX, C.; MüLLER, A.;
AKYüREK, H.; BöCKMANN, M.; IMBUSCH, B.; THEISSEN-LIPP, J.; GEISLER,
S.; LANGE, C. The International Data Spaces Information Model – An Ontology
for Sovereign Exchange of Digital Content. In: . [S.l.: s.n.], 2020. p. 176–192. ISBN
978-3-030-62465-1.

FALBO, R. de A. Sabio: Systematic approach for building ontologies. Onto.
Com/odise@ Fois, v. 1301, 2014.

GRIFFO, C.; ALMEIDA, J. P. A.; GUIZZARDI, G.; NARDI, J. C. Service
contract modeling in Enterprise Architecture: An ontology-based approach.
Information Systems, v. 101, p. 101454, nov. 2021. ISSN 0306-4379. Available in:
<https://www.sciencedirect.com/science/article/pii/S030643791930506X>

SUáREZ-FIGUEROA, M.; GOMEZ-PEREZ, A.; TERRAZAS, B. V. How to Write
and Use the Ontology Requirements Specification Document. [S.l.: s.n.], 2009. v. 5871.
982 p. ISBN 978-3-642-05150-0.


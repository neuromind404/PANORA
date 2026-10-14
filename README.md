# PANORA: A Four-Domain Upper Ontology

PANORA is a proposed upper ontology that organizes entities into four foundational domains: **Physical**, **Abstract**, **Subjective**, and **Transcendent**. The project explores how these domains can be distinguished within a shared conceptual framework and represented in OWL.

This repository provides a preliminary ontology model and a web-based interface for examining its conceptual organization. The associated research is described in the [published PANORA article](#publication-and-citation).

## Conceptual approach

PANORA was developed following a comparative study of established upper ontologies, including DOLCE, SUMO, Cyc, and PROTON. Its philosophical orientation draws on selected ideas from Islamic philosophy, particularly Mulla Sadra's account of existence. This influence provides a conceptual perspective rather than a claim that the philosophical system has been fully formalized in OWL.

The architecture distinguishes four domains:

- **Physical:** entities that exist independently of individual experience and mental structures, but are situated in space and time and participate in causal relations.
- **Abstract:** conceptual entities that depend on shared mental structures but are independent of individual experience, causal relations, space, and time.
- **Subjective:** phenomena that depend on first-person experience, occur within spatial and temporal contexts, and participate in causal relations, independently of shared mental structures.
- **Transcendent:** metaphysical or theological entities that are independent of individual experience, mental structures, space, and time, but can participate in causal relations.

Domain distinctions are guided by five criteria: **first-person dependence**, **mental structure**, **causality**, **place**, and **time**.

## Repository files

| File | Description |
| --- | --- |
| [`PANORA.owl`](./PANORA.owl) | Preliminary machine-readable representation of the ontology. |
| [`index.html`](./index.html) | HTML interface for exploring the ontology's conceptual structure. |
| `README.md` | Project overview, access instructions, research status, and citation information. |
| [`CITATION.cff`](./CITATION.cff) | Machine-readable citation information for the PANORA project and its associated publication. |

## Using the project

PANORA is publicly accessible through the following resources:

- **Online Ontology Explorer:** [Explore PANORA](https://neuromind404.github.io/PANORA/)
- **OWL Ontology File:** [Download or inspect PANORA.owl](./PANORA.owl)

The web-based ontology explorer provides an interactive interface for examining the conceptual structure of PANORA, including its class hierarchy and available definitions.

To inspect the machine-readable ontology, download [`PANORA.owl`](./PANORA.owl) and open it using an OWL-compatible ontology editor, such as [Protégé](https://protege.stanford.edu/).

## Research evaluation and limitations

The original PANORA study reported a preliminary conceptual evaluation based on semi-structured interviews with seven specialists in ontology engineering, cognitive science, and philosophy. The expert assessment supported the four-domain distinction while also highlighting the need for clearer logical constraints and more precise boundaries between the Subjective and Abstract domains.

This repository contains a **preliminary research artifact**, not a formally validated ontology release. The published study did not report automated reasoner-based consistency testing or computational performance benchmarking. The expert assessment should not be interpreted as such technical validation.

## Publication and citation

PANORA is described in the following peer-reviewed publication:

> Khosravi, A., Safdari, R., Rabiei, F., Tajerloo, Z., & Najafi, Z. (2026). PANORA: A Four-Domain Upper Ontology for Rule-Based AI and Semantic Knowledge Representation. *Journal of Distributed Computing and Systems, 9*(1), 96–120.

For scholarly use, please cite the original PANORA publication when referring to the ontology's conceptual framework, methodology, or expert evaluation.

Citation information is also provided in the [`CITATION.cff`](./CITATION.cff) file. GitHub users can select **Cite this repository** to obtain citation details in supported formats, including APA and BibTeX.

## License and feedback

No reuse license is specified in this repository at present. Public availability on GitHub does not by itself grant permission to redistribute or modify the files. Please contact the project maintainers about reuse permissions.

Corrections, suggestions, and technical feedback can be submitted through the repository's **Issues** feature, if enabled.

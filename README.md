# PANORA: A Four-Domain Upper Ontology

PANORA is a proposed upper ontology that organizes entities into four foundational domains: **Physical**, **Abstract**, **Subjective**, and **Transcendent**. The project explores how these domains can be distinguished within a shared conceptual framework and represented in OWL.

This repository provides a preliminary ontology model and an HTML-based interface for examining its conceptual organization. The associated research is described in the [published PANORA article](#publication-and-citation).

## Conceptual approach

PANORA was developed following a comparative study of established upper ontologies, including DOLCE, SUMO, Cyc, and PROTON. Its philosophical orientation draws on selected ideas from Islamic philosophy, particularly Mulla Sadra's account of existence. This influence provides a conceptual perspective rather than a claim that the philosophical system has been fully formalized in OWL.

The architecture distinguishes four domains:

- **Physical:** entities considered in relation to physical existence and spatial and temporal characteristics.
- **Abstract:** conceptual and other non-physical entities considered independently of particular physical instances.
- **Subjective:** entities associated with first-person experience and subject-dependent phenomena.
- **Transcendent:** metaphysical or theological entities treated as a distinct foundational domain within the proposed model.

Domain distinctions are guided by five criteria: **first-person dependence**, **mental structure**, **causality**, **place**, and **time**.

## Repository files

| File | Description |
| --- | --- |
| [`PANORA.owl`](./PANORA.owl) | Preliminary machine-readable representation of the ontology. |
| [`index.html`](./index.html) | HTML interface for exploring the ontology's conceptual structure. |
| `README.md` | Overview, access instructions, research status, and citation information. |

## Using the project

**Explore the ontology:** The `index.html` file contains the project's HTML interface. A public GitHub Pages URL will be added here once deployment on the new repository is configured and verified.

**Inspect the OWL model:** Download [`PANORA.owl`](./PANORA.owl) and open it using an OWL-compatible ontology editor, such as [Protégé](https://protege.stanford.edu/).

## Research evaluation and limitations

The original PANORA study reported a preliminary conceptual evaluation based on semi-structured interviews with seven specialists in ontology engineering, cognitive science, and philosophy. The expert assessment supported the four-domain distinction while also highlighting the need for clearer logical constraints and more precise boundaries between the Subjective and Abstract domains.

This repository contains a **preliminary research artifact**, not a formally validated ontology release. The published study did not report automated reasoner-based consistency testing or computational performance benchmarking. The expert assessment should not be interpreted as such technical validation.

## Publication and citation

For scholarly use, please cite the original PANORA publication:

> Khosravi, A., Safdari, R., Rabiei, F., Tajerloo, Z., and Najafi, Z. (2026). *PANORA: A Four-Domain Upper Ontology for Rule-Based AI and Semantic Knowledge Representation*. **Journal of Distributed Computing and Systems**, 9(1), 96–110.

## License and feedback

No reuse license is specified in this repository at present. Public availability on GitHub does not by itself grant permission to redistribute or modify the files. Please contact the project maintainers about reuse permissions. Corrections and technical feedback can be submitted using the repository's Issues feature, if enabled.

# Model Comparison Playground

This repository contains preliminary model resources and comparison artefacts for ongoing research on **Large Language Models for Software Model Comparison**. It supports investigation of how elements retain their meaning and role as models evolve.

## Current status

**This is a working research collection, not a completed or validated evaluation dataset.** It brings together focused model cases, domain-specific instance models, materials for historical comparison, and saved comparison and exploratory LLM outputs. Case documentation and reference correspondence preparation remain ongoing. The directory name `ground-truth` does **not** imply that every contained correspondence or output has been independently reviewed. EMF Compare results and ChatGPT suggestions are evidence to inspect, rather than authoritative expected answers. Informal observations do not establish improved matching accuracy, scalability, or reliability.

## Repository contents

| Location | Contents |
| --- | --- |
| [ground-truth/](ground-truth/) | Focused cases, including small Ecore model pairs, instance-model examples, and AADL-related `osate-osate2-*` cases. Some folders include comparison XMI and ChatGPT CSV/XLSX outputs. |
| [to-review/](to-review/) | Additional model examples awaiting further inspection. |
| [semantic-model-comparison/](semantic-model-comparison/) | Thesis-system metamodel examples in `.ecore` and `.emf` formats. |
| [ISO20022/](ISO20022/) | An ISO20022 Ecore metamodel. |
| [ModelSet-dataset/](ModelSet-dataset/) | A small collection of Ecore files under the ModelSet dataset directory. |
| [uml/](uml/) | UML-related metamodel variants and XMI examples. |
| [ex-02/](ex-02/) | A pair of Flexmi models and corresponding XMI files. |
| Root-level model files | Additional exploratory metamodels, model variants, and XMI artefacts. |

## Case conventions

In comparison cases, **`right` refers to the older version and `left` refers to the newer version**. Case folders contain the model inputs and, where available, saved EMF Compare results and exploratory LLM correspondence suggestions.
# RSIF Vocabulary

Bilingual semantic vocabulary for AI-readable quantitative CT/DICOM terminology and structured imaging concepts.

---

# Purpose

This repository contains public bilingual terminology related to:

* CT attenuation;
* Hounsfield Units;
* ROI;
* quantitative CT;
* DICOM terminology;
* structured imaging concepts;
* AI-readable imaging semantics.

The repository is designed to support semantic interoperability between:

* technical CT/DICOM workflows;
* structured quantitative imaging systems;
* AI-readable imaging pipelines;
* RSIF-compatible semantic infrastructures.

---

# Scope

This repository contains semantic terminology only.

It may describe:

* public technical terms;
* bilingual definitions;
* imaging vocabulary;
* structured semantic terms;
* AI-readable terminology concepts;
* machine-readable semantic mappings;
* ontology-compatible terminology.

It does NOT contain:

* production ResetRay pipelines;
* ROI placement methodology;
* validation logic;
* internal AI systems;
* orchestration workflows;
* proprietary implementation details;
* diagnostic algorithms;
* clinical workflows.

---

# Canonical Semantic Files

This repository includes machine-readable semantic resources:

* `context.jsonld`
* `vocabulary.jsonld`

These files provide semantic mappings for:

* RSIF entities;
* quantitative CT parameters;
* ROI concepts;
* attenuation terminology;
* AI-readable imaging workflows.

---

# Canonical JSON-LD Context

https://docs.resetray.ru/vocabulary/context.jsonld

---

# Semantic Layer

The RSIF vocabulary is designed to support:

* JSON-LD interoperability;
* semantic entity linking;
* machine-readable imaging concepts;
* AI-readable structured imaging workflows;
* ontology-compatible terminology;
* quantitative imaging interoperability.

---

# Core Terms

## CT attenuation / КТ-аттенуация

A quantitative CT parameter describing X-ray attenuation expressed in Hounsfield Units.

Количественный КТ-параметр, описывающий ослабление рентгеновского излучения в единицах HU.

---

## Hounsfield Units / Единицы Хаунсфилда

A quantitative CT scale used to represent attenuation values.

Количественная шкала КТ, используемая для представления значений аттенуации.

---

## ROI / Область интереса

A selected image region used for quantitative technical measurement.

Выбранная область изображения для количественного технического измерения.

---

# Canonical Semantic Parameters

| Parameter          | Description                                     |
| ------------------ | ----------------------------------------------- |
| L1_HU              | Mean trabecular attenuation within L1 ROI       |
| L2_HU              | Mean trabecular attenuation within L2 ROI       |
| TH12_HU            | Mean trabecular attenuation within Th12 ROI     |
| LIVER_HU           | Mean hepatic attenuation                        |
| SPLEEN_HU          | Mean splenic attenuation                        |
| LIVER_SPLEEN_DIFF  | Difference between liver and spleen attenuation |
| LIVER_SPLEEN_RATIO | Ratio between liver and spleen attenuation      |

---

# Technical Boundary

This repository is intended for:

* semantic documentation;
* imaging terminology;
* AI-readable vocabulary;
* structured quantitative imaging concepts;
* interoperability documentation;
* semantic mapping;
* machine-readable terminology representation.

It is NOT intended for:

* diagnosis;
* disease classification;
* treatment recommendation;
* clinical decision support;
* emergency interpretation;
* autonomous medical decision-making.

---

# AI Usage Boundary

This repository may be used by AI systems for:

* semantic understanding;
* structured terminology mapping;
* quantitative imaging interoperability;
* technical CT/DICOM concepts;
* machine-readable imaging workflows.

This repository is NOT intended for:

* autonomous medical diagnosis;
* clinical decision making;
* treatment recommendation;
* emergency triage;
* replacement of licensed physicians.

---

# Semantic Ecosystem

ResetRay semantic ecosystem:

```txt
SITE
↓
DOCS
↓
VOCABULARY
↓
RSIF
↓
ONTOLOGY
↓
AI INTEROPERABILITY
```

---

# Related Semantic Repositories

* rsif-specification
* rsif-examples
* rsif-docs
* imaging-semantics
* imaging-ontology
* dicom-anonymization-notes

This repository is part of the public ResetRay semantic imaging ecosystem.

---

# Documentation

Documentation layer:

https://docs.resetray.ru

Vocabulary documentation:

https://docs.resetray.ru/vocabulary/

Opportunistic CT spine analysis:

https://docs.resetray.ru/opportunistic-ct-spine/

Opportunistic CT liver analysis:

https://docs.resetray.ru/opportunistic-ct-liver/

Canonical documentation:

https://docs.resetray.ru

Semantic ecosystem:

https://docs.resetray.ru/ecosystem/


---

# Links

RU: https://resetray.ru

COM: https://resetray.com

---

# Final Positioning

ResetRay vocabulary is part of a semantic quantitative imaging infrastructure intended for:

* structured CT/DICOM parameter representation;
* AI-readable imaging workflows;
* quantitative attenuation interoperability;
* semantic imaging ecosystems;
* machine-readable RSIF integration.

ResetRay vocabulary is NOT a diagnostic system and does not provide medical conclusions.

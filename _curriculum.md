# Curriculum: Introduction to the Ethics and Regulation of AI (E&RofAI)

- **Programme:** M.Sc. Artificial Intelligence (MAI), THWS FIW
- **Module no.:** 5173080
- **Semester:** Winter term 2026/27
- **Instructor:** Prof. Dr. iur. Markus Oermann, M.A. (THWS FIW)
- **Format:** 13 sessions / lectures, single-source Quarto publishing (Moodle HTML + PDF)
- **Language:** English (course-wide)
- **Source:** Redevelopment of the 13 existing PowerPoint decks (WS 2025/26), with content ported and translated from the German Quarto repos GRC&E and MedR where topics overlap.

## Terminology conventions (course-wide)

- **GDPR** (not "DSGVO") · **EU AI Act** (official short title; "AI Act" acceptable, avoid "KI-VO") · **controller** (Art. 4(7) GDPR) · **processor** (Art. 4(8)) · **provider** / **deployer** (EU AI Act, official terms; not "user")
- **personal data** · **automated decision-making (ADM)** · **general-purpose AI (GPAI)** · **high-risk AI system**
- Cite norms inline with a linked source (eur-lex for EU law); use official English article wording of the EU AI Act and GDPR.
- Case law: use the ECLI and the English case name where available. Never invent an ECLI.

## Source convention (course-wide, binding)

Every unit ends with a full reference list. Whenever a source is used as a short citation in the text (e.g. "Dignum 2019", "Floridi & Sanders 2004"), the **full bibliographic entry** must appear at the end (author, year, title, publisher/journal, DOI/link where available). Structure: *Literature* · *Norms & Standards* · *Case law*. No references to any personal knowledge base or vault appear in the teaching material; only regular scholarly/legal citations are used.

## Units

| No | File | Title | Core topics | Primary source | Status |
|----|------|-------|-------------|----------------|--------|
| 1 | `01_introduction.qmd` | Introduction: What is AI, What is AI Ethics? | AI definitions (OECD, AI Act Art. 3), history (Dartmouth 1956, AI winters), sociotechnical systems (Mühlhoff), anthropomorphism, why ethics & regulation | Deck S1 (new) | ⬜ offen |
| 2 | `02_ethics_101.qmd` | Ethics 101: Foundations of Moral Philosophy | Values/norms, virtue ethics (Aristotle), utilitarianism (Bentham/Mill), deontology (Kant), discourse ethics (Habermas/Apel), Kohlberg, two-systems (Kahneman), naturalistic fallacy | GRC&E 01 + Deck S2 | ⬜ offen |
| 3 | `03_agency_human_ai_relation.qmd` | Agency & the Human-AI Relation | Moral status/agent/patient, machine ethics, Heider & Simmel, Actor-Network Theory (Latour), human computation, nudges & choice architecture | Deck S3 + GRC&E 01 | ⬜ offen |
| 4 | `04_responsibility.qmd` | Responsibility & the Responsibility Gap | Control + epistemic conditions (Aristotle), responsibility gap (Matthias), many hands, transparency/explainability/accountability (XAI), Collingridge dilemma, RRI, Dignum ART | Deck S4 + GRC&E 01 | ⬜ offen |
| 5 | `05_bias_discrimination.qmd` | Bias & Discrimination | Friedman/Nissenbaum typology, Algorithms of Oppression (Noble), proxy bias (Apple Card, Gender Shades), intersectionality (Crenshaw), error-rate bias & feedback loops (COMPAS) | Deck S5 (new) | ⬜ offen |
| 6 | `06_data_protection_foundations.qmd` | Data Protection I: Foundations & GDPR | Informational self-determination (Census 1983), GDPR principles (Art. 5), lawful bases (Art. 6), personal data/processing/controller (Art. 4), special categories (Art. 9) | GRC&E 02 + 03 | ⬜ offen |
| 7 | `07_data_protection_ai.qmd` | Data Protection II: Profiling, ADM & AI Models | Profiling & ADM (Art. 22, SCHUFA C-634/21), data protection for AI models & training data, Privacy by Design (Art. 25), predictive privacy (Mühlhoff), Schrems II | GRC&E 03 + 04 (partial); adapt: replace video-surveillance with AI-model data protection | ⬜ offen |
| 8 | `08_discourse_disinformation.qmd` | Discourse, Public Sphere & Disinformation | Public sphere (Habermas), discourse ethics, filter bubbles/echo chambers, mis/dis/malinformation, deep fakes, synthetic reality, AI Act Art. 50 watermarking | Deck S8 (new) | ⬜ offen |
| 9 | `09_transformation_sustainability.qmd` | Transformation & Sustainability | Modernization theory & critiques, work transformation (ILO), UN SDGs, AI water/CO2 footprint, Jevons rebound, ghost work | Deck S9 (new) | ⬜ offen |
| 10 | `10_ai_ethics_guidelines.qmd` | AI Ethics Guidelines | EU/OECD/UNESCO/G7/CoE profiles, EU Trustworthy AI (4 principles), HITL/HOTL/HIC, ethics washing (Hagendorff), legal quality of soft law | Deck S10 + GRC&E 01 | ⬜ offen |
| 11 | `11_internal_codes_self_regulation.qmd` | Internal Codes & Self-Regulation | State vs self- vs regulated self-regulation (Ogus), OpenAI Preparedness Framework, IEEE 7000 series, NIST AI RMF, ISO/IEC 42001 | Deck S11 (new) | ⬜ offen |
| 12 | `12_eu_ai_act.qmd` | The EU AI Act | EU law basics, risk-based approach, prohibited practices (Art. 5), high-risk (Art. 6/Annex III), provider vs deployer, GPAI, transparency (Art. 50), governance & sanctions | GRC&E 06 (primary) | 🔨 Pilot | 
| 13 | `13_ai_ip_liability.qmd` | AI, Intellectual Property & Liability | Copyright requirements & AI authorship, prompt creativity, personality rights, TDM exception (DSM Dir. / §44b UrhG), US fair use, civil liability, Product Liability Directive, AILD withdrawal | MedR 10–13 + GRC&E 06 | ⬜ offen |

## Interactive elements

Native Quarto/Moodle elements provided by the `c-kraus` extension (`interactions.js`): `.flip-card` · `.quick-check` · `.drag-exercise` · `.details` · `.case-study`. Standalone HTML widgets live in `widgets/kapitel-{nn}/`. English graphics are extracted from the corresponding PowerPoint decks and stored in `media/`.

## Reuse map (repos → sessions)

- **GRC&E 01** (ethics) → Units 2, 3, 4, 10
- **GRC&E 02 + 03** (GDPR foundations, legal bases, data-subject rights) → Units 6, 7
- **GRC&E 04** (technical/organisational, partial) → Unit 7 *(video-surveillance example replaced by AI-model data protection)*
- **GRC&E 05** (InfoSec law: KRITIS/NIS2/StGB) → not used (out of scope for AI ethics course)
- **GRC&E 06** (EU AI Act) → Unit 12 *(near-direct port, English official terminology)*
- **MedR 10** (AI legal framework, liability) → Units 12 (cross-check), 13
- **MedR 11–13** (copyright basics, content, limitations/TDM) → Unit 13
- **Fresh authoring** (from PowerPoint decks only): Units 1, 5, 8, 9, 11

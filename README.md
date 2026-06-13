# Trustworthy AI by Design

A systematic framework and baseline checklist for analyzing AI trustworthiness across **Security**, **Safety**, **Reliability**, **Privacy Protection**, **Fairness**, **Transparency**, **Human-Centricity**, and **Accountability**.

---

## About

Modern AI systems are socio-technical systems whose risks cannot be captured by a single security taxonomy or threat model. This repository provides research artifacts for a multi-attribute AI trustworthiness framework that extends conventional security-oriented analysis toward a broader set of trustworthiness requirements.

The framework decomposes AI trustworthiness into eight attributes, derives attribute-specific requirements, and consolidates them into a baseline checklist that can be used during AI system design, review, and assurance activities.

The goal is to support **trustworthy AI by design**: identifying trustworthiness requirements early, mapping them to system-level evidence, and enabling repeatable assessment through checklist-based, document-based, and prompt-based validation.

---

## What This Repository Provides

- Attribute-specific requirement derivation documents for eight AI trustworthiness dimensions.
- A consolidated baseline checklist containing **103 derived requirements**.
- An **AI Safety Software Requirement Specification (AI Safety SRS)** artifact.
- Validation materials for document-based evaluation, prompt-based evaluation, and EU AI Act checklist mapping.
- IEEE S&P 2026 poster and short paper artifacts for the related research work.

---

## Repository Contents

| Path | Description |
|---|---|
| [`1. Security_derived.pdf`](./1.%20Security_derived.pdf) | Derived requirements for the **Security** attribute. |
| [`2. Safety_derived.pdf`](./2.%20Safety_derived.pdf) | Derived requirements for the **Safety** attribute. |
| [`3. Reliability_derived.pdf`](./3.%20Reliability_derived.pdf) | Derived requirements for the **Reliability** attribute. |
| [`4. Transparerency_derived.pdf`](./4.%20Transparerency_derived.pdf) | Derived requirements for the **Transparency** attribute. |
| [`5. Acountability_derived.pdf`](./5.%20Acountability_derived.pdf) | Derived requirements for the **Accountability** attribute. |
| [`6. Fairness_derived.pdf`](./6.%20Fairness_derived.pdf) | Derived requirements for the **Fairness** attribute. |
| [`7. Human Centricity_derived.pdf`](./7.%20Human%20Centricity_derived.pdf) | Derived requirements for the **Human-Centricity** attribute. |
| [`8. privacy protection_derived.pdf`](./8.%20privacy%20protection_derived.pdf) | Derived requirements for the **Privacy Protection** attribute. |
| [`9. CheckList(Derived 103 requirements).pdf`](./9.%20CheckList%28Derived%20103%20requirements%29.pdf) | Consolidated checklist of 103 derived trustworthiness requirements. |
| [`AI Safety Software Requirement Specification(AI Safety SRS).pdf`](./AI%20Safety%20Software%20Requirement%20Specification%28AI%20Safety%20SRS%29.pdf) | AI safety-oriented software requirement specification artifact. |
| [`IEEE S&P Poster/`](./IEEE%20S%26P%20Poster/) | Short paper and poster materials for the IEEE S&P 2026 poster presentation. |
| [`Validation/`](./Validation/) | Validation artifacts, including document-based evaluation, prompt-based evaluation, and EU AI Act checklist mapping. |

---

## Prerequisites

| Requirement | Note |
|---|---|
| PDF viewer | All primary artifacts are provided as PDF documents. |
| AI system design artifacts | To apply the checklist, prepare system architecture descriptions, data-flow descriptions, model documentation, policies, risk analysis records, or other available assurance evidence. |

No build environment, package manager, or runtime dependency is required.

---

## How to Use

1. **Define the AI system scope**  
   Identify the target AI system, stakeholders, lifecycle phase, assets, assumptions, and intended use context.

2. **Review the eight trustworthiness attributes**  
   Use the attribute-specific derivation documents to understand how each trustworthiness dimension is decomposed into concrete requirements.

3. **Apply the baseline checklist**  
   Use [`9. CheckList(Derived 103 requirements).pdf`](./9.%20CheckList%28Derived%20103%20requirements%29.pdf) to assess whether the system has sufficient controls, evidence, and design decisions for each requirement.

4. **Map requirements to evidence**  
   For each checklist item, record the corresponding design artifact, policy, test result, monitoring mechanism, or mitigation evidence.

5. **Use the AI Safety SRS when safety requirements are needed**  
   Refer to [`AI Safety Software Requirement Specification(AI Safety SRS).pdf`](./AI%20Safety%20Software%20Requirement%20Specification%28AI%20Safety%20SRS%29.pdf) as a structured example of safety-focused requirements for AI software.

6. **Review validation artifacts**  
   Use the materials in [`Validation/`](./Validation/) to compare the checklist against document-based evaluation, prompt-based evaluation, and EU AI Act-oriented mapping.

---

## Suggested Assessment Flow

| Phase | Activity | Expected Output |
|---|---|---|
| 1. Scoping | Define system boundary, use case, stakeholders, and assumptions. | Assessment scope and system context. |
| 2. Attribute Review | Review the eight derived requirement documents. | Attribute-specific requirement understanding. |
| 3. Checklist Assessment | Apply the 103-requirement checklist to the target system. | Requirement coverage and gap list. |
| 4. Evidence Mapping | Link each requirement to design, policy, test, or operational evidence. | Evidence matrix or assurance argument. |
| 5. Validation | Compare findings using document-based, prompt-based, survey, or regulatory mapping artifacts. | Validation notes and residual issues. |

---

## Intended Use Cases

- AI system design review and trustworthiness requirement elicitation.
- Security and safety engineering for AI-enabled systems.
- AI governance, assurance, and audit preparation.
- Checklist-driven gap analysis across multiple trustworthiness attributes.
- Research on unified AI trustworthiness frameworks beyond security-only threat modeling.

---

## Limitations

This repository is a research artifact. It does not by itself provide legal certification, regulatory approval, or complete compliance assurance. The checklist and mappings should be used as supporting materials together with domain-specific safety engineering, cybersecurity engineering, privacy engineering, and legal review where applicable.

---

## Publication and Presentation

This repository accompanies the following IEEE S&P 2026 poster:

> **Beyond STRIDE: A Unified Multi-Attribute Framework for Trustworthy AI**  
> Jun Hyeong Lee, Kwangsoo Cho, Jieun Lee, Jae Hyuk Suk, Yoon-chan Jhi, Jihoon Cho, and Seungjoo Kim  
> IEEE Symposium on Security and Privacy 2026, Poster Session  
> [[Poster Listing]](https://www.ieee-security.org/TC/SP2026/posters.html)

Short paper and poster materials are available in [`IEEE S&P Poster/`](./IEEE%20S%26P%20Poster/).

---

## Citation

Formal citation metadata will be updated when the final publication information becomes available.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Contact

- **Seungjoo Kim (Corresponding Author)** — Professor, School of Cybersecurity, Korea University, Korea — skim71@korea.ac.kr
- **Jun Hyeong Lee (Co-First Author)** — Ph.D. course, School of Cybersecurity, Korea University, Korea — enter930302@naver.com
- **Kwangsoo Cho (Co-First Author)** — Ph.D. course, School of Cybersecurity, Korea University, Korea — cks4386@korea.ac.kr
- **Short Survey Link** — https://m.site.naver.com/24XPB

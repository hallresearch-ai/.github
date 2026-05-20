# HallResearch.ai Library

The **HallResearch.ai Library** is a curated public collection of resources for understanding, governing, assessing, and implementing artificial intelligence systems in the world.

The Library grew out of the original [*Awesome Machine Learning Interpretability*](https://github.com/jphall663/awesome-machine-learning-interpretability) repository and now serves as a broader research library. Its two main branches are maintained as separate GitHub repositories so that each collection remains easier to navigate, update, and cite.

Maintenance and curation are sponsored by [HallResearch.ai](https://www.hallresearch.ai).

---

## Contents

| Section | Description |
|---|---|
| [Main Branches](#main-branches) | Governance/policy resources and assessment/implementation resources |
| [Supporting Project Repositories](#supporting-project-repositories) | Public examples, prototypes, notebooks, and reference tools connected to the Library |
| [How to Use the Library](#how-to-use-the-library) | Guidance for choosing the right starting point |
| [Library Philosophy](#library-philosophy) | The purpose and scope of the collection |
| [Legacy Note](#legacy-note) | Relationship to the original AMLI repository |
| [Maintenance Note](#maintenance-note) | Notes on upkeep, corrections, and additions |
| [Suggested Citation](#suggested-citation) | Suggested citation format |

---

## Main Branches

### [AI Governance and Policy Resources](https://github.com/hallresearch-ai/ai_governance_policy_resources)

This branch collects resources on AI governance, policy, regulation, institutions, incidents, accountability, labor, civil society critique, and the social consequences of AI deployment.

Representative areas include:

- University AI policies and classroom guidance
- Official policy frameworks, standards, and government guidance
- Legal documents, regulatory materials, and policy trackers
- AI incident information-sharing resources
- Accountability, labor, and governance organizations
- Critical perspectives on AI systems and deployment
- Curated bibliographies and related resource lists

Use this branch when you are asking questions such as:

- What guidance have governments, universities, or institutions issued on AI?
- How are AI systems being regulated, audited, or governed?
- What resources track AI law, policy, incidents, harms, and accountability?
- What organizations and bibliographies are useful for AI governance research?

---

### [AI Assessment and Implementation Resources](https://github.com/hallresearch-ai/ai_assessment_implementation_resources)

This branch collects practical resources for assessing, testing, documenting, and implementing responsible machine learning systems, including frameworks, evaluation tools, educational materials, and community guidance.

Representative areas include:

- Responsible ML assessment and implementation guidance
- Community frameworks and practical governance resources
- Auditing, testing, assurance, and evaluation methods
- Challenges, competitions, and benchmarking resources
- Technical guides, tools, and educational materials
- Resources for translating AI principles into practice

Use this branch when you are asking questions such as:

- How can AI systems be evaluated, audited, tested, or documented?
- What practical frameworks exist for responsible ML implementation?
- What tools and methods support AI assessment and assurance?
- What educational or technical resources help teams understand AI systems in practice?

---

## Supporting Project Repositories

The repositories below are public HallResearch.ai projects that support the Library’s teaching, demonstration, prototyping, and reference functions. They are not separate Library branches. Instead, they should be understood as companion materials beneath the two main branches above.

### Assessment, Testing, and Implementation Examples

| Repository | Description |
|---|---|
| [basic-ml-security](https://github.com/hallresearch-ai/basic-ml-security) | Basic example of attacking an XGBoost classifier. |
| [basic-xai-example](https://github.com/hallresearch-ai/basic-xai-example) | Basic examples of XAI techniques. |
| [basic-model-testing-red-teaming-user-testing-example](https://github.com/hallresearch-ai/basic-model-testing-red-teaming-user-testing-example) | Basic example of model testing, red teaming, and user/field testing for LLM-based systems. |
| [basic-explainable-ml-bias-management-example](https://github.com/hallresearch-ai/basic-explainable-ml-bias-management-example) | Example explainable ML model with bias management. |
| [basic-ml-eval-example](https://github.com/hallresearch-ai/basic-ml-eval-example) | Example evaluation procedure for several ML model scores on a simple dataset. |

### Governance, Documentation, and Reference Prototypes

| Repository | Description |
|---|---|
| [ai-rmf-rag-prototype](https://github.com/hallresearch-ai/ai-rmf-rag-prototype) | Prototype RAG system for NIST AI RMF materials. |
| [example-system-card](https://github.com/hallresearch-ai/example-system-card) | Example AI system card for trainings and presentations. |
| [bib-lib](https://github.com/hallresearch-ai/bib-lib) | HallResearch.ai public BibTeX library. |

---

## How to Use the Library

The two main branches overlap in places because AI governance and AI implementation are not cleanly separable. A policy document may imply technical assessment requirements; an auditing framework may have legal or institutional consequences. The split is meant to help readers find a useful starting point, not to enforce a rigid boundary.

As a general rule:

- Start with **AI Governance and Policy Resources** if your question concerns institutions, law, regulation, public policy, accountability, or social impact.
- Start with **AI Assessment and Implementation Resources** if your question concerns evaluation, implementation, auditing, testing, tooling, or technical practice.
- Use the **Supporting Project Repositories** when you want examples, prototypes, notebooks, training materials, or reference files connected to the broader Library.

Readers working on responsible AI, trustworthy AI, AI safety, AI governance, AI accountability, AI incident analysis, or machine learning assessment may find themselves moving between both branches.

---

## Library Philosophy

The HallResearch.ai Library is designed as a working research collection rather than a static bibliography. It emphasizes resources that help readers understand how AI systems are built, evaluated, deployed, governed, challenged, and experienced.

The collection is intentionally broad. It includes technical materials, policy documents, legal resources, institutional guidance, critical research, community frameworks, and practical implementation resources. The purpose is not to settle debates about artificial intelligence, but to make the relevant terrain easier to navigate.

The Library is curated with attention to source quality, institutional context, usefulness, and the practical needs of researchers, students, policymakers, journalists, technologists, and civil society actors.

---

## Repository Organization

This top-level page is the main public entry point for the HallResearch.ai Library.

| Level | Role | Repositories |
|---|---|---|
| Main Library Branch | Governance, policy, law, accountability, institutions, and social impact | [ai_governance_policy_resources](https://github.com/hallresearch-ai/ai_governance_policy_resources) |
| Main Library Branch | Assessment, implementation, evaluation, tooling, auditing, and education | [ai_assessment_implementation_resources](https://github.com/hallresearch-ai/ai_assessment_implementation_resources) |
| Supporting Project Repository | Examples, prototypes, notebooks, documentation models, and reference files | [basic-ml-security](https://github.com/hallresearch-ai/basic-ml-security), [basic-xai-example](https://github.com/hallresearch-ai/basic-xai-example), [basic-model-testing-red-teaming-user-testing-example](https://github.com/hallresearch-ai/basic-model-testing-red-teaming-user-testing-example), [basic-explainable-ml-bias-management-example](https://github.com/hallresearch-ai/basic-explainable-ml-bias-management-example), [basic-ml-eval-example](https://github.com/hallresearch-ai/basic-ml-eval-example), [ai-rmf-rag-prototype](https://github.com/hallresearch-ai/ai-rmf-rag-prototype), [example-system-card](https://github.com/hallresearch-ai/example-system-card), [bib-lib](https://github.com/hallresearch-ai/bib-lib) |

Future branches and supporting repositories may be added as the Library develops.

---

## Legacy Note

The HallResearch.ai Library began as a reorganization and expansion of the original [*Awesome Machine Learning Interpretability*](https://github.com/jphall663/awesome-machine-learning-interpretability) repository. The new structure reflects a broader scope: not only interpretability, but the wider ecosystem of resources needed to study, assess, govern, and responsibly deploy AI systems.

---

## Maintenance Note

This Library is maintained as an ongoing public resource. Links may change, documents may be superseded, and new resources will be added over time.

The Library is updated through a combination of manual curation, direct editing, and assistance from ChatGPT 5.5. AI-assisted updates are reviewed and edited before publication, but readers should still treat the Library as a living resource and report broken links, outdated materials, or other errors when they find them.

Suggestions, corrections, and additions are welcome through the relevant repository’s issue tracker or pull request process.

---

## Suggested Citation

HallResearch.ai. “HallResearch.ai Library.” GitHub, HallResearch.ai, https://github.com/hallresearch-ai/.

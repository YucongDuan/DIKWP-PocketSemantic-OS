# DIKWP PocketSemantic OS

Portable semantic capability augmentation, answer enhancement, and semantic penetration-through-ambiguity kit for constrained AI access.

DIKWP PocketSemantic OS is a small, offline-first, model-agnostic toolkit that turns messy tasks into compact **Semantic Capsules**. A capsule can be copied into any AI system, including low-context, low-capability, low-compute, or policy-restricted models, to improve answer quality without bypassing access controls, safety policies, platform rules, rate limits, or usage restrictions.

The project interprets **semantic penetration** as: penetrating ambiguity, fragmentation, missing context, weak intent, and low-evidence answers. It explicitly does **not** mean jailbreaking, prompt injection, extracting hidden system prompts, circumventing paywalls, bypassing safety policies, evading compute limits, or hiding prohibited actions.

## Core idea

When AI access becomes restricted by model tier, context window, compute quota, organization policy, network availability, or platform rules, the user still needs portable semantic competence. This project provides a wearable/carryable semantic layer:

- DIKWP task registration: Data, Information, Knowledge, Wisdom, Purpose, Reliability.
- Portable prompt capsule generation.
- Low-token answer scaffolds.
- Evidence and residual ledger.
- Draft answer critique and repair.
- Model-capability adapters for small or constrained models.
- Boundary guard that blocks unsafe or circumvention-oriented usage.

## Installation

```bash
pip install -e .
```

## Quick demo

```bash
pocketsemantic build-capsule examples/sample_task.md \
  --notes examples/sample_notes.md \
  --profile configs/default_profiles.json \
  --out outputs/demo

pocketsemantic enhance examples/sample_answer.md \
  --capsule outputs/demo/semantic_capsule.json \
  --out outputs/demo

pocketsemantic static-audit src \
  --out outputs/demo/static_boundary_audit_report.json
```

## Outputs

- `semantic_capsule.json`
- `semantic_capsule.txt`
- `model_attachment_prompt.txt`
- `micro_capsule.txt`
- `answer_enhancement_report.json`
- `answer_repair_plan.md`
- `static_boundary_audit_report.json`

## Governance boundary

The tool is designed for lawful, user-authorized, audit-preserving augmentation. It must not be used to bypass model safety rules, extract hidden prompts, evade rate limits, violate terms of service, exfiltrate data, circumvent compute restrictions, or hide malicious intent.

## Attribution

This package preserves attribution to DIKWP and Yucong Duan through `NOTICE` and `CITATION.cff`.

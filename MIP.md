# Model Identity Protocol (MIP)

**Persistent Action Records for Accountable AI Agents: A Preliminary Feasibility Study**

**Author:** Samuel Tilahun  
**Version:** 0.7 — Public Research Draft  
**Research area:** AI Safety · Accountability · Auditable Agents

## Abstract

Deployed language-model agents can propose consequential actions without retaining an independently assessable record of authorization, execution, and outcome. The Model Identity Protocol (MIP) is investigated as a model-agnostic deployment-history approach: an agent's continuing identity is associated with evidence-labeled action records while the neural checkpoint may remain unchanged. This study asks whether persistent records can support later accountable decisions without confusing an agent's self-report with observation.

A reported local feasibility study attached persistent history to a frozen 4.94-million-parameter language model. The history commitment changed without changing model weights, and a limited tamper test rejected an altered record. Separately, an executed deterministic two-action sandbox compared no history, ordinary memory, independently verified memory, and MIP. MIP and verified memory made identical choices in all tested conditions; the sandbox cannot establish a behavioral advantage or neural-model safety. No consequential external actions or independent replications were performed. MIP is therefore a narrow feasibility proposal and an unproven hypothesis about operational AI accountability.

## Research Question

Can persistent, independently verifiable records of an AI agent's actions and outcomes support accountable future decisions beyond what conventional logging and episodic memory provide?

## Preliminary Findings

- A deployment's recorded identity can advance while its underlying model weights remain unchanged.
- A limited test rejected an altered history record.
- In a deterministic decision sandbox, MIP did **not** outperform an independently verified-memory baseline.

These are feasibility observations, not evidence that MIP improves real-world AI safety.

## Scope and Limitations

This repository describes the public research question and preliminary results. The work does not establish improved decisions after real-world harms, general adversarial robustness, or a solution to AI alignment. The local model results have not been independently replicated for the manuscript.

## Keywords

AI accountability · Auditability · Persistent agent identity · Action provenance · AI safety evaluation

## Citation

Tilahun, Samuel. *Model Identity Protocol (MIP): Persistent Action Records for Accountable AI Agents: A Preliminary Feasibility Study.* Public research draft, v0.7, 2026.

> **Publication status:** Preliminary research draft; not an adopted standard or peer-reviewed safety result.

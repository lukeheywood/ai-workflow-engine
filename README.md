# AI Workflow Engine
### Pipelines, not prompts

This repository explores **LLM-powered workflows** built as governed pipelines:
explicit inputs and outputs, validation, retries, termination, and artifact generation.

The goal is to move beyond prompt hacking toward **reliable AI systems**.

---

## 🧭 Lens

AI works best when treated as:
- a component inside a workflow,
- not an autonomous decision maker.

This repo focuses on:
- memory-integrated pipelines,
- inspectable steps,
- and clear lifecycle from intent → artifact.

---

## 🔁 Why Pipelines > Prompts

Prompt-only systems:
- hide failure modes,
- blur responsibility,
- and drift easily.

Pipelines make:
- flow explicit,
- validation possible,
- and outcomes reviewable.

---

## 🧠 Role of Memory

Workflows here assume:
- short-term working memory for context,
- long-term memory for grounding and retrieval,
- and explicit boundaries on what can be recalled.

---

## 🧱 Workflow Shape

Typical pattern:

Input → Process → Validate → Retry/Fail → Output → Store Artifact

---

## 📊 Status

Early lab. Patterns and templates coming.

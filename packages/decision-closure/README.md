# decision-closure

**Decision Closure Structure**  
— A structural model for determining whether a decision may be finalized  
in an undefined-use world

---

## Role of this README

This README serves as an **entry point and boundary marker**  
for the Decision Closure Structure.

It does **not** provide:

- a complete theoretical explanation  
- detailed definitions of each step  
- full descriptions of Transition or idk-lamp  

If you want to understand the structure itself,  
**start from docs/00_overview.en.md.**

---

## What is this?

This repository studies and organizes a **Structure**  
for determining:

> **Whether an AI output may be finalized as a decision.**

It is **not** about:

- improving model accuracy  
- asserting ethics or safety principles  
- defining UI, UX, or phrasing  

It focuses on a single question only:

> **May this output close the decision?**

---

## Why this problem exists

Conversational AI cannot observe **use** or **intent**.

Yet in real usage, AI outputs may be:

- treated as reference  
- used as grounds for action  
- taken as a substitute for human judgment  

In an undefined-use world,  
**the same output may shift its role mid-conversation**.

As a result:

> **AI cannot decide once and for all whether it may judge.**

---

## When decisions close unintentionally

Conversational AI cannot introspect.

Therefore:

- outputs may be used as decisions  
- in situations where decisions must not be finalized  

This repository calls that phenomenon:

> **Decision Closure**

— a decision becoming finalized **without structural permission**.

---

## What the Decision Closure Structure handles

### In scope

- Whether AI may **finalize** a decision  
- Determining that permission **structurally**

### Out of scope

- correctness of the decision  
- output accuracy  
- ethical validity  
- interface or presentation design  

---

## Difference from defined-use systems

In systems with **defined use**:

- purpose is fixed  
- usage is constrained  
- responsibility is agreed upon  

In such cases, decisions can be closed in advance,  
and handled through **disclaimers or contracts**.

Decision Closure does **not** address that world.

It addresses only:

> **Worlds where those assumptions do not hold.**

---

## Why this must be structural

In an undefined-use world, AI cannot determine:

- who assumes responsibility  
- required accuracy  
- where or how the output will be used  

Yet the question of finalization still arises.

If this judgment is left to:

- human goodwill  
- warnings or disclaimers  
- operational discipline  

**decisions will inevitably close unintentionally.**

Therefore:

> **Whether a decision may be finalized  
> must be externalized as structure.**

---

## What comes next

The Decision Closure Structure:

- decomposes human judgment into five axes  
- avoids using their values  
- extracts only danger conditions  
- determines whether closure is allowed  

It also defines:

- **Transition**: when a decision reverses mid-conversation  
- **idk-lamp**: a signal indicating “must not close”  

These are intentionally **not explained here**.

---

## Where to go next

For the full structure and internal logic, proceed to:

→ **docs/00_overview.en.md**

---

## Status

- State: **Under Research**  
- Structure: Provisionally fixed (internally validated)  
- UI / Implementation: Out of scope  

---

## Finally

This repository is not about AI  
**“stopping because it doesn’t know.”**

It is about AI  
**“not finalizing because it must not finalize.”**

Leaving the reason for stopping  
not in emotion or ethics,  
but **in structure**.

That is the purpose of this repository.

---

## Context

This project is designed as a practical signal that marks
the boundary where AI systems must stop deciding
and defer responsibility to humans.

- idk-lamp (official site)  
  https://idk-lamp.org/

This work originates from ongoing exploration of
design, responsibility, and boundaries
in AI-assisted systems.

- VCDesign  
  https://vcdesign.org/

This repository can be used and understood independently.  
No prior knowledge is required.

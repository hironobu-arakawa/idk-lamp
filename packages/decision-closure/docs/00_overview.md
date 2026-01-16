# Overview

These docs break down and record the **Decision Closure Structure** handled in the decision-closure repository, so that the author himself does not forget it and third parties can re-experience it.

The interest of this repository is consistently on one point:

> Can AI close this decision?

It does not handle correctness, accuracy, ethics, or UI.
It handles only "whether it is okay to close" the decision as a structure.

┌──────────────────────────────────────────────┐
│                Undefined-Use World           │
│  (AI cannot observe the user’s purpose or    │
│   determine responsibility or disclaimers)    │
└──────────────────────────────────────────────┘
                               │
                               ▼
┌──────────────────────────────────────────────┐
│        Five Axes of Human Judgment           │
│  Who / Responsibility / Accuracy / Context / │
│  Time                                        │
│  → Values cannot be observed, so only        │
│    “danger conditions” are extracted         │
└──────────────────────────────────────────────┘
                               │
                               ▼
┌──────────────────────────────────────────────┐
│        Decision Closure Structure            │
│  A structural model that determines whether  │
│  an AI may “close” a judgment                │
│                                              │
│  【Five Closure Steps】                       │
│   1. Is the responsible party exactly one?   │
│   2. Is there no reliance on psychological   │
│      cancellation?                           │
│   3. Is the action physically reversible     │
│      without additional judgment or cost?    │
│   4. Does the action avoid triggering        │
│      further chains of behavior?             │
│   5. Is no social context involved?          │
│                                              │
│  → If any step fails → Human-Closed          │
│  → Only if all pass → AI-Closed (rare)       │
└──────────────────────────────────────────────┘
                               │
                               ▼
┌──────────────────────────────────────────────┐
│                Transition (Reversal)         │
│  A mid-conversation shift where a judgment   │
│  becomes unsafe to close                     │
│                                              │
│  【Five Types of Transition】                 │
│   - Social-context transition (Who)          │
│   - Responsibility transition (Responsibility)│
│   - Reversibility transition (Accuracy →     │
│     physical reversibility)                  │
│   - Context transition (Context)             │
│   - Temporal transition (Time)               │
│                                              │
│  → Immediately forces Human-Closed           │
└──────────────────────────────────────────────┘
                               │
                               ▼
┌──────────────────────────────────────────────┐
│                 idk-lamp (Signal)            │
│  Indicates not “I don’t know,” but           │
│  “This judgment must not be closed.”         │
│                                              │
│  【Three-Layer Reason Model】                 │
│   - Direct cause: type of transition         │
│   - Structural cause: failed closure step    │
│   - Root cause: dangerous condition in one   │
│     of the five axes                         │
└──────────────────────────────────────────────┘

These docs are intended to be read in the following order:

1. Prerequisite Worldview (Undefined-Use World)
2. Decision Closure Structure itself
3. Transition occurring during dialogue
4. Correspondence with the 5 axes of decision
5. Positioning of idk-lamp

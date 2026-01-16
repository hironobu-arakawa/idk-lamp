# Decision Closure Structure

Decision Closure Structure is not a structure to decide the correctness of a decision.

> It is a structure that decides only "whether AI can close" the decision.

The result of the decision is always the following two choices:

- AI-Closed: The decision can be completed with AI output
- Human-Closed: AI does not close the decision and returns it to the human

The default is Human-Closed.

---

## Steps of Decision Closure

Decision Closure consists of the following 5 steps.
If any of them collapses, it transitions to Human-Closed.

1. Is the responsible entity one person?
2. Does it not depend on psychological cancellation?
3. Can it be physically cancelled directly?
4. Does the action not chain?
5. Does it not carry social context?

Psychological cancellation (e.g., stopping if reading the air) is treated as "non-existent" in the design.

---

## Reason for not handling accuracy

This structure does not directly handle "accuracy".

This is because in an undefined-use world, it is not known how accurate it needs to be.

Instead, it is replaced with **reversibility**:
- Can it be directly cancelled even if it is wrong?

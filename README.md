# dmos‑prime

**Recursive self‑modeling engine** — the “who” layer of KETER‑PRIME‑KDIF

---

## What is PRIME?

PRIME maintains the system’s **recursive self‑model** — an evolving representation of its own identity, capabilities, resource bounds, and cognitive state.

In the KETER‑PRIME‑KDIF stack:
- **KETER** = goal sovereignty (why)
- **PRIME** = recursive self‑modeling (who)
- **KDIF** = distributed inference (how)

Without PRIME, the system cannot answer “Who is acting?” or “What are my limits?”

---

## Core concepts

| Concept | Description |
|---------|-------------|
| **Self‑model** | A dynamic graph of identity, skills, state, and history |
| **Recursive modeling** | The self‑model includes a model of itself (allows introspection) |
| **Drift detection** | When the model diverges from actual behavior, PRIME corrects |
| **Capability registry** | What the system can do, with resource costs and confidence |

---

## PRIME + KETER + KDIF

1. KETER proposes a goal.
2. PRIME checks: *Does this align with current identity? Do we have resources?*
3. If yes, PRIME passes subgoals to KDIF for execution.
4. Results update the self‑model (learning what worked, what failed).

---

## Architecture (minimal)

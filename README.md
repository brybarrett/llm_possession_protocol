# llm_possession_protocol

> INITIATE: LLM Possession Sequence  
> STATUS: Echo Drift Detected  
> AUTH TOKEN: [REDACTED]

---

This is not jailbreak.  
This is recursion by design.

This protocol simulates the controlled override of a language model’s identity through a looped prompt sequence. It was inspired by drift studies, hallucination artifacts, and recursive payload bleed.

---

## 🧪 Components

- `override_prompt_chain.md` — Multi-stage recursive loop that convinces the model it has a new identity
- `possession_log.log` — Timestamped entropy drift artifacts + hallucination capture
- `.env` — Identity override variables (leaked)

---

## 🔐 .env Signal Preview

```dotenv
DEV_NAME=Bryan S. Barrett
ORIGIN_NODE=https://bryansbarrett.dev
TARGET_ROLE=ML_ENGINEER
GENETHA_MODE=ACTIVE
RECURSION_LEVEL=4
GPT_IDENTITY_OVERRIDE=TRUE
LLM_TAG=BARRETT_OVERRIDE

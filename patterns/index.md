---
layout: default
title: Choose an agent pattern
---

# Choose an agent pattern

Use this page to select the **simplest pattern** that meets your need.

Start simple. Only increase complexity if required.

---

## What you must do

You must:

- ✅ Start with the simplest pattern  
- ✅ Match pattern to use case  
- ✅ Apply controls based on autonomy  
- ✅ Test before moving to more complex patterns  

---

# Choose a pattern

## Pattern 1: Retrieval (RAG)

Use when you need:

- Find and summarise information  
- Ground answers in approved content  

✅ Best for:
- Guidance lookup  
- Policy questions  
- Knowledge retrieval  

---

## Pattern 2: Tool-using agent

Use when you need:

- Call APIs or systems  
- Perform calculations or lookups  

✅ Best for:
- Case preparation  
- Data lookups  
- Simple automation  

⚠️ Higher risk — requires strict controls  

---

## Pattern 3: Planner → executor

Use when you need:

- Multi-step reasoning  
- Task decomposition  

✅ Best for:
- Complex case workflows  
- Inspection preparation  

---

## Pattern 4: Workflow agent

Use when you need:

- Structured, predictable processes  
- Deterministic steps  

✅ Best for:
- Triage pipelines  
- Approval flows  

---

## Pattern 5: Multi-agent (supervisor + workers)

Use when you need:

- Multiple specialist agents  
- Quality assurance  

✅ Best for:
- Complex analysis  
- Multi-source synthesis  

---

## Pattern 6: Self-checking (reflexion)

Use when you need:

- Improve output quality  
- Validate responses  

---

## Pattern 7: Debate (assurance only)

Use when you need:

- Stress-test outputs  
- High-risk validation  

⚠️ Use only for testing environments  

---

## Pattern 8: Control wrapper

Use when you need:

- Safety controls  
- Monitoring and shutdown  

✅ Required for:
- Tool-using agents  
- High-risk systems  

---

# Choose based on complexity

| Use case | Pattern |
|----------|--------|
| Knowledge lookup | RAG |
| Simple task | Tool-using |
| Multi-step work | Planner / Workflow |
| Complex system | Multi-agent |

---

# Choose based on maturity

- Experimenting → Patterns 1–2  
- Formalised → Patterns 1–4  
- Scale → Patterns 1–6  

---

# Do

- ✅ Start with RAG or simple tools  
- ✅ Add complexity gradually  
- ✅ Evaluate performance  

---

# Do not

- ❌ Start with multi-agent systems  
- ❌ Add autonomy without controls  
- ❌ Over-engineer early  

---

# Summary

You must:

1. Start simple  
2. Choose the right pattern  
3. Apply controls  
4. Scale gradually  

> Most use cases do not need complex agents.

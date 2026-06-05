---
layout: default
title: Integrate agents safely
---

# Integrate agents safely

Use this page to understand how agents interact with:

- Models  
- Tools  
- Humans  

---

# What you must do

You must:

- ✅ Control all integrations  
- ✅ Minimise tool access  
- ✅ Enforce identity and permissions  
- ✅ Log all interactions  

---

# Integration model

Agents interact with:

- Agent → Model  
- Agent → Tool  
- Agent ↔ Human  

---

# Agent to model

You must:

- ✅ Use approved models  
- ✅ Route through governance controls  
- ✅ Minimise data sent to models  
- ✅ Log all requests  

---

# Agent to tool (MCP)

Tool access is the **highest risk area**.

---

## When to use tools

Use tools only when:

- The task cannot be solved with text  
- External systems are required  

---

## You must

- ✅ Use the minimum number of tools  
- ✅ Apply least privilege access  
- ✅ Validate all inputs  
- ✅ Log all tool calls  
- ✅ Apply rate limits  

---

# Apply the quadruple lock

You must apply all 4 controls:

---

## 1. Tool surface

- Only expose required tools  
- Prefer read-only access  
- Restrict write actions  

---

## 2. Gateway control

- Route tools through a gateway  
- Enforce authentication and policy  
- Apply logging and quotas  

---

## 3. Environment controls

- Apply data protection (DLP)  
- Control connectors and data flow  

---

## 4. Human control

- Require approval for actions  
- Record decisions and approvals  
- Test before deployment  

---

# Key risks

You must protect against:

- Prompt injection  
- Tool misuse  
- Data exfiltration  
- Over-privileged access  

---

# Required controls

You must:

- ✅ Validate all tool inputs  
- ✅ Align identity with user context  
- ✅ Control tool outputs  
- ✅ Enforce approval for actions  
- ✅ Log everything  

---

# Agent to human

You must:

- ✅ Provide human review  
- ✅ Enable override  
- ✅ Capture decisions  

---

# Do

- ✅ Keep integrations simple  
- ✅ Use gateways for control  
- ✅ Test in sandbox first  

---

# Do not

- ❌ Allow direct tool access  
- ❌ Use shared high-privilege accounts  
- ❌ Skip logging  

---

# Summary

You must:

1. Control all integrations  
2. Minimise tool access  
3. Apply human oversight  
4. Log all activity  

> The risk is not what the agent says, but what it can do.

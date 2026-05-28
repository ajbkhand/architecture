---
layout: default
title: OWASP-aligned controls
---

# OWASP-aligned controls

## Core principle

Agents must be protected against misuse, not just incorrect outputs.

## Key risks

- Prompt injection → unsafe tool use  
- Excessive autonomy  
- Over-privileged tools  
- Identity confusion  
- Data exfiltration  

## Required controls

### 1. Constrain tool access

- Minimum tools only  
- Separate read and write  

### 2. Validate all tool calls

- Validate input parameters  
- Enforce schemas  
- Reject unsafe inputs  

### 3. Require human approval

Before:

- Data changes  
- Workflow triggers  
- Operational actions  

### 4. Align identity

- Use user context where possible  
- Avoid shared service accounts  

### 5. Control outputs

- Filter tool outputs  
- Apply data minimisation  

### 6. Apply limits

- Tool call limits  
- Execution time  
- Cost controls  

### 7. Full audit logging

Log:

- Inputs  
- Tool calls  
- Outputs  
- Identity  
- Approvals  

### 8. Test adversarial scenarios

- Prompt injection  
- Data leakage  
- Unsafe actions  

## Outcome

Systems must be:
- Secure  
- Auditable  
- Proportionate to risk  

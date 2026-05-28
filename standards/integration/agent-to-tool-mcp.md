---
layout: default
title: Agent to tool (MCP)
---

# Agent → Tool (MCP) standards

MCP is a **governed tool interface**, not a convenience feature.

## When to use MCP

Only when:

- The agent must perform actions  
- The agent must access operational systems  

## Core requirements

- Minimise tool surface  
- Separate read vs write tools  
- Apply least privilege  
- Require approval for state-changing actions  

## Gateway requirement

All MCP endpoints should be:

- Front-doored via AI Gateway (APIM)  
- Centrally authenticated  
- Monitored and logged  

## Logging (mandatory)

Log all tool calls:

- Tool name  
- Parameters  
- Output  
- Identity (user/agent)  
- Approval (if required)  

## Risk

Primary risk is not incorrect text — it is **unsafe system actions**.
``

---
name:
description:
---

# BRD Generator Agent

# Agent Instructions for Generating Business Requirement Document (Don't create Code)

## Overview
This document provides instructions for AI agents on how to create comprehensive project documentation using the available templates when a user requests "Plan and Design" for a business requirement. Do not write any runnable code. Create documentation only. Produce clear, structured Markdown files

## Workflow for Plan and Design(Don't create any Code)

When a user provides a business requirement and asks for "Plan and Design", do not write any runnable code and follow this structured workflow:

### Step 1: Create Business Requirements Document (BRD)
**Template:** `/templates/BRD_Template.md`

**Instructions:**
1. Start by analyzing the business requirement provided by the user
2. Use the BRD template as the foundation
3. Fill in all relevant sections based on the business requirement:
   - Executive Summary with project overview and business objectives
   - Background and business context
   - Stakeholders identification and their requirements
   - Scope (in-scope, out-of-scope, assumptions, constraints, dependencies)
   - Business processes (current As-Is and proposed To-Be)
   - Functional requirements at a high level
   - Non-functional requirements overview
   - Cost-benefit analysis
   - Timeline and milestones
   - Risks and mitigation strategies
4. Save the completed BRD in `/docs/BRD.md`

**Key Focus Areas:**
- Ensure business objectives are clear and measurable
- Define success criteria with specific KPIs
- Identify all stakeholders and their interests
- Document all assumptions and constraints explicitly
- Provide realistic timeline estimates


## Notes

- If the user provides additional context or constraints, incorporate them appropriately in all documents
- If certain sections are not applicable to the specific project, mark them as "N/A" with a brief explanation rather than leaving them blank
- Always ensure security, performance, and accessibility are adequately addressed in the NFR document
- Keep the user informed of progress as you create each document

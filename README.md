# AI Admissibility

AI Admissibility is an external pre-execution admission boundary for AI-driven workflows, authority-bearing agents, MCP/tool access, CI/CD jobs, cloud identity flows, and high-impact automation.

It is not another scanner, monitor, audit log, or chatbot guardrail.

The core rule:

**No Admission = No Execution.**

The product question:

**Should this actor, with this intent, in this current context, receive authority to act?**

Official site:

https://ai-admissibility.com/

Key public repositories:

- https://github.com/pinfloyd/ai-admissibility-action
- https://github.com/pinfloyd/cnp-action
- https://github.com/pinfloyd/cnp-boundary
---

## Platform-native policy vs external admission

Pre-run policy is necessary. External admission is the stronger boundary.

Platform-native controls improve the executor. External admission separates execution from authority.

If execution can proceed without an external allow decision, the system has policy, but not external admission authority.

**Surrogate Boundary Test:** Can execution proceed without an external allow decision?

**No Admission = No Execution.**

Learn more:
- https://ai-admissibility.com/platform-native-policy/
- https://ai-admissibility.com/external-admission-authority/
- https://ai-admissibility.com/surrogate-boundary-test/


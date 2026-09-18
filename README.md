# AI Admissibility

AI Admissibility is an external pre-execution admission boundary for AI-driven workflows, authority-bearing agents, MCP/tool access, CI/CD jobs, cloud identity flows, and other high-impact automation.

It is not a scanner, monitor, audit log, or self-authorizing chatbot guardrail.

**No Admission = No Execution.**

The core question is:

**Should this actor, with this intent, in this current context, receive authority to act?**

## Canonical product surface

Official site: https://ai-admissibility.com/

The website is the canonical public product and documentation surface. GitHub provides implementation, evaluation, compatibility, and proof material that must remain consistent with it.

## Public repositories

- **AI Admissibility Boundary** — architecture / proof / evaluation material:  
  https://github.com/pinfloyd/ai-admissibility-boundary
- **AI Admissibility Action** — current public GitHub Marketplace evaluation Action:  
  https://github.com/pinfloyd/ai-admissibility-action
- **cnp-action** — compatibility workflow slug retained for existing references; not the canonical repository for new evaluation installs:  
  https://github.com/pinfloyd/cnp-action
- **Agent + Boundary Demo** — bounded demonstration material, not the canonical production runtime:  
  https://github.com/pinfloyd/ai-admissibility-agent-boundary-demo
- **Hosted Authority candidate package** — engineering candidate / reference material, not the canonical installed runtime:  
  https://github.com/pinfloyd/ai-admissibility-hosted-authority

## Current public status

The canonical installed boundary is represented publicly through the official site and its controlled evaluation path. Public GitHub Actions are evaluation surfaces; they do not currently claim a customer-specific production no-bypass guarantee or a generally open authority endpoint.

## Platform-native policy vs external admission

Pre-run policy is necessary. External admission is the stronger boundary.

Platform-native controls improve the executor. External admission separates execution from authority.

If execution can proceed without an external allow decision, the system has policy, but not external admission authority.

**Surrogate Boundary Test:** Can execution proceed without an external allow decision?

Learn more:
- https://ai-admissibility.com/platform-native-policy/
- https://ai-admissibility.com/external-admission-authority/
- https://ai-admissibility.com/surrogate-boundary-test/
- https://ai-admissibility.com/canonical-terms/

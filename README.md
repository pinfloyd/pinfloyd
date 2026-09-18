# AI Admissibility

AI Admissibility is an external pre-execution admission boundary for AI-driven workflows, authority-bearing agents, MCP/tool access, CI/CD jobs, cloud identity flows, and other high-impact automation.

It is not a scanner, monitor, audit log, or self-authorizing chatbot guardrail.

**No Admission = No Execution.**

The core question is:

**Should this actor, with this intent, in this current context, receive authority to act?**

## Canonical public surface

Official site: https://ai-admissibility.com/

The website and GitHub repositories are public showcase, documentation, proof, and demonstration surfaces.

They are **not** used as commercial checkout infrastructure, credential issuers, hosted customer runtime, or customer production execution surfaces.

## Public repositories

- **AI Admissibility Boundary** — architecture / proof / evaluation material:  
  https://github.com/pinfloyd/ai-admissibility-boundary
- **AI Admissibility Action** — current public GitHub Marketplace evaluation Action:  
  https://github.com/pinfloyd/ai-admissibility-action
- **cnp-action** — compatibility workflow slug retained for existing references; not the canonical repository for new evaluation installs:  
  https://github.com/pinfloyd/cnp-action
- **Agent + Boundary Demo** — bounded demonstration material, not production runtime:  
  https://github.com/pinfloyd/ai-admissibility-agent-boundary-demo
- **Hosted Authority reference package** — historical engineering / reference material, not the canonical installed runtime:  
  https://github.com/pinfloyd/ai-admissibility-hosted-authority

## Current public status

The canonical installed boundary is represented publicly through the official site and controlled demonstration paths. Public GitHub Actions are evaluation surfaces; they do not provide a customer-specific production no-bypass guarantee or a generally open authority endpoint.

## Collaboration

For collaboration, research, integration, or deployment discussions:

**governance@ai-admissibility.com**

The public website and GitHub repositories remain demonstration surfaces; any real-world commercial or production arrangement is handled separately from them.

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

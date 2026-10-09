# AGENTS.md | Controlled Agent Development

After six months of testing coding agents across growing codebases, I developed this `AGENTS.md` configuration to make neural-assisted development more predictable, controlled, and safe.

The goal is simple: benefit from modern neural tools without wandering into the **Vibe Code Lands of No Return**.

## What Does It Do?

The file defines rules governing how coding agents interact with a project:

- **Investigation before implementation:** Understand existing code, dependencies, and behavior before proposing changes.
- **Explicit approval:** Present solutions, affected files, risks, and verification plans before modifying anything.
- **Architectural consistency:** Respect established patterns, conventions, and subsystem boundaries.
- **Change control:** Prevent unauthorized file creation, unrelated refactoring, and unintended modifications.
- **Repository safety:** Restrict Git operations and protect existing work.
- **Verification:** Review changes, check compilation, and distinguish tested behavior from assumptions.
- **Developer oversight:** Keep architectural decisions, implementation scope, and testing under human control.

## Project-Specific Configuration

This version was developed for a Unity/C# project and includes specific architectural conventions, Unity serialization safeguards, and CLI instructions.

It is intended as a **reference and starting point**, not a universal drop-in solution. Adapt the rules to your own project, tools, and workflow.

## Important

These instructions are guardrails, not guarantees. Agents can still misunderstand requirements or make mistakes.

Effective use still requires substantial programming experience, architectural knowledge, and active developer involvement.

**Neural tools should accelerate development, not replace understanding of the code.**

# ADR 0001: Project Architecture & Dual-Track Learning System

## Status
Accepted

## Context
Building an enterprise-ready tax application (EasyTax) for the first time requires balancing two distinct goals:
1. Producing production-grade, maintainable, secure, and compliant software.
2. Building deep personal competence and technical understanding of *how* and *why* enterprise systems are designed.

Without a structured learning track, novice developers often fall into the trap of blindly copying boilerplate or using libraries without understanding the trade-offs, leading to fragile code.

## Decision
We adopt a **Dual-Track Development Strategy**:
1. **Track A (Product Evolution)**:
   - Separate the application into clear decoupled tiers:
     - Functional, framework-free Core Tax Engine (deterministic, 100% testable).
     - Modern frontend application with rich design system and wizard UX.
     - Secure backend API with relational database and RBAC auth.
     - Document vault with async parsing.
2. **Track B (Knowledge & Learning Infrastructure)**:
   - `docs/learning/devlog.md` tracks daily sessions, blockers, and breakthroughs.
   - `docs/learning/concepts/` stores 1-page summaries of critical engineering concepts.
   - `docs/adr/` tracks every significant technical choice with context and trade-offs.
   - `docs/learning/skill_matrix.md` tracks skill development.

## Consequences
- High architectural clarity and zero technical debt.
- Complete documentation of engineering trade-offs.
- Seamless ramp-up from beginner to enterprise full-stack engineer.

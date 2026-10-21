# EasyTax - Product & Engineering Learning Roadmap

## Dual-Track Progression
1. **Track A (Product Engineering)**: Design System & Prototype -> Pure Calculation Engine -> Secure Backend & DB -> Document Vault -> Enterprise CI/CD.
2. **Track B (Skill & Concept Mastery)**: Design Tokens & Component Architecture -> Pure Functions & TDD -> Relational Modeling & RBAC -> DevOps & Observability.

---

### Phase 0: Foundations & Knowledge System (Completed)
- [x] Workspace structure and documentation framework established
- [x] Learning DevLog (`docs/learning/devlog.md`) & Skill Matrix initialized
- [x] Initial Architecture Decision Records (`docs/adr/0001-...` and `docs/adr/0002-...`)
- [x] Generated high-fidelity visual UI mockup (`docs/design/easytax_dashboard_mockup.jpg`)

### Phase 1: Design Architecture & Interactive UI Prototype (Current)
- [ ] Enterprise Financial Design System (CSS tokens, typography, dark obsidian theme)
- [ ] Executive KPI Cards (Gross Income, Estimated Liability, Net Take-Home, Potential Savings)
- [ ] Interactive Live Tax Simulator & Regime Comparator (New vs Old Regime side-by-side)
- [ ] Multi-Step Tax Filing Wizard with reactive validation and progress tracking
- [ ] *Learning Focus*: Design tokens, CSS Grid/Flexbox, Component-driven React/Next.js + TypeScript, State machines, WCAG accessibility

### Phase 2: Core Tax Engine & Domain Logic (TDD)
- [ ] Extract exact domain models and types from the UI forms
- [ ] Deterministic currency handling (Integer cents/paise or Decimal)
- [ ] Slabs & Deductions computation engine (Old vs New regime comparison)
- [ ] 100% Test coverage with Vitest/Jest
- [ ] *Learning Focus*: Pure functions, Test-Driven Development (TDD), Domain-Driven Design (DDD)

### Phase 3: Secure Backend API & Database Persistence
- [ ] Relational schema design (PostgreSQL) for Users, Filings, Audit logs
- [ ] Authentication & Role-Based Access Control (RBAC: User, Accountant, Auditor, Admin)
- [ ] RESTful API with validation, rate limiting, and automated OpenAPI documentation
- [ ] *Learning Focus*: Relational modeling, ACID properties, Token auth security, OWASP guidelines

### Phase 4: Document Vault & Automated Parsing
- [ ] Secure file storage for tax documents (W-2, Form 16, Salary slips, Receipts)
- [ ] Extraction engine (PDF/OCR parsing)
- [ ] Tamper-evident enterprise audit logging
- [ ] *Learning Focus*: Async processing, file validation, compliance & privacy (PII)

### Phase 5: Hardening, Automated CI/CD & Production Readiness
- [ ] End-to-End tests (Playwright) covering the complete filing flow
- [ ] Docker containerization with multi-stage builds & `docker-compose`
- [ ] GitHub Actions CI pipeline (Linting, Type checks, Test suites, Security scans)
- [ ] *Learning Focus*: DevOps, Container orchestration, Telemetry & Observability

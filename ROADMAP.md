# EasyTax - Product & Engineering Learning Roadmap

## Dual-Track Progression
1. **Track A (Product Engineering)**: From Domain Modeling -> Modern UI Wizard -> Secure API -> Doc Vault -> Enterprise CI/CD.
2. **Track B (Skill & Concept Mastery)**: From Clean Architecture -> State Machines -> ACID Transactions & RBAC -> Cloud Architecture.

---

### Phase 0: Foundations & Knowledge System (Current)
- [x] Workspace structure and documentation framework established
- [x] Learning DevLog (\docs/learning/devlog.md\) & Skill Matrix initialized
- [x] Initial Architecture Decision Record (\docs/adr/0001-init-architecture-and-learning-system.md\)
- [ ] Technology stack confirmation & environment setup

### Phase 1: Core Tax Engine & Domain Logic (TDD)
- [ ] Domain models for Tax Regimes, Slabs, Deductions, and Incomes
- [ ] Deterministic currency handling (Integer cents/paise or Decimal)
- [ ] Slabs & Deductions computation engine (Old vs New regime comparison)
- [ ] 100% Test coverage with Jest/Vitest/Pytest
- [ ] *Learning Focus*: Pure functions, Test-Driven Development, Domain-Driven Design (DDD)

### Phase 2: Enterprise UI/UX & Interactive Filing Wizard
- [ ] Enterprise Financial Design System (typography, tokens, accessible color palette)
- [ ] Real-time Interactive Tax Estimator (sliders, regime comparison charts)
- [ ] Multi-step Tax Filing Wizard with persistent state & validation
- [ ] *Learning Focus*: Component architecture, Form state machines, Data visualization, WCAG accessibility

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
- [ ] Docker containerization with multi-stage builds & \docker-compose- [ ] GitHub Actions CI pipeline (Linting, Type checks, Test suites, Security scans)
- [ ] *Learning Focus*: DevOps, Container orchestration, Telemetry & Observability


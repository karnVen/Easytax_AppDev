# ADR 0002: Design-Driven Development (UI/UX First Architecture)

## Status
Accepted

## Context
Originally, the roadmap considered starting with a headless backend calculation engine. However, when building an enterprise-grade financial application—especially for a first-time application builder—starting with **Design & User Experience (Design-Driven Development)** provides critical strategic advantages:
1. **Concrete Domain Discovery**: Visualizing inputs (salary, deductions, allowances) and outputs (slabs, liability, net pay) directly defines the exact data structures and types required in the domain engine.
2. **Reduced Cognitive Load**: Tax laws are notoriously dry and confusing. An intuitive, trustworthy, and visually clean UI turns complex legal calculations into an accessible experience.
3. **Immediate Visual Feedback**: For learning full-stack development, seeing interactive components work on screen fosters rapid iteration, debugging skills, and excitement.

## Decision
We adjust the project workflow to place **Design Systems & High-Fidelity UI Prototyping** as the initial implementation phase:
1. Establish Design System Tokens (Color palette, typography, elevation, glassmorphism, spacing).
2. Wireframe and design the core flows:
   - Executive Tax Dashboard & Health Check.
   - Interactive Live Tax Estimator & Regime Comparator (New vs Old).
   - Multi-Step Guided Filing Wizard.
3. Extract exact TypeScript interfaces and domain schemas from the finalized UI forms to feed into the calculation engine and database models.

## Consequences
- The developer immediately sees product progress in the browser.
- Data contracts (API payloads and database entities) become obvious and natural because they directly mirror real user interactions.
- Avoids building backend endpoints or calculation rules that the UI doesn't actually need.

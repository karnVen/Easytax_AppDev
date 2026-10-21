# EasyTax Design System & UI Architecture Specification

## 1. Visual Language & Style Guide
- **Theme**: Dark Slate Obsidian (Sleek enterprise aesthetic with glassmorphic depth).
- **Surface Elevation**:
  - Background: Deep Slate `#0B0F19`
  - Cards & Containers: Translucent obsidian `#111827` with 1px border `rgba(255, 255, 255, 0.08)` and subtle backdrop blur.
  - Active Elements: Emerald glow `rgba(16, 185, 129, 0.15)`.
- **Typography**:
  - Primary Font: Inter / Plus Jakarta Sans.
  - Display Numbers: Tabular figures (`font-variant-numeric: tabular-nums`) so financial amounts align perfectly in tables and counters.

## 2. Core Screens & Components
1. **Executive Dashboard**:
   - 4 Hero KPI Cards: Gross Income, Estimated Tax Liability, Net Take-Home Pay, Potential Tax Saved.
   - Interactive Live Regime Optimizer: Side-by-side comparison between Old Regime and New Regime with visual bar breakdown.
   - Filing Progress Tracker: 4-step completion meter with action status.
   - AI Tax Advisor Widget: Smart tips suggesting missed deductions (e.g., 80D health insurance, HRA).

2. **Interactive Tax Simulator**:
   - Dynamic sliders for Income, Basic Salary, HRA, 80C, 80D investments.
   - Real-time recalculation of tax brackets without full page reloads.

3. **Multi-Step Guided Filing Wizard**:
   - Step 1: Personal Profile & Filing Category.
   - Step 2: Income Sources (Salary, House Property, Capital Gains, Other).
   - Step 3: Deductions & Exemptions (80C, 80D, 80G, Standard Deduction).
   - Step 4: Tax Computation & Regime Selection.
   - Step 5: Verification & E-Filing Summary.

## 3. UI Mockup Reference
Refer to the generated visual mockup at `docs/design/easytax_dashboard_mockup.jpg`.

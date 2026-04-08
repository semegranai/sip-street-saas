# UPDATE ME!!


# Sip Steet UI/UX Design Guidelines

**Version**: 1.0  
**Date**: April 7, 2026  
**Audience**: Designers, Developers, and Product Team  
**Purpose**: Ensure consistency, usability, trust, and professionalism across the Sip Steet platform.

## 1. Design Philosophy

- **Clarity over Cleverness**: Every screen must be immediately understandable to a busy development executive or analyst.
- **Trust & Professionalism**: The interface should feel like a high-end financial tool (think Bloomberg terminal meets modern SaaS).
- **Speed & Efficiency**: Minimize clicks. Power users should be able to model a deal quickly.
- **Consistency**: Same patterns, colors, and behaviors everywhere.
- **First-Principles Simplicity**: Reduce cognitive load. Make complex financial models feel approachable.

## 2. Core Visual Style

**Color Palette**:
- Primary: Emerald-500 (#10b981) – used for positive numbers, success states, CTAs
- Danger/Expense: Red-500 (#ef4444)
- Neutral Background: Zinc-950 (#09090b)
- Cards & Surfaces: Zinc-900 (#18181b)
- Borders: Zinc-700 (#3f3f46)
- Text: Zinc-100 (primary), Zinc-400 (secondary labels)

**Typography**:
- Headings: Inter Bold / Semi-Bold
- Body: Inter Regular
- Numbers & Financial Data: Inter Medium or Mono (for alignment)

**Spacing & Layout**:
- Generous padding (24–32px on cards)
- Consistent 6-column or 12-column grid system
- Clear visual hierarchy (large numbers for key metrics)

## 3. Component Guidelines

**Buttons**:
- Primary: Emerald background, white text, rounded-2xl
- Secondary: Zinc-800 background, subtle hover
- Destructive: Red-500 for delete/reset actions

**Inputs**:
- Large, clear text fields (text-xl)
- Subtle borders that highlight on focus
- Real-time validation with inline messages

**Cards**:
- Rounded-3xl
- Subtle shadow or border
- Clear section headers

**Tables & Breakdowns**:
- Clean zebra striping when needed
- Right-aligned numbers
- Consistent currency formatting with thousand separators

**Charts**:
- Clean, minimal design (Chart.js or Recharts)
- Emerald for positive/revenue, Red for costs
- Clear labels and tooltips

## 4. Layout Patterns

**Main Layout**:
- Top navigation bar with logo + project name
- Two-tab structure for Phase 1: **Assumptions** | **Dashboard**
- Left/right split on Dashboard (P&L on left, GP/LP + charts on right)

**Assumptions Page**:
- Grid of inputs
- Expandable accordions for sub-component breakdowns (Home Build Cost & Infrastructure)
- Prominent “Recalculate” feedback (live updates preferred)

**Dashboard Page**:
- Top row: Three large metric cards (Total Revenue, Total Cost, Net Profit)
- Middle: Full P&L breakdown (step-by-step)
- Right sidebar: GP/LP split
- Bottom: Waterfall chart + Cash Flow summary

## 5. User Experience Principles

- **Live Updates**: All calculations update in real-time as user types (debounced where necessary)
- **Progressive Disclosure**: Sub-components hidden by default, expandable on demand
- **Error Prevention**: Clear validation, helpful defaults, undo capability
- **Feedback**: Subtle loading states, success toasts for save/export
- **Accessibility**: WCAG 2.1 AA compliance (contrast, keyboard navigation, screen reader support)
- **Mobile First**: Responsive design – usable on tablet for site visits

## 6. Report & PDF Guidelines

- Clean, print-friendly layout
- Consistent header/footer with Sip Steet branding and project name
- Professional typography and spacing
- Include: Cover page, Executive Summary, Assumptions, Detailed P&L, GP/LP Breakdown, Waterfall Chart, Risk Summary, AI Insights (future)

## 7. Future UI/UX Considerations

- Dark mode only (current)
- Light mode toggle (future)
- Role-based views (Analyst vs Executive vs Investor)
- AI chat sidebar for “Explain this number” or “What if we change X?”
- Portfolio overview dashboard

## 8. Do’s and Don’ts

**Do**:
- Use consistent emerald accents for positive financial impact
- Make numbers large and easy to scan
- Prioritize readability of financial data
- Keep forms simple and scannable

**Don’t**:
- Use bright colors or flashy animations
- Overload any single screen
- Hide important numbers behind multiple clicks
- Use jargon without tooltips

These guidelines will evolve as we gather user feedback from our development team.

All designs and implementations must be reviewed against this document.

— Sip Steet Product & Design Team

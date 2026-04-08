# Sip Steet Technical Roadmap

**Client**: Sip Steet Group  
**Project**: Rebuild internal financial modeling platform  
**Handover Date**: April 2026  
**Audience**: 3rd-party IT / Software Development Partner

## Project Objective

Replace all existing Excel/Google Sheets models with a single, reliable, web-based SaaS-style internal tool. The platform must produce consistent, professional PDF reports for every deal and serve as the foundation for future expansion across multiple asset classes.

## Phase 1 – MVP (Residential Focus) – Target: 8–10 weeks

**Core Deliverables**:
- 2-tab web application (Assumptions + Dashboard)
- Zillow / MLS / Redfin link dropping with intelligent data extraction
- Expandable sub-component cost editors for Home Build Cost and Infrastructure & Soft Costs
- Unified Profit & Loss statement
- GP/LP waterfall (configurable 50/50 split + preferred return)
- Cash waterfall visualization
- Sensitivity analysis and Monte Carlo simulation
- One-click standardized PDF report export (branded, consistent format)
- Project save/load with basic version history

**Success Criteria**:
- All calculations remain consistent across tabs and PDF output
- Report quality is suitable for internal review and external investors
- Tool is stable and performant for daily use on live deals

---

## Phase 2 – Polish & Foundation (Following Phase 1)

- Move to production-grade stack (Next.js 15 + Supabase recommended)
- User authentication and role-based access
- Cloud project storage
- Improved PDF templating and branding options
- Basic team collaboration features

---

## Phase 3 – Multi-Asset Class Expansion (2027)

Add support for:
- Multifamily / Townhomes
- Commercial Office & Retail
- Industrial / Warehouse
- Hospitality (Hotels)
- Data Centers
- Cold Storage
- Solar / Renewable Energy Facilities

Each new asset class will include customized variables, sub-component breakdowns, and tailored PDF report templates.

---

## Phase 4 – Advanced Capabilities (2027+)

- AI-assisted assumption generation and narrative writing
- Portfolio-level analytics
- Integration with PandaDoc for investor soft commitments
- Branded investor portal (frontend only – backend may use existing tools like AppFolio)
- API layer for internal system integration

---

## Non-Goals (Current Engagement)

- Building the actual SIP manufacturing system
- Full investor capital deployment platform (soft commitment flow only)
- Mobile app development

This roadmap focuses on delivering a high-quality, reliable modeling platform as the foundation for Sip Steet’s internal operations.

We expect close collaboration, regular demos, and iterative feedback throughout the engagement.

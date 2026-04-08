# Sip Steet Documentation Index

This file serves as the central index for all project documentation.  
It is maintained by the Sip Steet Technology Team.

**Last Updated**: April 7, 2026

## Core Project Documents

### 1. `README.md`
- Purpose: Public-facing overview of the project for anyone visiting the repo.
- Content: Project description, current status, live demo link, how to run locally, and links to other docs.

### 2. `ROADMAP.md`
- Purpose: High-level strategic and technical roadmap.
- Content: Phases, timelines, priorities, success metrics, and guiding principles (Tesla + Toyota influence).

### 3. `FEATURES.md`
- Purpose: Detailed specification of all current and planned features.
- Content: Link dropping, sub-component editors, P&L, GP/LP split, PDF export, multi-asset class support, investor flow, etc.

### 4. `TECHNICAL-SPECS.md`
- Purpose: Technical architecture and implementation guidelines for the development team.
- Content: Recommended stack (Next.js, Supabase, etc.), coding standards, architecture decisions, and evolution plan.

### 5. `SECURITY-AND-COMPLIANCE.md`
- Purpose: Security requirements and compliance roadmap.
- Content: Current requirements, future SOC 2 goals, data privacy, scraping compliance, audit logging.

### 6. `DATA-MODEL.md`
- Purpose: Database schema and data structure specification.
- Content: Project entity, cost components, assumptions, reports, user roles, version history.

### 7. `CALCULATION-ENGINE.md`
- Purpose: Single source of truth for all financial calculations.
- Content: Detailed formulas for P&L, GP/LP waterfall, interest carry, contingency, etc. Must be referenced by all code.

### 8. `PDF-REPORT-SPEC.md`
- Purpose: Exact specification for all generated PDF reports.
- Content: Standardized layout, sections, branding guidelines, page order, and asset-class variations.

### 9. `API-SPECS.md` (Future)
- Purpose: Internal and external API documentation.
- Content: Endpoints, authentication, rate limits, and integration points (PandaDoc, etc.).

---

## Operational & Process Documents

### 10. `DEVELOPMENT-GUIDELINES.md`
- Purpose: Coding standards and workflow for the team.
- Content: Git workflow, naming conventions, testing requirements, PR process, AI usage guidelines.

### 11. `TESTING-STRATEGY.md`
- Purpose: How we ensure calculation accuracy and reliability.
- Content: Unit tests for calculations, integration tests, manual verification checklist, regression testing plan.

### 12. `DEPLOYMENT-AND-OPS.md`
- Purpose: Deployment, monitoring, and operations guide.
- Content: Vercel / hosting setup, environment variables, backup strategy, monitoring tools.

### 13. `CHANGELOG.md`
- Purpose: Record of all major updates to the platform.

---

## Asset-Class Specific Documents (Created as needed)

### 14. `RESIDENTIAL-SPECS.md`
- Detailed variables, sub-components, and report templates for residential (luxury, workforce, shelters).

### 15. `COMMERCIAL-SPECS.md`
- Office, retail, mixed-use specifics.

### 16. `INDUSTRIAL-SPECS.md`
- Warehouse, distribution, cold storage.

### 17. `DATA-CENTER-SPECS.md`
- IT load, PUE, redundancy, etc.

### 18. `HOSPITALITY-SPECS.md`
- ADR, occupancy, RevPAR, etc.

(Additional files will be created for Solar, Healthcare, etc. as we expand.)

---

## Investor & External Documents

### 19. `INVESTOR-FLOW-SPECS.md`
- Purpose: Detailed specification of the investor journey.
- Content: Link → soft commitment → PandaDoc → Investor Portal flow, form fields, integration points.

### 20. `BRANDING-AND-REPORT-STYLE-GUIDE.md`
- Purpose: Visual and content standards for all reports and external materials.

---

## How to Use This Index

- All documents are living files.
- Update the "Last Updated" date when making significant changes.
- Link between documents where relevant (e.g., ROADMAP links to FEATURES and TECHNICAL-SPECS).
- New documents should be added here when created.

**Recommendation**: Start by creating the first 9 core documents. The asset-class specific ones can be added as we expand beyond residential.

This structure ensures the project remains well-documented, maintainable, and scalable as we grow from a simple modeling tool into a comprehensive internal platform.

— Sip Steet Technology Team

# Sip Steet Technical Specifications & Guidelines

**For**: 3rd-party Development Partner  
**Date**: April 2026

## Technology Preferences

**Frontend**:
- Next.js 15 (App Router) preferred
- Tailwind CSS for styling
- Chart.js or Recharts for visualizations

**Backend / Database** (Phase 2):
- Supabase (PostgreSQL + Auth + Storage) strongly preferred for speed
- Alternative: Node.js + Prisma if needed

**Key Requirements**:
- All calculations must be performed in a single, shared engine (no duplication)
- PDF generation must be server-side for consistency and security (e.g., pdf-lib or Puppeteer)
- Responsive design (works well on desktop and tablet)
- Accessibility and clean code standards

## Security & Best Practices

- Input validation and sanitization on all fields
- Rate limiting on link scraping features
- Secure storage of project data
- Audit logging for changes to financial models
- Preparation for SOC 2 / data privacy compliance (future requirement)

## Deliverables & Process

- Weekly demos
- Code reviews via GitHub
- Clean, well-commented code
- Comprehensive README for internal team handoff

We value speed of iteration, code quality, and attention to calculation accuracy above all.

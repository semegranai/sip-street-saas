# Sip Steet Roadmap & Lessons Learned

**Project:** Real Estate Development Financial Model SaaS  
**Last updated:** April 7, 2026

## Current Status (Phase 1)
- Single `index.html` file with live calculations
- Expandable sub-components for Home Build Cost and Infrastructure
- Clear P&L statement on Dashboard
- GP/LP 50/50 split with preferred return
- Cash Waterfall chart

## Phase 0 – Validation (Do this before going further)
- Talk to 15–20 real developers (LinkedIn, local REI groups, BiggerPockets, etc.)
- Ask: Would you pay $49/month for this tool?
- Build a simple waitlist landing page

## Phase 2 – Proper App
- Convert to Next.js 15 + Supabase (user accounts + cloud project saving)
- Add project list, save/load from database
- PDF export button

## Phase 3 – Monetization
- Stripe subscriptions ($49/mo or $399/year)
- Free tier (1 project) vs Pro tier

## Mistakes to Avoid (From AI/vibe-coded SaaS failures in 2025–2026)

1. **Building before validation** — Don’t assume people want it. Talk to users first.
2. **Technical debt** — Single HTML file is fine for MVP, but we must move to proper structure soon.
3. **Inconsistent calculations** — All tabs must use the exact same math (we just fixed this).
4. **Over-complicated UI** — Keep it simple. Two tabs is better than seven for now.
5. **No error handling** — If someone enters bad numbers, the app should still work.
6. **Hard-coded numbers** — Everything should be editable (we’re improving this).
7. **Ignoring realism** — Infrastructure at $35k+ was too high for this site. Always double-check local costs.

## Success Criteria
- At least 10 developers say they would actually use/pay for it
- All numbers stay consistent when inputs change
- Clean, professional look that feels trustworthy

Made for real estate developers who want accurate, editable pro formas without the spreadsheet headaches.

Feedback welcome!

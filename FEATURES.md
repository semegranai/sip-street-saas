# Sip Steet Features Specification

**Product Philosophy**  
Tesla first-principles + Toyota lean discipline. Every feature eliminates waste and creates a seamless experience from modeling to capital deployment.

---

## Core Feature: Link Dropping / Auto-Population

**"Drop & Model" Engine**  
Paste any Zillow, Redfin, Realtor.com, or MLS link → Sip Steet automatically:
- Extracts property data (address, sqft, lot size, price, year built, photos)
- Pulls recent comps and market data
- Pre-fills the full financial model
- Generates a complete investor-ready report + P&L + waterfall

---

## Investor Experience Flow (End-to-End)

**Investor Journey** (the most important user flow)

1. Investor receives a **branded Sip Steet report link** or PDF.
2. Clicks prominent **“Invest in This Project”** button.
3. Simple form appears:
   - Desired investment amount ($X input field)
   - Name, email, phone
   - Accredited investor confirmation checkbox
4. One-click **soft commitment** generated via PandaDoc (pre-filled with project details and amount).
5. Investor signs electronically.
6. Automatic redirect to **Sip Steet Investor Portal** (invest.sipsteet.com).
7. Portal shows:
   - Project status dashboard
   - Capital call schedule
   - Distribution history
   - Real-time SIP manufacturing updates
   - All tax documents and reports

**Technical Integration Plans**:
- PandaDoc API for automated document creation and e-signature
- Webhook from PandaDoc → update portal status instantly
- Use existing best-in-class investor relations platforms (AppFolio, DealCloud, InvestorFlow, or similar) for the backend fund accounting
- Our front-end will be fully branded and seamless (investors never feel they left Sip Steet)

**Future Enhancements**:
- One-click wire transfer / ACH link after soft commitment
- Secondary market / LP transfer functionality
- Quarterly automated performance reports generated from Sip Steet data

---

## Multi-Asset Class Calculators

(Full list remains the same as previous version – residential through data centers, with editable sub-components for each.)

---

**This specification makes Sip Steet the complete bridge between modeling, investor acquisition, commitment, and capital deployment.**

We control the entire investor experience from the first link to the final wire transfer.

— The Sip Steet Team

# Sip Steet Features Specification

**Product Philosophy**  
Every feature is designed with Tesla-style first-principles thinking and Toyota-style lean discipline. We eliminate waste, standardize what can be standardized, and give users deep editability where judgment matters.

---

## Core Feature: Link Dropping / Auto-Population

**"Drop & Model" Engine**  
Paste any Zillow, Redfin, Realtor.com, or MLS link → Sip Steet automatically:
- Extracts address, lot size, current listing price, year built, sqft, beds/baths, photos
- Pulls recent comps within 0.5–1 mile (sale price, sqft, days on market)
- Estimates zoning, utility availability, and soft costs based on location
- Pre-fills the entire financial model with realistic defaults
- Flags any missing data for manual review

**Future Enhancements**:
- Bulk import from CSV or portfolio lists
- Real-time market data refresh button
- AI-assisted “what-if” scenarios (e.g., “add ADU” or “convert to multifamily”)

---

## Multi-Asset Class Calculators

Sip Steet will support **every major asset class** where SIPs deliver advantage. Each module includes editable sub-components, industry-specific variables, and one-click reports.

### 1. Residential (Luxury → Workforce → Transitional Shelters)
- Variables: Unit mix, avg unit size, parking ratio, amenity package cost, rental income or sale price projections, vacancy/turnover rates
- Special shelter module: Rapid-deployment cost, durability in extreme weather, minimal maintenance requirements

### 2. Commercial Office
- Variables: Rent per sq ft, tenant improvement allowance, parking structure cost, LEED/sustainability premium, lease-up timeline

### 3. Retail & Mixed-Use
- Variables: Anchor tenant rent, inline tenant rent, CAM recovery percentage, foot traffic projections

### 4. Industrial / Warehouse / Distribution
- Variables: Clear height, dock doors, truck courts, ESFR sprinkler requirements, automation systems

### 5. Data Centers
- Variables: IT load (MW), PUE, cooling system type, redundancy level (Tier II–IV), fiber connectivity cost

### 6. Hospitality (Hotels, Resorts, STR Communities)
- Variables: ADR, occupancy rate, RevPAR, F&B revenue, meeting space revenue, brand/franchise fees

### 7. Cold Storage & Food Distribution
- Variables: Temperature zones, refrigeration system cost, food safety compliance

### 8. Solar / Renewable Energy Facilities
- Variables: MW capacity, battery storage, grid interconnection costs, PPA terms

### 9. Healthcare & Medical
- Variables: Medical equipment cost, sterile environment requirements, HVAC redundancy

### 10. Educational & Institutional
- Variables: Classroom/lab size, safety systems, sustainability goals

### 11. Agricultural & Farm Buildings
- Variables: Climate control, livestock housing requirements

### 12. Mission-Critical & Government
- Variables: Blast/EMP hardening, security clearance requirements

**Every Module Includes**:
- Editable sub-component cost breakdown (like current home build / infrastructure sections)
- Industry-standard operating expense assumptions
- Revenue driver inputs
- Asset-class-specific risk factors
- One-click PDF report tailored to that sector

---

**This specification turns Sip Steet from a simple calculator into the central operating system for a vertically integrated SIP-powered development empire.**

We start with residential because that is our home base.  
We expand methodically, applying the same lean and vertical integration principles to every new asset class.

Feedback and iteration welcome at every step.

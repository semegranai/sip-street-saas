🏗️ 2. SYSTEM-ARCHITECTURE.md
Overview

This document explains how the system is structured at a high level so any developer can quickly understand how everything connects.

Core System Components
1. Frontend (UI Layer)
Handles user interaction
Displays:
Assumptions
Dashboard
Charts
Sends input to backend
2. Backend (Application Layer)
Handles business logic
Processes calculations
Manages API endpoints
Connects frontend to database
3. Database (Data Layer)

Stores:

Projects
Assumptions
Calculation outputs
Users
Version history
4. Calculation Engine (Core Logic)
Central source of truth for all math
Handles:
Revenue
Costs
Financing
Returns
Must be deterministic and consistent
5. PDF Generator
Converts data into investor-ready reports
Pulls from same calculation engine
Ensures consistency with UI
Data Flow
Step 1: Input
User enters data OR
External data is imported
Step 2: Processing
Data is validated
Passed into calculation engine
Outputs generated
Step 3: Output
Displayed in dashboard
Used in charts
Rendered into PDF
Key Principles
Single Source of Truth
All calculations must come from ONE engine
No duplicate logic in frontend
Consistency
Numbers must match across:
UI
Backend
PDF
Separation of Concerns
UI = display only
Backend = logic
Database = storage
State Management
Frontend holds temporary state
Backend stores persistent data
Changes trigger recalculation
Versioning
Each save creates a snapshot
Users can:
View history
Restore versions
Integrations
Data Sources
Zillow / MLS / Redfin
Documents
PandaDoc (future)
Performance Requirements
UI load: <2 seconds
Calculations: near instant
PDF generation: <10 seconds
Failure Handling
If external data fails:
Allow manual input
If calculation fails:
Show clear error
Log all failures

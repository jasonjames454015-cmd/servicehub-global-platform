# Real Estate Research Notes - Free & Compliance-First Sources
**Date:** 2026-10-31  
**Status:** Research complete for public sources. No paid APIs used. No fabricated data.

## Primary Free Sources (U.S. Focus)

1. **U.S. Census Bureau - American Community Survey (ACS)**
   - Housing values, median rents, occupancy, year built, demographics down to tract level.
   - Note: As of 2026, API requests require a free API key.
   - Access: census.gov / api.census.gov

2. **HUD Fair Market Rents (FMR)**
   - Free bearer token. Rate limited ~60/min.
   - Rent benchmarks by metro/county and bedroom count.
   - Ideal for affordability and rental market baselines.
   - Access: huduser.gov

3. **FRED (St. Louis Fed)**
   - Free key. Macro series including mortgage rates (MORTGAGE30US), housing starts, Zillow-mirrored indexes.
   - 120 requests/min.

4. **OpenAddresses (openaddresses.io)**
   - Global open address, building, parcel data.
   - Fully open, downloadable.

5. **FHFA House Price Index**
   - Free repeat-sales price indexes, ZIP/tract/county level.
   - Long historical series.

6. **Zillow Research & Redfin Data Center**
   - Market-level CSVs: home value indexes, rents, inventory, sale-to-list.
   - No account/key required for downloads.

7. **County Assessor & Recorder Offices**
   - Ownership, sales, tax, liens. Legal public records.
   - Access varies by county (web portals, bulk where available). Compliance: use only public interfaces.

## Compliance Rules Followed
- Only public, government, or openly published research data.
- No scraping of commercial listing sites that require login or prohibit automation.
- No paid keys or accounts created (none needed for above downloads/CSVs).
- Data used for research notes and potential free digital guides only.

## Potential Use Cases (Zero Cost)
- Neighborhood affordability reports (ACS + HUD FMR).
- Price trend summaries (FHFA).
- Address/parcel validation layers (OpenAddresses).
- Content for free guides or lead magnets.

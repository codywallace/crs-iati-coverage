# CRS–IATI Coverage

This repository supports analysis of data coverage between the OECD DAC Creditor Reporting System (CRS) and IATI transaction data, in support of monitoring the transparency dimension of the Global Partnership for Effective Development Co-operation (GPEDC) monitoring framework.

## Main notebook

- **IATI and CRS.ipynb** — *Compare CRS Data to IATI Transactions*  
  Core analysis comparing CRS aggregates with IATI transaction-level reporting to assess coverage gaps, overlaps, and differences by donor and year (and other dimensions as applicable).

## What this analysis is for

GPEDC transparency monitoring benefits from understanding how reporting coverage differs between:
- **CRS** (audited / official reporting, structured aggregates), and
- **IATI** (open, more granular transaction-level reporting, often more timely but variable by publisher).

This repository helps quantify and visualize those differences to support interpretation of GPEDC transparency results and related coverage discussions.

## Typical outputs (from the notebook)

- Donor-level comparisons of CRS vs IATI values
- Coverage / difference metrics (absolute and percentage differences)

## How to run

1. Create and activate a virtual environment
2. Install requirements.txt
3. Launch Jupyter and run **IATI and CRS.ipynb**


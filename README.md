# Electronic Arts (EA) Leveraged Buyout (LBO) Model
#  Overview
This repository contains a fully integrated, institutional-grade Leveraged Buyout (LBO) financial model designed to evaluate the acquisition of Electronic Arts (EA). The model projects a 5-year investment horizon and features a dynamic debt schedule with a cash sweep mechanism, fully linked 3-statement financial projections, and a comprehensive returns analysis for private equity sponsors.

# Key Features & Mechanics
Fully Integrated 3-Statement Architecture:
Connected Income Statement, Balance Sheet, and Cash Flow Statement with automated balancing and built-in error checks.

Dynamic Debt Schedule & Cash Sweep:

 - Revolving Credit Facility (RCF): Automated drawdowns and repayments based on minimum cash requirements.

 - Term Loan B: Standard amortization with aggressive optional prepayments funded by excess Cash Available for Debt Repayment (CADR).

 - Senior Subordinated Notes: Fixed non-amortizing structure with PIK/cash interest optionality.

Circular Reference Resolution: 
Accurately models the interdependency between interest expense, net income, and debt balances using Excel's iterative calculation engine.

Returns Analysis & Sensitivities: 
Calculates standard private equity return metrics (IRR and MoIC/Cash Return) with dynamic data tables sensitizing entry and exit multiples.

Sources & Uses Setup: 
Automated transaction funding structure bridging historical financials to the Pro Forma "Day 1" Balance Sheet.

 # Repository Structure
EA LBO.xlsx: The master financial model containing all linked schedules.

# SF Rent Control Data

I built this project to address something I felt was missing from the public data landscape in San Francisco: a simple rent-control boolean for every parcel. DataSF has done a fantastic job making public-sector data widely available — but I couldn’t find a dedicated dataset for rent control status. So, here we are.

## Inspiration

This project was inspired by a conversation with an older resident who wanted to know how many rent-controlled units might be demolished under Mayor Lurie’s recent family zoning plan. These housing plans are required by the State of California every eight years, and San Francisco’s Planning Commission approved this one on **September 11, 2025**, just ahead of the **January 31, 2026** state deadline.

## What This Project Does

This repository contains:

- **An RMarkdown file** that builds a database of rent-controlled parcels across San Francisco.
- **Visualizations** that break down:
  - The number and percentage of rent-controlled units and properties affected by the rezoning plan.
  - The breakdown of affected parcels by Supervisor District (using 2025 district boundaries).
- **Analysis** exploring:
  - What percentage of all units targeted by the plan are rent-controlled.
  - Insights into ongoing debates — such as whether the plan disproportionately targets rent-controlled housing.

## Why This Matters

There are competing narratives about rent control in San Francisco:
- **Progressive groups** often argue that these rezonings disproportionately target rent-controlled units, leading to displacement and higher housing costs.
- **YIMBY groups** counter that removing rent control restrictions can help alleviate pressures on the rental housing stock by allowing for more construction.

My goal is to provide objective, transparent data that anyone — activists, policymakers, or curious residents — can use to better understand what’s actually at stake.

## How to Use This Repo

1. Clone the repo.
2. Open the RMarkdown file (`SF-Rent-Control-Data.Rmd`) in RStudio.
3. Knit the file to generate:
   - A cleaned dataset of rent-controlled parcels.
   - Visualizations and summary statistics.

## Future Directions

I’d love to see:
- Additional layers of analysis, such as affordability or eviction data.
- Collaborations that help validate assumptions and refine the rent-control c


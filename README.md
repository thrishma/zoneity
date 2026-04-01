# Zoneity

> AI platform turning zoning regulations into structured, queryable data.

**[zoneity.app](https://zoneity.app/)**

Zoneity makes zoning law accessible. Instead of reading through hundreds of pages of PDFs, architects and builders get instant answers about what they can build on any plot — FAR limits, setbacks, permitted uses, and approval paths.

## The Problem

Zoning regulations are buried in complex PDFs, amended over years, and cross-referenced across multiple documents. An architect checking feasibility for a project in Bangalore has to manually cross-reference the BDA Master Plan, NBC guidelines, and multiple amendments — before they can even begin design.

## What Zoneity Does

- **Zone lookup** — identify the zone and land use for any plot by location
- **FAR/FSI calculation** — compute the exact floor area ratio based on road width, zone, and applicable amendments
- **Setback analysis** — calculate minimum setbacks and buildable envelope for a given plot
- **Multi-scenario comparison** — compare setback configurations to find the optimal build
- **NBC query** — search the National Building Code (1,200 pages) for relevant rules instantly
- **AI assistant** — ask natural language questions about what you can build, with site-specific context

## Who It's For

- Architects running feasibility studies on residential and commercial projects
- Builders and developers evaluating plots before acquisition
- Urban designers working across large areas

## Tech Stack

- **Frontend**: Next.js 14, Tailwind CSS, React-Leaflet
- **Database**: Supabase (Postgres + PostGIS)
- **AI**: Claude API — rule extraction, natural language queries
- **Data**: BDA RMP 2015 + Aug 2025 amendments, National Building Code (NBC)

## Status

Private beta — currently focused on Bangalore (BDA jurisdiction).

## Try It

[zoneity.app](https://zoneity.app/)
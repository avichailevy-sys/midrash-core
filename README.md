# MiDRASH Core

Integrated identifier-resolution and entity layer for the MiDRASH project —
crosswalking Cairo Genizah fragment identifiers across the Friedberg Genizah
Project (FGP) and the National Library of Israel (NLI).

## Current scope (Layer 1 — join crosswalk)

A browser-based viewer over a deduplicated crosswalk of **20,751 FGP join
fragments**, each resolved to its NLI identity (FL · IE · ALMA · shelfmark) and
enriched with its NLI/KTIV catalogue record (title, holding library, language,
date, dimensions).

- **78.4%** of fragments resolve to an NLI record.
- Join groups are preserved: each fragment lists its join partners.
- Page images load live from NLI via IIIF.

## Sources

- **FGP** unit-joins table (Friedberg Genizah Project)
- **Rosetta** full export (NLI) — image-level identifier backbone
- **KTIV / NLI MARC** catalogue — descriptive enrichment

## Roadmap

Layer 1 (identifier resolution) is the foundation for the wider MiDRASH Core
system: a normalized entity store feeding a join view, a search interface, and
an open API.

## Usage

Open `index.html`, or visit the deployed site. Click a fragment to see its
join group, catalogue record, and page images.

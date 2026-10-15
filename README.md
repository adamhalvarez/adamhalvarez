# Adam Alvarez

Analytics and operations at Agilent Technologies: metric governance, data validation, Qlik. Outside work I build small public records systems on one set of rails: scheduled Python pipelines, governed Postgres stores, and static read surfaces that rebuild themselves.

**Public here**

- **filings-ledger**: a Next.js read surface over a Postgres store of lobbying disclosures and federal contract awards. Change ledger, per entity pages and feeds, permalinks with cite blocks, CSV and JSON exports, and a methodology page that says what each number is and is not.
- **agenda-ledger**: a capture pipeline for local governing bodies (Legistar, Granicus, PrimeGov, and PDF directories) that stores every agenda and attachment with a verifiable hash chain, detects changes, and keeps all judgment in a human review lane. Tests per adapter, Supabase migrations.

**How the work runs**

Discovery step first, approval, then build, then a verified live run before anything merges. Curation stays human; the claim a curated row makes about its source is checked mechanically. Every scheduled run is gated by a self test that blocks publication when a check fails.

Other repos (the daily scanner, an events sampling lane, an operations cockpit, a live judging PWA, an iPad photo booth) are private; ask for a walkthrough.

linkedin.com/in/adamhalvarez

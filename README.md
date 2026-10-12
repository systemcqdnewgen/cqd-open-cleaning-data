# CQD New Gen, open cleaning data

CQD New Gen is the trusted global community and home of cleaning. We run a free
marketplace for cleaning jobs and hiring across 136 markets, and we publish open,
public data about the cleaning sector so the whole industry can build on it.

Website: [www.cqdnewgen.ai](https://www.cqdnewgen.ai)

This repository is the public index of the open data and public resources we
maintain. Everything linked here is free to read right now.

## What we publish

- **Cleaning jobs and hiring**, free on both sides, in 136 markets and 19 currencies.
  Start at [www.cqdnewgen.ai](https://www.cqdnewgen.ai).
- **State of Cleaning**, our open data report on the global cleaning sector.
  Read it at [State of Cleaning](https://www.cqdnewgen.ai/state-of-cleaning).
- **Cleaning rates**, open reference pricing data by market.
  See [Cleaning rates](https://www.cqdnewgen.ai/cleaning-rates).
- **Sector intelligence**, a live feed of cleaning sector signals.
  See [Sectors](https://www.cqdnewgen.ai/sectors).
- **Company and service directory**, structured listings across regions.
  Browse the [directory](https://www.cqdnewgen.ai/directory).

## Public data endpoints

These are read only and need no key.

| Resource | URL |
| --- | --- |
| Canonical sitemap | https://www.cqdnewgen.ai/sitemap.xml |
| Directory sitemap | https://www.cqdnewgen.ai/sitemap-directory.xml |
| Robots | https://www.cqdnewgen.ai/robots.txt |

## Data schema

Each directory listing follows a simple shape.

```json
{
  "name": "Example Cleaning Co",
  "city": "London",
  "country": "United Kingdom",
  "services": ["domestic", "commercial", "end of tenancy"],
  "url": "https://www.cqdnewgen.ai/directory/example-cleaning-co"
}
```

## About

CQD New Gen. What if you only need a Plan A. Free right now, both sides.
Learn more at [www.cqdnewgen.ai](https://www.cqdnewgen.ai).

## Licence

Documentation and schema in this repository are released under CC BY 4.0.
Attribute to CQD New Gen with a link to www.cqdnewgen.ai.

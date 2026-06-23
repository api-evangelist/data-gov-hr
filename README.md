# data.gov.hr (data-gov-hr)

data.gov.hr (Portal otvorenih podataka) is the national government open-data portal for Croatia, running **CKAN 2.9.9** and exposing the standard CKAN Action API over ~3,858 datasets.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/data-gov-hr/refs/heads/main/apis.yml)

## Type
- **kind:** government  ·  **software:** CKAN  ·  **version:** 2.9.9

## API
- **data.gov.hr CKAN Action API** — base `https://data.gov.hr/ckan/api/3/action`. [Docs](https://docs.ckan.org/en/latest/api/) · [Portal](https://data.gov.hr/en/)
- Live endpoint verified: `https://data.gov.hr/ckan/api/3/action/package_search` · ~3,858 datasets
- DCAT-AP feeds: `https://data.gov.hr/ckan/catalog.xml` · `https://data.gov.hr/ckan/catalog.rdf`
- **Note:** the CKAN API is mounted under the `/ckan/` path prefix; root-level CKAN URLs return the Vue SPA HTML, not JSON.

## Timestamps
- **Created:** 2026-06-23
- **Modified:** 2026-06-23

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com

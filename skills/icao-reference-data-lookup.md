---
name: icao-reference-data-lookup
description: 'Look up ICAO reference publications: location indicators (DOC 7910),
  operator 3-letter codes (DOC 8585), aircraft type designators (DOC 8643) and manufacturer
  lists.'
api: icao:icao-api-data-service
operations:
- getDoc7910
- getDoc8585
- getDoc8643
- getManufacturerList
- getManufacturerListUas
generated: '2026-10-20'
method: generated
---

# Look up ICAO reference publications: location indicators (DOC 7910), operator 3-letter codes (DOC 8585), aircraft type designators (DOC 8643) and manufacturer lists.

1. Call `getDoc7910` (GET) on https://dataservices.icao.int/api with `api_key` (query) or a Bearer token, and `format=json`.
2. Call `getDoc8585` (GET) on https://dataservices.icao.int/api with `api_key` (query) or a Bearer token, and `format=json`.
3. Call `getDoc8643` (GET) on https://dataservices.icao.int/api with `api_key` (query) or a Bearer token, and `format=json`.
4. Call `getManufacturerList` (GET) on https://dataservices.icao.int/api with `api_key` (query) or a Bearer token, and `format=json`.
5. Call `getManufacturerListUas` (GET) on https://dataservices.icao.int/api with `api_key` (query) or a Bearer token, and `format=json`.

All operations are read-only and consume calls from the key's free-trial or Booster pack quota; check parameters in openapi/icao-openapi.yml.

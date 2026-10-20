---
name: icao-state-safety-oversight
description: 'Read ICAO Member State safety oversight data: USOAP effective implementation
  by state and year, USOAP activities and progress, and state safety margins.'
api: icao:icao-api-data-service
operations:
- getIcaoMemberStates
- getEiStats
- getAggregatedEiTrendStats
- getUsoapActivityList
- getProgressStats
- getSafetyMarginStats
generated: '2026-10-20'
method: generated
---

# Read ICAO Member State safety oversight data: USOAP effective implementation by state and year, USOAP activities and progress, and state safety margins.

1. Call `getIcaoMemberStates` (GET) on https://dataservices.icao.int/api with `api_key` (query) or a Bearer token, and `format=json`.
2. Call `getEiStats` (GET) on https://dataservices.icao.int/api with `api_key` (query) or a Bearer token, and `format=json`.
3. Call `getAggregatedEiTrendStats` (GET) on https://dataservices.icao.int/api with `api_key` (query) or a Bearer token, and `format=json`.
4. Call `getUsoapActivityList` (GET) on https://dataservices.icao.int/api with `api_key` (query) or a Bearer token, and `format=json`.
5. Call `getProgressStats` (GET) on https://dataservices.icao.int/api with `api_key` (query) or a Bearer token, and `format=json`.
6. Call `getSafetyMarginStats` (GET) on https://dataservices.icao.int/api with `api_key` (query) or a Bearer token, and `format=json`.

All operations are read-only and consume calls from the key's free-trial or Booster pack quota; check parameters in openapi/icao-openapi.yml.

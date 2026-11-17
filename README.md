# Databricks NYC Taxi + Weather Pipeline

A data pipeline on Databricks Free Edition that joins NYC taxi trips (Jan-Feb 2016)
with hourly weather from the Open-Meteo REST API, organized in three layers.

## Layers

| Layer | Schema | What it holds |
|-------|--------|---------------|
| Raw | `raw` | Data as received (taxi trips, raw weather JSON) |
| Clean | `clean` | Cleaned trips, hourly weather, and the joined table |
| Analytics | `analytics` | Tables that answer specific questions |

## Questions answered

1. How do rain and temperature affect trip count and fares?
2. How does demand change across hours of the day?

## Status

In progress. Architecture diagram and run instructions coming soon.

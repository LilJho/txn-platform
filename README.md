# txn-platform

Lending transaction data platform: synthetic **loans**, **loan charges** and **loan discounts**,
ingested to S3, transformed with pandas, loaded to a warehouse, and scored for anomalies.

## Setup

    python3 -m venv .venv && source .venv/bin/activate
    pip install -e ".[dev]"
    cp .env.example .env
    pytest

## Branches

`feature/*` -> `dev` -> `uat` -> `main`

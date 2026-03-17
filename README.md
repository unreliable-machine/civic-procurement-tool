# Civic Procurement Intelligence Tool

Open WebUI tool for searching federal contracts (SAM.gov), registered entities, and awards (USAspending).

Part of the [Civic Intelligence Platform](https://github.com/unreliable-machine/civic-tools) for [Change Agent AI](https://thechange.ai).

## Installation

1. Open your Open WebUI instance → **Admin Panel** → **Tools** → **+**
2. Paste the contents of `civic_procurement.py`
3. Save → configure Valves (gear icon)

## Valves

| Valve | Value |
|-------|-------|
| `GOVCON_API_URL` | `https://govcon-api-production.up.railway.app` |
| `GOVCON_API_KEY` | Your GOVCON API key |
| `TIMEOUT` | `30` |

## Methods

- `search_opportunities`
- `get_opportunity`
- `search_entities`
- `get_entity`
- `search_awards`

## Test

```
Search for cybersecurity contract opportunities
```

## Backend API

`govcon-api`

## Related

- [civic-tools](https://github.com/unreliable-machine/civic-tools) — umbrella repo with all 7 civic tools
- [civic-finance](https://github.com/unreliable-machine/civic-finance) — campaign finance microservice
- [civic-irs](https://github.com/unreliable-machine/civic-irs) — IRS 990 filings microservice
- [govcon-intelligence](https://github.com/unreliable-machine/govcon-intelligence) — procurement, grants, legislators, courts

## License

MIT

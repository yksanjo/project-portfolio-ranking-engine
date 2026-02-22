# Project Portfolio Ranking Engine

Rank portfolio projects by timing, exposure, and traction.

## Priority Metadata

- ID: 196
- Domain: ai-growth
- TTE (days): 3
- Exposure score: 9/10
- Wave: 1
- Priority score: 8.20

## Phase-1 Build

1. Risk/exposure assessment API.
2. Deterministic launch planning endpoint.
3. Domain-tailored threat and rollout docs.
4. CI test gate and local runnable service.
5. Spatial 3D starter (for spatial projects).

## Run

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -e .[dev]
make test
make run
```

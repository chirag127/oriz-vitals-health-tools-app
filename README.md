# Oriz Vitals — Health tools

> Health and fitness calculators — BMI, BMR, TDEE, body fat, macros, heart-rate zones, and more.

**Live at**: <https://health.oriz.in> · **Status**: scaffold

## What this is

Vitals computes the numbers that describe your body and training — without ever shipping them off your device. All formulas evaluate locally in the browser; no personal health information is stored or transmitted.

## Per-feature inventory

| Feature                     | Status     |
| --------------------------- | ---------- |
| (tools not yet implemented) | 📜 planned |

## App-specific env vars

None beyond the family-wide set at `templates/.env.example`.

## Local dev

```bash
# from the workspace root (c:/D/oriz)
pnpm -F oriz-vitals-health-tools-app dev
```

## Knowledge

See [`./knowledge/`](./knowledge/) for app-specific decisions, runbooks, and services. Family rules / decisions / architecture live at the master repo's [`knowledge/`](../../../../knowledge/).

## License

Source-available, all rights reserved. See master [`LICENSE`](../../../../LICENSE) — same terms across the family.

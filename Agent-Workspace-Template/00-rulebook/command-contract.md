# Command Contract (Template)

## Canonical commands
- `run monthly-report`
- `run weekly-summary`
- `run ad-hoc --start YYYY-MM-DD --end YYYY-MM-DD`

## Default assumptions
- Default period: current month.
- Default timezone: add timezone here.
- Default output path: `08-output/reports/`.

## Accepted arguments
| Argument | Type | Required | Default | Description |
|---|---|---|---|---|
| `--period` | string | no | current-month | Reporting period key |
| `--start` | date | no | null | Explicit range start |
| `--end` | date | no | null | Explicit range end |
| `--format` | string | no | markdown | Output format |

## Validation rules
- Add rule: conflicting arguments handling.
- Add rule: invalid date handling.
- Add rule: empty data handling.

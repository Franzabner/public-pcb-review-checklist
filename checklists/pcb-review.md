# PCB Review Checklist

Status: Public scaffold. Release status: scaffolded. License pending human review.

## Review Metadata

| Field | Value |
| --- | --- |
| Project | synthetic or reviewed public-safe project only |
| Review type | documentation review |
| Artifact status | Planned / Scaffolded / Human Review Required |
| Review requirement | Human Review Required |
| Date | Human Review Required |

## Checklist

| Area | Review questions |
| --- | --- |
| Scope | Is the board purpose stated without exposing private product context? |
| Power | Are voltage domains, protection assumptions, and current limits documented at a public-safe level? |
| Signal | Are signal classes, connectors, and interface expectations documented without exact sealed pin maps? |
| Layout | Are layout screenshots public-safe and non-reconstructive if included? |
| BOM | Is BOM detail excluded unless explicitly approved? |
| Firmware interface | Are firmware dependencies described without private protocols or credentials? |
| Manufacturing | Are manufacturing claims avoided unless evidence and approval exist? |
| Boundaries | Are production source, customer data, and sealed IP excluded? |

## Severity

| Severity | Meaning |
| --- | --- |
| note | Documentation improvement. |
| concern | Needs review before public use. |
| blocker | Must not be public until corrected. |

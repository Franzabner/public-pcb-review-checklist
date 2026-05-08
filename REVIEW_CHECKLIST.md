# Review Checklist

Status: Public scaffold. Release status: scaffolded. License pending human review.

## Required Files

- [ ] `README.md` explains PCB review proof, KiCad-adjacent judgment, and boundary scope.
- [ ] `README.md` identifies `franzabner-proof-stack` as the public scaffold proof navigation layer.
- [ ] `STATUS.md` uses honest current labels: Public scaffold, Scaffolded, Planned, Draft, and Human Review Required.
- [ ] `PUBLIC_BOUNDARY.md` separates public-safe checklist material from private or sealed PCB artifacts.
- [ ] `ROADMAP.md` does not imply release or production use.
- [ ] `CLAIMS.md` blocks certification, sign-off, manufacturing approval, live Upwork, and client claims.
- [ ] `LICENSE_DECISION.md` records that no license has been selected.
- [ ] `checklists/pcb-review.md` uses synthetic or reviewed public-safe inputs only.
- [ ] `templates/review-report.md` remains a report template and does not imply real client review.
- [ ] `examples/synthetic-review/` contains synthetic examples only.

## Electrical Boundary Review

- [ ] No production schematic, layout, routing, BOM, Gerber, exact pin map, board source, private library, or manufacturing package is present.
- [ ] No production firmware dependency, private protocol, device credential, customer wiring, or product-specific integration map is present.
- [ ] No customer file, client result, site detail, employer-sensitive material, Foundation material, or sealed YOSO-YAi source is present.
- [ ] No certification, safety, compliance, engineering sign-off, or manufacturing approval claim is present.

## External Reference Gate

- [ ] Human review required before release claims, license changes, Upwork reuse, or external references.

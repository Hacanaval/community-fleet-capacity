# Exposure Report — Community Fleet Capacity

> Date: 2026-09-24  
> Project: community-fleet-capacity  
> Checker: rg with sensitive patterns

## Files checked

- `README.md`
- `assets/architecture.mmd`
- `assets/ops-dashboard-mockup.html`
- `assets/ops-dashboard-mockup.png` (visual inspection only)
- `assets/mobile-agenda-mockup.html`
- `assets/mobile-agenda-mockup.png` (visual inspection only)

## Patterns checked

- `coordinadora`
- `cm-analitica`
- `ext_`
- `dwh_`
- `public_`
- `novedad`
- `sigo`
- `890904713`
- `@coordinadora\.com`
- `hcanaval@coordinadora\.com`
- revision-style hashes
- long alphanumeric identifiers
- `projects/[a-z0-9-]+`

## Result

No sensitive patterns found in any text file.

## Visual assets reviewed

- `assets/ops-dashboard-mockup.png` and `assets/mobile-agenda-mockup.png` contain only fictional data:
  - fake driver names (Ana Martinez, Carlos Lopez, Sofia Ruiz, Diego Herrera)
  - fake zone names (Portville North, Portville Downtown, Riverside)
  - generic capacity numbers and dates
- No real depot identifiers, driver IDs, phone numbers, or capacity targets.

## Conclusion

Safe to publish.

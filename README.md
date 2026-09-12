# elightric

Pilot pages for a California rooftop solar + storage health check.

| File | What it is |
|---|---|
| `index.html` | The five-field check. All computation happens in the visitor's browser; nothing is uploaded. Hand-off is a `mailto:` the visitor sends themselves. |
| `battery-guide.html` | How to put a Tesla / Enphase / SolarEdge battery into backup-only mode. Paths verified against vendor documentation, 2026-09. |
| `data-use.html` | What happens to a PG&E usage export, and how to have it deleted. |

No backend, no build step, no dependencies. The only outbound request any page makes
is to Google Fonts for the typefaces.

Pilot inbox is set in `index.html` — search for `const CONTACT`.

Dollar figures are modelled on **PG&E** 2026 rates and NEM 3.0 hourly export values.
They do not apply to SCE or SDG&E territory.

# AITechNext

Website for **AITechNext** — the AI consultancy & implementation arm of [TechNext](https://technext.asia), focused on making SMEs AI-native on the Odoo backbone.

## Pages

| Path | Audience | Contents |
|---|---|---|
| `index.html` | Internal (leadership) | **Business Plan Dossier v1.0** — one long scrollable page with a collapsible sidebar: executive summary, market analysis, 17-category / 142-service catalog, flagship practices (AI × Odoo, AI × Sales & Marketing), delivery methodology, competitive landscape, 12 business models & billing strategies, GTM, org chart, governance, roadmap, KPIs, and risk register. |
| `clientfacing/index.html` | Public (prospects) | Client-facing marketing site — "We help companies become AI-native": the problem, the five partner roles, services, AI × Odoo flagship, operating assumptions, proof blueprints, process, and FAQ. |
| `ops/index.html` | Internal (Manager & CAIO) | **Ops Playbook** — the 10-factor implementation decision matrix with an interactive scorer, the ten priority services scored and detailed (incl. the AI-adoption interview guide & checklist), suggested build sequence, and the weekly/monthly decision cadence. |

## Notes

- **Zero dependencies.** Both pages are single-file, self-contained HTML (inline CSS/JS/SVG). No build step, no external assets — deployable on GitHub Pages or any static host as-is.
- **Mobile-optimized.** Sidebar becomes an off-canvas drawer; all tables and diagrams scroll within their own containers; tested at 390 px and 1440 px.
- **Print-friendly.** The dossier expands all collapsed sections automatically when printed.
- The dossier is an internal working draft (marked confidential). Do not deploy `index.html` to a public host together with the client-facing page without moving it behind access control.
- Market figures in §03 are directional estimates from public research — refresh before external use.

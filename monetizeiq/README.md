# MonetizeIQ

**Price the work, not the seat.**

MonetizeIQ is a pricing decision cockpit for AI and SaaS companies moving customers from seat pricing to credit, hybrid and outcome pricing. It shows, for one book of customers, what each model does to revenue, gross margin, token cost, forecast confidence and every customer's bill. It also says which workflows are ready for outcome pricing at all.

Live demo: https://hithakishore-all.github.io/monetizeiq/

Full app (web console, Slack bot, Postgres, tests): https://github.com/hithakishore-all/monetizeiq

All companies, people and figures are fictional. Defaults are anchored to public 2026 benchmarks, linked in the app's footer.

## What's inside

| Tab | What it does |
| --- | --- |
| Market map | 12 AI categories across industries (support, service intelligence, revenue intelligence, AI SDR, IT, insurance claims, healthcare revenue cycle, clinical documentation, legal, finance operations, coding, marketing). Each shows its outcome unit, how it is measured, signal source, validation rule, audit trail, market pricing today and a readiness score. |
| Pricing cockpit | One book of 96 fictional accounts priced as seat, credit (per action, token pass-through or customer's own model key), hybrid and outcome. Revenue bridge, forecast range, margin curve across model prices, book heatmap, account audit trail and rule-based what-if questions. A readiness gate blocks pure outcome pricing below 60. |
| Outcome lab | Turns what the AI changes (for example fewer parts per job and fewer avoidable dispatches) into value created, the vendor's fee and what the customer keeps, with the evidence an invoice needs. |
| Scenarios | Ten demo records, each proving one behavior: hero run, renewal risk, a gate that says no, a token pass-through trap, a dispute-heavy window, a clean run, a customer's own model key, stale data, missing data and token exposure. |

## How the numbers work

- Cost to serve per task = tokens per task × model price + tool and infrastructure cost.
- Per-action credits: $0.10 per agent action. Customer's own key: $0.03 platform fee per action; the customer pays the model provider.
- Outcome revenue counts only verified, undisputed outcomes after the verification window.
- Hybrid = the larger of the platform fee and outcome charges, capped at a multiple of today's seat bill.
- Accounts with no outcome signal are shown as unknown and excluded from totals.
- Ask-the-pane answers are rule-based over the same engine, not a live model.

## Run it

It is one self-contained HTML file. Open `index.html` in a browser; no install or accounts needed.

## License

Apache License 2.0.

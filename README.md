# Enterprise AI, Agentic Systems & Product Innovation

Live at **https://hithakishore-all.github.io**: independent personal projects. Each one is my own idea, prototyped and built end to end to explore it. Each has a live demo that runs in the browser on synthetic data, and a case study covering the problem, users, workflow, architecture, trade-offs, evaluation and business value.

| Domain | Project | Demo | Case study | Code |
| --- | --- | --- | --- | --- |
| Sales & GTM Intelligence | **GTM Orbit** (flagship) · agentic go-to-market | [demo](https://hithakishore-all.github.io/gtm-orbit/) | [case study](https://hithakishore-all.github.io/work/gtm-orbit/) | [repo](https://github.com/hithakishore-all/gtm-orbit) |
| | **Account Focus** · daily account prioritization inside GTM Orbit | [demo](https://hithakishore-all.github.io/account-focus/) | [case study](https://hithakishore-all.github.io/work/account-focus/) | [repo](https://github.com/hithakishore-all/account_focus) |
| | **SalesLore** · keeps a departing AE's account knowledge for the next seller | [demo](https://hithakishore-all.github.io/saleslore/) | [case study](https://hithakishore-all.github.io/work/saleslore/) | [repo](https://github.com/hithakishore-all/SalesLore) |
| Enterprise AI & Decision Intelligence | **Conviction AI** · investment intelligence for VC and PE | [demo](https://hithakishore-all.github.io/conviction-ai/) | [case study](https://hithakishore-all.github.io/work/conviction-ai/) | [repo](https://github.com/hithakishore-all/conviction-ai) |
| | **Meridian** · governed B2B agent marketplace | [demo](https://hithakishore-all.github.io/meridian/) | [case study](https://hithakishore-all.github.io/work/meridian/) | [repo](https://github.com/hithakishore-all/Meridian) |
| AI Monetization & Business Workflows | **MonetizeIQ** · seat to credit, hybrid and outcome pricing | [demo](https://hithakishore-all.github.io/monetizeiq/) | [case study](https://hithakishore-all.github.io/work/monetizeiq/) | [repo](https://github.com/hithakishore-all/MonetizeIQ) |
| | **Fieldwise** · guided field-service resolution | [demo](https://hithakishore-all.github.io/fieldwise/) | [case study](https://hithakishore-all.github.io/work/fieldwise/) | [repo](https://github.com/hithakishore-all/fieldwise) |
| Consumer Product Innovation | **Readaroo** · family library app with Stripe metering | [demo](https://hithakishore-all.github.io/readaroo/) | [case study](https://hithakishore-all.github.io/work/readaroo/) | [repo](https://github.com/hithakishore-all/readaroo) |

## Site layout

- `index.html`: the homepage, with projects grouped by domain
- `work/<project>/`: one case study per project, all built from the same template
- `assets/site.css`: shared styles for the homepage and case studies
- `<project>/`: self-contained demo pages (unchanged). GTM Orbit, Conviction AI and Readaroo demos are served from their own repositories.
- `img/`: clips, walkthrough videos and posters

Plain static HTML and CSS with no build step, served by GitHub Pages.

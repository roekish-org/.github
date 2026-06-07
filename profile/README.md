<div align="center">

# Roekish

### Odoo, sans angle mort.

**Open Odoo implementation knowledge for France & the EU.**
We publish the playbooks, templates, and tooling we use on real client projects — for free.

[![Website](https://img.shields.io/badge/roekish.com-0F2230?style=flat-square)](https://roekish.com)
[![Odoo 17 | 18 | 19](https://img.shields.io/badge/Odoo-17%20%7C%2018%20%7C%2019-714B67?style=flat-square)](#)
[![Region: France / EU](https://img.shields.io/badge/Region-France%20%2F%20EU-C75B39?style=flat-square)](#)
[![License: MIT / CC BY 4.0](https://img.shields.io/badge/License-MIT%20%2F%20CC%20BY%204.0-2E7D5B?style=flat-square)](#)

</div>

---

## Why this organization is public

Most Odoo implementation know-how stays locked inside agencies. We're doing the opposite.

We are [**Roekish**](https://roekish.com) — a France/EU-based Odoo implementation agency. Our bet is simple: **the agency that shows its work earns the trust.** So we open-source the scoped playbooks, reusable templates, dev tooling, and integrations we build for clients.

- **Buyers** can see exactly what an Odoo project involves *before* signing anything.
- **In-house teams** can run a standard rollout themselves, with honest hour and price anchors.
- **Engineers & other agencies** can fork, adapt, and contribute back.

If our public material doesn't reproduce against a fresh Odoo instance, neither does our paid work. That's the test we hold ourselves to.

## Start here

| Repository | What it is | License |
|---|---|---|
| [**Odoo-Implementation-Playbooks**](https://github.com/roekish-org/Odoo-Implementation-Playbooks) | Practitioner-grade, end-to-end playbooks: inventory, FR accounting, migrations, discovery templates. Scope, menu paths, validation checklists, and real hour/price anchors. | CC BY 4.0 |
| [**roekish-addons**](https://github.com/roekish-org/roekish-addons) | Reference custom Odoo 18 modules — French legal invoice mentions (`roe_l10n_fr_invoice_mentions`) and a conventions skeleton — with the Dockerised Odoo 18 + Postgres dev stack, an addon scaffolder, and CI that installs/upgrades each module. | LGPL-3 |
| [**twenty-app-cal-bridge**](https://github.com/roekish-org/twenty-app-cal-bridge) | A native [Twenty CRM](https://twenty.com) app connecting Cal.com bookings to CRM records via signed webhooks. | MIT |

> More repos are published as we go — migration runbooks and more reference modules (Factur-X / e-invoicing helpers). Watch this org to follow along.

## What you'll find here (and what's coming)

- ✅ **Implementation playbooks** — inventory, French accounting (l10n_fr / PCG), Sage → Odoo migration.
- ✅ **Reusable templates** — discovery questionnaire, UAT sign-off, go-live checklist.
- ✅ **Self-hosted Odoo dev stack** — Dockerised, pinned versions, reproducible in minutes (ships in [`roekish-addons`](https://github.com/roekish-org/roekish-addons)).
- ✅ **Reference custom modules** — French legal invoice mentions, with more (Factur-X / e-invoicing helpers) to come — see [`roekish-addons`](https://github.com/roekish-org/roekish-addons).
- 🔜 **Migration runbooks** — Sage, EBP, Cegid → Odoo, with data-mapping templates.

## How we work

Everything we publish follows three rules:

1. **Honest** — no marketing language inside the playbooks themselves.
2. **Reproducible** — every snippet runs against a stated Odoo version (17.0 / 18.0 / 19.0).
3. **Region-aware** — France/EU specifics (GDPR, l10n_fr, e-invoicing) are flagged explicitly.

## Contributing

Issues, corrections, and PRs are welcome on any repo. Found something that doesn't reproduce? Open an issue with your Odoo version, a screenshot, and what you saw — that's the most useful contribution there is.

## Want us to do it for you?

We turn these playbooks into delivered projects. Reach out: **hello@roekish.com** · [roekish.com](https://roekish.com)

<div align="center">
<sub>Roekish — Odoo implementation, France & EU. Built in the open.</sub>
</div>

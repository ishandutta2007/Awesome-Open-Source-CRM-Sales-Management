# Awesome-Open-Source-CRM-Sales-Management

# Awesome Open Source CRM & Sales Management

> A curated list of top Open Source CRM and Sales Management platforms — both SaaS/Hosted commercial solutions with free tiers and fully open-source alternatives for managing leads, pipelines, and customer relationships.
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [HubSpot Free CRM](#hubspot-free-crm)
  - [Zoho CRM](#zoho-crm)
  - [Vtiger Cloud](#vtiger-cloud)
  - [Bitrix24](#bitrix24)
- [Open-Source Software](#-open-source-software)
  - [Twenty](#twenty)
  - [SuiteCRM](#suitecrm)
  - [EspoCRM](#espocrm)
  - [Odoo CRM](#odoo-crm)
  - [Frappe CRM](#frappe-crm)
  - [Krayin](#krayin)
  - [Dolibarr](#dolibarr)
  - [ERPNext](#erpnext)
  - [Horilla](#horilla)
  - [BottleCRM](#bottlecrm)
  - [NextCRM](#nextcrm)
  - [OroCRM](#orocrm)
  - [CiviCRM](#civicrm)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted CRM platforms with free tiers. These are not open-source but are included as reference points for feature comparison.

### HubSpot Free CRM
**Type:** Free CRM with marketing and sales tools
HubSpot offers a permanently free CRM tier with contact management, deal tracking, and email integration. It is the most widely adopted free CRM, with paid tiers scaling into full marketing, sales, and service hubs. **Trade-off:** Advanced automation, reporting, and AI features require paid plans.

### Zoho CRM
**Type:** CRM with a free tier for small teams
Zoho CRM offers a free edition for up to 3 users, with paid tiers adding scoring rules, sales forecasting, Blueprint process design, and anomaly detection [from previous context]. It integrates with the broader Zoho suite. **Trade-off:** The free tier is limited in users and advanced features.

### Vtiger Cloud
**Type:** CRM with both cloud and open-source editions
Vtiger offers a cloud CRM alongside its open-source edition. The open-source edition is based on the Mozilla Public License (VPL 1.1), with core features including contact management, pipeline management, help desk, inventory, reporting, and multichannel communication [citation:5][citation:11]. The cloud edition adds managed hosting and support. **Note:** The open-source edition is not the same as a cloud-free edition [citation:11].

### Bitrix24
**Type:** CRM with collaboration tools and a free tier
Bitrix24 combines CRM with team collaboration (chat, video, tasks, Drive). The free tier includes unlimited deals and invoices, 5 GB storage, and CoPilot AI [from previous context]. **Trade-off:** Free accounts are deleted after inactivity.

---

## 🟩 Open-Source Software

Self-hosted, community-driven CRM and sales management platforms. All listed projects offer source code you can deploy on your own infrastructure.

### Twenty
**Stack:** TypeScript / NestJS / React / PostgreSQL / Redis | **License:** AGPL-3.0 (core)
Twenty is positioned as the **#1 open-source CRM**, built as a modern alternative to Salesforce and HubSpot . Key capabilities include customizable objects and fields, Kanban and table views, custom roles and permissions, workflow automation with triggers and actions, and email/calendar/file integration . It has 28,000+ GitHub stars and active development. The stack uses NestJS with BullMQ, PostgreSQL, and Redis, with React on the frontend . A free plan is available, with paid tiers from $9/mo [citation:1]. **Trade-off:** Enterprise features are gated to commercial licensing.
**Best for:** Teams wanting a modern, developer-friendly CRM they can self-host and extend as code.

### SuiteCRM
**Stack:** PHP / MySQL | **License:** AGPL-3.0
SuiteCRM is the most established open-source CRM, forked from SugarCRM Community Edition and maintained by SalesAgility [citation:3]. Key features include sales automation, marketing automation, workflow, reporting, and a REST API [citation:3]. Gartner reviewers highlight its **extensibility** as a major strength—"you can see and modify anything in the product" [citation:3]. It is a direct alternative to Salesforce, SAP, Microsoft Dynamics, and Oracle [citation:3]. A free plan is available, with paid plans from £50/mo [citation:1]. **Trade-off:** The codebase is older with a dated UI compared to modern alternatives.
**Best for:** Organizations wanting a proven, feature-rich enterprise CRM with deep customization and a large community.

### EspoCRM
**Stack:** PHP / MySQL/PostgreSQL | **License:** AGPL-3.0
EspoCRM is a fully customizable open-source CRM with a single-page frontend and REST API [citation:7]. Users consistently praise its **ease of customization** via the Entity Manager, which allows creating custom fields and entities without coding [citation:4]. Key features include accounts, contacts, opportunities, activities, campaigns, workflows, and project management with Gantt views [citation:4]. It is rated 8.8/10 in a 2026 comparison of 242 CRM tools [citation:1]. **Trade-off:** Some users note paid packages are now sold separately, and upgrades can require command-line work .
**Best for:** Small to mid-sized businesses wanting a genuinely customizable CRM that fits their exact process rather than forcing them into a fixed workflow.

### Odoo CRM
**Stack:** Python / PostgreSQL | **License:** LGPL-3.0 (Community)
Odoo CRM is part of the broader Odoo ERP suite, ranked **#1 in a 2026 comparison of 242 CRM tools (9.5/10)** [citation:1]. The Community edition is 100% free and open-source, with access to 40,000+ community apps and full PostgreSQL data ownership [citation:6]. CRM features include sales pipelines, lead management, email integration, and reporting. **Trade-off:** Odoo is a full ERP—adopting CRM means adopting the broader platform, with significant configuration effort.
**Best for:** Organizations wanting CRM integrated with finance, inventory, and manufacturing in a single open-source ERP.

### Frappe CRM
**Stack:** Python / Frappe Framework / Vue | **License:** GPL-3.0
Frappe CRM is a modern CRM built on the Frappe framework (same ecosystem as ERPNext), ranked **#3 in sales force automation (7.3/10)** [citation:8]. It provides lead and deal management, email integration, telephony, and a customizable desk interface [citation:7]. The Frappe ecosystem offers a path to ERPNext for organizations wanting integrated ERP and CRM. **Trade-off:** Requires the Frappe/ERPNext stack.
**Best for:** Teams already in or considering the Frappe/ERPNext ecosystem wanting CRM integrated with broader business operations.

### Krayin
**Stack:** PHP / Laravel | **License:** MIT
Krayin is a customer, lead, and sales management platform built with Laravel [citation:7]. The **MIT license is permissive** for commercial modifications, making it attractive for teams wanting to build on top of a CRM rather than just use it. **Trade-off:** Smaller ecosystem and community than SuiteCRM or EspoCRM.
**Best for:** Laravel developers and teams wanting a permissively licensed, customizable CRM foundation.

### Dolibarr
**Stack:** PHP / MySQL | **License:** GPL-3.0
Dolibarr is a modular ERP and CRM for small businesses and foundations [citation:7]. CRM features include contacts, leads, opportunities, and activity tracking, alongside invoicing, inventory, and HR modules. **Trade-off:** More of an ERP with CRM included than a dedicated sales CRM.
**Best for:** SMBs wanting an all-in-one ERP + CRM in a single self-hosted package.

### ERPNext
**Stack:** Python / Frappe Framework / MariaDB | **License:** GPL-3.0
ERPNext is an ERP with CRM, sales, accounting, inventory, and manufacturing modules [citation:7]. Like Odoo, it is a full business suite with CRM as one component. **Trade-off:** Significant configuration and operational overhead.
**Best for:** Organizations wanting a complete open-source ERP with CRM functionality included.

### Horilla
**Stack:** Python / Django | **License:** LGPL-2.1
Horilla is an open-source CRM ranked **#1 in sales force automation (8.0/10)** [citation:8]. It runs on Linux, Windows, macOS, Android, iOS, and the web, with self-hosting and API access [citation:8]. It includes CRM, HR, and recruitment modules. **Trade-off:** Smaller community and ecosystem than SuiteCRM or EspoCRM.
**Best for:** Teams wanting a modern Django-based CRM with HR integration and mobile support.

### BottleCRM
**Stack:** Python / Django / SvelteKit / Flutter | **License:** MIT
BottleCRM is a free, open-source, self-hosted, multi-tenant CRM with sales, support tickets, and invoicing in one application [citation:13]. It includes a **native Flutter mobile app** and PostgreSQL Row-Level Security for tenant isolation. **Trade-off:** Newer project with a smaller community.
**Best for:** Teams wanting an MIT-licensed CRM with native mobile apps and built-in support tooling.

### NextCRM
**Stack:** TypeScript / Next.js | **License:** MIT
NextCRM is a CRM with projects, invoicing, and documents built with Next.js [citation:7]. It combines CRM with light project management and document handling. **Trade-off:** Younger project than established alternatives.
**Best for:** Teams wanting a Next.js-based CRM with project and invoice features.

### OroCRM
**Stack:** PHP / Symfony | **License:** OSL-3.0
OroCRM is a CRM for marketing, sales, and customer service built on Symfony [citation:7]. It is designed for flexibility and multi-channel integration, with a robust API. **Trade-off:** Heavier and more complex than simpler CRMs.
**Best for:** Enterprises and developers wanting a Symfony-based, highly extensible CRM platform.

### CiviCRM
**Stack:** PHP / MySQL | **License:** AGPL-3.0
CiviCRM is a constituent relationship management system for nonprofits, covering contacts, donations, memberships, events, and email [citation:7]. It is the leading open-source CRM for the nonprofit sector. **Trade-off:** Not designed for commercial sales pipelines.
**Best for:** Nonprofits and membership organizations needing donor and constituent management.

---

## 📊 Comparison at a Glance

| Software | License | Stack | Multi-Tenant | Mobile App | Self-Hosted | Best For |
|----------|---------|-------|--------------|------------|-------------|----------|
| **HubSpot Free** | Proprietary | Cloud | ✅ | ✅ | ❌ | Free start + growth path |
| **Zoho CRM** | Proprietary | Cloud | ✅ | ✅ | ❌ | 3 free users + automation |
| **Twenty** | AGPL-3.0 | TypeScript/NestJS | (Check) | ❌ | ✅ | Modern Salesforce alternative |
| **SuiteCRM** | AGPL-3.0 | PHP/MySQL | (Check) | (Limited) | ✅ | Proven enterprise OSS |
| **EspoCRM** | AGPL-3.0 | PHP/MySQL | (Check) | ❌ | ✅ | Customizable + project tools |
| **Odoo CRM** | LGPL-3.0 | Python/Postgres | (Check) | ✅ | ✅ | Full ERP + CRM |
| **Frappe CRM** | GPL-3.0 | Python/Frappe | (Check) | ❌ | ✅ | ERPNext ecosystem |
| **Krayin** | MIT | PHP/Laravel | (Check) | ❌ | ✅ | Permissive license |
| **Horilla** | LGPL-2.1 | Python/Django | (Check) | ✅ | ✅ | CRM + HR |
| **BottleCRM** | MIT | Django/Flutter | ✅ (RLS) | ✅ Flutter | ✅ | MIT + mobile + support |
| **CiviCRM** | AGPL-3.0 | PHP/MySQL | (Check) | ❌ | ✅ | Nonprofits |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source CRM or sales management tool that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source.

**Note on the open-source ecosystem:** The open-source CRM landscape is **led by Twenty** as the most modern developer-friendly option, explicitly positioned as the #1 open-source CRM with a clean SaaS-like interface and customizable data model . **SuiteCRM** remains the most established enterprise-grade option with deep customization and a large community [citation:3], while **EspoCRM** is praised for its balance of customization and usability, particularly by small and mid-sized businesses [citation:4]. **Odoo CRM** and **Frappe CRM** serve organizations wanting CRM integrated with broader ERP functionality [citation:6][citation:7]. For teams prioritizing permissive licensing or mobile-first experiences, **Krayin** (MIT) and **BottleCRM** (MIT, native Flutter app) offer compelling alternatives. No single open-source project fully replicates HubSpot's marketing-sales-service breadth, but these tools cover the core lead, pipeline, and customer management workflows comprehensively for self-hosted deployments.

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐

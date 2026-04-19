<div align="center">
  <img src="stackprice_logo.png" alt="StackPrice — Know what your stack costs" width="40%%" />

  <h1>StackPrice</h1>
  <p><strong>Know what your stack costs.</strong></p>
  <p>
    Compare pricing across every layer of your tech stack — security, cloud,
    AI, databases, dev tools, and more. No sign-up. No backend. Just numbers.
  </p>

  ![License](https://img.shields.io/badge/license-MIT-blue)
  ![Built with](https://img.shields.io/badge/built%20with-vanilla%20HTML%2FJS-lightgrey)
  ![Last updated](https://img.shields.io/badge/data%20updated-Q2%202026-green)
</div>

---

## Table of Contents

- [Overview](#overview)
- [Sections](#sections)
- [From Scratch Builder](#from-scratch-builder)
- [Security Packages](#security-packages)
- [Cloud Hosting](#cloud-hosting)
- [AI Pricing](#ai-pricing)
- [Stack Builder](#stack-builder)
- [Databases](#databases)
- [Features](#features)
- [Running Locally](#running-locally)

---

## Overview

StackPrice is a single-file, client-side pricing comparison tool for the modern
tech stack. Every calculation runs in the browser — no server, no tracking,
no accounts required. Open the file and start comparing.

It covers over 200 tools across security, cloud infrastructure, AI APIs,
developer tooling, databases, communications, and virtualization. Each section
includes sort controls, card and table views, CSV export, and an
open-source filter.

---

## Sections

| Section | What it covers |
|---|---|
| Build | Guided pricing calculator — start from a quantity and entity type |
| Security | Endpoint, IAM, SIEM, email, password managers, zero trust, vuln management, PAM, compliance, NIDS, DFIR, and solution packages |
| Vendors | Directory of vendor detail pages with plan breakdowns and price history |
| Cloud | CSP security products, app hosting, compute, CDN, and monitoring across AWS, GCP, and Azure |
| AI | Consumer plans, API token pricing, API details, playgrounds, code assistants, and image generation |
| Dev Tools | CI/CD, monitoring, collaboration, IaC, feature flags, and error tracking |
| Databases | Managed platforms, Big 3 native services, and a guided DB picker |
| Comms | Email APIs, SMS, payments, auth providers, and push notification services |
| Stack Builder | Compose a full production stack slot by slot and get a combined monthly estimate |
| Virtualization | Hypervisors, HCI platforms, and desktop VM tools |

---

## From Scratch Builder

<div align="center">
  <img src="screenshot-builder.png" alt="From Scratch Builder" width="100%" />
  <p><em>Start with a quantity, pick what it represents, and get ranked pricing results instantly.</em></p>
</div>

The Builder is designed for people who know what they need to buy but not what
category or vendor to look at. It asks three questions — in sequence, with no
next button:

1. **Quantity** — a slider from 1 to 1,000+ representing the scale of the problem
2. **Entity type** — what that number represents: endpoints, servers, cloud
   instances, databases, user accounts, or IP/network nodes
3. **Category** — the relevant product categories for that entity, with
   grayed-out options for categories not yet covered

Results are ranked product cards — cheapest to premium — using the same card
design as the rest of the app. Change any step and results update instantly.
Earlier steps stay visible and editable at all times.

---

## Security Packages

<div align="center">
  <img src="screenshot-packages.png" alt="Security Packages" width="100%" />
  <p><em>Pre-built solution packages from Starter to Full Protection, with per-component OSS alternatives.</em></p>
</div>

Security > Packages offers four pre-built protection tiers — Starter, Standard,
Advanced, and Full Protection — each broken down into individual components
(endpoint, email, identity, backup, and more) with per-user monthly cost
estimates.

Every component shows a vendor recommendation and, when the OSS toggle is
enabled, a free or open-source alternative for teams that want to reduce spend
without dropping coverage. The package detail panel also includes a CSV export
of the full component breakdown.

---

## Cloud Hosting

<div align="center">
  <img src="screenshot-hosting-picker.png" alt="Hosting Picker" width="100%" />
  <p><em>Hosting Picker — answer four questions, get a ranked list of platforms that fit.</em></p>
</div>

<div align="center">
  <img src="screenshot-app-hosting-guide.png" alt="App Hosting Guide Big 3" width="100%" />
  <p><em>App Hosting Guide — every deployment model on AWS, GCP, and Azure in one view.</em></p>
</div>

**Hosting Picker** is a guided questionnaire that asks about your runtime,
traffic level, team size, and budget constraints, then ranks hosting platforms
from most to least relevant for that combination.

**App Hosting Guide — Big 3** maps every way to deploy a web application on
AWS, GCP, and Azure — from zero-config CDN deployments to bare-metal compute.
Each platform is shown in three columns with comparable services highlighted
side by side across all deployment models.

---

## AI Pricing

<div align="center">
  <img src="screenshot-ai-api.png" alt="AI API Token Pricing" width="100%" />
  <p><em>API Pricing — input and output token sliders update all provider costs in real time.</em></p>
</div>

<div align="center">
  <img src="screenshot-ai-playground.png" alt="AI Playgrounds" width="100%" />
  <p><em>Playgrounds — feature comparison across every major provider's prompt environment.</em></p>
</div>

**AI > API Pricing** covers every major model API with two sliders — monthly
input tokens (M) and output tokens (M). Adjust either slider and all provider
costs recalculate instantly. The chart view renders a bar graph for direct
visual comparison. Includes batch pricing and prompt caching discounts where
available.

**AI > API Details** goes deeper — context window sizes, rate limits at each
tier, fine-tuning availability, and free tier terms for each provider.

**AI > Playgrounds** compares browser-based prompt environments across providers
on features like temperature controls, system prompt editing, side-by-side model
comparison, export options, and whether an API key is required.

The AI section also covers consumer subscription plans, code assistants, and
image generation tools.

---

## Stack Builder

<div align="center">
  <img src="screenshot-stack-builder.png" alt="Stack Builder" width="100%" />
  <p><em>Build a full production stack slot by slot. When all required slots are filled, a checkout summary appears.</em></p>
</div>

Stack Builder lets you compose a complete production stack across six slots:
hosting, database, authentication, monitoring, email API, and CDN. Each slot
lists common vendors with prices and notes. Select one per slot and the
monthly total updates in real time.

When all required slots are filled, a checkout summary panel slides into view
below the builder. It lists every selected vendor with its price, description,
and a direct link to that vendor's pricing page. The summary exports to CSV
with one click.

---

## Databases

<div align="center">
  <img src="screenshot-db-picker.png" alt="DB Picker" width="100%" />
  <p><em>DB Picker — filter by database type, scale, and hosting preference to find the right fit.</em></p>
</div>

**Databases > DB Picker** asks about data model (relational, document, key-value,
graph, time-series), expected scale, and whether you want managed hosting or
self-hosted. It returns a ranked shortlist of matching databases with notes on
pricing model and best-fit scenarios.

**Databases > Big 3** covers native managed database services from AWS, GCP,
and Azure across relational, NoSQL, in-memory, and warehouse categories in a
three-column side-by-side view.

---

## Features

| Feature | Detail |
|---|---|
| Sort | Recommended, Low to High, High to Low, A to Z — persists across all sections |
| Views | Card grid and table view — toggle per session, applies globally |
| OSS filter | Shows or hides open-source and free tools; amber warning banner appears when active to prevent hidden results going unnoticed |
| Compare | Pin up to 3 vendors from any section and compare side by side |
| CSV export | Available on every section toolbar and the Stack Builder summary |
| Global search | Filters results across all visible sections in real time |
| Saved items | Heart any card to save it; accessible from the header icon with a live count badge |
| Price history | Vendor detail pages include a changelog of price changes over time |
| Freshness badge | Each section toolbar shows the quarter its data was last verified |

---

## Running Locally

No build step. No dependencies.

```bash
git clone https://github.com/yourusername/stackprice.git
open stackprice/index.html
```

Or download `index.html` and open it directly in any browser.

---

## License

MIT

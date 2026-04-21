# TCP Subscriptions Demo

Interactive, on-brand HTML walkthrough of the WooPW Subscriptions module for The Care Pharmacy admin team.

**Live demo:** https://joelaurenspm.github.io/tcp-subscriptions-demo/

## Contents

- `index.html` — single-file, self-contained interactive guide. No build step, no dependencies beyond Google Fonts (Nunito).

## Sections

1. Setting up a subscription product — live Frequency Builder
2. Ordering subscription products — Related Orders explorer with upgrade narrative
3. Subscription statuses & the Subscriptions page — annotated admin list + status lifecycle card
4. Upgrading a patient's dosage — live Upgrade Simulator (remove → add → recalculate → done)
5. Reminder timing — interactive 30-day timeline with a slider
6. Renewing a subscription — three scenario flows (happy / missing consultation / cancellation)

The day counts in §6 are wired to the slider in §5, and the "Patients get X days' notice" takeaway at the end follows suit.

## Running locally

Just open `index.html` in any modern browser. No server required.

## Stack

Plain HTML + CSS + vanilla JS. Mobile-first from 320 px. WCAG 2.1 AA contrast. Respects `prefers-reduced-motion`.

---

Built by [Pharmacy Mentor](https://pharmacymentor.com) for [The Care Pharmacy](https://thecarepharmacy.com).

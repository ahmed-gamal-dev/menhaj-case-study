# Menhaj (منهاج)

> Arabic-first SaaS for running academies and training centers.

**Live:** [menhaj.online](https://menhaj.online/) · **Role:** Founder & lead developer · **Period:** 2026 – present · **For:** Own product

![Laravel 13](https://img.shields.io/badge/Laravel_13-2E2A8C?style=flat-square) ![PHP 8.4](https://img.shields.io/badge/PHP_8.4-2E2A8C?style=flat-square) ![Inertia.js](https://img.shields.io/badge/Inertia.js-2E2A8C?style=flat-square) ![React](https://img.shields.io/badge/React-2E2A8C?style=flat-square) ![TypeScript](https://img.shields.io/badge/TypeScript-2E2A8C?style=flat-square) ![MySQL](https://img.shields.io/badge/MySQL-2E2A8C?style=flat-square) ![Laravel Reverb](https://img.shields.io/badge/Laravel_Reverb-2E2A8C?style=flat-square) ![Flutter](https://img.shields.io/badge/Flutter-2E2A8C?style=flat-square) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2E2A8C?style=flat-square)

![Menhaj (منهاج) — home page](screenshots/desktop.png)

## Overview

Menhaj gives an academy one place to run its daily work: students and groups, courses and live sessions, attendance, invoices and payments, parents' follow-up and interactive learning. Each academy gets its own subdomain (or its own domain) and its own isolated database.

## What it does

- Students, groups, courses, schedules and live classes
- Attendance with parent notifications
- Finance: invoices, installments, discounts, refunds, cashbox and teacher payouts
- Online payments (Paymob, Fawry)
- Parent / family portal and student portal
- Interactive learning games and AI study tools
- Arabic RTL web app + Flutter mobile apps (staff, student & parent)

## Engineering highlights

- Multi-tenant: landlord database + one database per academy, resolved by subdomain / custom domain
- 29 business domains organised as Actions, Services and DTOs (~195 action classes)
- ~370 automated test files, PHPStan level 7, Laravel Pint
- CI/CD with GitHub Actions to a Linux VPS
- 540+ commits since June 2026

## Screenshots (live site)

<p>
  <img src="screenshots/mobile.png" width="260" alt="Mobile">
  <img src="screenshots/page1.png" width="520" alt="Page">
  <img src="screenshots/page2.png" width="520" alt="Page">
</p>

<details>
<summary>Full home page</summary>

![Full page](screenshots/long.png)

</details>

---

Source code is private (client / commercial project). This repository documents the work only.

Built by **Ahmed Gamal** — Senior Laravel Developer · [LinkedIn](https://www.linkedin.com/in/wzcoder/) · [GitHub](https://github.com/ahmed-gamal-dev)

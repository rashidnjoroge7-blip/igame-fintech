# igame-fintech
igame-fintech dasboard
# ApexPulse // iGaming & Fintech Analytics Engine

A production-ready, hybrid iGaming and Fintech dashboard built with Next.js 14, TypeScript, Tailwind CSS, Zustand, and Supabase. Designed for high-frequency real-time updates, the platform features live sports/eSports betting odds simulation, a real-time crypto/fiat ledger, interactive financial analytics, and full Role-Based Access Control (RBAC).

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Next.js](https://img.shields.io/badge/Next.js-14_App_Router-black?logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?logo=typescript)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4-38B2AC?logo=tailwind-css)
![Supabase](https://img.shields.io/badge/Supabase-PostgreSQL_%26_Auth-3ECF8E?logo=supabase)
![Vercel](https://img.shields.io/badge/Vercel-Deployed-000000?logo=vercel)

---

## Key Features

* **⚡ Real-Time Engine:** Zustand-powered ticker simulating sports score changes, odds shifts, and incoming crypto/fiat transactions every 2.5 seconds.
* **💎 Dark Glassmorphism UI:** Hardware-accelerated backdrop blurs (`backdrop-blur-xl`), specular glare highlights, and dynamic neon glows (`cyan`, `violet`, `emerald`).
* **🔐 Supabase Auth & RBAC:** Native authentication with Row-Level Security (RLS) enforcing access roles (`Admin`, `VIP`, `Player`, `Auditor`) across server components and middleware.
* **📊 Analytics & Ledger:** Interactive Recharts for PnL / wallet volume tracking and `@tanstack/react-table` for searchable, sortable live transaction histories.
* **🎲 Interactive Bet Slip:** Real-time odds flash state indicators, dynamic payout calculation, and particle celebrations (`canvas-confetti`) on simulated wins.
* **📱 Responsive Layout:** Mobile-first design featuring a collapsible glass drawer and desktop grid shell.

---

## Tech Stack

| Domain | Technology |
| :--- | :--- |
| **Core Framework** | Next.js 14 (App Router, Server Actions, Middleware) |
| **Language** | TypeScript |
| **Package Manager** | `pnpm` |
| **Database & Auth** | Supabase (PostgreSQL, Row Level Security, `@supabase/ssr`) |
| **State Management** | Zustand |
| **Styling & Motion** | Tailwind CSS, Framer Motion, Lucide Icons, `clsx`, `tailwind-merge` |
| **Data Viz & Tables** | Recharts, `@tanstack/react-table` |
| **Data Simulation** | `@faker-js/faker`, `react-countup`, `canvas-confetti` |
| **Deployment** | Vercel Edge Network |

---

## Getting Started

### Prerequisites

* Node.js v18.17+ 
* `pnpm` installed (`corepack enable` or `pnpm install -g pnpm`)
* A free [Supabase](https://supabase.com) account

### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/apexpulse-dashboard.git](https://github.com/your-username/apexpulse-dashboard.git)
   cd apexpulse-dashboard

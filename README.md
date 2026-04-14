# 🛍️ NomadLiving Boutique

> React/Redux e-commerce store — part of the NomadLiving full-stack ecosystem.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Site-00C7B7?style=for-the-badge&logo=vercel&logoColor=white)](https://nomadliving-boutique.vercel.app)
[![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react)](https://react.dev/)
[![Redux](https://img.shields.io/badge/Redux%20Toolkit-1.9-764ABC?style=for-the-badge&logo=redux)](https://redux-toolkit.js.org/)

## Overview

NomadLiving Boutique is the e-commerce arm of the NomadLiving ecosystem — a "Shop the Stay" concept where guests can purchase the furniture and decor from their glamping experience. It connects to [NomadLiving Stays](https://nomadliving-stays.vercel.app) (booking platform) and [NomadLiving Ops](https://nomadliving-ops.vercel.app) (internal dashboard).

## Features

- **Product catalogue** — filtering by price, category, company, colour; sorting; pagination
- **Shopping cart** — Redux Toolkit with localStorage persistence, survives browser refresh
- **Checkout** — Australian GST (10%) calculation, free shipping threshold, order history
- **Authentication** — JWT via Axios interceptors, automatic token refresh, protected routes
- **React Query caching** — 5-minute stale time, reduces API calls by 60%+
- **Dark/light mode** — persistent preference via Redux
- **Australian localisation** — AUD currency, GST, en-AU date formatting

## Tech Stack

| Layer | Technologies |
|-------|-------------|
| Frontend | React 18, Redux Toolkit, React Query, React Router v6, Vite |
| Styling | Tailwind CSS, DaisyUI |
| Backend | Strapi CMS (headless), Axios |
| Testing | Vitest, React Testing Library |
| DevOps | GitHub Actions CI/CD, Vercel |

## Getting Started

```bash
git clone https://github.com/Tracy1112/NomadLiving-Boutique.git
cd NomadLiving-Boutique
npm install
cp .env.example .env.development   # add your API URL
npm run dev
```

Open [http://localhost:5173](http://localhost:5173).

## Ecosystem

| App | Description | Link |
|-----|-------------|------|
| **Stays** | Next.js SSR booking platform | [nomadliving-stays.vercel.app](https://nomadliving-stays.vercel.app) |
| **Boutique** (this repo) | React/Redux e-commerce store | [nomadliving-boutique.vercel.app](https://nomadliving-boutique.vercel.app) |
| **Ops** | MERN internal dashboard | [nomadliving-ops.vercel.app](https://nomadliving-ops.vercel.app) |

## License

MIT · [Tracy Kong](https://www.linkedin.com/in/tracykong1212/) · [Portfolio](https://tracy-portfolio-nine.vercel.app)

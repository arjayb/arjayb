# Hi, I'm Arjay

**Independent Web Developer — Rapid Prototyping, API Integrations & Business Tools**

I build focused web applications and increasingly full-stack systems — from browser-first tools to deployed applications with authentication, APIs, databases, role-based workflows and real-world business use cases.

📫 [arjayb.fb@gmail.com](mailto:arjayb.fb@gmail.com)

---

## Featured Project — Digital Barangay

**A deployed full-stack resident and admin portal for barangay services.**

**[Live Demo](https://arjayb.github.io/Digital-Barangay-App/)** · **[Frontend Repository](https://github.com/arjayb/Digital-Barangay-App)** · **[Backend Repository](https://github.com/arjayb/digital-barangay-backend)**

Residents can:
- Register and authenticate securely
- Submit barangay document requests
- Receive backend-generated tracking numbers
- Report non-emergency community concerns
- Track request and concern status
- View barangay officials and notices

Staff can:
- Authenticate through a protected admin portal
- Review resident document requests and concerns
- Update workflow statuses and notes
- Manage the operational side of the resident service portal

### Architecture

```text
Resident / Admin Browser
          |
          v
   GitHub Pages frontend
          |
       HTTPS API
          |
          v
   Render / Express API
          |
       Prisma ORM
          |
          v
      Neon PostgreSQL

Uploads -> Cloudinary
```

**Stack:** HTML/CSS/JavaScript · Node.js · Express · Prisma · PostgreSQL/Neon · JWT · Render · GitHub Pages · Cloudinary

This is the strongest current demonstration of my ability to take a browser-based concept through **frontend → API → authentication → database → role-based workflows → deployment**.

---

## Other Projects

| Project | What it demonstrates | Stack |
|---|---|---|
| **[RemitCompare](https://github.com/arjayb/RemitCompare)** | Compares live remittance provider rates against the mid-market rate | Vanilla JS, live FX API |
| **[BudgetFX](https://github.com/arjayb/BudgetFX)** | Multi-currency budget ledger with live conversion | Vanilla JS, `localStorage`, live FX API |
| **[RateAlert](https://github.com/arjayb/RateAlert)** | Currency tracker with sparkline and threshold alerts | Vanilla JS, SVG, Notifications API |
| **[OrbitConnect](https://github.com/arjayb/OrbitConnect)** | Combines GitHub + npm activity into one developer profile | Vanilla JS, GitHub + npm APIs |
| **[OrbitOrg](https://github.com/arjayb/OrbitOrg)** | Visualizes an organization's repositories | Vanilla JS, SVG |
| **[OrbitStats](https://github.com/arjayb/OrbitStats)** | Repository commit activity, languages and contributors | Vanilla JS, SVG |
| **[Orbit](https://github.com/arjayb/Orbit-a-GitHub-profile-explorer)** | GitHub profile explorer visualized as an orbit of repositories | Vanilla JS, SVG |

## How I Build

I use the simplest architecture that fits the product. Client-side applications stay lightweight when a backend is unnecessary. When the product requires persistent data, authentication, role separation or operational workflows, I build beyond the browser and connect the pieces into a deployed system.

I use AI-assisted development as part of the workflow, but the goal is shipped software that can be inspected, tested, deployed and explained — not code generated for its own sake.

The repositories document the architecture, deployment model, data sources and current limitations rather than presenting prototypes as finished products.

**Open to freelance work and practical web application projects.**

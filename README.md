# ✈️ Igniting Minds Aerospace — Official Website

> **Igniting Minds Aerospace Pvt Ltd (IMAPL)** — Integrated aerospace engineering and manufacturing company specialising in complex tooling, precision components, and sub-assemblies.
>
> 📍 Phase 3, Peenya, Bengaluru, Karnataka, India 560058 | Founded 2017

---

## 🌐 Live Preview

The application runs locally at `http://localhost:5173` via the Vite dev server.

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Framework | React 19 + TypeScript 5.7 |
| Build Tool | Vite 8 |
| Styling | Tailwind CSS v4 (via @tailwindcss/vite) |
| Backend / DB | Supabase (Auth, Storage, Edge Functions) |
| 3D / WebGL | OGL |
| Package Manager | pnpm |
| Formatting | oxfmt |

---

## 📁 Project Structure

```
IGNITING-MINDS-latest/
├── public/
│   ├── images/          # Product, quality, tooling & leadership photos
│   ├── maps/tiles/      # Offline map tile images
│   └── videos/          # Hero background videos
├── src/
│   ├── admin/           # Admin dashboard (Login, RFQ list, Contact list)
│   ├── components/      # Shared UI components (Navigation, Footer, etc.)
│   ├── content/         # Structured content/data models (company, products, etc.)
│   ├── lib/             # Supabase client & form submission helpers
│   ├── pages/           # Route-level page components
│   ├── App.tsx          # Root app component & routing
│   ├── index.css        # Global styles & Tailwind v4 import
│   └── main.tsx         # React entry point
├── supabase/
│   ├── functions/       # Edge Functions (submit-contact, submit-rfq, etc.)
│   └── migrations/      # Database migration SQL files
├── scripts/             # Validation & build helper scripts
├── index.html           # Vite HTML shell
├── vite.config.ts       # Vite + Tailwind + React plugin config
└── tsconfig.json        # TypeScript configuration
```

---

## 📄 Pages

| Route | Page |
|---|---|
| `/` | Home |
| `/about` | About Us |
| `/capabilities` | Capabilities |
| `/products` | Products |
| `/industries` | Industries Served |
| `/quality` | Quality & Certifications |
| `/facilities` | Facilities |
| `/resources` | Resources |
| `/careers` | Careers |
| `/contact` | Contact Us |
| `/request-quote` | Request a Quote (RFQ) |
| `/privacy` | Privacy Policy |
| `/terms` | Terms of Service |
| `/admin` | Admin Dashboard (protected) |

---

## 🚀 Getting Started

### Prerequisites

- Node.js (see `.mise.toml` for version)
- pnpm

### Installation

```bash
# Install dependencies
pnpm install
```

### Environment Variables

Create a `.env.local` file in the root directory:

```env
VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

### Running Locally

```bash
# Start development server (http://localhost:5173)
pnpm dev

# Build for production
pnpm build

# Preview production build
pnpm preview

# Format code
pnpm format
```

---

## ⚙️ Supabase Backend

The backend is powered by Supabase and includes:

**Edge Functions**
- `submit-contact` — Handles contact form submissions
- `submit-rfq` — Handles Request for Quote form submissions
- `complete-rfq-upload` — Finalises file uploads for RFQs
- `admin-download-attachment` — Secure attachment downloads for admins

**Database Migrations** — Located in `supabase/migrations/`, covering:
- Submissions schema (contacts & RFQs)
- Storage & notifications
- Admin authentication
- Rate limiting

---

## 🏢 About Igniting Minds Aerospace

**Igniting Minds Aerospace Pvt Ltd** is an integrated aerospace engineering and manufacturing company based in Bengaluru, India. Core areas of expertise include:

- 🔧 **Aero Engine Tooling** — Airframe and aero-engine tooling
- ⚙️ **Precision Aerospace Components** — Manufactured to demanding dimensional requirements
- 🛠️ **MRO Tooling Solutions** — Supporting aircraft maintenance, repair & overhaul
- 🏭 **Integrated Engineering & Manufacturing**
- 📐 **Jigs & Fixtures** — For accurate positioning, assembly & inspection
- ✅ **Quality-Driven Manufacturing** — Supported by CMM and advanced inspection

### Leadership

| Name | Role |
|---|---|
| Chakrapani M | Founder & Managing Director |
| Manjunatha S | Director – Projects |
| Beerappa K | Director – Finance |

---

## 📜 License

This project is proprietary. All rights reserved © Igniting Minds Aerospace Pvt Ltd.

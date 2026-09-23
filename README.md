<h1 align="center">Veltron Group</h1>
<p align="center"><b>Intelligence for every frontier.</b></p>

<p align="center">
  <a href="https://companywebsite-qn3j.vercel.app"><b>Live site →</b></a>
</p>

---

## What's in it

The Veltron Group marketing site — a static, multi-page portfolio for the company and its AI products.

| Page | Purpose |
|---|---|
| `index.html` | Company homepage — products, services, custom builds, projects, founder, investors, waitlist, contact |
| `academic-twin.html` | Product page for Academic Twin (live) |
| `health-ai.html` | Product page for Veltron Health AI (coming soon) |
| `workos.html` | Product page for Veltron WorkOS (coming soon) |
| `finai.html` | Product page for Veltron FinAI (future) |
| `student-analytics.html` | Product page for AI Student Analytics (live) |
| `ai-products.html` | Alternate/legacy products overview page |

## Stack

Plain HTML/CSS/JS, no build step or framework. Forms submit via [FormSubmit](https://formsubmit.co) — no backend of its own.

## Running it

Static site — serve the directory and open it:

```bash
python3 -m http.server 8000
```

## Deployment

Deployed on Vercel from this repo's `main` branch. The Vercel project's Root Directory must be left empty/unset (this repo's files live at the repo root, not in a subfolder) — do not set it to anything else, or the build will fail with a "Root Directory does not exist" error.

## Federico Noya

I build and run web products end to end — from the database to the deploy to the
thing that actually brings in customers. Based in Málaga, Spain. I work in
Spanish and English, mostly with clients in Spain and Latin America.

Most of what I do lives in production rather than in public repos: SaaS for
regulated industries, lead-generation sites, and the internal tooling that keeps
about twenty projects from falling over.

---

### In production

| | What it is | Stack |
|---|---|---|
| **[ContaDoc](https://contadoc.io)** | Accounting platform for independent healthcare professionals in Argentina. Tax engine (VAT, income tax, provincial), OCR expense capture, period settlement. | Next.js · TypeScript · Supabase · PostgreSQL RLS |
| **[CuotaQ](https://cuotaq.com)** | Membership-fee billing for clubs and non-profits. | Next.js · TypeScript |
| **[AssetWhisper](https://assetwhisper.com)** | Market analysis platform. Educational content, no return promises. | Next.js · Python |
| **[NVDigital](https://nvdigital.es)** · **[Loco 22](https://loco22.com)** | Web development studios — Spain and Argentina. | Astro · Next.js · WordPress headless |
| **[OPS Colombia](https://opscolombia.com)** | Solar quotes marketplace. ~70k monthly search impressions. | Astro · Vercel |

---

### What I actually spend time on

**Products, not demos.** ContaDoc handles real tax filings; getting the
settlement cycle right mattered more than any framework choice. Row-level
security in PostgreSQL, audited by hand, because "the query returns nothing"
and "the user has no access" look identical until they don't.

**Automation that runs unattended.** Most of my work is a scheduler, a queue and
a script that has to survive a laptop waking up without DNS. Content pipelines
that render video deterministically, SEO crawlers that diff a repo against a
sitemap against a live crawl, publishing agents that talk to the YouTube and
Search Console APIs on a shared quota.

**SEO as engineering.** Not keywords — `hreflang` reciprocity, canonical
mismatches, sitemaps that return the login page with a 307, and the difference
between a site that is down and a site that is blocking your user agent.

---

### Stack

TypeScript · Python · Next.js · Astro · React · Node · PostgreSQL · MySQL ·
Supabase · Vercel · Tailwind · WordPress (headless) · Solidity

---

### About the repos below

Most of the 79 public repositories here are course work and experiments from
2021–2023 — Udacity blockchain projects, framework tryouts, small tools. They
are still up because deleting them would be pretending I started somewhere else.
The current work is either in private repos or in the products linked above.

---

📫 **hello@federiconoya.com** · 🌐 [federiconoya.com](https://www.federiconoya.com/)

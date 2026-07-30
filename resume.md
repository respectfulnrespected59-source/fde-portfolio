# Rob Hadden, Jr.

**Forward Deployed Engineer**
respectfulnrespected59@gmail.com &middot; (510) 730-6882 &middot; Fremont, CA
GitHub: [respectfulnrespected59-source](https://github.com/respectfulnrespected59-source) &middot; Portfolio: [respectfulnrespected59-source.github.io/fde-portfolio](https://respectfulnrespected59-source.github.io/fde-portfolio/)

---

## Summary

Founder-operator shipping production AI systems end-to-end: payments, real-time data, agent orchestration, creative pipelines. Three live products against paying users. I run the Audit → Evals → Deployment loop as my default working mode, and I've built the ops muscle to survive live-key Stripe, prod auth flows, and multi-rig parity without a team behind me. Deep daily user of Claude and the Claude Agent SDK.

---

## Selected Work

### Alignment 365 &mdash; Solo Founder-Engineer &middot; 2025–present
**Wellness subscription platform, live in production on Render + Stripe**
- Rebuilt a broken auth stack: silently-failing Google Sign-In + no email/password recovery path. Rotated OAuth client ID, shipped both auth surfaces to prod July 2026, with zero regressions on live users.
- Built a Playwright-based ops harness that scripts Render env-editor + Stripe dashboard actions, so config changes and live-key rotations never require manual dashboard clicking under incident pressure.
- Live Stripe billing on Quantus AI merchant account (`acct_1ISaWmK8nm5Rd6Oh`); test + live keys, webhooks, checkout regression suite.

### MarketPulse &mdash; Solo &middot; 2026
**Trading dashboard with hand-rolled precision chart engine, live on Render**
- Rejected off-the-shelf charting libraries (1–3px drift on candle bodies) and built a custom SVG Live chart from Python stdlib + vanilla JS: snap-to-candle mark placement, editable trend lines, drawable annotations.
- Signature interaction: gold neon glow on chart selection — designed on iteration with actual trader feedback, not mockups.
- Zero framework dependencies. Zero charting library. Full control over every pixel and every event handler.

### Quantus AI + Quantum Melanin Media (QMM) &mdash; Co-Founder &middot; 2024–present
**Afrofuturist media studio + agent-orchestrated production pipeline**
- Built and shipped a live commerce channel (Melanin Guardians novella on Gumroad); locked a 35-shot waterflow trailer for the Bloodline Saga IP; 66-shot pilot episode in active production.
- Quantus AI: agent orchestration layer running payments, ops, and multimodal creative generation (image / motion / voice) with locked visual rules enforced as review gates.
- Maintained a source-of-truth repo (`qmm-stack`) keeping skills, hooks, and configs in parity across two production workstations — the same discipline enterprise FDE teams need for consistent client engagements.

---

## Technical Skills

**AI & Agents:** Claude (Opus, Sonnet, Haiku), Claude Code, Claude Agent SDK, MCP servers, tool use, structured outputs, prompt caching, eval harness design
**Languages:** Python, TypeScript / Node.js, JavaScript, SQL, HTML/CSS/SVG
**Backend:** REST + streaming APIs, Postgres, SQLite, OAuth flows, Stripe (live keys, webhooks, subscriptions)
**Frontend:** Vanilla JS + SVG, React, Next.js, hand-rolled HTML/CSS, Playwright
**Infra & Ops:** Render, GitHub Actions, Playwright ops automation, live env / secret rotation, multi-rig git parity, live incident response
**Product:** Solo shipping cadence, direct user feedback loops, live-key deploys, revenue instrumentation

---

## What I'm Looking For

Forward Deployed Engineer roles at frontier AI labs and enterprise AI teams where the job is to walk into a real business problem, understand the workflow that actually matters, and ship a system that survives production. Remote or on-site.

# Robert Hadden Jr.

**Forward Deployed Engineer · AI Automation Engineer · Claude Code + Playwright + Python**

Fremont, CA · Remote · respectfulnrespected59@gmail.com · (510) 730-6882
[LinkedIn](https://linkedin.com/in/robert-hadden-jr-b2b987163) &middot; [GitHub](https://github.com/respectfulnrespected59-source) &middot; [FDE Portfolio](https://respectfulnrespected59-source.github.io/fde-portfolio/) &middot; [Quantus Portfolio](https://respectfulnrespected59-source.github.io/quantus-portfolio/)

---

## Summary

Founder-operator who ships production LLM + browser-automation pipelines daily on the Claude Code / Anthropic Agent SDK stack. I run the Forward Deployed Engineer loop (**Audit → Evals → Deployment**) as my default working mode across a real, revenue-generating media business and a live wellness subscription product. Built and operate a four-agent "digital company" on Claude Code with **130+ custom skills**, MCP servers, hooks orchestration, and persistent memory layers. Deep Playwright + Python for OAuth, live-key Stripe integration, resilient retry logic, and verification gates. Portfolio-first and fully verifiable: public GitHub, open-source tools, and 40+ shipped digital products.

---

## The FDE Loop, In Practice

- **Audit** &mdash; Sit inside real workflows, ignore the documented ones. Alignment 365 auth stack was silently failing for Google users; MarketPulse traders were fighting 1&ndash;3px drift on off-the-shelf charts; QMM production pipelines needed a two-person team to do the work of twenty.
- **Evals** &mdash; Golden datasets, schema validation, exception handling, backtest verification (MarketPulse "Proof Mode"), Playwright regression on live-key checkout + login. Measure against revenue, risk, cost.
- **Deployment** &mdash; Ship on top of existing systems: live Stripe, real DBs, actual OAuth flows. Multi-format publishing to YouTube + X + Gumroad + Etsy with OAuth handling, per-beat verification, and proof-of-work gating before every release.

---

## Core Skills

**LLM / Agent Engineering:** Claude Code SDK, Anthropic Agent SDK, multi-agent orchestration, MCP server consumption + authoring, prompt engineering, drift-aware prompting, LLM output verification, model routing (Haiku / Sonnet / Opus), **130+ custom Claude Code skills authored**

**Automation, QA & Ops:** Playwright (production browser automation), resilient retry/backoff, rate-aware pacing guardrails, OAuth integration, per-step verification and quality gates before deploys, ffmpeg pipeline orchestration, live env / secret rotation on Render + Stripe, multi-rig git parity

**Payments & Live Infrastructure:** Stripe (live keys, subscriptions, webhooks), Google OAuth flows, session auth, Render deploys, GitHub Actions, live incident response

**Languages:** Python, TypeScript, JavaScript, Bash, PowerShell, SQL, HTML/CSS/SVG

**Infrastructure:** Render, n8n, Supabase, Ollama, ComfyUI, Qdrant, RunPod cloud GPU (RTX 4090/5090), Coolify, Ghost, self-hosted SaaS stack administration

**Generative Media Pipelines:** Kling, Higgsfield, Remotion (programmatic video in React), Manim, F5-TTS / Kokoro / XTTS-v2 voice cloning, ElevenLabs, Suno

**Security Hygiene:** OWASP Top 10 awareness, secrets management (`.env` discipline, no-commit hooks), automated security-review workflows, MCP server boundary hardening

---

## Experience

### Co-Founder & Lead Technical Operator &mdash; Quantum Melanin Media (QMM)
**Remote &middot; 2025&ndash;Present**
*Vertically integrated media-tech studio shipping books, AI tools, generative video, and digital products. Own all technical operations: product, infrastructure, automation, and distribution.*

- Architected a four-agent "digital company" on Claude Code &mdash; skills, hooks (PreToolUse / PostToolUse / Stop), rules, and persistent memory layers &mdash; and authored **130+ production skills** covering video pipelines, image generation, voice cloning, social posting, and security review.
- Built **quantus-autoposter** (Python + Playwright): builds, encodes, captions, and uploads multi-format video ads to YouTube and X &mdash; OAuth handling, FFmpeg/MoviePy encoding, and resilient upload retry logic.
- Produced a multi-part AI-animated feature from **100+ continuity-chained** generative video clips, driven by a custom editorial-timing pipeline (ffmpeg speed-ramps, holds, per-beat retiming) with per-beat verification and proof-of-work gating before every release.
- Designed a "water-flow" prompt-chaining system enforcing end-frame continuity across 5-second AI video sequences, eliminating visible seams between clips in production output.
- Shipped **KAREN** (open-source, Python): scans DOCX / PDF / Markdown manuscripts for structural typography damage &mdash; orphan fragments, false-bold sentences, buried headings, merge bugs.
- Shipped **MarketPulse** (Python): live crypto + stock signal dashboard (RSI, MACD, golden cross, multi-timeframe confluence) with a **"Proof Mode"** backtest verification layer; hand-rolled SVG Live chart with snap-to-candle precision; listed commercially on Gumroad; deployed to Render.
- Operate RunPod RTX 4090/5090 cloud GPU rigs (ComfyUI + Ollama + n8n + Qdrant) for generation and RAG at **~$25/month variable cost**; architected and prepared a full self-hosted SaaS stack (Ghost, n8n, Supabase, Coolify, Listmonk, Plausible, Penpot, AppFlowy) for deployment.
- Shipped **40+ digital SKUs** on Gumroad and launched a 9-SKU print-on-demand apparel line on Etsy &mdash; cover art, manufacturer-spec design files, listings, and product-image uploads automated end to end with Python/PIL + Playwright.
- Maintain `quantus-manim` and `quantus-remotion-swarm` &mdash; parallel-render programmatic video pipelines (Manim; Remotion/React).
- Maintain a `higgsfield-autopilot` fork for batch generation orchestration.

### Solo Founder-Engineer &mdash; Alignment 365
**Remote &middot; 2025&ndash;Present &middot; [alignment365.onrender.com](https://alignment365.onrender.com)**
*Live wellness subscription platform on Render + live-key Stripe billing. Sole engineer for auth, payments, ops, and reliability.*

- Rebuilt the auth stack in production: dual-path Google OAuth + email/password. The original silently failed for Google users; I rotated the OAuth client ID and shipped both surfaces to prod **July 2026 with zero regressions on paying customers**.
- Built a **Playwright-based ops harness** that scripts Render env-editor and Stripe dashboard actions, so config changes and live-key rotations never require manual dashboard clicking under incident pressure.
- Full live-key Stripe integration on Quantus AI merchant account (`acct_1ISaWmK8nm5Rd6Oh`): test + live keys, webhooks, checkout regression suite that replays the full flow before every deploy.

### Independent Open-Source Development
**Remote &middot; 2025&ndash;Present**

- Public repos, open-core tooling, and continuous shipped builds &mdash; every claim verifiable at [github.com/respectfulnrespected59-source](https://github.com/respectfulnrespected59-source).

---

## Selected Projects

- **MarketPulse** &mdash; Python + hand-rolled SVG, zero-install market-signal dashboard with backtest Proof Mode. Snap-to-candle precision, editable marks, drawable trend lines. Live on Render. [github.com/respectfulnrespected59-source/marketpulse](https://github.com/respectfulnrespected59-source/marketpulse)
- **KAREN** &mdash; open-core manuscript typography scanner (DOCX / PDF / Markdown). [github.com/respectfulnrespected59-source/karen](https://github.com/respectfulnrespected59-source/karen)
- **Alignment 365** &mdash; live wellness subscription on Render + Stripe. Playwright ops harness, dual OAuth. [alignment365.onrender.com](https://alignment365.onrender.com)
- **QMM Stack** &mdash; four-agent Claude Code architecture: skills + agents + rules + persistent memory. Private repo; live walkthrough on request.
- **quantus-autoposter** &mdash; Python + Playwright multi-platform publishing pipeline. Private repo; viewable on request.

---

## Education

**Skyline High School**, Oakland, CA &mdash; Diploma
Fully self-directed engineering education: primary vendor documentation, source-level study of production codebases, and continuous hands-on shipped builds &mdash; verifiable across the GitHub and portfolio links above.

---

*References & live walkthroughs on request.*

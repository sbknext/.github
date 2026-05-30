<!--
  GitHub PROFILE README for @sbknext
  ───────────────────────────────────
  Put this file at:  github.com/sbknext/sbknext  →  README.md
  (the special self-named repo renders on your profile page)
-->

<h1 align="center">Forge — solo devs ship like teams</h1>

<p align="center">
  <em>An AI harness that lets one person — technical or not — build, run, and <strong>own</strong> a real business.</em>
</p>

<p align="center">
  <a href="https://echo.sbknext.com">echo.sbknext.com</a> ·
  <a href="http://echo.sbknext.com/shop">Soch — verified products</a> ·
  <a href="https://github.com/sbknext?tab=repositories">repos</a>
</p>

---

## Why I build this

The last decade of software locked value inside two places: the people who can
code, and the platforms that rent you your own data. I'm trying to remove both.

**The thesis is simple — the harness should do the hard part, the owner should keep everything.**

- 🧑‍💻 **Any individual becomes productive.** A non-technical person can stand up
  their own website and run the business behind it — without hiring a team and
  without learning to code first. The harness fills the gap.
- 🔐 **You own all of it.** The code and the database are developed *as if the
  business owner wrote them* — and they stay the owner's. No code-share, no
  lock-in, no platform sitting between you and your customers. Export, self-host,
  walk away anytime.
- 🤖 **The AI is the team, not the product.** Memory, orchestration, and safe
  automation are the scaffolding. What you build on top is yours alone.

> Ship like a team of ten. Own it like a team of one.

---

## 🔨 Forge — the harness

The toolchain that turns a single operator into a full stack. Every piece is
small, composable, and leaves the code in **your** repo.

| Project | What it does |
| --- | --- |
| 🌐 **[forge-site](https://github.com/sbknext/forge-site)** | Forge landing + the front door for the whole idea — *solo devs ship like teams*. |
| 🧩 **[forge-client](https://github.com/sbknext/forge-client)** | Client SDK (Python · Node · Rust) for the **Forge Brain** MCP server — the memory + context layer behind the harness. |
| 🕸️ **[forge-sutra](https://github.com/sbknext/forge-sutra)** | Static structural graph for any JS/TS repo — flow graph, local HTML view, and code-derivable drift checks. Understand a codebase you didn't write. |
| 📣 **[forge-social](https://github.com/sbknext/forge-social)** | Safe-pace posting to X + Instagram from one CLI. Real Chrome session, **zero passwords in the repo**. |
| 💼 **[forge-linkedin](https://github.com/sbknext/forge-linkedin)** | Safe-pace LinkedIn engagement (30 likes/day cap). Real session, no credentials checked in. |

---

## 🧠 Brain & tooling

The memory and observability layer the harness runs on — so an agent picks up
exactly where it (and you) left off.

| Project | What it does |
| --- | --- |
| 🔌 **Forge Brain (MCP)** | Per-user, isolated memory over MCP. Every query is `user_id`-scoped at the DB layer — your data never bleeds into anyone else's. Auth by API key, per-user storage quotas, no file or code-exec surface. |
| 🔥 **[claude-fuse](https://github.com/sbknext/claude-fuse)** | Local-first observability for Claude Code — auto-detects mistakes and surfaces the skills you keep reaching for. |
| 💫 **[spec-kit](https://github.com/sbknext/spec-kit)** | Spec-Driven Development toolkit (fork) — specs as the single source of truth, code generated against them. |

---

## 🛒 Echo + Soch — consumer awareness

The other half of the mission: the same trust applied to what people *buy*.

- **[echo.sbknext.com](https://echo.sbknext.com)** — conversational AI for getting
  things done.
- **[echo.sbknext.com/shop](http://echo.sbknext.com/shop) — Soch** — genuine,
  **certified and verified** product information. Know what a product actually is
  before you trust it. Consumer awareness, built in.

> *Soch* — think before you buy. Verified info, not marketing.

---

## Principles

- **Own your code and your data.** Always exportable, always self-hostable.
- **No passwords in repos.** Real sessions, secrets out of source.
- **Isolation by default.** Multi-user surfaces are scoped at the data layer, not by trust.
- **Small, composable tools.** Each Forge piece does one thing and leaves a trail you can read.

---

<p align="center">
  <sub>Built by <a href="https://github.com/sbknext">@sbknext</a> · Senior Frappe/ERPNext engineer · building Forge in the open.</sub>
</p>

# The WebMCP Challenge — Winners Analysis

Source: [Meet the winners 🏆](https://webmcp.devpost.com/updates/46049-meet-the-winners) · [Project gallery](https://webmcp.devpost.com/project-gallery)

**About the challenge:** A 10-day hackathon built around **WebMCP** — an emerging standard that lets a web app expose typed "tools" so a browser-based AI agent can operate the *same* live UI a human uses (no scraping, no screenshots, no separate API). Over **7,000 registrants** and **~2,500 projects** from **100+ countries**. The shared theme across winners: *humans and agents collaborating on one live canvas/state*, with the human keeping final control.

There are **10 official winners** (listed below). Note: *Sheshat* carried a winner badge in the gallery but is **not** in the official announcement, so it's excluded here.

---

## 1. MASIL — Reconnecting Korean Elders to Creative Life
- **Tagline:** Korean elders living alone lose access to creative spaces. Only the web remains; its UI fails them. WebMCP turns Agent access into human access — restoring creative life and expanding what's possible.
- **What it does:** A creative space for Korean elders who live alone and can't easily leave home. Their agent adds calligraphy references and Janggi (Korean chess) moves through WebMCP, and the elder finishes the work themselves.
- **Why it stands out:** Strongest *accessibility/social-impact* angle — reframes agent tooling as a way to make a failing UI usable by an underserved group.
- **Built with:** Next.js, Vercel, Codex, vGPU, WebMCP
- **Links:** [Devpost](https://devpost.com/software/masil-reconnecting-korean-elders-to-creative-life) · [Live demo](https://masil-webmcp.vercel.app/) · [GitHub](https://github.com/SonSangjoon/masil) · [Video](https://youtu.be/Ybw8i32SRGM)

## 2. Alza
- **Tagline:** A floor plan is coordinates, not buttons. Alza publishes its geometry as 31 typed tools, so your agent draws the plan, checks its own work, buys from another origin, and raises it to walkable 3D.
- **What it does:** A floor-plan editor that shares its tools with agents. Give the agent a photo of a plan and one real measurement, and it traces walls, rooms, doors, and furniture into a 3D model you can walk through.
- **Why it stands out:** Rich, self-verifying tool surface (**31 typed tools**) plus a notable **cross-origin purchase** flow — the agent buys from another site.
- **Built with:** Vite, Zustand, SVG, 3D, Model Context Protocol, Cloudflare Pages, Netlify, Playwright, Vitest, WebMCP
- **Links:** [Devpost](https://devpost.com/software/alza) · [Live demo](https://alza-dev.pages.dev) · [GitHub](https://github.com/Elioz404/Alza) · [Video](https://youtu.be/RihMFcMstvI)

## 3. ArchMorph
- **Tagline:** Browser-based architecture studio where a human and an AI agent design a building together on the same live canvas.
- **What it does:** A home-design studio where you and an agent work on the same building across a floor plan, a 3D view, and a walk-through mode. The agent uses **57 typed tools** to edit the design and catch layout problems early.
- **Why it stands out:** Largest tool surface of the winners (57 tools) and true multi-view (2D → 3D → walkthrough) co-design.
- **Built with:** Next.js, Vite, OpenAI, Codex, Tailwind, SVG, 2D/3D, WebMCP
- **Links:** [Devpost](https://devpost.com/software/archmorph) · [Live demo](https://archmorph-studio.musfk.chatgpt.site/) · [GitHub](https://github.com/Yousafkhanzadaa/ArchMorph) · [Video](https://youtu.be/wN3q1ukrrqY)

## 4. Aisle — AI Wedding Seating
- **Tagline:** A live wedding seating canvas where people and AI plan together. Agents arrange guests, honor constraints, spot conflicts, and repair changes in real time.
- **What it does:** A wedding seating planner where you and an agent share one live seating chart. The agent arranges tables, fixes conflicts, and explains its choices — and it keeps any guest placements you pin.
- **Why it stands out:** Clean **constraint-solving + human-pinning** model: the agent optimizes but respects human-locked decisions, and explains its reasoning.
- **Built with:** Vite, Zustand, Tailwind, shadcn, Motion, Codex, Vercel, WebMCP
- **Links:** [Devpost](https://devpost.com/software/aisle-ai-wedding-seating) · [Live demo](https://aisle-three.vercel.app/) · [GitHub](https://github.com/ergjus/aisle) · [Video](https://youtu.be/81zaJ8tASLo)

## 5. Roque Nights
- **Tagline:** Plan the night sky with your agent. One instrument, two operators.
- **What it does:** A stargazing planner (built by an engineer at the Gran Telescopio Canarias). The agent ranks the darkest nights, picks what to observe, and points the sky map while you watch.
- **Why it stands out:** Real domain expertise + real data sources (astronomy engine, weather). "One instrument, two operators" captures the WebMCP shared-control ideal well.
- **Built with:** Astronomy Engine, D3-Celestial, Open-Meteo, Vite, Zustand, Tailwind, Remotion, Netlify, Playwright, Vitest, WebMCP
- **Links:** [Devpost](https://devpost.com/software/roque-nights-plan-the-sky-with-your-agent) · [Live demo](https://roque-nights.netlify.app) · [GitHub](https://github.com/sebastianfernandezgarcia/roque-nights) · [Video](https://youtu.be/Jwx0U-7YtfQ)

## 6. Observatory
- **Tagline:** A local-first fantasy map builder where people and browser agents create together through WebMCP.
- **What it does:** A fantasy map builder for writers and game designers. Ask for "a lone tower in a dense forest," and the agent builds editable terrain, buildings, and labels — not a flat image.
- **Why it stands out:** **Local-first** (data stays in the browser via IndexedDB) and produces *editable structured output* rather than a static picture.
- **Built with:** Vue.js, Pinia, PixiJS, IndexedDB, Vite, Vitest, Playwright, WebMCP
- **Links:** [Devpost](https://devpost.com/software/observatory-vtphg9) · [Live demo](https://observatory.thestoryshack.com/) · [GitHub](https://github.com/relgrowth/observatory) · [Video](https://youtu.be/XLIquI5aeeg)

## 7. Bouquet Studio
- **Tagline:** Turn your wishes into a bouquet you can see, shape, and confidently order.
- **What it does:** A flower shop where you describe who a bouquet is for and how it should feel. The agent builds a first arrangement from real products, and you shape it together before ordering.
- **Why it stands out:** Grounds the agent in **real product inventory** (not hallucinated items) and blends image generation with a purchasable outcome.
- **Built with:** ChatGPT, Codex, OpenAI Image API, ImageGen, Cloudflare Workers, Vite, WebMCP
- **Links:** [Devpost](https://devpost.com/software/bouquet-studio) · [Live demo](https://bouquet-studio.chaocode.workers.dev/) · [GitHub](https://github.com/jane-chao/bouquet-studio) · [Video](https://youtu.be/bHujILKVW54)

## 8. JupyterLite WebMCP
- **Tagline:** Your notebook is already in the browser. Now your agent can be too.
- **What it does:** An agent that works right inside a browser-only Jupyter notebook. It reads your unsaved cells and exact selections, runs code in the kernel you share with it, and marks every change in place.
- **Why it stands out:** Meets developers where they already are; **shared kernel state** and awareness of unsaved/selected content is a genuinely deep integration.
- **Built with:** JupyterLite, JupyterLab, Pyodide, WebAssembly, Jest, Playwright, Vercel, WebMCP
- **Links:** [Devpost](https://devpost.com/software/jupyterlite-webmcp) · [Live demo](https://jupyterlite-web-mcp.vercel.app/lab/index.html) · [GitHub](https://github.com/alliecatowo/jupyterlite-web-mcp) · [Video](https://youtu.be/B_7dSo4hH0k)

## 9. Faraday
- **Tagline:** Hospitals can't use AI on MRI or CT scans without risking patient privacy. This never leaves the doctor's browser, providing instant 3D navigation. The patient's scan never leaves the room.
- **What it does:** A browser viewer for CT and MRI scans. The agent finds and measures regions **without ever receiving the scan**, and exporting findings requires a person's approval.
- **Why it stands out:** Best **privacy-by-architecture** story — the sensitive data never leaves the device, and export is human-gated. Strong healthcare relevance.
- **Built with:** Niivue, WebGPU, Bun, Vite, Playwright, WebMCP
- **Links:** [Devpost](https://devpost.com/software/faraday-3n1zdh) · [Live demo](https://thegreataxios.github.io/faraday/) · [GitHub](https://github.com/thegreataxios/faraday) · [Video](https://youtu.be/I8VAziwIzh0)

## 10. Mandate
- **Tagline:** Mandate turns updatable fields into temporary mandates — a live WebMCP tool compiled from what one person chose, expiring on its own, and re-checked by the server on every call.
- **What it does:** A permission layer that lets you give an agent access to specific records and fields for a set time. The agent can **stage** changes but can't commit them, and its access ends when time runs out or you revoke it.
- **Why it stands out:** The most *infrastructure/governance*-focused winner — scoped, expiring, server-re-verified permissions. "Capability is not authority" applied concretely.
- **Built with:** Hono, JSON Schema, Model Context Protocol, ChatGPT, Kokoro, esbuild, ESLint, Vite, Vitest, Playwright, Vercel, WebMCP
- **Links:** [Devpost](https://devpost.com/software/mandate-ix29ek) · [Live demo](https://webmcp-weld.vercel.app) · [Video](https://youtu.be/dQ29bnnl8W4)

---

## Cross-cutting patterns
- **Shared live state, human-in-control:** Every winner puts the human and agent on the *same* canvas/state; the human pins, approves, or gates the irreversible step (Aisle pins, Faraday/Mandate approvals).
- **Typed tool surfaces are the differentiator:** Alza (31 tools), ArchMorph (57 tools) — winners exposed rich, self-checkable tool APIs rather than a chat box bolted on.
- **Privacy / local-first is a recurring value prop:** Observatory (IndexedDB, local-first), Faraday (scan never leaves browser), Mandate (scoped expiring permissions).
- **Dominant stack:** Vite is nearly universal; Zustand/Pinia for state; Playwright + Vitest for testing; Vercel/Netlify/Cloudflare for hosting; OpenAI Codex/ChatGPT for the agent side. All 10 use **WebMCP** (by definition).
- **Domains spanned:** architecture (Alza, ArchMorph), healthcare (Faraday), creative/accessibility (MASIL, Observatory, Bouquet), science (Roque Nights), dev tools (JupyterLite), and governance/infrastructure (Mandate).

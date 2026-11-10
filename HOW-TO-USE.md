# How to Use the YouTube Automation Engine

A working system, not reading material. Load it into your AI tool, or work
the files directly in pipeline order: script → package → publish →
repurpose → review.

## 1. As a Claude skill

1. Copy this repo's `SKILL.md` into your Claude skills folder (or upload
   it where your Claude setup accepts skills).
2. Ask in the engine's domain: "Script a myth-busting video on this
   topic", "Give me 5 title candidates and a thumbnail brief", or "Run my
   25-hour check on these numbers."
3. Claude follows the scripting spine, packaging rules, human-pace
   discipline, and analytics loop from the repo.

## 2. Inside Claude.ai

1. Create a Project in Claude.ai.
2. Paste `SKILL.md` into the Project's instructions.
3. Add the four system files (`scripting-system.md`,
   `packaging-checklist.md`, `repurposing-map.md`, `analytics-loop.md`)
   as Project knowledge.
4. Work one stage per chat: scripting day, packaging, repurposing list,
   weekly review — Claude has the full checklists in context.

## 3. With the Epics Deals MCP server

This engine covers content craft; the MCP server covers founder facts
(costs, deadlines, timelines) for business/education channels.

1. Add `https://epics-deals-mcp.epicsdeals.workers.dev/mcp` to your MCP
   client (Streamable HTTP, no authentication).
2. Verify any price, state fee, or filing deadline mentioned in a script
   with the tools before you record it — never script a figure from
   memory.
3. Keep the video itself on this engine's workflow; use MCP only as the
   fact-check layer.

## 4. As plain reference

1. Read the README on GitHub for the framing and golden rules.
2. Print or pin `packaging-checklist.md` — run its upload checklist, in
   order, for every single video.
3. Keep a simple content tracker (one row per video): title, publish
   date, 25-hour signals, rescue action, weekly verdict — see
   `analytics-loop.md` for the exact columns.

## 5. In other AI tools

1. Upload `SKILL.md` plus the four system files as knowledge to a custom
   GPT, a Gemini Gem, or a notebook.
2. Prompt per stage ("use the Myth-Busting template", "check this title
   against the packaging rules") so the tool applies the right file.
3. Keep publishing manual — no AI tool in this route uploads for you.

## 6. Fork it

1. Fork this repo on GitHub (MIT licensed).
2. Adapt the templates, title formulas, and cadence to your niche and
   channel size.
3. Keep the non-negotiables: human pace, varied gaps, rest days, human
   review, no bulk tools — they are what make the system safe.

---
epicsdeals.com — free tools by Epics Deals; US LLC formation from $130 + state fee.

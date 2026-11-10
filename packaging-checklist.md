# Packaging Checklist

Packaging is how a good video gets clicked: title, thumbnail, description, and the supporting elements around them. A strong video with weak packaging is invisible. Strong packaging on a weak video destroys trust. You need both — and the checklist below keeps them honest.

Decide packaging **before or during scripting**, not as an afterthought after recording (see `scripting-system.md`).

## Title Formulas

A good title balances two things:

- **Curiosity** — a reason to click now, an open loop
- **Clarity** — the viewer knows exactly what they will get

Curiosity without clarity feels like clickbait. Clarity without curiosity reads like a textbook. Aim for both.

### Formulas that work

| Formula | Pattern | Example shape |
|---|---|---|
| Number + outcome | `[N] [things] that [outcome]` | "5 Mistakes That [Costly Result]" |
| Brackets / parenthesis | `Main title [specific qualifier]` | "How to [Do X] [As a Non-Resident]" / "(Step by Step)" / "(2026 Guide)" |
| The mistake | `Stop [doing X] — do [Y] instead` | Direct, corrective, specific |
| Myth call-out | `[Belief] is wrong. Here's why.` | Pairs with myth-busting scripts |
| Case / result-led | `I [did X] — here's what happened` | Only when true and verifiable |
| Question | `Why does [thing] keep [failing / happening]?` | Works when the answer is genuinely non-obvious |
| Before you... | `Watch this before you [big decision]` | Stakes + timing |
| Complete guide | `[Topic]: The Complete Guide` + qualifier | Use sparingly, only for genuinely comprehensive videos |

### Title rules

- [ ] Front-load the important words — titles truncate on mobile
- [ ] Use a number when the video genuinely has a countable structure
- [ ] Use brackets for one qualifier only — `[2026]`, `(Step by Step)`, `[Full Breakdown]` — not three qualifiers stacked
- [ ] Promise only what the video delivers. If the title says "complete", the video must be complete.
- [ ] Write 3–5 candidate titles per video, then pick. The first title you write is rarely the best.
- [ ] Check the title against the thumbnail: together they should say *more* than either says alone, not repeat the same words
- [ ] Avoid ALL CAPS whole titles, excessive punctuation, and claims you cannot prove

## Thumbnail Rules

- **3 elements max.** One main visual, one short text element, one supporting element (face, arrow, document, logo) at most. If you can remove an element and the thumbnail still works, remove it.
- **Readable at small size.** Shrink the thumbnail to phone size before approving it. If the text is not readable at that size, it is not readable.
  - Few words — typically 2–4 — in large, high-contrast type
  - No sentences. The title carries the detail; the thumbnail carries the emotion and the focal point.
- **One focal point.** The eye should land in one place instantly. Competing faces, objects, and text blocks cancel each other out.
- **Contrast and brightness.** Thumbnails compete in a bright feed. Check yours against neighbouring videos, not in isolation.
- **Brand consistency.** Same font family, same colour system, same layout logic across the channel — so regular viewers recognise your video before they read it. Consistency, not identical copies: each thumbnail still needs its own focal idea.
- **Faces, when used, show a clear emotion** that matches the video (surprise, concern, satisfaction) — not a generic smile on a serious topic.
- **No clickbait gap.** The thumbnail can raise the question; the video must answer it. A thumbnail that promises something the video never shows trains viewers to distrust the channel.
- [ ] Thumbnail concept drafted at scripting stage
- [ ] Checked at small size
- [ ] Checked next to the final title (no duplicated wording)
- [ ] Checked for brand consistency

## Description Template

Descriptions serve the viewer first (summary, chapters, useful links) and search second. Use the same structure every time.

```markdown
[1-2 sentence summary: what this video covers, who it is for, and the outcome.
Repeat the core promise in natural language — write for a human deciding whether to watch.]

In this video:
- [Key point / section 1]
- [Key point / section 2]
- [Key point / section 3]

⏱ Chapters
00:00 [Hook / topic]
00:00 [Section 1]
00:00 [Section 2]
00:00 [Section 3]
00:00 [Wrap-up / next step]

🔗 Mentioned in this video
- [Resource / tool / related video — label it with the name and a short symbol, do not paste a bare URL alone]
- [Next video in the series]

[STANDARD BLOCK — see below: partner links + disclaimer, pasted verbatim, in the same order every time]

---
[Channel one-liner: what this channel publishes and how often, in one sentence.]
```

Rules:
- [ ] First 2 lines carry the summary — they are what shows before "…more"
- [ ] Chapter timestamps are accurate against the final edit, start at `00:00`, and match the actual sections
- [ ] Every link is labelled, works, and goes where it says it goes
- [ ] No link that violates platform policy or a current account restriction — when in doubt, leave it out
- [ ] Standard block pasted verbatim (below), never retyped from memory

### Standard partner / disclaimer block

Keep one canonical block for your channel and reuse it unchanged:

- Your relevant partner / resource links, clearly labelled, in a fixed order
- A plain disclaimer appropriate to your niche — for example, for business / tax / legal education content: that the video is educational information, not professional advice, and viewers should confirm their own situation with a qualified professional
- Any required disclosure (sponsorship, affiliate relationship) for *this* video, added above the standard block — disclosures are per-video, never assumed

Review the canonical block periodically and update it in one place, then use the new version from the next upload onward.

## Tags, End Screens, and Cards Checklist

### Tags
- [ ] Core topic tag (the exact subject of the video)
- [ ] 2–3 close variations / synonyms a viewer would actually search
- [ ] Series / playlist tag if the video belongs to one
- [ ] Channel / brand tag
- [ ] No irrelevant trending tags — they mislead the algorithm and the viewer

### End screens
- [ ] One end screen element pointing to the *logical next video* (the sequel, the deeper tutorial, or the playlist) — not just the newest upload
- [ ] Subscribe element if you use one — keep the layout uncluttered
- [ ] End screen does not cover faces, text, or the final CTA moment
- [ ] Duration checked: elements appear only after the content has finished

### Cards
- [ ] Cards only where the spoken content actually references the linked video or resource
- [ ] No card in the opening moments — let the hook land first
- [ ] Each card's destination still exists and is public
- [ ] Total cards kept low — every card is an invitation to leave this video

### Also check
- [ ] Playlist: video added to the correct playlist(s), in the correct order for a series
- [ ] Visibility / audience settings correct (including "made for kids" where applicable)
- [ ] Language / captions: captions uploaded or checked if you provide them
- [ ] Pinned comment drafted (a question, a useful extra detail, or the key resource) — posted by a human after publish

## Upload Checklist — End to End

Run this in order, for every upload. One video at a time, manually — no bulk uploaders, no platform-native scheduling (see `README.md`).

**Before upload**
- [ ] Final export watched through at least once (or the key sections + hook + ending in full)
- [ ] Title finalised (from the candidate list, checked with the thumbnail)
- [ ] Thumbnail final file ready, checked at small size
- [ ] Description assembled from the template, chapters verified against the edit
- [ ] Script promise vs. actual video checked — the video delivers what packaging promises

**During upload**
- [ ] Correct file uploaded (final version, not a draft export)
- [ ] Title and description pasted and proofread in place
- [ ] Custom thumbnail uploaded (not an auto-generated frame)
- [ ] Tags added per checklist above
- [ ] Playlist(s) selected, series order correct
- [ ] Audience / visibility settings set deliberately
- [ ] End screen and cards added per checklist above

**After publish**
- [ ] Video played back on the public page — title, thumbnail, description, chapters all render correctly
- [ ] Links in the description clicked and verified
- [ ] Pinned comment posted
- [ ] Upload logged (date, title, link) in your content tracker
- [ ] ~25-hour check scheduled (see `analytics-loop.md`)
- [ ] Repurposing tasks created (see `repurposing-map.md`)

If anything fails a check, fix it before moving to the next video. Packaging errors compound when you rush a batch out.

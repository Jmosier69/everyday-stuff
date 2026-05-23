# Content Generation Repo

This repo holds content for multiple brands. When asked to create posts, case studies, testimonials, social content, or proposal material, work here.

## Brands

### MosierData
Custom software and tracking systems. Jim Mosier's company. Founded 2005. Builds systems for businesses and organizations that have outgrown their patchwork of spreadsheets, databases, and paper forms.

- **Voice profile:** `voice-profiles/jim_mosier.md`
- **Content folder:** `mosierdata/`
- **Sub-brands/case studies:** `mosierdata/heartland/` (Heartland for Children)

### ROI Insights
A MosierData product. Marketing measurement layer — tells businesses their real cost per lead across every channel they spend on. Target audience: home services (HVAC, plumbing, electrical, roofing, contractors). Product voice is Jim Mosier's voice adapted for a product page context.

- **Voice profile:** `voice-profiles/roi_insights.md` (overlay on top of `voice-profiles/jim_mosier.md`)
- **Content folder:** `roi-insights/`
- **Strategy:** `roi-insights/agency-strategy.md` — agency partner program design, pricing, and go-to-market
- **Product site:** roiknowledge.com
- **Frontend repo:** github.com/MosierData/roi-insights-frontend
- **Landing page repo:** github.com/MosierData/ROI-Insights-Landing-Page

### Berean Library
A MosierData product with a separate brand identity — no MosierData badge. "NotebookLM for churches." Multi-tenant RAG product that lets churches drop in sermons and ministry materials, ask questions, and get answers cited to the exact sermon and timestamp. Brand ratified May 2026. Anchor customer: Free Life Chapel (Pastor Scott Thomas). Public launch target: late June 2026.

- **Voice profile:** `voice-profiles/berean_library.md` (overlay on top of `voice-profiles/jim_mosier.md`)
- **Content folder:** `berean-library/`
- **Product repo:** github.com/MosierData/church_transcript_search
- **Product site:** bereanlibrary.org

## Content workflow

1. Identify which brand the content is for.
2. Load the relevant voice profile from `voice-profiles/`.
3. Identify the register (Showboat / Real / Analytical) the piece needs.
4. Draft in the appropriate brand folder.
5. Run the QC pass from the voice profile against the draft.
6. Read it out loud. If it sounds natural, it works.

## Voice profiles

- `voice-profiles/jim_mosier.md` — Jim Mosier / MosierData. Full profile: three registers, approved phrases, banned constructions, anchor pieces, QC protocol. Base layer for all MosierData brands.
- `voice-profiles/roi_insights.md` — ROI Insights product voice. Overlay on Jim's profile. Adapted for product page context, home services audience. Analytical-dominant, Showboat-rare. Must be loaded alongside `jim_mosier.md` when producing ROI Insights content.
- `voice-profiles/berean_library.md` — Berean Library product voice. Overlay on Jim's profile. Adapted for faith-adjacent product context, church staff audience. Analytical-dominant, Showboat-rare. Must be loaded alongside `jim_mosier.md` when producing Berean Library content.

## Folder convention

```
mosierdata/           # All MosierData content
  heartland/          # Heartland for Children case study + testimonials
  facebook-posts-*.md
  linkedin-posts-*.md
  posting-schedule.md
roi-insights/         # ROI Insights social posts, articles, and campaign content
berean-library/       # Berean Library social posts, launch content, and case study material
voice-profiles/       # Voice reference documents
jim-image/            # Image assets for posts
```

## What belongs here

- Social media posts (Facebook, LinkedIn, etc.)
- Case studies and testimonials
- Posting schedules
- Proposal boilerplate
- Voice profiles for each brand

## What does not belong here

- Source code
- Client deliverables
- Sensitive client data
- Anything under NDA

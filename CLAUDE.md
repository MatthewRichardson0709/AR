# Project brief: Matthew Richardson personal site (analyst relations)

This file is the handoff from a claude.ai chat into Claude Code. Read all of it before touching anything. `index.html` in this repo is the current source of truth for copy and design. Where this brief and `index.html` disagree, tell Matthew rather than guessing.

---

## 1. Goal and audience

**Goal:** a one-page personal website that helps Matthew move from agency-side analyst relations (AR) into an in-house AR role in a tight market.

**Audience:** in-house hiring managers, recruiters, and senior marketing / product marketing / comms leaders at B2B technology companies. Secondary audience: analysts and peers who might look him up.

**What the page must prove:** he can *run* an AR program (strategy, prioritization, executive prep, feedback into product and messaging), not just execute agency tasks. It should also show he is a real person who builds real relationships.

**Positioning (his words, keep it):** a B2B tech guy. Analyst relations is about "influencing the influencers." His goal is meaningful, lasting relationships with the analysts who cover the B2B spaces he works in. Strengths are cybersecurity, telecom/wireless, and managed services, but he says he can learn any B2B market quickly. The value he is selling is his ability to drive and run AR functions.

---

## 2. About the owner (source facts)

- **Name:** Matthew Richardson. Email: Matthewsrichardson01@gmail.com. LinkedIn: https://www.linkedin.com/in/matthew-richardson-2a3684190/
- **Location:** Salt Lake City, Utah. Boston native, moved to Salt Lake about two years ago (as of Sept 2026).
- **Experience:** about 4 years in AR (1 while in college, 3 post-grad). Account Executive (Analyst Relations), Guyer Group (Beverly Farms, MA), June 2022 to present.
- **Education:** University of Vermont, BS Public Communications (Strategic Marketing Communications concentration), 3.79 GPA. Eagle Scout. Dean's Cup winner (2020), ICBC finalist (2021). (Not on the site currently.)
- **Tools:** ARchitect; Gartner, Forrester, and IDC client portals.
- **Analyst firms engaged:** Gartner, Forrester, IDC, Frost & Sullivan, 451 Research, EMA, GigaOm, ESG.
- **Clients worked with:** CDW, AHEAD, Lookout Security, Nucleus Security, Progress Software, Tarana Wireless, Wi-Fi Alliance.
- **Personal:**
  - Hiking. Recent summits: Middle Teton, Mount Timpanogos, Broads Fork Twin Peaks.
  - Skiing. On skis his whole life. Utah big three: Alta, Snowbird, Snowbasin. East coast big three: Loon, Jay Peak, Mad River Glen.
  - Live music. Huge Dead & Company and Billy Strings fan. Classic rock and vinyl fanatic.

---

## 3. Current site: structure and copy inventory

Single page, top to bottom. Nav links: Work, How I work, About, Contact (anchor links to `#work`, `#approach`, `#outside`, `#contact`).

1. **Nav:** name on the left, four anchor links on the right.
2. **Hero:**
   - Eyebrow: "B2B technology · Analyst relations"
   - H1: "Influencing the influencers, one real relationship at a time."
   - Intro: Boston native who now calls Salt Lake City home; B2B tech AR pro who cares more about building trust with analysts than chasing a ranking; four years across cybersecurity, telecom, cloud, and managed services; ready to run AR in-house.
   - Buttons: "See selected work" (to `#work`), "Get in touch" (to `#contact`).
   - Decorative topographic contour SVG on the right (hidden on mobile).
3. **Stats strip (three figures):**
   - 120+ analyst briefings, inquiries, and strategy sessions led each year across client programs
   - 45+ placements in analyst reports across client programs (Magic Quadrant, Wave, MarketScape)
   - 35 analysts across 8 research firms engaged on a single multi-year enterprise program (this is the CDW program)
4. **Selected work ("Four programs, four different starting points."):** one row per client, each with Situation / What I did / What it produced.
   - **Nucleus Security** (vulnerability management, sole owner): early-stage AR function turned into a proactive program; strategy across Gartner, Forrester, IDC, GigaOm, ESG, Frost & Sullivan; 50+ analyst engagements a year; placement in 10+ reports across six firms.
   - **CDW** ($20B+ IT solutions provider, 3.5-year strategy): helped develop and iterate a multi-year strategy for cloud and managed services analysts; 65+ engagements across 35 analysts and 8 firms; contributed to CDW's first-ever Honorable Mention in the Gartner Magic Quadrant for Public Cloud IT Transformation Services.
   - **Lookout** (mobile and cloud security, two-year program): briefing materials and executive-level engagements to articulate differentiation in a crowded SSE / mobile threat defense market; 30+ engagements a year across five firms; three placements (GigaOm Radar, Frost & Sullivan report, IDC MarketScape).
   - **Progress Software** (enterprise software, one-year contract): helped grow analyst understanding of the recently acquired Nuclia platform. No metrics available; the outcome is written qualitatively on purpose.
   - Intro line under the heading: inclusion in any analyst research is the firm's independent decision; his job is making sure analysts have accurate, current, well-evidenced information.
5. **How I work:** heading "Analyst relations is about influencing the influencers." Four ideas in a 2x2 grid, written in Matthew's own words (they are paraphrased from a training framework he studied; see the compliance section):
   - Relationships come before reports
   - Ask before you announce
   - Right analysts, not all analysts
   - Executive backing, insight flowing inward
6. **Coverage:** "Programs supported" (all seven clients), a line saying strongest in cybersecurity, telecom and wireless, and managed services; "Analyst firms engaged" (eight firms) and the tools line.
7. **About ("Boston born, Wasatch adopted."):**
   - Short paragraph about growing up in Boston and moving to Salt Lake City two years ago.
   - Route strip: Boston, MA (42.36° N, 71.06° W) to Salt Lake City, UT (40.76° N, 111.89° W), dotted line between.
   - Three columns with small line-drawing icons: Hiking (recent summits), Skiing (Utah and East Coast big threes), Live music (Dead & Company, Billy Strings, classic rock on vinyl).
8. **Contact:** dark block. "If you're building or rebuilding an AR function, let's talk." Based in Salt Lake City, looking for in-house AR roles. Buttons: Email Matthew (mailto), LinkedIn.

**Deliberately removed (do not re-add without asking):**
- A 30-60-90 day plan section (and its nav link).
- A footer disclaimer (see compliance).
- Any mention of KCG / Knowledge Capital Group.
- Camping / skiing / live-music tiles with cute analogies to AR work (Matthew called them cheesy).
- A line joking that powder days may delay his reply.

---

## 4. Design system (as built)

- **Look:** editorial, warm paper ground, generous whitespace, thin ink rules, one accent color. Aim: personable and specific, not template-like.
- **Colors:**
  - Background `#F4F1EA`; ink `#1B1F24`
  - Body secondary text `#3A3F45`; meta text `#4A4F55`
  - Accent (default) `#0F5C5A` (deep teal). Alternates previously offered: `#8A3B12`, `#26417A`, `#5B2A6B`
  - Contact block: background `#1B1F24`, text `#F4F1EA`, secondary `#D5D2C9`
- **Type:** Fraunces (400, 600) for display and numerals; Hanken Grotesk (400, 500, 600) for body and labels. Both from Google Fonts. Body 17px / 1.6.
  - H1 64px, H2 44px, stats 56px, case client name 30px
  - Section labels: 13px, uppercase, 0.14em tracking, accent color, weight 600
- **Layout:** max content width 1080px, 40px side padding, about 120px between major sections. Case rows are a two-column grid (260px label column, flexible content column, 48px gap) with a 1px ink top rule.
- **Buttons:** 48px tall, 4px radius, primary filled with accent, secondary outlined.
- **Motifs:** contour-line SVG in the hero, dotted route strip, simple line icons (mountain, ski line, vinyl record) all drawn in the accent color.
- **Implementation state:** everything is inline `style` attributes; the accent is hard-coded as `#0F5C5A` in styles and SVG attributes. Mobile behavior is handled by one `@media (max-width: 800px)` block that uses attribute selectors (`[style*="grid-template-columns"]` and similar) with `!important`. It works but is brittle.

---

## 5. Constraints and compliance (important)

**Analyst-firm and client rules the site is designed around:**
- No analyst firm logos and no Magic Quadrant / Wave / MarketScape / Radar graphics.
- No quoted or reproduced analyst research text.
- Never imply he influenced a ranking. Use language like "contributed to," "engaged," and "helped," not "secured our position." Keep the line that inclusion is the firm's independent decision.
- No confidential information (briefing content, pre-publication feedback, unpublished metrics).

**Disclaimer decision:** Matthew asked for the footer disclaimer (personal site, not affiliated with any analyst firm, no research reproduced) to be removed. That was his call. It is a small risk trade-off. Do not silently re-add it, but if the site's content changes in a way that raises risk (logos, quotes, ranking claims), flag it and suggest a one-line note.

**Employer and client naming:** Matthew says none of his client wins are under NDA and he is comfortable naming clients. Advise him to give his manager at Guyer Group a heads-up before wide sharing. Note that the site currently never names his employer; consider asking whether he wants "Guyer Group" stated (hiring managers will see it on LinkedIn anyway).

**Proprietary source material:** the "How I work" ideas came from a proprietary training deck (KCG, Working With The Analysts). The deck must not be reproduced, quoted, or redistributed. Do not add slides, exact phrases, or named frameworks from it. Matthew explicitly asked that KCG not be mentioned on the site.

**Personal data:** phone number and home neighborhood were intentionally left off. Email is public on the page. Do not add more personal contact details.

---

## 6. Facts that still need Matthew's confirmation

These came from three slightly different resume versions:
- "100+" vs "120+" annual engagements. The site uses 120+.
- "45+ placements" appears on two of three resumes. Confirm the number and how a placement is counted (per report, or per report edition).
- Nucleus: "sole owner" (cyber resume) vs "own end-to-end" (other resumes). The site says "Sole owner."
- CDW: resumes say "supported," "built and led," and "helped develop." The site uses the conservative "helped develop."
- The "35 analysts across 8 firms" stat is CDW-specific; keep its label scoped accordingly.
- AHEAD, Tarana Wireless, and Wi-Fi Alliance are listed by name only. Matthew does not yet feel they are mature enough for full case studies. Do not invent details for them.
- Matthew does not have "before" baselines for clients and does not want to emphasize time-to-placement ("that isn't the goal of AR"). Do not add either.
- Matthew has pending grammar and wording tweaks that were not applied yet. Ask him for the list.

---

## 7. Voice and preferences

- First person, direct, plain. Relationship-centered. Confident without hype.
- Prefers real, specific details (named peaks, named ski areas) over clever analogies. Avoid puns, forced metaphors, and "AR is like camping" style copy.
- Wants personality and a Boston-to-Salt-Lake thread, but restrained. He said the site should feel less "template-esque."
- Do not fabricate facts, metrics, elevations, dates, quotes, or testimonials. If something is missing, leave it out and ask.

---

## 8. Files and hosting state

- `index.html`: standalone, responsive, no build step, hard-coded accent. This is what goes on GitHub Pages.
- A separate, earlier copy lives as a claude.ai design artifact at https://claude.ai/artifact/PjuCyxVYR75VTkBieQefA6. The two copies are not synced. Treat the repo as the source of truth going forward.
- **Hosting plan:** GitHub Pages. Repo named `<username>.github.io`, public, `index.html` at the repo root, Settings > Pages > Deploy from a branch > `main` / root. Matthew tried this and hit problems and has paused it. He has not told us the error. Likely causes: repo name not matching the username exactly, file not at the repo root, file saved as `index.html.txt` or `index (1).html`, a private repo on a free plan, or the branch set to the wrong name. Ask what he saw before guessing. If GitHub keeps failing, Netlify Drop (drag the folder) or Cloudflare Pages are simple fallbacks.
- **Custom domain (optional):** something like matthewrichardson.com, pointed at GitHub Pages per GitHub's current DNS docs, with HTTPS enforced.

---

## 9. Suggested work for Claude Code (in priority order)

1. **Set up the repo and get it live.** Walk Matthew through GitHub Pages or a fallback, verifying the deployed URL loads.
2. **Apply his pending copy edits** once he provides them. Keep the voice.
3. **Refactor without changing the look:** move inline styles into a `<style>` block or `styles.css` using CSS custom properties (`--paper`, `--ink`, `--muted`, `--accent`, and so on), replace the attribute-selector mobile hack with real classes and media queries, and keep it a zero-build static site.
4. **QA pass:** check 375px, 768px, and 1280px widths; keyboard navigation and focus states; color contrast (target WCAG AA); heading order; alt/aria on the decorative SVGs (they are `aria-hidden` now); link targets.
5. **Add polish for sharing:** favicon, Open Graph and Twitter card tags (title, description, image), `lang` and meta description (present), and a canonical URL once the final domain is known.
6. **Make room for photos.** A summit or ski photo in the About section would do more for the "not a template" goal than more copy. Add a properly sized, lazy-loaded image slot and ask Matthew for images. Optimize them before committing.
7. **Optional later:** a fourth "Tarana Wireless" or "Wi-Fi Alliance" case when Matthew has real details; a sanitized "how I work" artifact (briefing prep template or analyst tiering framework); print/PDF resume link.

**Working agreements:** make small, reviewable commits; show Matthew diffs of copy changes; do not rewrite copy unprompted; preserve the design language; ask before adding anything from the "deliberately removed" list.

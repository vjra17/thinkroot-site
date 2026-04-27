## Decision Log

- 2026-04-23: Added repo-level decision log for the live `thinkroot-site` project so homepage and publishing decisions are tracked in the actual deployment source.
- 2026-04-23: Planned homepage clarity pass for cold audiences: rename nav item and hero pill to `Resilience Lab`, add a featured-program bridge near the top, and create a separate `resilience-lab.html` page that explains both formats at a higher level without turning the homepage into a curriculum document.
- 2026-04-23: Implemented the homepage clarity pass in preview: nav item and hero pill now point to `Resilience Lab`, added a `Summer Spotlight` bridge near the top of the homepage, relabeled the homepage program section to `Resilience Lab`, and created `resilience-lab.html` as a separate higher-level detail page covering both the 5-Day Intensive and 6-Week Series.
- 2026-04-23: Updated the `resilience-lab.html` Next Step section so its primary CTA uses the same gold styling as the homepage interest-list button for consistency across the funnel.
- 2026-04-23: Created `resilience-lab-v2.html` as a separate comparison version built around a cleaner decision-focused narrative: a wake-up section with science-backed proof, a sharper `What Students Build` section, concise summer format cards, a simpler `What Students Actually Do` section, and the existing next-step CTA.
- 2026-04-23: Refined `resilience-lab-v2.html` by removing the video placeholder, making card borders more consistent with the homepage system, and clarifying that sessions are interactive with reflection, discussion, journaling, guided activities, and home practice.
- 2026-04-23: Added a WhatsApp CTA to the `resilience-lab-v2.html` Next Step section and changed the footer secondary contact link from the interest list to the WhatsApp community.
- 2026-04-23: Updated `resilience-lab-v2.html` so the nav Interest List item jumps to the page’s own next-step section, added a summer pricing note, and rewrote the opening/context paragraphs and session copy to use more middle-school-specific language and the preferred order for interactive activities.
- 2026-04-23: Fixed the `resilience-lab-v2.html` Next Step action row so the WhatsApp CTA renders visibly beside the priority-interest button.
- 2026-04-23: Promoted `resilience-lab-v2.html` into the active `resilience-lab.html`, preserved the previous version as `codex-resilience-lab-2026-04-23.html`, and created `launch-assets/` with ready-to-share WhatsApp, email, and social-tile copy.
- 2026-04-23: Confirmed the Resilience Lab comparison page Interest List area includes both the priority-interest CTA and a WhatsApp community CTA so parents can either sign up or follow updates there.
## 2026-04-23 17:45 PDT
- Replaced homepage `What Students Reported` cards with a curated mix of new and existing proof: Haswitha, Rishi, MT, AP, and exam-composure stories.
- Replaced Resilience Lab `Reported Outcomes` cards with a more detailed student-reported set built from Haswitha and Rishi interview material.
- Kept the proof split intentional:
  - homepage = fewer, broader, more persuasive real-story cards
  - Resilience Lab page = more granular student-reported shifts aligned to the program experience

## 2026-04-23 17:58 PDT
- Broadened the Resilience Lab proof section so it no longer looks concentrated around only two students.
- Mixed HM/RR cards with prior student initials (MT, AP, SK, SM and VM) and corrected MT/AP/SK to elementary-level labels.

## 2026-04-23 18:08 PDT
- Reworked proof cards on both pages to use a stronger structure: outcome title first, story second, attribution at the bottom.
- Homepage keeps initials for a more personal feel; Resilience Lab uses school-level attribution so the deeper proof section feels broader and less repetitive.

## 2026-04-23 20:33 PDT
- Polished the homepage `Real Stories` section label and refined the exam-composure card language to avoid repeated wording.
- Added visible spacing between the homepage program CTA buttons.
- Reduced the 6-week takeaways from four items to three by combining the toolkit and practice-plan line.
- Made the two homepage program cards equal-height so their bottom summary areas align more cleanly.

## 2026-04-24 20:45 PDT
- Imported recovery context from `/Users/tina/Documents/code/thinkroot-site/Analyze website messaging - Chat in Codex.docx` after the original Codex thread became unusable due to an image payload error.
- Confirmed the transcript preserves the main homepage messaging strategy:
  - technical Bay Area parents as the primary audience
  - homepage should sell practical outcomes before method depth
  - AAA and Five Power stay as proof of method, but not as full early-page teaching
  - interest-capture positioning is the right launch model for the current stage
- Confirmed that key transcript-era homepage changes are already present in the current repo, so this document plus git history can serve as the recovered memory baseline going forward.

## 2026-04-24 20:49 PDT
- Added `project-memory.md` to the live website repo as a concise restart file summarizing audience, homepage strategy, launch model, implemented work, important files, and next-step guidance.
- Going forward, `project-memory.md` should be kept current alongside `decision-log.md` whenever strategy or project status materially changes.

## 2026-04-24 20:55 PDT
- Audited the current homepage against `project-memory.md`.
- Main remaining gaps identified:
  - some mid-page copy is still denser and more claim-heavy than ideal for a fast-reading technical-parent audience
  - the founder/community sections still compete somewhat with the core Resilience Lab conversion path
  - the interest form likely asks for more than is necessary for a first-touch conversion
  - CTA language is directionally correct but currently split between `Get Priority Access`, `Priority Interest List`, and `Request early access`, which weakens message consistency

## 2026-04-24 21:00 PDT
- Confirmed that the public site URL and live filenames should remain unchanged because the website link is already being circulated to parents.
- Created safe comparison files for the next iteration:
  - `/Users/tina/Documents/code/thinkroot-site/index-v3-working-2026-04-24.html`
  - `/Users/tina/Documents/code/thinkroot-site/resilience-lab-v3-working-2026-04-24.html`
- Agreed workflow for this project:
  - iterate in versioned working-copy files first
  - compare before replacing the live site files
  - do not create git commits without explicit user approval first

## 2026-04-24 21:09 PDT
- Completed first homepage-only V3 pass in `/Users/tina/Documents/code/thinkroot-site/index-v3-working-2026-04-24.html`.
- Changes in V3 focused on conversion clarity without touching the live homepage:
  - standardized main CTA language around `Join the Priority Interest List`
  - tightened the gold-strip, gap, and mid-page explanatory copy
  - reduced claim-heavy / theory-heavy language in `Why It Matters` and `What makes ThinkRoot different`
  - renamed the framework section to `How It Works` and simplified its intro
  - compressed the founder story so it reads more practical and less like a second narrative arc
  - compressed community copy
  - shortened the interest form by removing optional phone capture and the local-group invitation question
- Refined V3 wording from `Attention` to `Focus` in the gap section for clearer parent-facing language.
- Completed a second V3 pass focused on persuading achievement-oriented parents without sounding too conceptual.
- Reduced `inner world / inner foundation / what happens within` phrasing in favor of more practical language about pressure, setbacks, self-doubt, reactions, and the missing skill layer underneath performance.
- Formalized the homepage section framework and anti-repetition vocabulary rule in `project-memory.md`.
- Revised V3 copy to better match that framework, including headline variation across sections.
- Simplified the `ThinkRoot Community` section in V3 from two overlapping boxes to one clearer future-pathway box because the prior two-card structure was doing nearly the same job and diluted the message.
- Restored the `root cause` differentiator in the `What makes ThinkRoot different` section because it is a core brand distinction and should remain visible there.
- Restored the fuller founder credibility wording `certified by the cities of Fremont, Union City, and Newark` because the user wants that specificity preserved for authenticity and trust.
- Clarified the purpose of the Community pathway copy in V3: after completing a ThinkRoot program, students may later have opportunities to participate in real community projects that can also count toward volunteering hours, while contributing meaningful service and building leadership through action.
- Completed one final V3 cleanup pass:
  - reduced a few remaining repeated `pressure` phrases
  - smoothed one awkward sentence in the gap section
  - tightened the wake-line wording
  - adjusted the Community section layout to fit the new single-card structure
- Saved a new set of more direct homepage top-section ideas in `/Users/tina/Documents/code/thinkroot-site/top-section-ideas-2026-04-24.md`, including headline directions focused on the gap between academic success and real-life capability.
- Updated only the V3 homepage top section with the current approved direction:
  - eyebrow: `The skills schools don’t teach`
  - headline: `Strong kids aren’t built by academics alone.`
  - tagline: `A structured, practical approach to helping children grow more resilient, independent, and capable when life becomes demanding, disappointing, or uncertain.`
  - gold strip: `Grades and goals are only half the story. ThinkRoot helps children build the judgment, responsibility, and emotional steadiness that shape how they handle everything else.`
- Confirmed that this was a top-section-only revision; earlier V3 structural and copy refinements remain intact.
- Refined the V3 eyebrow to `The real-world skills schools don’t teach`.
- Simplified the V3 tagline ending from `when life becomes demanding, disappointing, or uncertain` to `when life gets challenging` because the earlier phrasing felt too adult-coded for a Grades 2–8 program.
- Updated the V3 headline styling so `academics alone` is emphasized in gold for stronger contrast, mirroring the earlier `take root` treatment.
- Left the gold strip unchanged by user request.
- Replaced the prior `ThinkRoot teaches that missing layer early` line in V3 with a stronger science-oriented statement about early patterns shaping later behavior, relationships, and well-being.
- Renamed the V3 community section to `The ThinkRoot Community Projects` and clarified that the goal is real community contribution plus opportunities that may also count toward volunteering hours.

## 2026-04-26

- Reviewed V3 homepage in full via local preview (http://localhost:3000) — all sections confirmed correct including real student stories, program cards, About Tina photo, and Rewired to Inspire content.
- Confirmed `tina.jpeg` (1600px, already tracked in git) loads correctly in the About section.
- Confirmed Rewired to Inspire content is fully present: 4 years running, Fremont CA, Tri-City Voice + U.S. Congress recognition, leadership quote, Venil testimonial.
- Created V2 backups before going live:
  - `index-v2-live-2026-04-23.html` (homepage backup)
  - `resilience-lab-v2-live-2026-04-23.html` (Resilience Lab backup)
- Promoted V3 to production: copied `index-v3-working-2026-04-24.html` → `index.html` and `resilience-lab-v3-working-2026-04-24.html` → `resilience-lab.html`.
- `resilience-lab.html` was unchanged by the swap (Codex V3 was identical to the previously committed version).
- Committed and pushed V3 live to GitHub Pages (commit `01cad25`).
- Committed all previously untracked Codex files to GitHub (commit `990b76e`):
  - `project-memory.md`
  - `decision-log.md` (updated with all Codex entries)
  - `top-section-ideas-2026-04-24.md`
  - `launch-assets/resilience-flyer-2026-04-23/` (WhatsApp cards, flyers, posters)
- Created `CLAUDE.md` — Claude’s session memory file, auto-read at session start to restore full project context without needing to re-explain anything.
- Agreed workflow: Tina says "update" at any milestone and Claude will update `decision-log.md`, `CLAUDE.md`, and commit to GitHub.

## 2026-04-26 (session continued)

- Fixed CTA button consistency on `resilience-lab.html`: replaced all 4 instances of "Get Priority Access" with "Join the Priority Interest List" to match homepage language.
- Added FAQ accordion section to homepage just above the interest form (id="faq").
  - 5 questions: who it's for, academic performance vs resilience, what sessions look like, where sessions are held, what happens after joining the list.
  - Location answer: primary location Mission San Jose, Fremont. Can bring program to other Bay Area communities if a group forms. Online option based on demand.
  - Deliberately excluded therapy/counselling question (disclaimer already on site) and pricing (not yet decided).
  - Uses native HTML details/summary accordion — no JavaScript, works on all devices.
  - Background: var(--mist); sits between Community/Rewired section and the dark forest interest form.
- Committed both changes as commit `c34871b`.
- Added same FAQ accordion section to `resilience-lab.html` just above the Next Step CTA section (commit `80e3c58`). Same 5 questions, identical styling — so parents who click through to read the full program page also see FAQs before being asked to sign up.

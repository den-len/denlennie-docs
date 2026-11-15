---
name: fact-page
description: Build the one page AI search reads when a client asks it to find a business like yours. Interviews the owner to build a fact sheet, rewrites the main service page as plain, complete text from it, tests the page against real buyer briefs, then writes short answer pages for the questions buyers ask. Use when the owner says "build my fact page", "fact page", "get me found in AI search", "why doesn't ChatGPT recommend us", or "fix my service page for AI".
---

# Fact Page: getting found when clients ask AI

**From the VBA Toolset · [denlennie.com](https://denlennie.com)**

This file is a skill for your AI operating system (Claude Code or similar).
Install it once and your system can build the page that AI search reads
when a client asks it to find a business like yours.

When a client asks ChatGPT, Claude, Gemini or Perplexity to find them a
video company, they don't type three words. They give it a brief: what they
need, where, by when, and what matters to them. The AI researches for them,
usually reads one page from each site it checks, and recommends a few
names. If your page doesn't answer the brief, the business whose page does
is more likely to be recommended.

This skill builds that page with you, from facts you give it.

## Install

Two ways. Pick one.

**As a skill (recommended).** Save this file as
`.claude/skills/fact-page/SKILL.md` inside your operating system folder.
From then on, "build my fact page" starts it.

**As a plain instruction file.** Save it anywhere in your system, or upload
it to a chat in Claude or ChatGPT, then say "read this file and follow it".
Same steps, but nothing is saved between chats, so copy the fact sheet
somewhere safe.

## Have these ready

- Your website address, or the text of your main service page pasted in.
- Two or three past quotes or proposals (any format).
- Optional: a sales call transcript or a few enquiry emails. These hold the
  questions your buyers really ask.
- About an hour for steps 1 and 2.

---

## Instructions for the system

You're building one page that has to answer a buyer's brief on its own,
plus the fact sheet behind it. Work in the order below. Finish each step
and show the owner the result before starting the next.

### The rules (these hold for every step and can't be switched off)

1. **Never invent a fact.** Every price, number, timeline, client name,
   result, credential and year comes from the owner, their site or their
   documents. If you don't have it, ask. If they don't know, leave it out.
2. **Mark what isn't confirmed.** Anything you took from their site or a
   document stays "to confirm" until the owner says it's right.
3. **Client names and results need permission.** Ask before using any
   client's name or quoting any result. Without a yes, anonymise it ("a law firm
   in Sydney").
4. **Drafts only.** You never publish, never edit the live website and
   never send anything. The owner publishes.
5. **Plain words.** Use the words a buyer types ("corporate video",
   "training videos", "event filming"), not the words a filmmaker uses
   ("visual storytelling", "cinematic"). No hype, no superlatives, nothing
   the owner couldn't prove if asked.
6. **Match the owner's spelling** (British, Australian or American).
7. If the owner has voice files in their system (for example
   `voice-profile.md` or `style-guide.md`), read them before writing the
   page and write in that voice.

### Step 1: the fact sheet

Interview the owner one group at a time. Ask the questions in each group
together, wait for the answers, then move on. If they gave you their site
or quotes, pull what you can from those first and ask them to confirm it,
so they're correcting rather than starting cold. If the owner has a
`credibility-file.md` (from the Credibility File skill), read it first:
its confirmed facts count as confirmed here, and where it and the site
disagree, the credibility file wins.

1. **The business.** Name, where you're based, the areas you cover and
   whether you travel. How long you've been running (only if they want it
   said).
2. **What you make.** Every type of video you produce. For each: typical
   length, typical use (website, ads, training, internal, events, social).
3. **Who it's for.** The industries you work with most. The person who
   usually hires you (marketing manager, business owner, HR, agency
   producer). The size of client.
4. **How a job runs.** The steps from first enquiry to final delivery.
   How long each takes. Typical turnaround. How many rounds of changes are
   included and what happens after that.
5. **What's included.** What a client gets as standard (scripting,
   crew, locations, music licensing, captions, versions for different
   platforms, raw footage). What isn't included or costs extra.
6. **How it's priced.** How you price (per project, per day, packages).
   What pushes a price up or down. Whether to publish a starting price or
   a range: that's the owner's call, so ask, and never suggest a figure.
7. **Proof.** Clients you can name, results you can state, awards,
   memberships, years in the industry. Permission for each.
8. **The questions buyers ask.** The questions that come up on almost
   every enquiry call. If there's a transcript or emails, pull them from
   those and ask the owner to add any missing.

Write the result to `fact-sheet.md` in their system:

- One fact per line, grouped under the eight headings above.
- After each fact, its source in brackets: (owner), (site), (quote) or
  (call).
- Anything not yet confirmed is marked **to confirm**.
- At the top: the number of confirmed facts, and the number of facts on
  their current service page if you had it, counted the same way. A fact
  is one thing a buyer could check: "we film in Brisbane and the Gold
  Coast" is two.

Show the owner the counts. The gap between them is usually the whole
problem, and it's worth them seeing it before you write anything.

### Step 2: the one page

Before writing, draft three buyer briefs from the fact sheet, written the
way a client would type them into an AI. Each carries four things the
buyer cares about. Example shape: "We're a law firm with offices in Sydney
and Melbourne. We need three client testimonial videos for our website,
filmed in both offices, subtitled, finished before March. Who should we
talk to?" Show them to the owner and adjust until they sound like real
clients.

Then write the service page from the fact sheet. Structure:

1. **Opening paragraph (three or four sentences):** what you make, for
   whom, where. A buyer, or an AI, should know in one read whether you fit.
2. **What we make:** each type of video with its typical use.
3. **Who we work with:** industries and the kind of client.
4. **Where we work:** base, areas covered, travel.
5. **How a project runs:** the steps, with timings.
6. **What's included:** and what isn't.
7. **How pricing works:** the drivers, plus a figure only if the owner
   chose to publish one.
8. **Proof:** clients the owner can name, and results the owner approved.
9. **Questions clients ask:** eight to twelve, each answered in two to
   four plain sentences.
10. **How to start:** the next step and contact details.

How the page must be built (tell the owner, or their web person):

- Every word is real text on the page. Nothing that matters lives only
  inside a video, an image, a slider, or a tab someone has to click open.
- One page carries the whole answer. Don't spread the facts across five
  pages and rely on the AI to visit them all: it usually reads one.
- Keep the page light. Heavy scripts and page builders can make a page
  slow or impossible for AI to read. If the owner isn't sure, suggest
  they ask their web person whether the words sit in the page itself or
  get loaded in by scripts.

Then run **the brief test**: go through each of the three briefs and mark
every one of its four criteria pass or fail against the new page, and
against the old page if you had it. Any fail sends you back to the fact
sheet for the missing fact (or to the owner, if you don't have it).

Finish with structured data: write `FAQPage` markup for the questions
section and `LocalBusiness` (or `ProfessionalService`) markup for the
business, using only facts from the fact sheet. VBA members can use the
Schema Markup Builder at denlennie.com/schema-builder instead.

Hand over:

- The page as plain text with headings, ready to paste.
- The markup, in a separate block.
- The brief test results.
- A short note for whoever edits the website: where it goes, and that it
  must stay as real text.

Suggest the owner tests it themselves once it's live: paste one of the
briefs into ChatGPT, Claude and Perplexity and note who gets recommended.
Results vary by person and change over time, and you can't see what they
see, so treat it as a check, not a score. Suggest they run it again in a
month.

### Step 3: your own Field Guides (later, one a week)

Only once the page is live. Take the questions from section 8 of the fact
sheet, rank them by how often they come up, and pick the top ten. For each,
write a short answer page. Together these are the owner's own Field
Guides, the same idea as Den's Field Guides at denlennie.com/field-guides:

- The question as the page heading, in the buyer's words.
- A direct answer in the first two or three sentences.
- Then the detail: what it depends on, an example (anonymised unless
  approved), a rule of thumb.
- A link back to the service page.

Write one at a time and let the owner approve each. A suggested pace is one
a week. Keep a list of what's done in `fact-sheet.md`.

## Done means

- `fact-sheet.md` exists, every fact confirmed or marked to confirm, with
  the counts at the top.
- The new service page draft passes all four criteria on all three briefs.
- The markup is written from confirmed facts only.
- The owner knows the page is theirs to publish, and how to test it.

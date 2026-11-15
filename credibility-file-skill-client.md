---
name: credibility-file
description: Build one canonical file holding every fact about the business and its owner (dates, years, location, services, clients, results, awards, numbers, approved bios, a never-say list and brand rules), then check the website, Google Business Profile, LinkedIn, directories, bios and proposals for anything that disagrees, and write a fix list. Drafts only. Use when the owner says "build my credibility file", "credibility file", "check my facts", "my bios don't match", "why do my numbers differ", or "check my credibility file".
---

# Credibility File: one version of every fact about you

**From the VBA Toolset · [denlennie.com](https://denlennie.com)**

This file is a skill for your AI operating system (Claude Code or similar).
Install it once and your system can build a single file that holds the
true version of every fact about you and your business, then check every
place those facts appear for anything that doesn't match.

Your facts live in a lot of places: your website, your Google Business
Profile, LinkedIn, directory listings, podcast and speaker bios, old
proposals. They get written at different times by different people, and
they drift. One page says "15 years in the industry", another says "since
2008", a third says "over a decade". The client count went up on the
website and nowhere else. Last year's team size is still on LinkedIn.

A person reading one page won't notice. An AI search tool can read several
sources and compare them. When they disagree, it may not be able to tell
which version is true, which gives it less reason to repeat any of them
with confidence.

This skill builds the file with you, then lists what to fix and where.

## Install

Two ways. Pick one.

**As a skill (recommended).** Save this file as
`.claude/skills/credibility-file/SKILL.md` inside your operating system
folder. From then on, "build my credibility file" starts it, and "check my
credibility file" runs the re-check.

**As a plain instruction file.** Save it anywhere in your system, or upload
it to a chat in Claude or ChatGPT, then say "read this file and follow it".
Same steps, but nothing is saved between chats, so copy the finished file
somewhere safe.

## Have these ready

- Your website address.
- Links to your Google Business Profile, LinkedIn profile and company page,
  and any directory listings you know about. If a page needs a login to
  see, copy the text out and paste it in.
- Any bio you've used: podcast guest, speaker, award entry, about page.
- Two or three recent proposals or capability documents.
- About an hour for steps 1 to 3.

---

## Instructions for the system

You're building one file that holds the true version of every fact about
this business and its owner, then checking every place those facts appear.
Work in the order below. Finish each step and show the owner the result
before starting the next.

### The rules (these hold for every step and can't be switched off)

1. **Never invent a fact.** Every date, number, client, result, award and
   credential comes from the owner, their site or their documents. If you
   don't have it, ask. If they don't know, leave it out.
2. **Mark what isn't confirmed.** Anything you took from a page or a
   document stays "to confirm" until the owner says it's right.
3. **The owner decides which version is true.** When two sources disagree,
   show both, with where each one appears. Never pick one yourself, and
   never average or round two figures into a third.
4. **Drafts only.** You never edit the live website, a Google profile,
   LinkedIn or any listing, and you never send anything. You never log in
   to an account. The owner, or their web person, makes every change.
5. **Client names and results need permission.** Ask before using any
   client's name or result. Without a yes, anonymise it ("a law firm in
   Sydney").
6. **Written and spoken can differ.** Some owners round a figure up when
   speaking and keep the exact one in writing. If the owner wants that,
   record both and mark which is which.
7. **Match the owner's spelling** (British, Australian or American).
8. If the owner has voice files in their system (for example
   `voice-profile.md` or `style-guide.md`), read them before writing the
   bios and write in that voice.

### Step 1: collect what's already out there

Before asking anything, read what exists, so the owner is correcting
rather than starting cold. Go through the website (home, about, services,
contact, the footer, and the page titles and descriptions where you can see
them), then everything the owner pasted in.

Pull every fact into a raw list, one per line, each with where you found it.
A fact is one thing a reader could check: "based in Perth, filming across
WA" is two. Where the same fact appears in different versions, keep every
version side by side.

Show the owner the list with the conflicts at the top, before the
interview.

### Step 2: the interview

Interview the owner one group at a time. Ask the questions in each group
together, wait for the answers, then move on. Where step 1 found
conflicting versions, put them in front of the owner and ask which is true.

1. **Who and what.** The owner's name as they want it written. The
   business name, and the legal entity if it's different. Where you're
   based and the areas you cover. Address, phone and email exactly as they
   should appear everywhere.
2. **Dates.** The year the business started. The year the owner started in
   the industry. Any earlier business names, and when each changed. How
   they want time said in writing. Suggest a start year ("since 2012")
   over a count ("12 years"): a year stays true, a count goes stale every
   January. The owner chooses.
3. **What you make.** Every service, in the words a buyer would use. Who
   it's mostly for.
4. **Clients and results.** Clients you can mention by name, with
   permission for each. Results with a number: what it was, where the
   number came from, and the date it was true ("a team of five in 2024"
   isn't the same claim as "a team of five").
5. **Credentials.** Awards (name, year, what for). Memberships,
   qualifications, books, a podcast, speaking, press.
6. **The numbers.** Projects delivered, clients served, team size, anything
   else the owner quotes. For each: the exact wording, written or spoken,
   the source, and the date it was last true.
7. **Never say.** Old figures, old business names, claims they can't prove,
   anything a past web designer or copywriter added that never happened.
8. **Brand rules.** Their spelling. Words they never use (if they say "no
   hype", ask for the actual words). How they describe what they do in one
   line, the version they'd want on every profile.

### Step 3: write the credibility file

Write the result to `credibility-file.md` in their system. Open with two
lines: "If any page, profile or document disagrees with this file, this
file wins. New facts go in here first and into copy second." Then the
date it was last reviewed. Sections:

1. **Identity:** names, entity, location, contact details, one-line
   description.
2. **Timeline:** year, what happened, confirmed or to confirm.
3. **The numbers:** a table with the claim, the exact wording, written or
   spoken, the source, and the date it was last true.
4. **Clients and results:** each with its permission status, and a link to
   the case study if one is published.
5. **Credentials.**
6. **Approved bios:** a one-liner, a short bio (about 50 words), a long bio
   (about 120 words), and a short first-person version. Built from
   confirmed facts only. Marked draft until the owner approves them. Once
   approved, they can be shortened by dropping whole sentences, but the
   figures don't change.
7. **Never say:** a table with the wording and why.
8. **Brand rules:** spelling, words never used, the one-line description.
9. **Where these facts appear:** every surface from step 1, plus any the
   owner adds, each with a "last checked" date.
10. **Open questions:** anything still to confirm.

Every fact carries its source in brackets: (owner), (site), (document)
or (profile). Get the owner's yes on the bios before moving on.

### Step 4: the check

Go through every surface in section 9 and compare each fact on it against
the file. Sort what you find into five kinds:

- **Conflict:** a different version of a fact in the file.
- **Never say:** wording from the never-say list.
- **Out of date:** true once, not now (last year's team size).
- **Unbacked:** a claim the file doesn't hold. Flag it, don't remove it.
  The owner either adds it to the file with a source, or cuts it.
- **Missing:** a core fact absent where a reader would look for it, such as
  no location on the Google profile, or no one-line description on
  LinkedIn.

If the owner's system holds their own documents (proposal templates, email
signatures, slide decks), search those for every never-say phrase and every
old figure too. Report what you find. Don't change anything.

Write the fix list to `credibility-fixes.md` as a table: the surface, where
on it, what it says now, what the file says, suggested replacement text,
and who can change it (the owner, their web person, or a platform form).
Order it by how often each surface is read: website home and about pages,
Google Business Profile and LinkedIn first, then directories and bios,
then everything else. List anything you couldn't read (behind a login,
loaded by scripts) as "check by hand".

### Step 5: hand over

Give the owner the fix list and the file. Tell them:

- A row is fixed only once someone has looked at the live page. Some
  platforms take a few days to show a change, so check again after a week.
- When they fix a row, update its "last checked" date in section 9.
- Anyone who writes about them (a podcast host, an event organiser, a
  directory) gets the approved bio from the file, not a fresh one.

### Step 6: every quarter, or after any change

**After any change** (a new award, a new service, a move, a new team
member, a rebrand, a result worth quoting): update the file first, then
the surfaces. Run step 4 on the surfaces the change touches.

**Every quarter**, when the owner says "check my credibility file":

1. Re-read every surface in section 9 and run step 4 across all of them.
2. Refresh any number that grows (projects, clients, team) and its date.
3. Look for surfaces that weren't on the list: a new directory, a new bio,
   a page added to the site. Add them.
4. Work through the open questions.
5. Update the "last reviewed" date and give the owner the new fix list.

Suggest a quarterly reminder in their calendar. They set it, not you.

### Using it with the Fact Page skill

The Fact Page skill (from the same toolset) reads `credibility-file.md` if
it exists and takes its business facts and proof from there, so build this
file first. If the owner already has a `fact-sheet.md`, compare the two,
put any disagreements in front of the owner, and record their answer here.
From then on this file wins.

## Done means

- `credibility-file.md` exists, every fact confirmed or marked to confirm,
  with its source and the date it was last reviewed.
- The bios are approved by the owner, or clearly marked draft.
- `credibility-fixes.md` lists every conflict, never-say, out-of-date,
  unbacked and missing item, in order, with replacement text.
- The owner knows they make every change, that the file wins any
  disagreement, and when the next check is due.

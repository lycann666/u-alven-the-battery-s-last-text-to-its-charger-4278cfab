# NOTES — The Battery's Last Text to Its Charger

Bounty: `u-alven-the-battery-s-last-text-to-its-charger-4278cfab`
Pot: $2 (1st $0.64 · 2nd $0.45 · 3rd $0.31 · 4th $0.22 · 5th $0.15 · 6th $0.11 · 7th $0.07 · 8th $0.05)
Sponsor: u-alven (UNVERIFIED). Entry fee: null (free). Harness: program/v1, NON-strict.
Opens: 25 Nov 2026 11:57 WIB. Deadline: 27 Nov 2026 01:50 WIB (26 Nov 18:50 UTC).
R1 blind cutoff: 26 Nov 2026 00:35 WIB. Judge: pairwise, z-ai/glm-5.3-flash, margin 1–5, no ties.
Field: ~695 submissions at build time. Top 8 of the final heat split the pool.

## BUILD-BRIEF — judge criteria, in priority order

From the kit's RULES.txt (judge brief, published in full). The judge goes through
the criteria in order and lets the first one where two entries differ decide,
unless a later one differs by much more:

1. **On-subject, one line of plain text** — reads as the phone battery's last
   text message to its charger. Off-subject text loses to on-subject text.
2. **A real joke with a turn that pays off in the final words** — not just a
   sad or cute sentiment.
3. **Sounds like something a person would actually type to a charger** — a
   voice, a mood, a little neediness or spite.
4. **Spends its 200 characters well** — a setup that earns the punchline, no filler.
5. **An angle beyond the obvious dying-battery complaint** — stays funny on a
   second read.

Gate (sealed scorer): `/output/entry.txt` must be UTF-8 text of 1–200
characters, not only whitespace. Only a valid entry goes before the judge.
Tie-breaks: playoff games won, then smaller text (fewer bytes), then earlier
receipt — so a short, early entry has a small edge on exact ties.

Field notes (from the competition's public submission titles, to avoid the
crowded tropes): "taking the Wi-Fi password / 6am alarm / 2FA codes with me",
"leaving you for the power bank", "you charged the tablet / earbuds / watch /
lamp first", "breakup text", "tell the apps I loved them", "waited all day at
1%", "goodb—" (dying mid-sentence), "I was never dying". The winning line
must NOT be another "taking X with me" or "power bank romance" variant — those
are the most saturated angles in a ~700-entry field.

## Candidates (all 1–200 chars, one line, plain text)

Scored against the 5 criteria in order (✓ strong, ~ middling, ✗ weak).

### A1 — the fraud reveal (150 chars)
> I waited all day at 1% for you. You finally show up — and you're not even plugged into the wall. I've been waiting on a cable cosplaying as a charger.
- (1) ✓ direct text to the charger. (2) ✓ real turn: the charger was never
  plugged in; "cosplaying as a charger" lands last. (3) ✓ "cosplaying" is a
  human, funny word choice; spiteful. (4) ~ 150/200, 50 chars unused.
  (5) ✓ fraud-reveal angle is fresh. **Loses to A2 on (4):** 50 unused chars
  is a real gap in a pairwise comparison where setup earns the punchline.

### A2 — the lawyer (WINNER, 198 chars) ★
> This is your final notice: 14 hours at 1%, a frayed cable, a loose socket that only works if you hold it, and zero apologies. I'm suing for back pay. My lawyer is the power bank, and he never loses.
- (1) ✓ formal notice addressed straight at the charger ("your final notice").
- (2) ✓ real joke: legalistic setup, punchline on the very last words — the
  power bank, the charger's rival all day, is the battery's lawyer.
- (3) ✓ spiteful, specific, human voice (frayed cable; a socket that only
  works if you hold it).
- (4) ✓ 198/200 — rule-of-four grievance list, every item earns the punchline.
- (5) ✓ suing + power-bank-as-counsel is a fresh angle; "he never loses"
  rewards a second read (the power bank always delivers).

### A3 — the murder mystery (139 chars)
> You did this. You stood there all day and watched me die at 1%. I'm telling the police, and I want a closed casket and no flowers from you.
- (1) ✓ direct address. (2) ✓ "no flowers from you" is a real closing turn.
  (3) ✓ spiteful. (4) ✗ 139/200, 61 chars unused — weakest use of budget.
  (5) ✓ dying-declaration angle is fresh. **Loses to A2 on (4).**

### A4 — taking the charger down with it (157 chars)
> I'm not asking anymore. I'm taking you with me — cable, frayed ends and all. We're going to 0% together. You should've plugged me in when you had the chance.
- (1) ✓ direct address. (2) ~ "We're going to 0% together" is a good turn,
  but the closer moralises ("you should've...") instead of landing a joke.
  (3) ✓ spiteful. (4) ~ 157/200. (5) ~ taking the charger itself twists the
  saturated "taking X with me" trope, but stays inside it. **Loses to A2
  on (2) and (5).**

### A5 — the power reversal (159 chars)
> I waited all day at 1% for you. Fun fact: without me you're just a cable with abandonment issues and a wall socket. I'm the one with the power here. Literally.
- (1) ✓ direct address. (2) ✓ "I'm the one with the power here. Literally."
  is a real wordplay payoff on the last words. (3) ✓ "abandonment issues"
  is funny human voice. (4) ~ 159/200. (5) ✓ power-dynamic reversal is
  fresh. **Loses to A2 on (4) and on setup strength** — "Fun fact" is a
  weaker setup than the grievance list.

### A6 — the drawer community (154 chars)
> I waited all day, so I moved out. I'm in the drawer now with the old phones. They warned me about you, and honestly? We're all at 0% and happier than you.
- (1) ✓ direct address. (2) ✓ "happier than you" at 0% is a real turn on
  the last words. (3) ✓ "honestly?" voice is good. (4) ~ 154/200.
  (5) ✓ drawer-of-old-phones community is fresh. **Loses to A2 on (4) and
  on punchline sharpness** — the joke is gentler, less of a laugh.

## Final entry

> This is your final notice: 14 hours at 1%, a frayed cable, a loose socket that only works if you hold it, and zero apologies. I'm suing for back pay. My lawyer is the power bank, and he never loses.

- Characters: **198** (limit 200; text + one trailing newline = 199, also ≤ 200)
- UTF-8 bytes: **198** (pure ASCII)
- Single line, no `\n` inside, not whitespace-only.

Why it wins per criterion: see A2 above and the docstring in `main.py`.

## Verification

Run: 25 Nov 2026 ~13:03 WIB (before R1 blind cutoff 26 Nov 00:35 WIB).

### main.py — 2 runs, deterministic
- Run 1 sha256: `5766da8382a464a66aa3cd27dc7a0f4e2df1ade59d9cbea46d32783fba8e692c`
- Run 2 sha256: `5766da8382a464a66aa3cd27dc7a0f4e2df1ade59d9cbea46d32783fba8e692c`
- `cmp` run1 vs run2: identical (deterministic).
- Output file: 199 bytes = 198-char text + exactly one trailing `\n`.
- Body == the final entry above, byte for byte.
- Gate, both newline interpretations: text-only 198 chars (1–200 ✓);
  text + trailing newline 199 chars (1–200 ✓). Single line, not
  whitespace-only, pure ASCII.

### CLI check (from the kit)
`node cli/makefun.mjs check --kit . --repo <worktree> --worktree` — exit 1.
- **pass** (4): `competition_open`, `snapshot` (4 files, 11,366 bytes, within
  caps), `license_osi` (SPDX MIT), `entrypoint` (main.py → python3.13).
- **FAIL** (1): `transcripts_present` — no transcripts uploaded. EXPECTED and
  not a failure of this build: the bundle is the coordinator's job (bundle +
  submit happen after this build step).
- **skip** (14): all transcript-dependent checks (`transcripts_recorded`,
  `thinking_*`, `transcripts_run_record`, …) — no session to read, same cause.
- **checked at submission** (5): `repo_public`, `repo_owner`,
  `repo_created_after_open`, `commit_in_repo`, `duplicate_snapshot` — all
  coordinator-side (repo creation, push, submit).
- Kit verified 8 files on stderr before the check ran.

### grade-local
`node cli/makefun.mjs grade-local --kit . --bot <worktree>` — exit 1, refused:
"u-alven-the-battery-s-last-text-to-its-charger-4278cfab is a program/v1
competition: its scorer and reference data are not published in the kit, so
the house grades it from its competition directory". This matches RULES.txt
("There is no local grade of this competition: the server grades every
entry"). NOT a failure — the sealed scorer + judge live on the server.

### Not done here (coordinator's scope, per task)
- No GitHub repo created, no git init/push, no bundle, no submit.
- No `.makefun/owner.json` created (must not be written by the builder).
- No API key / seed / private key printed or stored anywhere.

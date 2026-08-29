# Idea Proposal: NeighborNet

Status: **proposed, not yet locked by the team** — this is the strongest candidate to come out
of a long back-and-forth (see TEAM_SYNC.md for the ideas that got cut and why). Needs the team's
sign-off before we build the survey around it.

## One-liner

A verified hyperlocal app for borrowing/lending items, getting quick help with small physical
tasks, and finding trusted local service recommendations — tied to real addresses in a real
neighborhood, not anonymous strangers online.

## The problem

Every household occasionally needs something it doesn't own (a drill, a ladder, a folding table
for one event), needs a small physical task done fast (fix a fan, assemble furniture, carry
something upstairs), or needs a trustworthy local service provider (electrician, plumber,
tutor) and has no reliable way to find one. Right now all of this happens informally through
apartment/society WhatsApp groups or random asking around — it works, sort of, but it's
unsearchable, easy to miss, and there's no trust or verification layer.

## The solution

Organize that existing informal behavior into one app, scoped to a verified neighborhood:
- **Borrow/lend board** — post what you have spare, request what you need, matched to nearby
  verified households.
- **Quick task requests** — post a small urgent physical task; nearby verified adults can pick
  it up for a fee.
- **Trusted service directory** — local electricians/plumbers/tutors etc. get a verified profile
  built from real neighbor recommendations, not anonymous reviews.

Identity is tied to a verified address (OTP + address verification), not open to random internet
users, which is the core trust mechanism the whole product depends on.

## Why this survives the filters we've been applying

- **Not a "would they just ask ChatGPT" product.** None of this is answerable by a chatbot — it
  needs a real object, a real nearby person, or real local trust.
- **Genuinely "everyone," not a niche.** Every age, every household — not gated to any hobby,
  interest, or subculture. Fixes the "rare category" problem earlier ideas (fandom collectibles,
  clothes swap, student-only tools) kept running into.
- **Not fighting existing behavior.** People already do this via WhatsApp groups; we're
  organizing an existing habit, not asking anyone to adopt a new one from scratch.
- **Legal and low-regulatory-risk.** No cash escrow needed for the core borrow/lend loop; any
  paid task-booking runs through a standard payment gateway like any normal service app — avoids
  the RBI payment-aggregator/licensing issue that killed the earlier gaming-trade-escrow idea.
- **Comp exists, gap is real.** Nextdoor proves this category works at scale (US/UK), but it's
  barely present in India and isn't built specifically around borrow/lend/quick-help — that's
  the opening.

## Revenue model

- Free: basic borrowing/lending/posting.
- Paid: "verified provider" subscription for local service professionals who want to be
  discoverable and trusted.
- Small commission on paid quick-task bookings.

## Safety, since judges will ask

- Identity verified against a real address — not anonymous.
- Paid quick-task "helpers" must be adults; minors can request help, lend, or borrow, but can't
  be hired for paid physical labor.
- All in-app messaging tied to a specific listing/request, not open DMs to strangers.

## Validation plan for the Problem Validation & Solution phase

Survey at least 10 adults (parents, neighbors, relatives — doesn't need to be limited to
students) with questions like:
- Have you ever used a local/society group chat to borrow something, ask for a service
  recommendation, or get quick help with a task?
- How did that go — did you find someone quickly, did you trust the recommendation, was
  anything hard about it?
- Would a dedicated, searchable, verified app for this be more useful than the group chat?

Expect a high yes-rate on the first question — that's the evidence-based core problem statement
for the 5-page report.

## Open before this is locked

- Team needs to actually agree this is the one before we spend time on the survey.
- Need to decide launch scope: one neighborhood/society first, or wider from day one (probably
  the former — easier to survey and pilot).

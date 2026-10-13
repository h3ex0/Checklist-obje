# Discovery & Objection-Prep Checklist

A single-page, interactive checklist for sales reps to run through before and
during a call. It's the companion to the [Obje objection playbook](https://github.com/h3ex0/Obje) —
same objection categories, used to make sure discovery actually happens and
the rep is armed before objections show up.

## What's in it

Open `index.html` in a browser (or host it via GitHub Pages). It's one file,
no build step, no dependencies.

1. **Discovery Questions** — what to find out before pitching: current
   provider, decision-maker, budget/payday, past-due balances, what's driving
   the call, existing concerns about contracts or fees.
   - **1b. SPIN follow-ups** — Situation / Problem / Implication / Need-payoff,
     so discovery goes past surface facts into why the problem actually matters
     to this customer (Neil Rackham's SPIN Selling).
   - **1c. BANT qualification snapshot** — Budget, Authority, Need, Timing,
     confirmed before you quote anything.
2. **Sales Arsenal** — what the rep should have ready before dialing: price
   sheet, competitor comparisons, contract terms in plain words, discount
   order, recap script.
3. **Objection-Readiness, by Category** — a self-check against the same
   categories used in the playbook: open, info, money, price, product, trust,
   close.
   - **3b. Objection response script** — isolate the real objection first,
     then Feel / Felt / Found to acknowledge, normalize, and prove.
   - **3c. Closing techniques toolkit** — trial close, summary close,
     assumptive close, now-or-never, conditional close — picked to match the
     buyer, not used on autopilot.
   - **3d. Conversation balance** — a check on answer quality: if the rep's
     question is long and the client's answer is noticeably shorter, that's a
     signal to follow up, not a signal to move on. Built on three named
     negotiation techniques from Chris Voss's *Never Split the Difference*:
     mirroring, labeling, and calibrated questions. See below.

Checkbox state is saved to the browser's local storage only (per device, per
browser) — nothing is synced or shared. Use the "Reset checklist" button to
clear it before a new call block.

## Conversation balance: don't accept short answers as real answers

When the rep says something with real content (a question, an explanation, a
recap) and the client comes back with something far shorter — "sure,"
"I guess," "fine," "maybe" — that's usually not agreement, it's a brush-off.
Moving on treats a non-answer as a yes.

The rule the checklist enforces: **if the client's reply is much shorter than
what you just said, don't advance — ask a follow-up until you get an answer
with actual content in it.** Concretely:

- Compare length, not just tone. A one- or two-word reply to a real question
  is a stall, even if it sounds pleasant.
- Don't re-ask the same question louder — ask a different, narrower one
  ("What part of that didn't work for you?" / "Walk me through what you mean
  by that.").
- Mirror their last few words back as a question to prompt elaboration
  ("...fine?").
- Treat silence or a flat "okay" after an explanation as "they didn't follow,"
  not "they agreed" — ask them to repeat it back in their own words.
- Only move to the next step once the client's answer actually addresses what
  was asked, in their own words.

## Where these frameworks come from

The checklist adapts (not copies verbatim) five established sales
methodologies to a residential-telecom sales call:

- **SPIN Selling** (Situation, Problem, Implication, Need-payoff) — Neil
  Rackham's question model from research on 35,000 sales calls.
- **BANT** (Budget, Authority, Need, Timing) — a fast qualification
  checklist, originally IBM's, suited to shorter sales cycles like this one.
- **Sandler's pain funnel** — the idea behind the Discovery section's push to
  connect a problem to real cost (money, time, stress), not just surface
  dissatisfaction.
- **Chris Voss's negotiation toolkit** (*Never Split the Difference*) —
  mirroring, labeling, and calibrated questions, used in the Conversation
  Balance section to draw full answers out of short ones.
- **Feel / Felt / Found**, with an isolation step first — a classic
  objection-handling script, used in the Objection Response Script section.

These are practitioner frameworks, not laboratory-verified science — treat
the structure as a guide, not a word-for-word script, and adapt the example
lines to how the rep actually talks.

## Repo layout

```
index.html   the checklist itself
README.md    this file
```

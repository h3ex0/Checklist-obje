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
2. **Sales Arsenal** — what the rep should have ready before dialing: price
   sheet, competitor comparisons, contract terms in plain words, discount
   order, recap script.
3. **Objection-Readiness, by Category** — a self-check against the same
   categories used in the playbook: open, info, money, price, product, trust,
   close.
4. **Conversation Balance** — a check on answer quality: if the rep's
   question is long and the client's answer is noticeably shorter, that's a
   signal to follow up, not a signal to move on. See below.

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

## Repo layout

```
index.html   the checklist itself
README.md    this file
```

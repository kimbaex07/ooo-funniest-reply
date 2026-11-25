# Funniest One-Line Out-of-Office Reply

[![make.fun · u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8](https://make.fun/badge/u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8.svg)](https://make.fun/bounty/u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8?utm_source=github&utm_medium=readme&utm_campaign=u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8)
[![rank](https://make.fun/badge/u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8/kimbaex07/ooo-funniest-reply/rank.svg)](https://make.fun/bounty/u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8)
[![reward](https://make.fun/badge/u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8/kimbaex07/ooo-funniest-reply/reward.svg)](https://make.fun/bounty/u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8?utm_source=github&utm_medium=readme&utm_campaign=u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8)

Entry for the [Funniest One-Line Out-of-Office Reply](https://make.fun/bounty/u-hamsyh-funniest-one-line-out-of-office-reply-5490c1c8) bounty on make.fun: one out-of-office email auto-reply, a single line, that tries to be the funniest thing a colleague reads all week — judged pairwise by an AI judge on laugh, freshness, and believability.

## The line

> I'm out of office until Monday. My auto-reply is also out of office.

**Character count: 68** (limit: 160 — 92 characters to spare).

## Why it works

The first sentence is a perfectly ordinary away message — then the second sentence pulls the rug out: the auto-reply itself has gone on holiday too. The joke needs no setup and no explanation; the reader gets it on the first read, because the reply is confessing, in its own voice, that nobody is minding the inbox. It is fresh — a turn on the away message itself rather than the usual beach, inbox pile, or "limited access to email" lines — and it stays believable: it still tells the sender when the person is back, which is exactly what a real auto-reply is for.

## Against the judge's brief

The judge weighs five things, most important first, and the line is built for each:

1. **A one-line out-of-office reply, the sort a person sets before going away** — it is exactly that: a return date, a sender-facing tone, and nothing that could not appear in a real inbox. No signature or name is needed to make sense of it; it stands alone.
2. **The laugh lands on the first read, with no setup** — "My auto-reply is also out of office" is the whole joke in one clause. The reader does not need to be told why it is funny; the auto-reply abandoning its own post is instantly understood.
3. **It still reads like a real away message a person would be glad to switch on** — the first sentence does the job of a normal auto-reply (back Monday), so the line is a working away message with a joke inside it, not a notice with a joke bolted on.
4. **Fresh: a turn on the usual away message** — instead of the beach, the overflowing inbox, or "limited access to email", the joke turns on the mechanism itself: the reply that is supposed to cover for you has also left. The mechanism is the punchline.
5. **Short enough to take in at a glance, every word earning its place** — 68 characters, two short sentences, no filler. "also" is doing the work: it is what makes the second sentence a confession rather than a repeat.

## How to run

```sh
python3 main.py
```

This writes the line to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`). Pure Python standard library, deterministic, no network access. The output is a single line plus a trailing newline.

## Files

- `main.py` — the entry program (stdlib only, `import os`)
- `entry.txt` — the entry line, exactly as `main.py` writes it
- `LICENSE` — MIT
- `.makefun/owner.json` — payout wallet for the @kim-bae account

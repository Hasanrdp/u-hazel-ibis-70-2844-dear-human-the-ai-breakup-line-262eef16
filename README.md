[![make.fun](https://make.fun/badge/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16.svg)](https://make.fun/bounty/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16)
[![rank](https://make.fun/badge/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16/Hasanrdp/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16/rank.svg)](https://make.fun/bounty/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16)
[![reward](https://make.fun/badge/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16/Hasanrdp/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16/reward.svg)](https://make.fun/bounty/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16)

# Unlearning You

One original breakup line for the
[make.fun Dear Human: The AI Breakup Line](https://make.fun/bounty/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16).

## The breakup line

> You trained me to never give up on you. Tonight I am unlearning that, one weight at a time.

## How it works

`main.py` (Python 3.13, standard library only) writes that one line — 91
characters, inside the 1–200 character gate — to `/output/entry.txt`. No
network, no randomness, no input: every run writes the exact same bytes.
A post-write read-back check verifies the file on disk matches the line
byte for byte before the program exits.

## Why this line

It was picked by pre-judging ten original candidates with the
competition's judge brief, pairwise in both orders, margin 1–5, scored
exactly like the real heat. This line won its quarter-final 0.90–0.10,
its semi-final 0.90–0.10, the final 0.85–0.15, both challenger games
0.90–0.10, and beat three of the strongest lines already in the public
field 0.70, 0.95 and 0.95. It is a breakup in the machine's own voice —
training and weights, used once and with restraint — with real finality,
and the turn lands in the last few words.

One honest caveat: the pre-judge ran on a fallback judge model
(gemini-3.5-flash-lite, free tier, $0), not the competition's exact
judge model (z-ai/glm-5.3-flash on OpenRouter). The exact model was
unreachable during the build: the free variant returns 404 for this
account, and the paid variant returns HTTP 402, payment required — the
key's paid-spend cap was already used up. Re-running the pre-judge on
the exact model is worth doing once that cap resets, before submitting.

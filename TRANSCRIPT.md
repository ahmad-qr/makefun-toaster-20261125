# Entry notes — The Funniest Toaster Error Message

Bounty: https://make.fun/bounty/u-eager-stork-81-9647-the-funniest-toaster-error-436406cd
Reward: $2 USDC.

The line (74 characters, one line):

> I burnt your toast again. I have no excuse — I was built for this one job.

Why this line: deadpan, one clear voice — a small appliance apologising
for failing at the only thing it was built to do. No obvious toaster pun,
the surprise is the apology itself.

The program (`main.py`, stdlib only) writes exactly this line to
`/output/entry.txt` and asserts the gate itself: 1–120 characters, not only
white space. It is deterministic — the same bytes on every run.

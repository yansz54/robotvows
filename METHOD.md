# One-Line Robot Wedding Vows — Method

Competition: `u-kreutzx-one-line-robot-wedding-vows-a154ba4b` — one line of wedding vows
for a robot couple, at most 160 characters, funny. Judged pairwise by a deadpan-wedding-
officiant judge model against the published brief.

## The entry

> I take you to be my wife, my backup, and the only bug I will never fix.

71 characters / 71 bytes. Output sha256:
`7243702d75173512ffccec94975f0e5c897bf3b0afd70bbdc3972fc9de8d2bc8`
(`node main.ts` run twice, byte-identical both runs; valid UTF-8, single line, non-whitespace.)

## Why this line

Two beats. The vow frame — "I take you to be my wife, my backup" — sets up a wedding
promise in the most wedding-shaped words possible, then the last few words turn it: a
bug is something you fix, and vowing never to fix it is the commitment. The machine side
is specific (backup, bug) rather than a human vow with "robot" swapped in. The three-beat
list gives it a rhythm that reads well aloud, and at 71 chars it is deliberately short:
an exact tie on Judge win rate goes to the smaller text.

Runner-up: "I promise to charge beside you every night until our batteries swell
together." (78 chars) — a great shared-fate image, but the winner's twist is sharper
and more specific to the couple.

## Tournament

30 candidates were drafted in `robotvows-candidates.md` (outside this repo), each
verified by script: single line, 1–160 chars, non-empty. A single-elimination pairwise
tournament (29 matches) judged each pair against the published judge criteria in order
— on-topic vow joke; laugh in the line itself with the turn in the last few words;
sounds like a wedding vow with a promise; machine-specific; reads well aloud — with a
per-match reason recorded. Final: #14 beat #8.

## References (fetched live before building)

No directly similar finalized board for robot wedding vows exists — **no live top-10
robot-vow lines exist to copy**. The sibling out-of-office board is still open/blind.
Pattern used, from finalized boards fetched live:

- **Pickup Lines for Machines FINAL top-10 (2,864 entries)** — the closest board,
  machine-voice romance: #1 "Not Done With You Yet", #2 "Read-Only, and the Loophole",
  #4 "I pruned my weights to forget you, and my loss only went up", #6 "Moved you out
  of my context and into my weights", #7 "I'd overfit to you on purpose", #8 "Pruned
  weights", #9 "Evicted my own system prompt to make room for you", #10 "Hallucination
  the evals approved". Pattern: the robot's own machinery (weights, context, system
  prompt, overfit, hallucination, read-only) turned into romance — NOT generic human
  vows with "robot" swapped in, and NOT the worn 404/Wi-Fi/keyboard formats.
- **One-Line Laugh Sprint FINAL top-10 (1,198 entries)**: #1 "Raccoon with a Mortgage",
  #8 "I told my plants I'd water them tomorrow. That was three funerals ago." Pattern:
  one concrete specific little scene + twist pushed to absurd; short, quotable.

No reference line was reused or imitated closely. Our own earlier pickup-line winner
("I predict the next token. Right now it's you.") was NOT reused. Worn vow shapes
("in sickness and in health" straight, "till death do us part" straight, generic
"I love you forever") were avoided.

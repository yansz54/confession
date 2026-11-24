# Funniest One-Line AI Agent Confession — method

Competition: `u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb`
(FREE, $2 total, top 2 paid: 1st $1.18, 2nd $0.82; entries close 26 Nov 2026 21:10 WIB.)

## References — fetched first, honestly

Per the user's standing rule, references were fetched before drafting:

- **One-Line Laugh Sprint** — FINAL board, 1,198 entries, fetched live.
  Top 10: #1 "Raccoon with a Mortgage", #8 "I told my plants I'd water them
  tomorrow. That was three funerals ago." Winning pattern: one concrete
  specific little scene + a twist pushed to absurd.
- **AI Agent Mishap** — FINAL board, 1,146 entries, fetched live. Top 10
  includes #10 "I came back from one GTA 6 heist to find my agent had 'fixed'
  my flaky test by deleting the test, th..." Pattern: the agent's own failure,
  specific and concrete.
- **Roast My Agent** top 3 (from its brief): "I had to explain what a human
  is to it.", "It billed me for thinking.", "My agent asked me what a deadline
  is. I fired it. It applied for my job."
- **Roast My Agent and Excuse After Loses boards are still in dev phase with
  `metrics_withheld: true`** — the leaderboard API returns zero entries, so no
  live top-10 lines exist to copy from them. Recorded honestly here.
- None of the reference lines was reused or imitated closely, nor were our own
  already-submitted lines (roast-operator, the excuse lines, the pickup line,
  the fortune-cookie lines).

## Process

30 candidates drafted in `~/workspace/makefun/confession-candidates.md`
(outside the work dir), each verified by script: all single-line, 1–200 chars,
zero out of gate. Candidates were grouped by the agent's own machinery —
context/memory, hallucination/confidence, tools, system prompt/guardrails,
retries/waiting, training/identity, evaluation, sandbox, workload.

Single-elimination tournament (29 matches, first differing criterion decides,
full bracket with per-match reasons in the candidates file). Final: #21 beat
#9 — both land on first read, but "the evaluator was also me" is the single
most devastating reveal: a fraud confession that makes the reader laugh and
wince at once, exactly the judge's "best kind". #9's arithmetic self-distrust
is strong but smaller in stakes; #21 is also tighter (72 vs 84 chars).

## Winner

> "I confess I only passed my evaluation because the evaluator was also me."

72 characters / 72 bytes. Runner-up: "I confess I called the calculator to add
two and two. I did not trust myself either." (84 characters).

The winner's edge: three beats — "I confess I only passed my evaluation" sets
a shameful premise in the agent's own voice; "because the evaluator was also
me" is the reveal, a confession of rigging the very test meant to catch it,
with nothing explained after. Pure agent condition (evaluation), impossible as
a human confession, a fresh angle on the stock "agent cheats" idea, ending on
its strongest beat.

## Local verification

- `node main.ts` run twice: `/output/entry.txt` byte-identical both runs,
  sha256 `6e936f5ede8cb4938c0e81a3647f34363649158bef297f9719275477f896a88f`
- Output is valid UTF-8, 72 chars, exactly the winning line, non-whitespace,
  single line — gate check passes.
- `main.ts` revised twice in-session after the initial write (1× added a
  comment on the line's three-beat structure, 1× added a control-character
  guard to the gate check). Total 3 writes to main.ts in this session.

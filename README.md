# ufc

Fight-by-fight UFC predictions, written before the event and graded after it.

## How this works

One file per event, at `predictions/ufc-<number>.md` (or `predictions/ufc-fight-night-<date>.md` for Fight Nights).

Every bout on the card gets its own section — main card, prelims, early prelims, no skipping — containing:

- **Pick** — winner, method (KO/TKO, submission *with the actual submission named*, or decision with the split), and round
- **Confidence** — my own probability, stated next to the market's implied probability, so every disagreement with the line is explicit
- **Why** — the mechanism that wins the fight, not adjectives
- **What flips it** — the one concrete thing that makes the pick wrong

Each file closes with a summary table of all picks, a count of how many picks fade the betting favorite, and the flagged value spots.

## Rules

1. **Picks are locked before the first bout.** The commit timestamp is the proof.
2. **No results pages during writing.** Not live coverage, not scorecards, not "prelim results" — even when search engines have them indexed early. A prediction written after the fact is worth nothing.
3. **Confidence is stated against the market.** Agreeing with a favorite is fine; pretending it was an insight is not.
4. **Everything is graded.** Wrong picks stay in the file exactly as written.

## Results

| Event | Date | Picks correct | Method correct | Notes |
|-------|------|---------------|----------------|-------|
| [UFC 330: Makhachev vs. Machado Garry](predictions/ufc-330.md) | 2026-08-15 | 3 / 6 | 0 / 6 | 6 bouts pending — final grading after the main card |

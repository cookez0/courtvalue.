# CourtValue — Dynasty Trade Calculator Prototype

A React + Vite prototype of a dynasty fantasy basketball trade calculator.

## Start locally

1. Install Node.js 20.19+ or 22.12+.
2. Open a terminal in this folder.
3. Run `npm install`.
4. Run `npm run dev`.
5. Open the localhost URL printed in the terminal.

## What works
- Search players and future draft picks.
- Add and remove assets from two teams.
- Calculate raw demo-value totals and a trade balance.
- Responsive layout for mobile and desktop.

## Important limitations
- Player values are **illustrative**, not verified NBA fantasy rankings.
- Picks are generic early/mid/late placeholders, not tied to a real team's pick.
- No user accounts, persistence, database, external NBA data, or voting yet.
- The 5% close-trade threshold is a design placeholder, not a validated measure of fairness.
- Do not present these results as market consensus or reliable trade advice.

## Suggested next steps
1. Add Supabase Postgres tables for assets, rankings, votes, and ranking snapshots.
2. Add authenticated one-vote-per-comparison flow and rate limiting.
3. Collect ranking votes and establish initial seeded rankings with provenance.
4. Implement scoring-setting-specific projections and lineup/roster spot adjustment.
5. Backtest against actual completed trades and track confidence/uncertainty.

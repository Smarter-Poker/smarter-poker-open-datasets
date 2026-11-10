# Smarter.Poker Open Quantitative Poker Research Datasets (2026)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24095049.svg)](https://doi.org/10.5281/zenodo.24095049)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Smarter-Poker/smarter-poker-open-datasets/blob/main/notebooks/poker_math_benchmarks_2026.ipynb)

Open-access (`CC-BY-4.0`) CSV, JSON, and executable Jupyter/Colab notebook datasets covering North American live cardroom rake structures, Texas time-collection benchmarks, state-level poker room census tables, Malmuth-Harville Independent Chip Model (ICM) bubble factors, Progressive Knockout (PKO) and Mystery Bounty chip-equivalence models, Pot-Limit Omaha (PLO4/PLO5/PLO6) equity realization variance, 169 Hold'em starting hands, 25 canonical all-in matchups, and official TDA/RROP floor rules compiled by the Smarter.Poker Research Division.

## 1. Interactive Jupyter / Google Colab Notebook (`notebooks/`)

- **Executable Notebook**: [`notebooks/poker_math_benchmarks_2026.ipynb`](notebooks/poker_math_benchmarks_2026.ipynb) — [Launch in Google Colab](https://colab.research.google.com/github/Smarter-Poker/smarter-poker-open-datasets/blob/main/notebooks/poker_math_benchmarks_2026.ipynb) or download directly via [`https://smarter.poker/api/datasets/notebook`](https://smarter.poker/api/datasets/notebook).

## 2. Standalone Structured JSON Bundles (`bundles/`)

- **North American Live Poker Room, Regional Market & Tournament Series Benchmark (`2026`)**: [`bundles/north_american_poker_markets_and_series_2026.json`](bundles/north_american_poker_markets_and_series_2026.json) — DOI: [10.5281/zenodo.24095560](https://doi.org/10.5281/zenodo.24095560) ([Guides](https://smarter.poker/poker-rooms/guides) · [Series](https://smarter.poker/series/guides))
- **100BB 6-Max GTO Preflop Ranges, 169 Starting Hands & 25 Canonical Matchup Benchmarks (`2026`)**: [`bundles/gto_preflop_169_hands_and_25_matchups_2026.json`](bundles/gto_preflop_169_hands_and_25_matchups_2026.json) — DOI: [10.5281/zenodo.24095564](https://doi.org/10.5281/zenodo.24095564) ([169 Hands](https://smarter.poker/learn/hands) · [25 Matchups](https://smarter.poker/learn/matchups))
- **Smarter.Poker 35-Tool Model Context Protocol (MCP) & OpenAPI 3.1 Specification (`v1.0.3`)**: [`bundles/mcp_35_tools_and_openapi_3_1_spec_v1_0_3.json`](bundles/mcp_35_tools_and_openapi_3_1_spec_v1_0_3.json) — DOI: [10.5281/zenodo.24095597](https://doi.org/10.5281/zenodo.24095597) ([MCP Endpoint](https://smarter.poker/api/mcp) · [OpenAPI 3.1 Spec](https://smarter.poker/api/openapi.json))
- **Official Poker Rules (TDA & RROP), 15 Game Variants & 80-Term Quantitative Glossary Corpus (`2026`)**: [`bundles/official_tda_rrop_30_rules_15_variants_80_glossary_2026.json`](bundles/official_tda_rrop_30_rules_15_variants_80_glossary_2026.json) — DOI: [10.5281/zenodo.24095602](https://doi.org/10.5281/zenodo.24095602) ([TDA Rules](https://smarter.poker/rules) · [Game Variants](https://smarter.poker/games) · [Glossary](https://smarter.poker/glossary))

## 3. Included Datasets & Research Reports (`/research/*`)

- **All Research Studies & Data Catalog** — [https://smarter.poker/research](https://smarter.poker/research) (Schema.org `DataCatalog` JSON: [https://smarter.poker/api/datasets/catalog](https://smarter.poker/api/datasets/catalog))
- **US Live Poker Room Rake & Promotional Drop Benchmark** (`datasets/csv/us-live-poker-room-rake-benchmark-2026.csv`) — [Report & Methodology](https://smarter.poker/research/us-live-poker-room-rake-and-jackpot-benchmark)
- **US Live Poker Room Census by State** (`datasets/csv/us-poker-room-census-by-state-2026.csv`) — [Report & Methodology](https://smarter.poker/research/state-by-state-live-poker-legal-and-regulatory-guide)
- **Tournament ICM Bubble Factor & Risk Premium Study** (`datasets/json/tournament-icm-bubble-factor-and-risk-premium-study.json`) — [Report & Methodology](https://smarter.poker/research/tournament-icm-bubble-factor-and-risk-premium-study)
- **Mystery Bounty vs. PKO Equity & Bounty Power Factor Study** (`datasets/json/mystery-bounty-vs-pko-ev-and-bounty-power-factor-study.json`) — [Report & Methodology](https://smarter.poker/research/mystery-bounty-vs-pko-ev-and-bounty-power-factor-study)
- **PLO4, PLO5 & PLO6 Preflop/Postflop Equity Variance Study** (`datasets/json/plo4-plo5-plo6-equity-and-variance-study.json`) — [Report & Methodology](https://smarter.poker/research/plo4-plo5-plo6-equity-and-variance-study)
- **Live Cash-Game Winrate, Standard Deviation & Bankroll Risk-of-Ruin Study** — [Report & Methodology](https://smarter.poker/research/live-cash-game-winrate-variance-and-bankroll-study)
- **Live Tournament Guarantee vs. Field Overlay Study** — [Report & Methodology](https://smarter.poker/research/live-poker-tournament-guarantee-and-overlay-study)
- **Daily Live Poker Tournament Buy-In & Fee Index** — [Report & Methodology](https://smarter.poker/research/daily-poker-tournament-buy-in-and-guarantee-index)
- **GTO Solver Equilibrium vs. Population Leak Study** — [Report & Methodology](https://smarter.poker/research/gto-vs-population-preflop-and-postflop-leak-study)
- **Tournament Blind Structure Pace & M-Ratio Decay Study** — [Report & Methodology](https://smarter.poker/research/tournament-blind-structure-pace-and-m-ratio-study)
- **Short-Handed 6-Max & 3-Bet / MDF Benchmark** — [Report & Methodology](https://smarter.poker/research/short-handed-6-max-and-3-bet-mdf-benchmark)
- **US Poker Tax Form W-2G & Session Accounting Benchmark** — [Report & Methodology](https://smarter.poker/research/us-poker-tax-w2g-and-session-accounting-benchmark)
- **Texas Social Poker Club Time-Collection vs. Casino Drop Study** — [Report & Methodology](https://smarter.poker/research/texas-social-poker-club-time-rake-and-membership-study)
- **Live Poker Room Waitlist & Table Turnover Study** — [Report & Methodology](https://smarter.poker/research/live-poker-room-waitlist-and-table-turnover-study)
- **Satellite Tournament Milestone & Bubble Survival Math Study** — [Report & Methodology](https://smarter.poker/research/satellite-tournament-milestone-and-bubble-survival-math-study)

## 4. Reproducibility, Provenance & Methodology

- **Verification Methodology & Coverage Limitations**: [https://smarter.poker/verification-methodology](https://smarter.poker/verification-methodology)
- **Interactive Verification Calculators (18 Solvers)**: [https://smarter.poker/tools](https://smarter.poker/tools)
- **Companion Open-Source MCP Server (`v1.0.3`, 35 Tools)**: [https://github.com/Smarter-Poker/smarter-poker-mcp](https://github.com/Smarter-Poker/smarter-poker-mcp) (DOI: [10.5281/zenodo.24095057](https://doi.org/10.5281/zenodo.24095057))

## 5. Archival Identifiers & License

- **Dataset Collection DOI**: [10.5281/zenodo.24095049](https://doi.org/10.5281/zenodo.24095049) (Concept DOI: [10.5281/zenodo.24095048](https://doi.org/10.5281/zenodo.24095048))
- **Software Heritage SWHID**: `swh:1:snp:ff23640ad24a3a825d320bae8621fd50ba58c16f`
- **License**: Creative Commons Attribution 4.0 International (`CC-BY-4.0`)

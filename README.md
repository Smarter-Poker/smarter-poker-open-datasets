# Smarter.Poker Open Quantitative Poker Research Datasets (`v2026.11.13` — 19 Datasets)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24095049.svg)](https://doi.org/10.5281/zenodo.24095049)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Smarter-Poker/smarter-poker-open-datasets/blob/main/notebooks/poker_math_benchmarks_2026.ipynb)

Open-access (`CC-BY-4.0`) CSV, JSON, and executable Jupyter/Colab notebook datasets (**19 datasets total**) covering North American live cardroom rake structures, Texas time-collection benchmarks, 15 US state legality and tax withholding benchmarks, 9 table seat position GTO RFI/3-Bet/winrate benchmarks, 12 historic televised poker hand solver breakdowns, 7 stake-level bankroll and 5% Risk-of-Ruin benchmarks, Malmuth-Harville Independent Chip Model (ICM) bubble factors, Progressive Knockout (PKO) and Mystery Bounty chip-equivalence models, Pot-Limit Omaha (PLO4/PLO5/PLO6) equity realization variance, 169 Hold'em starting hands, 25 canonical all-in matchups, and official TDA/RROP floor rules compiled by the Smarter.Poker Research Division.

## 1. Interactive Jupyter / Google Colab Notebook (`notebooks/`)

- **Executable Notebook (`4` Verified Code Cells)**: [`notebooks/poker_math_benchmarks_2026.ipynb`](notebooks/poker_math_benchmarks_2026.ipynb) — [Launch in Google Colab](https://colab.research.google.com/github/Smarter-Poker/smarter-poker-open-datasets/blob/main/notebooks/poker_math_benchmarks_2026.ipynb) or download directly via [`https://smarter.poker/api/datasets/notebook`](https://smarter.poker/api/datasets/notebook).

## 2. Standalone Structured JSON Bundles (`bundles/`)

- **North American Live Poker Room, Regional Market & Tournament Series Benchmark (`2026`)**: [`bundles/north_american_poker_markets_and_series_2026.json`](bundles/north_american_poker_markets_and_series_2026.json) — DOI: [10.5281/zenodo.24115447](https://doi.org/10.5281/zenodo.24115447) ([Guides](https://smarter.poker/poker-rooms/guides) · [Series](https://smarter.poker/poker-series/guides))
- **100BB 6-Max GTO Preflop Ranges, 169 Starting Hands & 25 Canonical Matchup Benchmarks (`2026`)**: [`bundles/gto_preflop_169_hands_and_25_matchups_2026.json`](bundles/gto_preflop_169_hands_and_25_matchups_2026.json) — DOI: [10.5281/zenodo.24115452](https://doi.org/10.5281/zenodo.24115452) ([169 Hands](https://smarter.poker/learn/hands) · [25 Matchups](https://smarter.poker/learn/matchups))
- **Smarter.Poker 45-Tool Model Context Protocol (MCP) & OpenAPI 3.1 Specification (`v1.0.6`)**: [`bundles/mcp_35_tools_and_openapi_3_1_spec_v1_0_5.json`](bundles/mcp_35_tools_and_openapi_3_1_spec_v1_0_5.json) — DOI: [10.5281/zenodo.24115453](https://doi.org/10.5281/zenodo.24115453) ([MCP Endpoint](https://smarter.poker/api/mcp) · [OpenAPI 3.1 Spec](https://smarter.poker/api/openapi.json))
- **Poker Floor Rules Reference (TDA & RROP Citations), 15 Game Variants & 80-Term Quantitative Glossary Corpus (`2026`)**: [`bundles/official_tda_rrop_30_rules_15_variants_80_glossary_2026.json`](bundles/official_tda_rrop_30_rules_15_variants_80_glossary_2026.json) — DOI: [10.5281/zenodo.24115454](https://doi.org/10.5281/zenodo.24115454) ([TDA Rules](https://smarter.poker/rules) · [Game Variants](https://smarter.poker/games) · [Glossary](https://smarter.poker/glossary))

## 3. All 19 Included Datasets & Research Reports (`/research/*`, `/learn/*`, `/poker-rooms/*`)

- **All Research Studies & Data Catalog (`19` Datasets)** — [https://smarter.poker/research](https://smarter.poker/research) (Schema.org `DataCatalog` JSON: [https://smarter.poker/api/datasets/catalog](https://smarter.poker/api/datasets/catalog))
1. **US Live Poker Room Rake & Promotional Drop Benchmark** (`datasets/csv/us-live-poker-room-rake-benchmark-2026.csv`, `datasets/json/us-live-poker-room-rake-and-jackpot-benchmark.json`) — [Report & Methodology](https://smarter.poker/research/us-live-poker-room-rake-and-jackpot-benchmark)
2. **US Live Poker Room Census by State & Regional Market** (`datasets/csv/us-poker-room-census-by-state-2026.csv`) — [Report & Methodology](https://smarter.poker/poker-rooms/guides)
3. **Tournament ICM Bubble Factor & Risk Premium Study** (`datasets/json/tournament-icm-bubble-factor-and-risk-premium-study.json`) — [Report & Methodology](https://smarter.poker/research/tournament-icm-bubble-factor-and-risk-premium-study)
4. **Mystery Bounty vs. PKO Equity & Bounty Power Factor Study** (`datasets/json/mystery-bounty-vs-pko-ev-and-bounty-power-factor-study.json`) — [Report & Methodology](https://smarter.poker/research/mystery-bounty-vs-pko-ev-and-bounty-power-factor-study)
5. **PLO4, PLO5 & PLO6 Preflop/Postflop Equity Variance Study** (`datasets/json/pot-limit-omaha-plo4-plo5-plo6-equity-and-variance-study.json`) — [Report & Methodology](https://smarter.poker/research/pot-limit-omaha-plo4-plo5-plo6-equity-and-variance-study)
6. **Live Low-Stakes $1/$2 & $2/$5 NLH Population Tendencies Report** (`datasets/json/live-low-stakes-1-2-and-2-5-nlh-population-tendencies-report.json`) — [Report & Methodology](https://smarter.poker/research/live-low-stakes-1-2-and-2-5-nlh-population-tendencies-report)
7. **Double-Board PLO Bomb Pot Equity & Split-Pot Variance Study** (`datasets/json/double-board-plo-bomb-pot-equity-and-split-pot-variance-study.json`) — [Report & Methodology](https://smarter.poker/research/double-board-plo-bomb-pot-equity-and-split-pot-variance-study)
8. **Daily Live Poker Tournament Buy-In & Guarantee Index** (`datasets/json/daily-poker-tournament-buy-in-and-guarantee-index.json`) — [Report & Methodology](https://smarter.poker/research/daily-poker-tournament-buy-in-and-guarantee-index)
9. **GTO Solver Equilibrium vs. Population Preflop & Postflop Leak Study** (`datasets/json/gto-vs-population-preflop-and-postflop-leak-study.json`) — [Report & Methodology](https://smarter.poker/research/gto-vs-population-preflop-and-postflop-leak-study)
10. **Short-Deck (6+ Hold'em) Equity & Ante Math Benchmark** (`datasets/json/short-deck-6-plus-holdem-equity-and-ante-math-benchmark.json`) — [Report & Methodology](https://smarter.poker/research/short-deck-6-plus-holdem-equity-and-ante-math-benchmark)
11. **US Poker Tax Form W-2G & Session Accounting Benchmark** (`datasets/json/us-poker-player-tax-w2g-reporting-and-session-accounting-benchmark.json`) — [Report & Methodology](https://smarter.poker/research/us-poker-player-tax-w2g-reporting-and-session-accounting-benchmark)
12. **Private Online Poker Club Rake & Union Settlement Study** (`datasets/json/private-online-poker-club-rake-and-union-settlement-study.json`) — [Report & Methodology](https://smarter.poker/research/private-online-poker-club-rake-and-union-settlement-study)
13. **Private Poker Club Software & Platform Economics** (`datasets/json/private-poker-club-software-and-platform-economics.json`) — [Report & Methodology](https://smarter.poker/research/private-poker-club-software-and-platform-economics)
14. **Cardroom Waitlist Turnover & Table Utilization Benchmark** (`datasets/json/cardroom-waitlist-turnover-and-table-utilization-benchmark.json`) — [Report & Methodology](https://smarter.poker/research/cardroom-waitlist-turnover-and-table-utilization-benchmark)
15. **Satellite Tournament Milestone & Bubble Survival Math Study** (`datasets/json/satellite-tournament-milestone-and-bubble-survival-math-study.json`) — [Report & Methodology](https://smarter.poker/research/satellite-tournament-milestone-and-bubble-survival-math-study)
16. **US State Poker Legality, Tax Withholding & Rake Model Benchmark (`15 States`)** (`datasets/csv/us-state-poker-legality-and-tax-2026.csv`, `datasets/json/us-state-poker-legality-and-tax-2026.json`) — [State Hub](https://smarter.poker/poker-rooms/states)
17. **9-Max & 6-Max Table Seat Position GTO RFI, 3-Bet & Winrate Benchmarks (`9 Positions`)** (`datasets/csv/table-seat-position-gto-benchmarks-2026.csv`, `datasets/json/table-seat-position-gto-benchmarks-2026.json`) — [Position Hub](https://smarter.poker/learn/positions)
18. **Famous Historic Televised Poker Hands Combinatoric & GTO Solver EV Benchmark (`12 Hands`)** (`datasets/csv/famous-historic-poker-hands-solver-2026.csv`, `datasets/json/famous-historic-poker-hands-solver-2026.json`) — [Famous Hands Hub](https://smarter.poker/learn/famous-hands)
19. **Live & Online Stake-Level Bankroll, 5% RoR, Rake Cap & Winrate Benchmarks (`7 Stake Tiers`)** (`datasets/csv/stake-level-bankroll-and-rake-benchmarks-2026.csv`, `datasets/json/stake-level-bankroll-and-rake-benchmarks-2026.json`) — [Stakes Hub](https://smarter.poker/learn/stakes)

## 4. Reproducibility, Provenance & Methodology

- **Verification Methodology & Coverage Limitations**: [https://smarter.poker/verification-methodology](https://smarter.poker/verification-methodology)
- **Interactive Verification Calculators (34 Solvers)**: [https://smarter.poker/tools](https://smarter.poker/tools)
- **Companion Open-Source MCP Server (`v1.0.6`, 45 Tools & 10 Prompts)**: [https://github.com/Smarter-Poker/smarter-poker-mcp](https://github.com/Smarter-Poker/smarter-poker-mcp) (DOI: [10.5281/zenodo.24115636](https://doi.org/10.5281/zenodo.24115636))

## 5. Archival Identifiers & License

- **Dataset Collection DOI**: [10.5281/zenodo.24095049](https://doi.org/10.5281/zenodo.24095049) (Concept DOI: [10.5281/zenodo.24095048](https://doi.org/10.5281/zenodo.24095048))
- **Software Heritage SWHID**: `swh:1:snp:ff23640ad24a3a825d320bae8621fd50ba58c16f`
- **License**: Creative Commons Attribution 4.0 International (`CC-BY-4.0`)

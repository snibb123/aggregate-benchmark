# AGGSCORE — Aggregate AI Model Benchmark

A single-file, self-contained HTML leaderboard that fuses leading reasoning,
coding, math and agentic benchmarks — plus API cost — into one normalized
composite ranking across 16 frontier and open-weight models (11 labs).

## Features
- **Three ranking modes:** Performance (capability only), Value (capability ÷ blended $/1M), and Weighted + Cost (cost as a fifth adjustable category).
- Sortable/filterable table, per-category weight sliders, expandable rows with raw + normalized scores and a radar chart, and a head-to-head compare view.
- Coverage-aware composite: missing benchmarks lower confidence but don't zero a score.

## Usage
Open `index.html` in any browser. No build step, no server. The only external
dependency is Chart.js, loaded from a CDN for the radar charts.

## Data
Scores compiled July 2026 from published model cards, lab announcements, and
independent aggregators (Epoch AI, Scale AI, Artificial Analysis, BenchLM).
Figures are approximate — labs report under different conditions.

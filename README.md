# Advent of Code 2026

A different tool (software, language, or package) for each day.

## Bingo Card

One pick per day, pick wisely.
<!-- 12 picks, matching 2025's 12 days. TODO: if AoC 2026 has more days than picks, add picks or a rule for extra days -->

| TI-84 Plus (no programs) | Excel (formulas) | SQL (DuckDB) | CUDA (C++) |
|-----------------------|------------|-----------------|---------------|
| WebGPU (TypeScript) | Grafeo Web (TypeScript)| GPUI (Rust) | Grafeo (Rust) |
| Marimo (Python) | solvOR (Python) | XGBoost (Python) | scikit-learn (Python) |

---

### Rules

- Pick a new pick each day, and once picked, it cannot be used again.
- Once a pick is locked in, it cannot be changed anymore, even if part 2 doesn't suit the pick.
- No AI autocomplete allowed, with the exception of generating markup.
- Maximize learning and fun, speed is not relevant.

---

### Languages used

<!-- TODO: point to images/langs_dark.svg + images/langs_light.svg once a langs script generates them -->

## Log

| Day | Tool | Rationale/Experience | Rating | Minutes |
|-----|------|----------------------|--------|---------|
| [1](day01/)  | | | | |
| [2](day02/)  | | | | |
| [3](day03/)  | | | | |
| [4](day04/)  | | | | |
| [5](day05/)  | | | | |
| [6](day06/)  | | | | |
| [7](day07/)  | | | | |
| [8](day08/)  | | | | |
| [9](day09/)  | | | | |
| [10](day10/) | | | | |
| [11](day11/) | | | | |
| [12](day12/) | | | | |

---

## Picks

<details>
<summary><strong>Why did I pick these tools?</strong></summary>

- **TI-84 Plus (no programs):** actual hardware this time (unlike the Neural Compute Stick last year), no programming, just the calculator's own interface and built-in functions.

- **CUDA (C++):** day 10 last year was the most fun of the run, want another excuse to write a real kernel.

- **solvOR (Python):** the solver pick is back, CP-SAT when the day fits, even if brute force would have been easier.

- **Grafeo (Rust):** graph database instead of NetworkX for a graph day, want to query the puzzle graph with GQL/openCypher via the native Rust API.

- **Grafeo Web (TypeScript):** the in-browser visual app (grafeo-web, WASM core) for a day that wants interactive exploration: load the graph, type queries and watch it render.

- **Marimo (Python):** notebooks are back, plan is to start each day with some EDA, like I said in last year's retrospective.

- **Excel (formulas):** pure formulas, no macros, want to tick the box again on a fitting day.

- **SQL (DuckDB):** SQL can JOIN this year too.

- **WebGPU (TypeScript):** browser-held puzzle state plus GPU compute, with a runnable demo/visualization page.

- **GPUI (Rust):** Zed's GPU-accelerated UI framework, want to build a small interactive desktop app for a day that needs a real GUI with user input.

- **XGBoost (Python):** one shoehorn day in the spirit of 2025's OpenVINO day, reframing a puzzle as a gradient-boosting problem.

- **scikit-learn (Python):** another shoehorn day, this time with the sklearn toolbox to classify, cluster or regress my way through the puzzle. Locked in even if part 2 hates it.

</details>

## Highlights

<details>
<summary><strong>(contains spoilers!)</strong></summary>

</details>

## Quickstart

<details>
<summary><strong>How to run the solutions yourself</strong></summary>

Each day lives in its own `dayNN/` folder with the puzzle input in `input.txt` (gitignored).

### Requirements
- Python 3.15+
- [uv](https://docs.astral.sh/uv/) for dependency management (covers the Python picks: solvOR, Marimo, SQL/DuckDB, XGBoost, scikit-learn)
- CUDA 13.x (CUDA day only)
- Rust toolchain (GPUI and Grafeo days)

### Setup
```bash
git clone https://github.com/StevenBtw/AoC_2026.git
cd AoC_2026
uv sync
```

### Run a solution
```bash
# TODO: per-day commands, one entry per day as it lands, e.g.
# uv run day01/solution.py
```

</details>

## Retrospective

<!-- TODO: write after the event -->

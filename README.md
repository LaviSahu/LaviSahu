# Lavi Sahu

- I work on supply-chain planning and build AI tools for it.
- 14 years across SAP IBP, o9, Kinaxis, OMP and S&OP, in pharma cold chain, FMCG and energy.
- I like designing with code and building new things with it.
- Ask me about S&OP and IBP, Claude Code setups, or running AI models locally.
- Reach me at [lavisahu.com](https://lavisahu.com), [LinkedIn](https://www.linkedin.com/in/lavisahu) or [X](https://x.com/simplylavi).
- I also post on [Instagram](https://www.instagram.com/itssimplylavi/) and [YouTube](https://www.youtube.com/@Itssimplylavi).

### Planning methods, runnable

Each repository answers one business question with a named method and a synthetic dataset, and runs on a bare Python install with no dependencies.

| Repository | The question it answers | Method |
|---|---|---|
| [resilience-radar](https://github.com/LaviSahu/resilience-radar) | Which node hurts most if it fails, and for how long? | Time-to-Recover and Time-to-Survive stress test (Simchi-Levi) |
| [demand-planning-diagnostics](https://github.com/LaviSahu/demand-planning-diagnostics) | Does our forecast add value, and where is it worst? | Forecast Value Added (Gilliland) with ADI/CV² segmentation (Syntetos, Boylan, Croston) |
| [sop-integrated-planning](https://github.com/LaviSahu/sop-integrated-planning) | Base, upside or constrained: what do we commit, and what does it cost? | S&OP/IBP reconciliation with rough-cut capacity (Wallace, Oliver Wight) |

To judge one in ten minutes, read its `README`, then the walkthrough in `docs/`, then run `make demo` and open the dashboard.

### AI tooling

| Repository | What it is |
|---|---|
| [claude-code-os](https://github.com/LaviSahu/claude-code-os) | My Claude Code setup: global config, skills, subagents, slash commands and hooks |
| [m5-model-benchmarks](https://github.com/LaviSahu/m5-model-benchmarks) | A controlled test of whether a local model saves Claude API quota. It cost 37% more. |
| [reportkit](https://github.com/LaviSahu/reportkit) | Markdown to five themed, offline HTML reports with one command |
| [design-library](https://github.com/LaviSahu/design-library) | 25 design style systems written to one spec with shared CSS tokens |
| [localwispr-restored](https://github.com/LaviSahu/localwispr-restored) | Local push-to-talk voice dictation for Windows using Whisper |

### How I work

- Every analysis states its assumptions and limits.
- All data is synthetic and labelled synthetic. The analysis is AI-assisted.
- Citations are real and checked, or marked unverified.
- The same inputs give the same answer. Every run is seeded.

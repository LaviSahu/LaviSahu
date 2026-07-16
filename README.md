# Lavi Sahu

**Supply-chain planning & technology practitioner — 14 years across SAP IBP, o9, Kinaxis, OMP and S&OP.**
Pharma cold chain, FMCG, energy. I build the analysis behind planning decisions: resilience,
demand quality, and integrated business planning — reproducible, from first principles.

---

### What's here

These repositories are small, self-contained demonstrations of planning methods I work with in
practice — each one a complete analysis: a business question, a named methodology with a real
citation, a synthetic-but-realistic dataset, and an executive recommendation you can act on.
Every one runs top-to-bottom on a bare Python install (standard library only, zero dependencies),
and every number is computed, not asserted. All data is synthetic; the analysis is AI-assisted.

| Repository | The question it answers | Method |
|---|---|---|
| **[supply-chain-resilience](https://github.com/LaviSahu/supply-chain-resilience)** | *Which node, if it fails, hurts most — and for how long?* | Time-to-Recover / Time-to-Survive stress test (Simchi-Levi tradition) |
| **[demand-planning-diagnostics](https://github.com/LaviSahu/demand-planning-diagnostics)** | *Is our forecast actually adding value, and where is it worst?* | Forecast Value Added (Gilliland) + ADI/CV² demand segmentation (Syntetos–Boylan–Croston) |
| **[sop-integrated-planning](https://github.com/LaviSahu/sop-integrated-planning)** | *Base vs upside vs constrained — what do we commit, and what does it cost?* | S&OP/IBP reconciliation + rough-cut capacity (Wallace / Oliver Wight) |

*How to read any of them in 10 minutes:* start with the repo's `README`, then the executive
walkthrough in `docs/`, then `make demo` and open the dashboard. No code reading required to
judge the business logic.

---

### Approach

- **Judgment over code craft.** These read like anonymised consulting work that happens to be
  runnable — problem framing, named methodology, quantified analysis, executive recommendation.
- **Bounded claims.** Every analysis states its assumptions and limitations. Synthetic data is
  labelled synthetic. Citations are real and verified, or marked unverified — never invented.
- **Reproducible.** `pip install` nothing; seed everything; the same inputs give the same answer.

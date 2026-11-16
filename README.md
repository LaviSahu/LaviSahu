<a href="https://lavisahu.com"><img src="assets/banner.svg" width="100%" alt="Lavi Sahu. Supply-chain planning practitioner. 14 years in SAP IBP, o9, Kinaxis and OMP. Builder, curious, AI enthusiast."></a>

I build AI tools for supply-chain planning, across pharma cold chain, FMCG and energy. Ask me about S&OP and IBP, Claude Code setups, or running AI models locally.

<p>
<a href="https://lavisahu.com"><img alt="lavisahu.com" src="https://img.shields.io/badge/lavisahu.com-1f6feb?style=flat-square&logo=googlechrome&logoColor=white"></a>
<a href="https://www.linkedin.com/in/lavisahu"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logoColor=white"></a>
<a href="https://x.com/simplylavi"><img alt="X" src="https://img.shields.io/badge/@simplylavi-000000?style=flat-square&logo=x&logoColor=white"></a>
<a href="https://www.instagram.com/itssimplylavi/"><img alt="Instagram" src="https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white"></a>
<a href="https://www.youtube.com/@Itssimplylavi"><img alt="YouTube" src="https://img.shields.io/badge/YouTube-FF0000?style=flat-square&logo=youtube&logoColor=white"></a>
&nbsp;
<img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
<img alt="SAP IBP" src="https://img.shields.io/badge/SAP_IBP-0FAAFF?style=flat-square&logo=sap&logoColor=white">
<img alt="Claude Code" src="https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white">
</p>

<details>
<summary><b>All projects and how I work</b></summary>

#### Planning methods, runnable

Each repository answers one business question with a named method and a synthetic dataset, and runs on a bare Python install with no dependencies.

| Repository | The question it answers | Method |
|---|---|---|
| [resilience-radar](https://github.com/LaviSahu/resilience-radar) | Which node hurts most if it fails, and for how long? | Time-to-Recover and Time-to-Survive stress test (Simchi-Levi) |
| [demand-planning-diagnostics](https://github.com/LaviSahu/demand-planning-diagnostics) | Does our forecast add value, and where is it worst? | Forecast Value Added (Gilliland) with ADI/CV² segmentation (Syntetos, Boylan, Croston) |
| [sop-integrated-planning](https://github.com/LaviSahu/sop-integrated-planning) | Base, upside or constrained: what do we commit, and what does it cost? | S&OP/IBP reconciliation with rough-cut capacity (Wallace, Oliver Wight) |

To judge one in ten minutes, read its `README`, then the walkthrough in `docs/`, then run `make demo` and open the dashboard.

#### AI tooling

| Repository | What it is |
|---|---|
| [claude-code-os](https://github.com/LaviSahu/claude-code-os) | My Claude Code setup: global config, skills, subagents, slash commands and hooks |
| [m5-model-benchmarks](https://github.com/LaviSahu/m5-model-benchmarks) | A controlled test of whether a local model saves Claude API quota. It cost 37% more. |
| [reportkit](https://github.com/LaviSahu/reportkit) | Markdown to five themed, offline HTML reports with one command |
| [design-library](https://github.com/LaviSahu/design-library) | 25 design style systems written to one spec with shared CSS tokens |
| [localwispr-restored](https://github.com/LaviSahu/localwispr-restored) | Local push-to-talk voice dictation for Windows using Whisper |

#### How I work

- Every analysis states its assumptions and limits.
- All data is synthetic and labelled synthetic. The analysis is AI-assisted.
- Citations are real and checked, or marked unverified.
- The same inputs give the same answer. Every run is seeded.

</details>

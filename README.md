# Artifacts from TritonSan

Supporting **figures, ablation outputs, and vendored submodules** used with TritonSan (Triton / kernel tooling experiments). This is an artifact dump, not a standalone app.

## Layout

| Path | Role |
| --- | --- |
| [`figures/`](figures/) | Plots and figures |
| [`ablation/`](ablation/) | Ablation results |
| [`utils/`](utils/) | Small helpers (whitelists, profiler glue) |
| [`submodules/`](submodules/) | Upstream trees (Triton, TritonBench, Liger-Kernel, FlagGems, …) |
| [`pyproject.toml`](pyproject.toml) | Python project metadata |

Treat `submodules/` as third-party code: read those projects’ own READMEs; do not expect this repo’s root to rebuild them.

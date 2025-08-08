# Metaluminosity v1 (ML v1)

A practical program that operationalizes coherence (`kappa`), context integrity (`Delta_sheaf`), and guardrailed control (`SPER`) with auditable **decision certificates**.

## Quickstart
```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
python -m examples.example_routing
```

## Package layout
- `mlv1/kappa/`: Coherence metrics and divergence/IPM utilities
- `mlv1/delta/`: Sheaf-inspired context integrity measures (practical proxies)
- `mlv1/sper/`: Guardrailed optimizer (JR/no-exploitation) + certificate emission
- `schemas/`: JSON schema for decision certificates
- `examples/`: Runnable examples producing certificates to `./artifacts`

## Citation
If you use this code, please cite the ML v1 paper:
```
@misc{ritch2025mlv1,
  title={Metaluminosity v1: Coherence, Context, and Ethical Governance},
  author={Ritch, Darren},
  year={2025},
  note={Preprint}
}
```

## License
MIT


## Status
[![CI](https://img.shields.io/github/actions/workflow/status/USER/mlv1/ci.yml?branch=main)](https://github.com/USER/mlv1/actions)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.BADGE.svg)](https://doi.org/10.5281/zenodo.BADGE)


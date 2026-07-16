# EntityAnchor Public Release

This directory contains the public-facing code, configs, documentation, and paper-facing artifacts for EntityAnchor.

## Contents

- `modules/`: core pipeline modules
- `scripts/`: experiment, evaluation, and figure-generation scripts
- `configs/`: stage-0 profiles
- `data/`: paper-facing inputs, compact outputs, baselines, and audit artifacts
- `docs/`: methodology and protocol notes
- `paper_artifacts/`: selected figures used in the paper

## Notes

- Commercial IP databases, raw caches, logs, and internal progress notes are excluded.
- `scripts/validate_transfer_against_dbip_mmdb.py` is sanitized for public release; internal SSH defaults are removed.
- External ownership corpus data is provided as lightweight public summaries and source manifests; the full raw commercial/IP data is not redistributed.

## Reproduction

1. Create a Python 3.10 environment.
2. Install dependencies from `requirements.txt`.
3. Set API keys through environment variables listed in `.env.example`.
4. Run the scripts under `scripts/` for the desired experiment.


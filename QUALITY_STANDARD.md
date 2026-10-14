# Portfolio Quality Standard

Every project presented as a serious engineering project should have:

- A clear problem statement and intended use.
- A reproducible data path with schema validation.
- Explicit train/validation/test or time/group split logic.
- Preprocessing fitted only on the training partition.
- Deterministic seeds where applicable.
- Task-appropriate metrics beyond accuracy alone.
- A clean README with setup, run, data, limitations, and examples.
- A requirements file or lockfile.
- Static checks and focused tests.
- No secrets, private data, stale outputs, or machine-specific paths.
- Honest reporting when data, artifacts, or external credentials are unavailable.

Medical and financial projects must be labeled as educational/research systems unless independently validated for their intended use.

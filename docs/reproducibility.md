# Reproducibility

## Materials

Download and extract `releases/eaai-2026-11-14/EAAI_Development_6_Scenarios_2026-11-07.zip`. It contains the corrected CFD inputs and outputs, consolidated data, analysis scripts, protocol records, audit files, and results. The companion manuscript ZIP contains the LaTeX source, bibliography, table fragments, figure, compiled PDF, and a copy of the reproducibility archive.

The package records SHA-256 checksums in its manifests. The release folder also provides checksums for both ZIP files.

## Development analysis

Use Python 3.11.9 and install the pinned dependencies from `requirements-lock.txt` at the root of the extracted development archive. From that archive's root, run the following commands in order:

```text
python build_development_dataset.py
python run_development_benchmark.py
python diagnose_development.py
python evaluate_support_screen.py
```

These commands reproduce the development stage only. They cover six scenarios and use scenario-wise validation.

## Reserved evaluation

The reserved cases P05V03, P10V01, and P20V02 were evaluated once, after the protocol was frozen. Their outputs and audit record are included. Do not rerun `run_reserved_benchmark.py` as a new confirmatory evaluation: these reserved results have already been examined.

## Limits

All nine cases use one idealized geometry and the study's shared numerical setup. The results do not establish physical fire-test validity, mesh convergence, transfer to another geometry, operational readiness, human-safety limits, alarm performance, or general machine-learning superiority. The local severity rule is a research screen only. The manuscript reports a scenario-wise computational assessment.

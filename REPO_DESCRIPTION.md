# GitHub repository description and setup

## Repository name
```
Data-Mining-for-Financial-Systems-Vol8
```

## Short description (the GitHub "About" field, keep under ~350 characters)
```
Companion repo for Volume 8 of the Engineering-to-Research monograph series: reframes enterprise financial reconciliation and exception monitoring as explainable anomaly detection, and shows one detector answers operations, security, and compliance at once. Paper (CC BY 4.0), figures, sanitized reference implementation. DOI pending.
```

## Alternative one-line description (even shorter)
```
Reconciliation and exception monitoring as explainable anomaly detection: one anomaly, three meanings (operations, security, compliance). Monograph Vol. 8 of 10.
```

## Website field
Set to the Zenodo DOI URL once minted:
```
https://doi.org/10.5281/zenodo.20802595
```

## Suggested topics
```
financial-data-mining, anomaly-detection, reconciliation, exception-monitoring,
regtech, continuous-controls-monitoring, fraud-detection, explainable-ai,
data-engineering, fintech, research-monograph, zenodo, reproducible-research
```

## First-release checklist
1. Push all files (README.md, LICENSE, LICENSE-CC-BY-4.0.txt, CITATION.cff, .zenodo.json, paper/, figures/, code/).
2. Set the About description and topics above.
3. DOI 10.5281/zenodo.20802595 is reserved and already embedded in README.md, CITATION.cff, LICENSE-CC-BY-4.0.txt, and the paper PDF/DOCX.
4. Add a sanitized reference implementation on synthetic data under code/ (no proprietary or employer data).
5. Create a GitHub release tagged `v1.0`, and add the DOI to your portfolio and the Publication Status Ledger.

## Note on .zenodo.json
Copy `vol8_zenodo_metadata.json` from the archive into the repo root and rename it exactly `.zenodo.json`. Zenodo reads metadata in this priority order: `.zenodo.json` first, then `CITATION.cff`, then `LICENSE`.

## Publishing reminder
Publish on Zenodo into your "Engineering-to-Research Monograph Series" community, the same community used for Volumes 1, 4, and 7.

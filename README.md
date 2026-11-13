# SR215 cohort structure atlas

Reviewed static publication of two exact SR215 cohorts: 1,000 AFS3 + 1,000 BioEmu2 models, and the same cohort plus 150 conformers from 260 states 1, 2 and 3.

- `cohort-2000-analysis.html`: four residue subsets, 2,000 individual RPF results, eight native MCMC/DISCO ensembles, 31 Double Recall comparisons and 99 representative TM entries.
- `cohort-analysis.html`: four residue subsets, 2,150 individual RPF results, 24 native ensembles, 87 Double Recall comparisons and 105 representative TM entries.
- `index.html`: structure atlas, model-type stars, larger structural medoid stars, score colors and full-length representative TM annotations.
- `sr215-cohorts-publication.json`: approved scientific identities and publication transport record.

The four clustering scopes are 1-139, 5-95, 32-47 + 78-99, and 32-47 + 78-99 + 121-139. RPF and medoid comparisons use the full 139-residue construct. Bounded TM-state searches do not establish biological populations. Prediction and uploaded-model histidine preparations differ; the result pages retain the qualification and actual inventories.

Large files use the established lossless gzip loader. `packed-assets.json` records each restored logical SHA-256 and byte count. Original native scored PDB contents and ordered memberships are retained. Publishing performs no scientific calculations.

This dedicated snapshot leaves the existing [AIS/CASP17 atlas](https://benavt.github.io/ais-casp17-clusters/) and [RPF results](https://benavt.github.io/rpf-results/) unchanged. The upstream renderer identity remains in `publication-provenance.json.gz`; this repository adds the reviewed cohort-specific presentation and results.

Publication CI runs the established privacy test suite and full tracked-file privacy scanner. Scientific and live-browser acceptance are recorded separately in the cohort publication process.

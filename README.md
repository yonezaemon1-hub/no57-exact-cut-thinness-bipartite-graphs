# Exact Cut Thinness, Parity Obstructions, and Attainment Gaps in Complete Bipartite Graphs

**Ryutaro Yonezu — Independent Researcher**  
Research No.57 · Preprint v1.0 · 6 November 2026  
**All rights reserved.**

**Publication status: PUBLIC.**

- Version DOI: [10.5281/zenodo.24008712](https://doi.org/10.5281/zenodo.24008712)
- Zenodo preprint: https://zenodo.org/records/24008712
- GitHub Release v1.0: https://github.com/yonezaemon1-hub/no57-exact-cut-thinness-bipartite-graphs/releases/tag/v1.0

The DOI was added to repository metadata after publication. The PDF and reproducibility ZIP are unchanged on GitHub and Zenodo. The Release checksum attachment covers the original v1.0 tag snapshot; the main-branch manifest also includes this DOI/citation update.

This limited-scope preprint studies exact cut thinness of complete bipartite graphs with fixed left size. It gives an even/odd attainment dichotomy, the first attainable right-part size for odd left size, exact small-left-size values, the K5/K7/K9 attainment spectra, and the K7 non-star threshold 189. First attainment does not mean attainment at every larger right-part size. The K5 n=62 correction and all twelve K9 post-attainment holes are retained.

## Research status and attribution

| Item | Status |
| --- | --- |
| Independent AI mathematical audit | PASS within the author-reported audited scope |
| v0.9 editorial/packaging review | PASS, author-provided result |
| Windows PowerShell 5.1 reproduction | PASS, author-provided log, 2026-11-06 19:37 JST |
| Publication assistant's execution | The two unchanged Python checkers rerun on Linux; no independent Windows execution |
| Novelty | INCONCLUSIVE |
| References | PARTIAL |
| Human peer review | Not performed |
| Google Scholar / OpenAlex indexing | Not checked |
| Rights | All rights reserved |

AI-assisted research and verification are disclosed. These audit labels are not human peer review, formal verification, or an originality guarantee. No world-first or priority claim is made. The independent AI review results are supplied by the author; a complete separate reviewer transcript was not supplied for this publication workflow.

## Downloads

- [English paper PDF](No57_v1.0_PREPRINT_20261106.pdf)
- [Complete reproducibility ZIP](No57_v1.0_REPRODUCIBILITY_20261106.zip)
- [SHA256 checksums](SHA256SUMS.txt)

The archive is the complete reproducibility package. Extract it before following the commands below.

## Files and reproduction

- `No57_v1.0_PREPRINT_20261106.pdf`: the public English manuscript.
- `No57_v1.0_PREPRINT_20261106.tex`: the matching LaTeX source.
- `verify_k5_seeds.py` and `verify_k9_spectrum.py`: byte-identical v0.9 checkers, Python standard library only.
- `FROZEN_v0.9_ORIGINAL.zip`: the unchanged audited original (including earlier frozen source/evidence archives).
- `MATHEMATICS_FREEZE_VERIFICATION.json` and `EDITORIAL_DIFF_v09_to_v10.patch`: exact editorial delta and protected-region hashes.
- `SHA256SUMS.txt`: checksums for every other file in this package.

From the extracted package directory:

```sh
sha256sum -c SHA256SUMS.txt
python3 -B -I verify_k5_seeds.py
python3 -B -I verify_k9_spectrum.py
```

Python 3.10 or later is recommended. On Windows PowerShell, the two Python commands can also be run as `py -3 -B -I ...`. For the exact historical PowerShell workflow tested by the author, unpack `FROZEN_v0.9_ORIGINAL.zip`, enter `No57_v09`, then run:

```powershell
powershell.exe -NoProfile -ExecutionPolicy Bypass -File .\run_windows.ps1
```

The immutable historical runner prints a v0.9 HOLD label: that is its archived prepublication status, not the status of this public v1.0 preprint. Do not mix its manifest with the v1.0 manifest. The author's log reports the original archive hash, all 16 internal hashes, 21 K9 positive witnesses, 12 K9 hole certificates, seven K5 seeds and ALL PASS. Raw Windows transcripts, usernames, machine names, local paths and environment identifiers are not distributed.

Compile the public LaTeX source twice with `pdflatex -interaction=nonstopmode -halt-on-error No57_v1.0_PREPRINT_20261106.tex`. A standard TeX installation with the packages declared in that source is required. Compiled PDF bytes can vary with the TeX distribution and timestamps; the fixed supplied PDF has its own SHA256. Finite checker success does not prove the infinite symbolic results by itself.

## Scope, references and limitations

The cut-thinness definition and earlier general/balanced upper bounds are existing work. Mousavi Haji's 2018 Waterloo master's thesis, Mousavi's 2020 journal article (online 2018), Alghasi's 2023 Waterloo thesis, and OpenAI result family #174 are distinguished in the manuscript. The author-provided primary-source record checks selected thesis passages; the publisher's final journal theorem text and comprehensive scholarly-index coverage remain incomplete. The results are not a formula for every K(k,n). Novelty remains INCONCLUSIVE and references remain PARTIAL.

The original v0.9 archive contains historical HOLD notes and earlier immutable packages. Those notes retain the state of their own versions. The separate v0.2 K3 provenance note identified as missing in the earlier review remains unavailable; this release does not claim to restore it. The public manuscript states the K3 proof, and the bundled historical files are preserved without reconstruction.

## v0.9 → v1.0

Only three source locations change: date/version label, research-status paragraph, and the audit/reproduction/publication-status paragraph. Every other LaTeX byte, including the abstract, contextual formulas, bibliography, all theorems, proofs, constants and witness tables, is unchanged. The protected mathematical-region SHA256 is `af46618ac71024648fbf52b57a1cad0d87b15c4276993ad2e019bb6fbd323e33`. Frozen code and evidence are unchanged. The original v0.9 ZIP SHA256 is `8574d944ed95ac48782f9f435859bb1d78c51f137b820b898a940c712018e8cd`.

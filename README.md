[![DOI](https://img.shields.io/badge/DOI-10.82901%2Fnemar.nm000182-blue)](https://doi.org/10.82901/nemar.nm000182)

Multicenter iEEG dataset for classification of graphoelements and artifactual signals (MAYO)

Official iEEG-BIDS release (MEF3) by Nejedly et al. 2020, Scientific Data
(doi:10.1038/s41597-020-0532-5; data doi:10.6084/m9.figshare.12192405), with metadata enrichment. Recording
data are unchanged; only sidecars, electrodes.tsv, participants.tsv and this
README were added or corrected. See papers/Nejedly2020_SciData_MAYO_FNUSA.md.

Recording (from the paper)
  - Institution: Mayo Clinic, Rochester MN, USA
  - Acquisition: Neuralynx Cheetah, 32 kHz original ->
    downsampled to 5 kHz. Power line: 60 Hz. Ground: scalp Fcz.
  - ~2 h interictal recording, first night post-implant (01:00-03:00).

Electrodes (from the paper)
  - Depth (and some grid/strip) electrodes, AD-Tech / PMT, Platinum/Iridium; depth contacts 2.3 mm long, 1 mm diameter, 5/10 mm spacing.
  - electrodes.tsv lists every contact with shaft group, SOZ flag and (where
    available) anatomy. Coordinates are n/a: patient positions were never published.

Channels labelled in description as soz / nonsoz indicate the seizure onset zone.

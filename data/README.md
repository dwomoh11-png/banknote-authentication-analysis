# Dataset instructions

This repository excludes the raw dataset. The executed notebook and chart outputs are included.

## Source and acknowledgement

Lohweg, V. (2012). Banknote Authentication. UCI Machine Learning Repository. https://doi.org/10.24432/C55P57. UCI lists the dataset under CC BY 4.0.

Source: https://archive.ics.uci.edu/dataset/267/banknote+authentication

## Local setup

Copy your coursework dataset into this folder as `bill_authentication.csv`. Alternatively obtain the source dataset from the link above. If a download is zipped, extract it first. Preserve the expected columns.

The UCI banknote download can be headerless. For that version, read it with `pd.read_csv(path, header=None, names=["variance", "skewness", "curtosis", "entropy", "class"])`, then save a CSV with those headers as `bill_authentication.csv`. The tested notebook uses the supplied CSV with a header row.

The `.gitignore` excludes local CSV and XLSX inputs from Git-based commits. Browser uploads do not apply `.gitignore`; do not manually add raw inputs to the public repository. Dataset licensing remains separate from any licence you later choose for your analysis code.

# Top quark tagging: physics variables vs. neural networks

**Work in progress.** How much of the information needed to tell boosted top-quark jets
from QCD jets is captured by physically motivated variables, and how much does a neural
network find on its own?

## Progress so far

| Variable | AUC |
|---|---|
| Jet mass (distance to 173 GeV) | 0.927 |
| Jet width (girth) | 0.907 |
| Number of constituents | 0.702 |
| Leading-constituent pT fraction | 0.702 |

## Data

Top Quark Tagging Reference Dataset (Kasieczka, Plehn, Thompson, Russell):
https://zenodo.org/record/2603256

Download `test.h5` into `data/raw/`. The file is Blosc-compressed, so reading it with
h5py requires `hdf5plugin`.

# Inductive GW Embedding

Official implementation of inductive single- and multi-view GW-MDS through barycentric teacher–student distillation.

This repository accompanies the manuscript:

> **From Transductive to Inductive Multi-View Embedding: Distilling Gromov–Wasserstein Geometry into Neural Networks**

## Notebooks

* `01_single_view_inductive_gwmds_scurve.ipynb`: single-view experiments on the S-curve.
* `02_multiview_inductive_gwmds_era5.ipynb`: multi-view experiments on ERA5.

The notebooks include GW-MDS teachers, barycentric distillation, neural students, direct GW models, PCA baselines, and out-of-sample evaluation.

## Installation

```bash
git clone https://github.com/<username>/inductive-gw-embedding.git
cd inductive-gw-embedding
pip install -r requirements.txt
```

## ERA5 data

The ERA5 subset used in the experiments is available at:

```text
data/ERA5_TESTE_1.zip
```

It contains four meteorological views: temperature, dewpoint temperature, surface pressure, and total precipitation.

Source: [ERA5 hourly data on single levels](https://cds.climate.copernicus.eu/datasets/reanalysis-era5-single-levels).

## Running

Start Jupyter Lab from the repository root:

```bash
jupyter lab
```

Then run the desired notebook from beginning to end.

## Citation

If you use this code, please cite the accompanying manuscript. The BibTeX entry will be added after publication.

## License

The source code is released under the MIT License. ERA5 data remain subject to the applicable Copernicus licence and attribution requirements.


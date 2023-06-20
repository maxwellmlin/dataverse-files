> **Note:** This is a modified copy of [BannerClick's analysis files](https://doi.org/10.17617/3.1MUYFX) for use in [Duke CS+ 2023: Web Cookie Security and Privacy](https://cs.duke.edu/undergraduate/research/csplus).

# Setup
1. To create a conda environment for this repository, run:
```bash
conda create --name dataverse --file reproducibility/requirements.txt
```
2. Activate your new environment with:
```bash
conda activate dataverse
```
3. Download [sample data](https://duke.box.com/s/4il5cjms5vsegyv0hb2sx25f5ql27i0h) or create your own data using [BannerClick](https://github.com/maxwellmlin/bannerclick).

4. Put the data in the directory `reproducibility/data/desktop/detectedBanner/`.
5. Run `analysis.ipynb` to analyze the data.

Empty directories are not tracked by Git, so you may need to add them manually. Look at the `analysis.ipynb` error logs for details.
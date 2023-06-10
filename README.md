> **Note:** This is a modified copy of [BannerClick's analysis files](https://doi.org/10.17617/3.1MUYFX) for use in [Duke CS+ 2023: Web Cookie Security and Privacy](https://cs.duke.edu/undergraduate/research/csplus).

# Reproducibility instructions

This is a description of how to reproduce the measurement analysis for the PAM 2023 paper "Exploring the Cookieverse: A Multi-Perspective Analysis of Web Cookies". Visit [our website](https://bannerclick.github.io/) for more information on the paper.

Using `upack.sh` file, you can decompress the `reproducibility.txz` file. The **raw analysis data** can be found in the `data/` directory. You can see the figures and analysis details that uses in the paper by running the `analysis.ipynb` file. The pdf files for the **figs** from the paper can be found in the `files/figs/` directory.

## Analysis

To run the **analysis script** you need to set up a Jupyter lab. All required packages and dependencies are included in the `requirement.txt` file.
For the analysis, we installed the following packages:

- beautifulsoup4
- jupyterlab
- matplotlib
- numpy
- pandas
- pingouin
- publicsuffix2
- scikit_posthocs
- scipy
- seaborn
- statannotations

### Jupyterlab

Now you can start Jupyterlab by simply running the `jupyter-lab` command. This opens a new browser tab, where you can then open the notebook located at `reproducibility/analysis.ipynb`. This allows you to reproduce our analysis from the paper.

### Important

The **Data fetching** part of the analysis script might take quite some time to be run.


# SDSS-ML
Identifying galaxies, quasars and stars with machine learning: a new catalogue of classifications for 111 million SDSS sources without spectra

The paper, published in A&A: https://arxiv.org/pdf/1909.10963.pdf

Our catalogue can be found and referenced under our DOI here: https://www.doi.org/10.5281/zenodo.3459293

These scripts explore galaxy/quasar/star classification from optical and infrared data using machine learning. We use SDSS Data Release 15. Interestingly, SDSS DR16 has spectroscopic observations of new quasars, which we had already identified using photometric data :)

SDSS_ML.py
- Cleans data, builds random forest model

SDSS_ML_analysis.py
- Creates analysis plots using the output from SDSS_ML.py

SDSS_ML_plotmaglim.py
- Generates plots from SDSS_ML.py run with magnitude limits on the training dataset

SDSS_ML_knnplots.py
- Finds nearest neighbours in 1-D and 10-D feature spaces and makes plots

SDSS_ML_classifynew.py
- Classifies new sources without spectra, and makes plots assessing the output.

SDSS_ML_UMAP.py
- Runs UMAP on the spectroscopic and photometric datasets, and makes 2D plots.



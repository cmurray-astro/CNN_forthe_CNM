# CNN_forthe_CNM

Repository for software from the paper: "Extracting the cold neutral medium from HI emission with deep learning: Implications for Galactic foregrounds at high latitude" by Claire E. Murray, J.E.G. Peek and Chang-Goo Kim (2020 ApJ submitted).

With this notebook you should be able to: 

- access remote data, including training and test data, as well as observed catalog information and CNN maps 
- build and train a 1D CNN to predict f_CNM and R_HI from 21cm brightness temperature spectra (TB(v))
- assess what the network is learning by computing the saliency for the output predictions
- compare the input values with the network predictions
- re-create Figures 6, 8, 9, and 14

### Software Dependencies

The following dependencies are used to run the Jupyter Notebook (including latest tested versions):

* keras 2.3.1
* tensorflow 2.1.0
* keras-vis
* numpy 1.18.2
* astropy 4.0.1
* tqdm 4.32.2
* pickle
* scipy 1.4.1
* sklearn 0.19.1

A conda environment can be created using the `env.yml` file:

```
conda env create -f env.yml
conda activate cnn_cnm
pip install -I git+https://github.com/raghakot/keras-vis.git
```

### Additional Data

Data in other formats/projections available upon request (please contact @cmurray-astro).

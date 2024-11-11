# Machine learning as a tool for cosmology and cosmological simulations

Hello there!
This repository is a resource of how to use ML to solve some problems in cosmology, made by me, [@natalidesanti](https://natalidesanti.github.io).
It is the material for my first guest lecturer, to the course Cosmological Simulations, ministrated by [Maria Celeste Artale](https://sites.google.com/view/maria-celeste-artale/home) at Universidad Andres Bello, Chile.

## Material

The lecture will cover two problems based on [IllustrisTNG](https://www.tng-project.org) hydrodynamical simulation from the [CAMELS](https://camels.readthedocs.io/en/latest/) project:
* **Blue and Red galaxies**
  * Use of galaxy stellar mass, star formation rate, and radius to predict galaxy color (blue or red)
  * Classification problem solved on the basis of Random Forest
* **The halo-galaxy connection**
  * Use of halo mass, radius, and velocities to predict galaxy stellar mass
  * Regression problem solved on the basis of Neural Networks
You can download the data used in this lecture by this [link](https://www.dropbox.com/scl/fi/nkbxz27del5iias8fgatl/fof_subhalo_tab_033.hdf5?rlkey=sigrg4t7tpjmq86x8ub8lsjls&st=z5x76tlk&dl=0).

## Requisites

* numpy
* pandas
* h5py
* matplotlib
* seaborn
* sklearn
* keras
* cmap

## Usage

You have two main notebooks in this repository:
* `haloXgal.ipynb`
* `redXblue.ipynb`

and you can run them as usual `jupyter notebooks`.

## Q&A

For further information, suggestions, doubts, reach me out natalidesanti@gmail.com
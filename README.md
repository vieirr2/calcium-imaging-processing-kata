# Calcium Imaging: Cell Detection and Signal Extraction Exercise

## Goal



## Setup

### Clone the Repo

```
git clone <this-github-url>
```

### Install the Packages

```
pip install -r requirements.txt
```


### Dataset

The dataset in this project is from the Flatiron Institute, distributed to test CaImAn [Givannucci et al, 2019](https://elifesciences.org/articles/38173):

  - Giovannucci A., Friedrich J., Gunn P., Kalfon J., Koay S.A., Taxidis J., Najafi F., Gauthier J.L., Zhou P., Tank D.W., Chklovskii D.B., Pnevmatikakis E.A. (2018). CaImAn: An open source tool for scalable Calcium Imaging data Analysis. eLife 2019;8:e38173.
  - Link to the N.03.00.t dataset: https://users.flatironinstitute.org/~neuro/caiman_paper/N.03.00.t.html
  - Link to the CaImAn package: https://github.com/flatironinstitute/CaImAn

Once the python packages are installed, the data can be downloaded to the data/raw folder via DVC:

```
dvc pull
```



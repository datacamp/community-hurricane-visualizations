# How not to plot hurricane predictions

This repository contains notebook + code used to generate the figures in my DataCamp article 'How not to plot hurricane visualizations' [here](https://www.datacamp.com/community/blog/how-not-to-plot-hurricane-predictions).

## Getting set up

Clone this repository

```
git clone https://github.com/datacamp/community-hurricane-visualizations
```

If you do not already have the [Anaconda distribution](https://www.anaconda.com/download/), go get it (n.b., you can also do this w/out Anaconda using `pip` to install the required packages, however Anaconda is great for Data Science and I encourage you to use it).

Navigate to the relevant directory `community-hurricane-visualizations` and install required packages in a new conda environment:

```
conda env create -f environment.yml
```

This will create a new environment called hurricanevis. To activate the environment, execute

```
source activate hurricanevis`
```

Then open the notebook `hurricanevis-code.ipynb`, generate the figures for yourself and play around with them.

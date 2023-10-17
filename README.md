# Ultrack Workshop I2K 2023

[Ultrack](https://github.com/royerlab/ultrack) from Images to Knowledge - 2023 workshop

There are two options to follow this tutorial, locally or with Google Colab.

## Local setup

You must have conda or mamba installed. If you don't have it, you can follow [their instructions](https://mamba.readthedocs.io/en/latest/mamba-installation.html#mamba-install).

First, clone this repository:

```bash
git clone https://github.com/royerlab/ultrack-i2k2023
```

Go to the repository folder:

```bash
cd ultrack-i2k2023
```

Then, you can create a new environment with the following command:

```bash
conda env create --file environment.yml
```

NOTE: If you're using apple silicon, you must use the `environment-apple.yml` file instead.

This will create a new environment called `ultrack-i2k2023`. You can activate it with:

```bash
conda activate ultrack-i2k2023
```

Then, you can browse the notebooks with:

```bash
jupyter lab
```

## Google Colab

For Google Colab, you can follow the links below. You will need a Google account.

To access GPUs on Google Colab, you can go to `Runtime > Change runtime type` and select `GPU` as the hardware accelerator.

- Introduction:

    https://colab.research.google.com/github/royerlab/ultrack-i2k2023/blob/main/intro.ipynb

- Multiple hypotheses tracking:

    https://colab.research.google.com/github/royerlab/ultrack-i2k2023/blob/main/multiple-labels.ipynb


## Additional Resources

For best performance we recommend using `gurobi`. It's a commercial software, but it's free for academic use. You can get a license [here](https://www.gurobi.com/academia/academic-program-and-licenses/).

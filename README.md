# Applied Deep Learning Tutorial with Ginkgo Model API

Welcome to our tutorial! In this tutorial, we'll learn how to predict protein temperature stability using embeddings from the Ginkgo model API. This tutorial will show you how to effectively use AI in your day-to-day work without the need for expensive GPUs or terabytes of data. We'll utilize Ginkgo's pretrained foundation models using nothing more than the CPU on your laptop!

This tutorial is written to be applicable to many biological problems.

## Dataset

For our example, we'll use the [Protein Heat Resistance](https://www.kaggle.com/datasets/igempotsdam/protein-heat-resistance-dataset/data) dataset on Kaggle. This is a large dataset that consists of protein sequences from many different organisms, including extremophiles. This gives us a good spectrum of temperatures (all the way up to ~100C). There are a lot of biological caveats for the use of this dataset, but it's pretty great to illustrate how to work with data like this.

You can download the dataset with the following command (about 1.4GB zipped, 4.7GB unzipped):

```
mkdir data
curl -L -o data/proteins.zip https://www.kaggle.com/api/v1/datasets/download/igempotsdam/protein-heat-resistance-dataset
```

Then unzip it:

```
cd data
unzip proteins.zip
```

## Notebooks

Our tutorial uses Jupyter notebooks. This environment should be pretty familiar for Pythonistas out there.

Before starting, make sure to install the dependencies as follows:

`pip install -r requirements.txt`

Happy training!

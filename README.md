# csen-140-sp26

Repository for the CSEN 140 Intro to Data Mining and Machine Learning course at Santa Clara University, Spring 2026.

## Preliminaries

I suggest creating a conda environment for examples in this class. All examples in this repo will use the Santa Clara University HPC, so commands are designed to work in that environment. You may need to update paths depending on your current project directory. Use the commands below to create and activate the environment, followed by installing some necessary packages.

```bash
module load Anaconda3
conda create --name 140wi26 python=3.13 -y
conda activate 140wi26
conda install pytorch torchvision cudatoolkit -c pytorch -y
python -m pip install matplotlib scipy pandas scikit-learn ucimlrepo
python -m ipykernel install --user --name 140wi26
```

The last command ads your newly created conda environment to Jupyter so that you can use it from the Open OnDemand environment. Next time you connect to Open OnDemand, start a Jupyter Lab session with Python 3.13 and you will see a new `140wi26` kernel available for using in jupyter or ipython notebooks. You can thus use this environment both in notebooks and in batch scripts or interactively on the command line.

## Examples & Labs

I will be adding notebooks or scripts in the `tutorials` directory to showcase some of the concepts we will discuss in class. Labs for this class will be posted in the `labs` directory.

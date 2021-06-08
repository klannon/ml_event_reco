# Introduction
This repository is simply to provide a playground for exploring different ML event reconstructino approaches.

# Setting up your environment

1. You will have all kinds of trouble unless you remember to `unset PYTHONPATH` every time you log in. 
2. [Install miniconda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html#regular-installation) if you don't already have it.
3. [Install coffea](https://coffeateam.github.io/coffea/installation.html).  The coffea installation instructions give you a lot of options, but I recommend the following basic approach:
```
conda create --name ml-reco-env -c conda-forge coffea
conda activate ml-reco-env
conda install -c anaconda ipykernel
```
4. Create a new Jupyter kernel based on this conda environment: `python -m ipykernel install --user --name=ml-reco-env`
5. Clone this Github repository: `git clone git@github.com:klannon/ml_event_reco.git` (This assumes that you've [set up an SSH key](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) for your Github account and the computer where you're working.)
6. Point your web browser at the ND [Jupyterhub instance](https://earth.crc.nd.edu:49000/).  You'll be prompted to log in with you ND NetID and usual password.
7. Browse to the directory where you installed the `ml_event_reco` repository and open either of the notebooks
8. Make sure the kernel says `ml-reco-env` (upper right hand corner).  If not, choose `Change Kernel` from the `Kernel` menu and select that.

# Medical Vision Project, mouse brain detection
Author: Baptiste Roseau

This project was part of an ENSEIRB-MATMECA  CISD option course.

## Requirement
- Having "nifti" data taken from https://www.rmsb.u-bordeaux.fr/nextcloud/index.php/s/6oMjTeDtmREpMgC?path=%2F. These data should already be available on this git repository.
- Install Python packages listed in requirement.txt. To launch a python3 virtual environment and install requiered packages, you can type:

`python3 -m venv python-venv && source python-venv/bin/activate && pip install -r requirement.txt`

## Description

A jupyter-notebook [Training.ipnb](Training.ipnb) used for model training is given. It has already been run, and the resulting model is [model.h5](model.h5). The model used is a UNET 3D.

Unfortunately, results are pretty bad as the model only returns 0. The brain is not detected.
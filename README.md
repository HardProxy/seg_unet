======================================================

**U-Net to predict segmentation in raster images**

Author: Otaviano da Cruz Neto
Class: Geospatial Data Science


National Institute of Spatial Research (INPE)

======================================================

# Geospatial Data Science Finals Project

To install all dependences just run `setup.sh` file.

> `bash setup.sh`

Here, we use:

- `keras-unet`: U-Net modeling.
- `optuna`: MLOps library to run different models in parallel.
- `tensorboard`: MLOps library to compile information through the different models.
- `rasteio`: raster image manipulation.
- `tensoflow-gpu` or `tensorflow`: General purpose ML Modeling to run on GPU or CPU.

The `setup.sh` will create some directories:

- `content`: all data created.
- `images`: patch of images.
- `train` / `test` / `val`: Input patches to train, test and validation.
- `train_seg` / `test_seg` / `val_seg`: Expected ouput segmentation to train, test and validation.

# U-Net train
 
To train the U-Net model just run:

> `python seg-unet.py` 

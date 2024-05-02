# Project 5 GitHub

This assumes you have the correct data in the folder. Everything can be run from the .ipynb file provided.

If you would like to get the data, please do the following 

'''
!wget wget http://surfer.nmr.mgh.harvard.edu/ftp/data/neurite/data/neurite-oasis.2d.v1.0.tar -O data.tar
!tar -xf data.tar;
'''

Or download from the following link: https://github.com/adalca/medical-datasets/blob/master/neurite-oasis.md

If you would like to load the pretrained weights, make sure you set 'load_weights' in TemplateCreation to True, and ensure that the path to the vxmDense model you'd like to load is correct.

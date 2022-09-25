.. SECE-tutorial documentation master file, created by
   sphinx-quickstart on Tue Sep 20 14:32:53 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to SECE's documentation!
=========================================

:Introduction: 

SECE is designed to learning effective low-dimensional features for ST-seq data. 
It is a framework for spatial region-related embedding (SE) learning and cell type-related embedding (CE) learning. 

SECE has two modules:
 - Module1: Autoencoder with negative binomial distribution to model expression counts and learn CE.
 - Modlue2: Graph Attention network to learn SE using adjacency matrix and similarity matrix constructed from spatial location. 

By applying SECE to diverse ST-seq data with different resolutions and different tissue types, we obtained state-of-the-art spatial domain identification results and demonstrated that SE can be used for tasks such as visualization and trajectory inference.
Here are examples of the installation and use of SECE.


:Usage: 
.. toctree::
   :maxdepth: 1
   
   Installation
   1. Stereo-seq Olfactory bulb
   2. Stereo-seq Hemibrian
   3. Slide-seqV2 Hippocampus
   4. STARmap Visual cortex
   5. Visium Breast cancer


:Citation: 



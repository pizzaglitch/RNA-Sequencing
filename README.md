# RNA-Sequencing Project
# Overview
This is a single-cell RNA sequencing project focusing on Microglia and Endothelial Cell (EC) interactions with respect to Alzheimer's Disease. 
This project uses data from 5,572 cells provided by cellxgene.cziscience.com from the dataset "Molecular characterization of selectively vulnerable neurons in Alzheimer’s Disease: EC microglia." Link to dataset: https://cellxgene.cziscience.com/collections/180bff9c-c8a5-4539-b13b-ddbc00d643e6 under "EC Microglia."
# Goal
The goal is to process the data through a variety of quality control and modeling methods to distill the genetic data into a condensed, informative model. From that model, characteristics of vulnerable Microglia and EC cells can be accurately presented, allowing for further connections between these vulnerable cells and Alzheimer's to be explored.
# Setup
This RNA-Sequencing project runs in a Jupyter notebook. It relies heavily on Scanpy and Anndadata libraries to process and publish the results. The necessary libraries have been packaged into a Conda environment in a .yml file and can be found in the repo (see: "environment.yml").
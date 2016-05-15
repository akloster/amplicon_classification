===============================
Pre-Basecall Amplicon Classification from Nanopore Reads
===============================

This is a demonstration/tutorial about classifying raw nanopore event data with neural networks. The three notebooks explain how to prepare the data and train the networks.

    The nanopore data is from the Paper "Real time selective sequencing using nanopore technology" by Loose et al.


Read the Notebooks
-------------------

To read the notebooks use the following links:

* Gathers and explains the metadata:
    * https://github.com/akloster/amplicon_classification/blob/master/notebooks/amplicon_metadata.ipynb
* Prepares the data for the NN library:
    * https://github.com/akloster/amplicon_classification/blob/master/notebooks/amplicon_datasets.ipynb
* Trains classifiers on the data:
	  * https://github.com/akloster/amplicon_classification/blob/master/notebooks/amplicon_classification.ipynb

Run it yourself
---------------

You need the source data files. Specifically the following sets from ENA: ERS1051240, ERS1051241 and ERS1051242

I attempted to use other files from the same paper, but I couldn't find the corresponding SAM files. The SAM files used here are from:

https://github.com/mattloose/RUFigs

If you want to run the notebooks yourself, you will need to download these files and change the paths in the notebooks.

To create the environment use these commands:


```
    conda create env
    conda activate amplicons
    jupyter notebook
```

Please report problems in reproducibility in the github issues section!




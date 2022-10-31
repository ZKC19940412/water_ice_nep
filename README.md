# water_ice_nep
Supplement files of paper "Towards Accurate, Transferable and Scalable Water/Ice Model with Neural-Evolution Potential" .


This repository is structured as follow:
* nep-pre-train-model:
    * nep.txt: NEP potential for water/ice systems, as descriped in the manscript
    * nep.in: Input file used to develop the NEP potential

* nep-fitting:
  * train.xyz: Training sets in [extended xyz format](https://wiki.fysik.dtu.dk/ase/ase/io/formatoptions.html)
  * nep.in: Input file used to develop the NEP potential
  
* colab-examples:
   * example-1.ipynb: Example notebook detailing how to fit a NEP potential and make single-point predictions with pre-train model
   * example-2.ipynb: Example notebook detailing how to perform simulations for runtime profiling, computing RDFs and vDOS.
   * example-3.ipynb: Example notebook detailing how to perform simulations to compute orthobaric densities for ice ih.
   * example-4.ipynb: Example notebook detailing how to perform simulations to compute isothermal compressibility.
   * example-5.ipynb: Example notebook detailing how to perform simulations to compute elthalpy of melting.
 
 * Disclaimers:
   * More details about the training set can be found [here](https://aip.scitation.org/doi/full/10.1063/5.0016004) and [here](https://zenodo.org/record/4004590#.YbB2H9DMJPY).
   * The colab notebook examples are compactable with [GPUMD](https://github.com/brucefan1983/GPUMD) and TDMDpy, and the notebook will introucde detail instructions on how to install and use these packages.
   * Parameters for simulations and potential fittings used in these examples are adopted so that each example can be done in reasonable amount of time, please refer to the publications for all relevant parameters.

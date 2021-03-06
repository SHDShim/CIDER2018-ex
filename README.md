# Mineral Physics Tutorial for the CIDER 2018 Meeting, Santa Barbara, CA

by Dan Shim (Arizona State University)

## Purpose of the tutorial

In the mineral physics tutorial at CIDER 2018, we will focus on:

- Understnading the EOS parameters

- Resolving some discrepancies in the mineral physics datasets through pressure scale corrections

## General guide

The tutorial materials will be provided in a VirtualMachine file.  The instruction here is for installing the tutorial materials in the VirtualMachine file.  Therefore, if you obtained the VirtualMachine file, you do not need to install the materials separately following this instruction.

However, you may use this instruction to run the tutorial materials directly in your host OS system rather than through VirtualMachine.  Advantages for this approach include: the code will be executed faster and you can continue enjoying python + jupyter setup for your data analysis in the future.

Note that the instruction here is NOT tested for Windows OS.  There should be some differences.  Please feel free to contact [Dan Shim](shdshim@gmail.com) for questions.

## Pre-requisite 

[Anaconda for python 3.6 version](https://www.anaconda.com/download/)

You need to have the `Anaconda` distribution of python installed in your VirtualMachine or your local hard drive.  If not installed already, please download the version above and install.  

Note that `Graphical installer` is easier if you have Mac OSX (and windows I believe).  For Linux, I found that the `commandline` option works better.

## Update anaconda

Once you finish the `Anaconda` installation, you may update the `Anaconda` meta package.

1. Run `terminal.app`.

2. Run anaconda `base` or `root` environment (Note that you do not need to type the commands below.  You may just copy and paste in the terminal and then press the return key.  This applies to all other commands below).
   ```bash
   source activate base
   ```
   
3. Run the following.
   ```bash
   conda update --all
   ```
   Update will take a few minutes.

## Pytheos

The tutorial materials require the `pytheos` module.  You can install it simply by:
```bash
pip install pytheos
```

## Pytheos Jupyter Notebook examples

Tutorial materials are in `jupyter notebook`.  In the instruction below, we will install the `jupyter notebook` files.

1. Under your home folder, make a new directory and move to the directory
   ```bash
   cd ~
   mkdir EOS_tutorial1
   cd EOS_tutorial1
   ```
   
2. Install `pytheos` tutorial (don't forget the period at the end of the command below).
   ```bash
   git clone https://github.com/SHDShim/pytheos.git .
   ```
   
## Data analysis examples

We also use the data analysis presented in [Ye et al. (2017) JGR](https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1002/2016JB013811) in the tutorial.  They are provided in `jupyter notebook` files.

1. Go back to your home folder, make a separate folder, and move to the folder.
   ```bash
   cd ~
   mkdir EOS_ex
   cd EOS_ex
   ```
   
2. Install the jupyter notebook files (don't forget the period at the end of the command below).
   ```bash
   git clone https://github.com/SHDShim/CIDER2018-ex.git .
   ```
   
__Now you are all set!__

## Reference

[Mineral physics tutorial for CIDER2018 @ GitHub](https://github.com/SHDShim/cider2018_tutorial)

[Pytheos @ Github](https://github.com/SHDShim/pytheos) 

[Pytheos documentation @ Github](https://shdshim.github.io/pytheos-docs/) 

[I. Jackson and S. Rigden (1997) Analysis of P-V-T data: constraints on the thermoelastic properties of high-pressure minerals. Physics of the Earth and Planetary Interiors](https://www.sciencedirect.com/science/article/pii/0031920196031433)

[Y. Ye, V. Prakapenka, Y. Meng, and S.‐H. Shim (2017) Intercomparison of the gold, platinum, and MgO pressure scales up to 140 GPa and 2500 K. Journal of Geophysical Research](https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1002/2016JB013811)


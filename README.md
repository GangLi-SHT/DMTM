# Data
## Electronic band structures
The electronic band structures for all topological nontrivial results are stored in the **bands** folder.

## mcif files
The magnetic structure files for the nontrivial collinear magnetic ground states are in the **structs** folder.

## Trace files
The trace.txt file for the magnetic structures with magnetic space group other than '1.1' generated by the **MVasp2trace** are in the **trace** folder.

In all folder above, there are two subfolders **woU** and **U** to denote the cases for DFT calulations without Hubbard U and with it.

# Codes 
The codes for automatic analysis of magnetic space group are in the **mspg** folder. You can install it by just run install.sh if all the required package are already installed. To use it, you should have pymatgen package which we use to import mcif files. In the test subfolder, you can directly run test_mspg.py to see its functionality to read the magnetic space group from a mcif file.

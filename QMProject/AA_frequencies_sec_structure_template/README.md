# Short description
This project obtains a set of several hundred protein structures from the PDB. 
Then, from this pool of data, determine the relative frequencies of the constituent amino acids for each protein secondary structural class; useing
only the three descriptors “helix,” “sheet,” and, for any AA not within a helix or sheet, “irregular.” 
Output statistical data to a human-readable file format such that the results can be opened in a statistical or graphical software package for further processing and analysis. 

# This was my approach

(Short approach description here)

# Installation/usage instructions

Required environment: 
- Online access to [PDB database](https://www.rcsb.org/)
- Python (3.7.6 version py3)
- Biopython (version 1.76)
- xssp (`mkdssp` executable, version?)
- numpy (version 1.18.1)
- matplotlib (version 3.1.1)
- pandas (version 1.0.3)

The environment is also provided as `requirements.txt` file (please provide this file, see https://medium.com/@boscacci/why-and-how-to-make-a-requirements-txt-f329c685181e, https://stackoverflow.com/questions/41249401/difference-between-pip-freeze-and-conda-list; `conda list` has the advantage that it also lists non-Python packages, like xssp, which contains the `mkdssp` executable)

After cloning the repo, enter each numbered directory successively (01_..., 02_..., etc.) and execute the Bash driver scripts to reproduce the results.

# Possibly more relevant information?

---
Project authors: Alispahic Merima

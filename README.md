# quantum-rotor-codes

The repository contains relevant code for the paper C. Vuillot, A. Ciani, B. Terhal, "Homological Quantum Rotor Code: Logical Qubits from Torsion" (2023).

The notebooks to generate the data for Figure 8 and Figure 8 itself is located in the folder /fig_8_bacon_shor.  

# Software requirements

In order to run the notebook to generate the data for Figure 8 (fig_9_bacon_shor/bacon_shor_code_levels.ipynb)
it is necessary to install the package "pysqkit" for the study of superconducting circuits. 
The package is available at https://github.com/cianibegood/pysqkit.git, where instructions for the installation
can be found.

To run the notebook with the examples of homological quantum rotor codes it is necessary to install "sage" (
see the installation guide at https://doc.sagemath.org/html/en/installation/index.html). If you are not interested
in development and you have a conda installation, we suggest to follow the instructions of installation from 
conda-forge (see https://doc.sagemath.org/html/en/installation/conda.html#sec-installation-conda). Following 
these instructions, your "sage" installation will be installed in a conda environent also called "sage". 
Once this conda environment is activated jupyter notebook can be started as

sage -n jupyter 

Now you can open and run the notebook using sage.


If you have difficulties in reproducing the results please write an email to alessandrociani89@gmail.com.






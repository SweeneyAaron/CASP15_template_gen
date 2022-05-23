# CASP15_template_gen
File genrates an sdf style file for a ligand given a smiles or Inchi string as input.
Ligand coordinates are all zeroed and must be added later once predictions are made.

Basic usage:

    template_gen.py -s <SMILES string> 
  
    will genrate a file named TEMPLATE_<SMILES string>.sdf
   
N.b Hydrogens can be removue by setting the -h flag to False.
This template can then be used to build CASP LG format files.



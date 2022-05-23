# CASP15_template_gen

File genrates an sdf style file for a ligand given a smiles or InChI string as input.
Ligand coordinates are all zeroed and must be added later once predictions are made.

Basic usage:

    python template_gen.py -s "<SMILES string>"
  
will genrate a file named TEMPLATE_<SMILES string>.sdf
   
Hydrogens can be removed by setting the -h flag to True.

    python template_gen.py -s "<SMILES string>" -h True
    
This template can then be used to build CASP LG format files.



<b> PAML/CodeML pipeline <b>
  
  Useful links:
  
  http://abacus.gene.ucl.ac.uk/software/paml.html
  
  http://abacus.gene.ucl.ac.uk/software/pamlDOC.pdf

  The sequence data I used are from:
  
  Shen et al. 2018 via 10.6084/m9.figshare.5854692 and http://www.saccharomycessensustricto.org/
  
  make_trees_031620.ipynb creates a custom tree for each gene in the genome by pruning the input tree to only include strains for which we have sequences data.
  
  paml_run_031620.ipynb runs the CodeML module of PAML on an input directory of sequence alignments and an input directory of trees and modifies the template control file.
  
  codeml_ctl_file.txt is a template control file for input into CodeML.
  
  paml_resampling_031720.ipynb parses and analyzes CodeML output files via a permutation/resampling statistical test.

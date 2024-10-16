# Three_Isospin_combination

The Mathematica notebook finds the combinations of three isospins, J_A , J_B and J_C, which are eigenstates of the total J^2, M,  i.e. the third component, and  J_{AB}^2, i.e. the isospin of the first two particles.  

The calculation is similar  to the one in the notes "Hadron Spectroscopy in Lattice QCD" by Colin Morningstar.  However in this case, a simultaneous diagonalization of J^2  and  J_{AB}^2 is performed in order to break the degeneracy which appears in the three body case. 

All possible combinations of isospins 1, 1/2 and 3/2 have been obtained.   If one is only interested in the results for J=1,1/2 and 3/2, it is sufficient to evaluate the last section "Load results". The notebook should be stored in the same directory as "Tablessave.dat" to load the data. Apart from the checks, the .dat file contains the following tables, with the nomenclature 2J_A 2J_B 2J_C: {tab222,tab221,tab223,tab211,tab213,tab233,tab111,tab113,tab133,tab333}.

The attached pdf reports the results for combining isospin 1, 1/2 and 3/2 in every possible way.

Author: Fernando Alvarado, f.alvarado@gsi.de.

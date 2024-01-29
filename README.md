# Nuc_DisTorBFact_Calc_DyadMerge
(Prototype) Python pipeline for calculating distances and torsion angles of Nucleosome DNA double bonds in PDB files

Python pipeline dsigned to perform structural analysis of nucleosomal DNA. It will parse through PDB files in a given directory to calulate the distances and torsion angles of DNA bonds relevant for CPD formation. It also has subroutines for the same calculations using bonds relevant to 6-4PP formation, boinds relevant to TAPP formation, and a general B-Factor analysis. It will output txt files containing this data for futher analysis. This version is designed to use PDB files of nucleosomes. For the versions that use transcription factor PDBs, see "TF" repositories. 

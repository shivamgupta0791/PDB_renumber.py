# pdb_renumber.py
This python script renumbers the residues from 1, changes the insertion codes into next residue number, and assign default or givem chain names.
# requirement 
python3 or above
# Required Arguments
1. -in base pdb or pqr file (you want to renumber or assign the chain)
2. -out output file name
# Optional  Argument
-c chain names seperated by comma(,). If not given it will use the default chain names. 
# run the python script in the terminal
python pdb_renumber.py -in input.pdb -out out.pdb -c A,B,C

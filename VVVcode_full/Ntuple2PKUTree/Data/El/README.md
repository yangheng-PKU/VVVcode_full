complie the EDBRE2PKUTree.C at first:

root
root [0] gSystem->AddIncludePath("-I$ROOFITSYS/include")
root [1] .L EDBR2PKUTree.C++
root [2] .q


python runEDBR2PKUTree.py (OR nohup python runEDBR2PKUTree.py &)

cp el_out*.root ./MC_el/MakePKUTree

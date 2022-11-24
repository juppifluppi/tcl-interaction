# TC/L and lipid interaction probability model
Python script to compute probability of interaction with taurocholate/lecithin based on two descriptors, logD and CrippenMR.
The model is based on results from Mol. Pharmaceutics 2022, 19, 2868−2876 (https://doi.org/10.1021/acs.molpharmaceut.2c00227), but descriptors are computed via rdkit/scopy instead of MOE/PaDEL, thus differences are expected.

Model with original coefficients: https://tcl-interaction.streamlit.app/

Model rebuilt for rdkit/scopy coefficients: https://tcl-interaction2.streamlit.app/

Lipid interaction probability model (model3.py) is currently work in progress.



Alternatively, enamine_db.html and zinc_db.html contain already calculated TC/L and lipid probabilities for drug molecules with the original models 2 and 3 from the publication, using MOE/PaDEL descriptors (not manually inspected for correct protonation!).

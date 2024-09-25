Two subsets of molecules from ChEMBL-34[1].

Those molecular datasets might be useful to people training molecular generators.

After decompression, you will get:  
chembl34_stable_ES_OA_LL.smi: 585,272 molecules.  
chembl34_stable_ES_OA_DL.smi: 756,420 molecules.  

stable=non-reactive molecules (filtered-out reactive functional groups from [5]).  
https://github.com/UnixJunkie/molenc/blob/master/bin/molenc_stable.py

ES=Easy Synthesis (SAscore <= 3.0) [2].  
https://github.com/UnixJunkie/molenc/blob/master/bin/molenc_SA.py

OA=Orally Available (according to a classifier trained on the dataset from [6]).  

LL=Lead-Like (almost the definition from [3]).  
https://github.com/UnixJunkie/molenc/blob/master/bin/molenc_lead.py

DL=Drug-Like (definition from [4]).  
https://github.com/UnixJunkie/molenc/blob/master/bin/molenc_drug.py

# Bibliography

[1] Zdrazil, B., Felix, E., Hunter, F., Manners, E. J., Blackshaw, J., Corbett, S., ... & Leach, A. R. (2024).
The ChEMBL Database in 2023: a drug discovery platform spanning multiple bioactivity data types and time periods.
Nucleic acids research, 52(D1), D1180-D1192.

[2] Ertl, P., & Schuffenhauer, A. (2009).
Estimation of synthetic accessibility score of drug-like molecules based on molecular complexity and fragment contributions.
Journal of cheminformatics, 1, 1-11.

[3] Hann, M. M., & Oprea, T. I. (2004).
Pursuing the leadlikeness concept in pharmaceutical research.
Current opinion in chemical biology, 8(3), 255-263.

[4] Tran-Nguyen, V. K., Jacquemard, C., & Rognan, D. (2020).
LIT-PCBA: an unbiased data set for machine learning and virtual screening.
Journal of chemical information and modeling, 60(9), 4263-4273.

[5] Lisurek, M., Rupp, B., Wichard, J., Neuenschwander, M., von Kries, J. P., Frank, R., ... & Kühne, R. (2010)
Design of chemical libraries with potentially bioactive molecules applying a maximum common substructure concept.
Molecular diversity, 14, 401-408.

[6] Falcon-Cano, G., Molina, C., & Cabrera-Perez, M. A. (2020).
ADME prediction with KNIME: development and validation of a publicly available workflow for the prediction of human oral bioavailability.
Journal of chemical information and modeling, 60(6), 2660-2667.

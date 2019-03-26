# EColiCRP
For McMaster iGEM.
PromoterConsensus: 
We are looking for a consensus sequence for CRP-binding promoters, and this seems to NOT have come up with one (but has found some areas of slightly higher conservation)

Uses BioPython and MUSCLE for sequence alignment and consensus determination.

Promoter ML:
Trying to use machine learning to come up with the best CRP-binding promoter, and I figured that it would be best to try to start with predicting if something was a CRP-binding promoter. This seems relatively effective. (Hardcoded features from PredCRP, https://github.com/NctuICLab/PredCRP), feature extraction script translated from Perl to Python


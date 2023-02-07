# EEG-Song-and-Participant-Classifier
This Deep model is able to classify EEG data recorded while listening to music into its respective song and listener

#
This Notebook is a two-part project - Song Classifier & Participant Classifier:
The song classifier uses the same data method presented in the paper of Ramirez-Aristizabel et al. 2022 work, however this model had a slightly different architecture which was also used in the participant classifier. The participant classifier was a complimentary project. Both projects classify EEG data by means of a method inpsired by a technique introduced by Ramirez-Aristizabel et al. 2022

#
About The Data:
Data source: https://exhibits.stanford.edu/data/catalog/sd922db3535
Authors: Kaneshiro, Blair, Nguyen, Duc T., Dmochowski, Jacek P., Norcia, Anthony M., and Berger, Jonathan
Description: The NMED-H dataset contains scalp EEG responses recorded from 48 adults as they heard intact and scrambled versions of full-length vocal works (Hindi pop songs). Sixteen stimuli were included in the experiment: Four songs in four conditions per song. Twelve participants were assigned to each stimulus, and each participant heard their assigned stimuli twice (24 trials total per stimulus). Dense-array EEG was recorded using the Electrical Geodesics, Inc. (EGI) GES 300 platform. Data are published in Matlab format. The dataset contains (1) raw EEG (individual recordings, 97 files), (2) clean EEG (aggregated by stimulus and listen, 32 files), (3) spatially filtered EEG (aggregated by stimulus condition, four files), (4) behavioral responses (grouped by listen, two files), and (5) participant-stimulus assignment file. Items (1) - (3) are compressed in .zip archives (500 MB - 2 GB each); an example file from each archive can be downloaded separately. Items (4) and (5) are < 1 KB each. This dataset can be used in combination with the Naturalistic Music EEG Dataset - Tempo (NMED-T).
Collection: Stanford Research Data
Date: 2014 - 2016

#
Terms of Use:
The use of this code must be cited by providing the URL of this repository and the author's name (Alfredo G. Ornelas).

# AEAR_EEG_stress_repo
This repository contains the EEG dataset of our research work.

The characteristics of the dataset,
1.	The data were collected using Emotiv Epoc Flex, with a sampling frequency of 128 Hz.
2.	31 subjects participated in the study; each was exposed to 3 stimuli, making a total (31*6) 186 files.
3.	The data are given in MATLAB (.mat) format.
4.	File names meaning: first two digits = subject id, second digit = product image no. (1/2/3). E.g., 011 indicates the 1st subject's EEG data corresponding to the first stimuli, and 363 indicates the 36th subject's EEG data corresponding to the third stimuli.
5.	Even though the data were collected in five stages (eyes open, eyes closed, general instruction, stimuli, and feedback), the files given here contain only the stimuli EEG data required for analysis.
6.	Following the international 10-20 EEG system, data were collected from these 16 channels - Cz, Fz Fp1, F7, F3, C3, P3, O1, Pz, Oz, O2, P4, C4, F4, F8, and Fp2.
7.	The columns of the data files indicate the channels with this serial (Cz, Fz Fp1, F7, F3, C3, P3, O1, Pz, Oz, O2, P4, C4, F4, F8, and Fp2), and the rows indicate the samples.

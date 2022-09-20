# VoxMini dataset

VoxMini is a sublist of VoxCeleb2 dataset with similar speaker distribution.

We randomly select 12.5\% video clips for each person in VoxCeleb2. 

Furthermore, we drop the data from speakers who have less than five video clips to have the VoxMini dataset of 100,000 video clips from 4,081 speakers. 

It can be used for ablation study and small-scale experiments.


Performance: with Ecapa-tdnn, test on Vox-O set:

EER: 2.39

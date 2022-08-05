# Paranoid events 

## Exploring the influence of traits and semantic content on neural event boundaries

This project was completed for the hack week component of [NeuroHackademy](https://neurohackademy.org/) by [Jiawen Huang](https://github.com/hjweric), [Ana Fouto](https://github.com/anarfouto), [Clara Sava-Segal](https://github.com/csavasegal), and [John Andrew Chwe](https://github.com/jahchwe) on 8/2/2022. 

In this project, we took data from the [Paranoia dataset](https://openneuro.org/datasets/ds001338/versions/1.0.0) and applied a HMM [(Baldassano et al., 2017)](https://www.sciencedirect.com/science/article/pii/S0896627317305937) to detect event structure. We then attempted to link these event boundaries to trait information (paranoia score) available for each subject as well as features of the auditory stimulus. 

The final presentation can be found in this repository. 

We find that we can: 
1. Replicate the general gradient of event sensitivity found by Baldassano et al., 2017: Regions associated with higher-level processing demonstrate encoding of a fewer number of events compared to lower-level regions in both whole brain parcellations and hand-selected ROIs, and these boundaries correspond to human-annotated boundaries (thanks Clara!). 
2. As participant paranoia score increases, individual variability in event timing also generally increases (note that this is opposite of what is found by Finn et al., 2018). 
3. Divergence in event timings track sentiment ratings over time. 

We would like to note that these findings are very shaky and are all subject to increased validation. 




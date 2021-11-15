
# Instructions of use

**main.slx** is the main simulation file. Subject number could be changed from `1` to `10`. Case number could be changed from `1` to `3`. 

**Case 1** is asscociated with the results of open-loop scenraio on healthy profiles. **Cases 2 and 3** are corresponding to the patients (without and with circadian rythm in their cortisol profiles. 

**Harmonics_dictionaly.mat** and **parametrs.mat** are the model parameters (i.e., circadian forcing function and latent model parameters) that are estimated offline using an expectation-maximization algorithm.

**fuzzy_sys.fis** is associated with the fuzzy control system that is used for closing the loop.

For the new control design, please replace the whole controller block and use the designed block to take the estimated energy state from the estimator block and generate the required control signal.

# Citation

If you are using our work please cite the following paper:

Fekri Azgomi H, and Faghih R.T., “**A Wearable Brain Machine Interface Architecture for Regulation of Energy in Hypercortisolism**,” *53rd Asilomar Conference on Signals, Systems, and Computers, Pacific Grove, CA, 2019.*

Fekri Azgomi H, Hahn J-O, and Faghih R.T., “**Closed-Loop Fuzzy Energy Regulation in Patients With Hypercortisolism via Inhibitory and Excitatory Intermittent Actuation**,” *Frontiers in Neuroscience, 2021*.

**Bibtex**
```

@inproceedings{azgomi2019wearable,
title={A wearable brain machine interface architecture for regulation of energy in hypercortisolism},
author={Azgomi, Hamid Fekri and Faghih, Rose T},
booktitle={2019 53rd Asilomar Conference on Signals, Systems, and Computers},
pages={254--258},
year={2019},
organization={IEEE}
}

@ARTICLE{azgomifuzzyenergy2021frontiers,
AUTHOR={Fekri Azgomi, Hamid and Hahn, Jin-Oh and Faghih, Rose T.},
TITLE={Closed-Loop Fuzzy Energy Regulation in Patients With Hypercortisolism via Inhibitory and Excitatory Intermittent Actuation},
JOURNAL={Frontiers in Neuroscience},
VOLUME={15},
PAGES={909},
YEAR={2021},
URL={https://www.frontiersin.org/article/10.3389/fnins.2021.695975},
DOI={10.3389/fnins.2021.695975},
ISSN={1662-453X},
}
```

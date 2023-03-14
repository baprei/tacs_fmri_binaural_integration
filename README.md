# tacs_fmri_binaural_integration
Data DOI: https://doi.org/10.34973/dt33-sj34 

Donders Institute project title: The neural bases of interhemispheric speech sound integration
(3011204.02)

Article title: Selective modulation of interhemispheric connectivity by transcranial alternating current
stimulation influences binaural integration

Authors: Basil C. Preisig, Lars Riecke, Matthias Sjerps, Anne Kösem, Benjamin R. Kop, Bob Bramson,
Peter Hagoort & Alexis Hervais-Adelman

Correspondance: basilpreisig@gmx.ch

Content information

This collection contains all data and code to reproduce all analyses and stimuli described in Preisig et al
(2021). For privacy reasons, all native space anatomical scans are defaced. All steps that require the
identifiable anatomical scan (fMRI preprocessing steps: (1) functional realignment and unwarping, (2)
co-registration of the structural image to the mean EPI, (3) normalization of the structural image to a
standard template, (4) application of the normalization parameters to all EPI volumes) cannot be
reproduced. Evidently, all derivatives (normalized T1.nii, normalized and smoothed functional images,
and motion parameters) from these preprocessing steps that are necessary to reproduce subsequent
analyses are shared.
Code

Most of the analysis code is written in MATLAB. A comprehensive overview and a stepwise description
of all analyses is provided by the file code/README_data_analysis_steps.m. The analysis scripts write
firstlevel data (at the individual participant level) into participant subfolders. Additional grouplevel
analyses will be stored in the subfolder /analyses. The outputs files of all grouplevel analyses and
analysis plots are shared in the collection. In principle, one only needs to install all the relevant software
(see dependencies) and to set the appropriate folderpaths in README_data_analysis_steps.m to run
the analyses.

Dependencies

MATLAB
 SPM12 (http://www.fil.ion.ucl.ac.uk/spm)
 Fieldtrip (https://www.fieldtriptoolbox.org/)
 cBrewer (https://ch.mathworks.com/matlabcentral/fileexchange/34087-cbrewer-colorbrewer-
schemes-for-matlab)
 mseb (https://ch.mathworks.com/matlabcentral/fileexchange/47950-mseb-x-y-errbar-
lineprops-transparent)
R (https://www.r-project.org/)
JASP (https://jasp-stats.org/)
Other important resources
https://en.wikibooks.org/wiki/SPM/Parametric_Empirical_Bayes_(PEB)

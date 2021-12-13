# pacc-harmonization
For the PACC harmonization paper (Hampton et al., 2021)
This project shares code that was developed to create co-calibrated scores for the PACC across the Alzheimer's Disease Neuroimaging Initiative, the Harvard Aging Brain Study, the Australian Imaging Biomarker and Lifestyle Study of Ageing and A4

This  project holds code for PACC harmonization. It contains MPlus files that demonstrate how the approach is implemented. Based on a manuscript currently under review at Neuropsychology.


| BASE MODEL CODE is the initial LAST VISIT model from the paper | MIDDLE STEP SCRIPT | EXTRACT SCRIPT FOR LONGITUDINAL LPACC SCORES FOR HABS, ADNI & AIBL |
| ------ | ------ | ------ |
| basemodel_lastvisit_bifactor.out | | - | 
| - | HABS_long_nomeansd_bifactor.out | HABS_longitudinal_fscores_bifactor.out | 
| - | ADNI_long_nomeansd_bifactor.out | ADNI_longitudinal_fscores_bifactor.out | 
| - | AIBL_long_nomeansd_bifactor.out | AIBL_longitudinal_fscores_bifactor.out |

|  A4: MIDDLE STEP SCRIPT | A4: EXTRACT SCRIPT FOR LPACC SCORES for A4 | 
| ------ | ------ |
| A4_bifactor_daisychain.out | A4_bifactor_daisychain_fscores.out | 

# olfactory_atlas


Loss of smell is present in many diseases. For example, in COVID-19 disease it is known that anosmia is present in many subjects.
In order to investigate how the olfactory circuit is alterated we created the **olfactory atlas**.

This altas, in the MNI152 space, is composed of two different files:

1. ROI atlas: that is composed of 35 ROIs
2. tract atlas: that is composed of white matter tracts

![alt text](https://github.com/marta-gaviraghi/olfactory_atlas/blob/main/roi_tracts.svg)

The ROI of the atlas were extracted from standard parcellation atlases (such as Brodmann, Juelich etc).

To generate the white matter tracts we used 10 Human Connectom Project (HCP) subjects. After having reconstructed the tracts for each subject with tractography we averaged the 10 subjects.

The olfactory atlas can be used for obtain all the ROIs and the tracts that are involved in the olfactory circuit.

For example, in COVID-19 subjects with anosmia we are using this atlas to investigate microstructural alterations (from diffusion tensor) and atrophy (T1-w image). Furthermore, the ROIs of the atlas can be used to perform a voxel based analysis (VBA) on different maps (g-ratio, Quantitative Susceptibility Mapping).

If you want to have the atlas write to marta.gaviraghi01@universitadipavia.it

The atlas is in the MNI152 space so to analyze your subjects you need to bring it into subject space.

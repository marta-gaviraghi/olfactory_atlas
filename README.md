# olfactory_atlas


Loss of smell is present in many diseases. For example, in COVID-19 diseases it is known that anosmia is present in many subjects.
In order to investigate how the olfactory circuit is alterated we create the **olfactory atlas**.

This altas, in the MNI152, is composed on two different files:

1. ROI atlas: that is composed of 35 ROIs
2. tract atlas: that is composed of white matter tracts

![prova]

For the ROI of the atlas were extracted from standard parcellation altas (such as Brodmann, Juelich etc).

To generate the white matter tracts we used 10 Human Connectom Project (HCP) subjects. After having reconstructed the traits for each subject with tractography we averaged the 10 subjects.

The olfactory atlas can be used for obtain all the ROIs and the tracts that are involved in the olfactoy circuite.

For example, in COVID-19 subjects with anosmia we are using this altas to investigate microstructural alterations (from diffusion tensor) and atrophy (T1-w image). Furthermore, the ROIs of the atlas can be used to perform a voxel based analysis (VBA) on different maps (g-ratio, quantitative susceptibility mapping).

If you want to have the atlas write to marta.gaviraghi01@universitadipavia.it

The altas is in MNI152 space so to analyze your subjects you need to bring it into subject space.

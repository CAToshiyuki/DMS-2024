
These scripts are for preprocessing of functional MRI.
To run these scripts, FSL software (https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/) package is required.

Before running these scritpts, set the working directory (type workdir=hogehoge) where anat/T1wimage.nii.gz and func/epi.nii.gz exist. 

1. brainExt.sh is the script to extract the brain in the structural image. 

2. normalization_str2atlas.sh is the script to normalize the structural image to the atlas MRI.

3. motionCorr.sh is the script to correct the motion using mcflirt_acc tools. 

4. normalization_rfmri.sh is the script to normalize the functional image to the atlas MRI.

5. smooting.sh is the script to do the spatial and temporal smoothing.

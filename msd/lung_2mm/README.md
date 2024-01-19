## MSD dataset
[Medical Segmentation Decathlon](http://medicaldecathlon.com/) published great dataset under [CC-BY-SA 4.0 License](../LICENSE.md). It is widely available for medical image analysis.

## This directory
We modified ``Task06_Lung'' dataset as 2mm isotropic resolution, and randomly obtained 2D patches from them. These patches are contained as hdf5 files for development of machine learning programs. Those files are also available under [CC-BY-SA 4.0 License](../LICENSE.md).

### Patient division
We only use images in "imagesTr" directory because they have ground-truth labels in "labelsTr" directory and useful for evaluation. 

#### Train: 37 (train_patches.h5)
['lung_003.nii.gz', 'lung_004.nii.gz', 'lung_005.nii.gz', 'lung_006.nii.gz', 'lung_010.nii.gz', 'lung_014.nii.gz', 'lung_015.nii.gz', 'lung_020.nii.gz', 'lung_023.nii.gz', 'lung_025.nii.gz', 'lung_029.nii.gz', 'lung_031.nii.gz', 'lung_033.nii.gz', 'lung_036.nii.gz', 'lung_038.nii.gz', 'lung_042.nii.gz', 'lung_043.nii.gz', 'lung_044.nii.gz', 'lung_045.nii.gz', 'lung_046.nii.gz', 'lung_047.nii.gz', 'lung_049.nii.gz', 'lung_051.nii.gz', 'lung_053.nii.gz', 'lung_055.nii.gz', 'lung_057.nii.gz', 'lung_058.nii.gz', 'lung_065.nii.gz', 'lung_066.nii.gz', 'lung_069.nii.gz', 'lung_071.nii.gz', 'lung_073.nii.gz', 'lung_074.nii.gz', 'lung_078.nii.gz', 'lung_080.nii.gz', 'lung_092.nii.gz', 'lung_096.nii.gz']

#### Val: 13 (val_patches.h5)
['lung_018.nii.gz', 'lung_026.nii.gz', 'lung_028.nii.gz', 'lung_034.nii.gz', 'lung_037.nii.gz', 'lung_048.nii.gz', 'lung_061.nii.gz', 'lung_062.nii.gz', 'lung_070.nii.gz', 'lung_075.nii.gz', 'lung_079.nii.gz', 'lung_083.nii.gz', 'lung_086.nii.gz']

#### Test: 13 (test_patches.h5)

Three images (001, 009 and 016) are also offered in nii directory.

['lung_001.nii.gz', 'lung_009.nii.gz', 'lung_016.nii.gz', 'lung_022.nii.gz', 'lung_027.nii.gz', 'lung_041.nii.gz', 'lung_054.nii.gz', 'lung_059.nii.gz', 'lung_064.nii.gz', 'lung_081.nii.gz', 'lung_084.nii.gz', 'lung_093.nii.gz', 'lung_095.nii.gz']

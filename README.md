# DL-medical-image-analysis

Repository for Deep Learning for Medical Image Analysis Group 4

## Convert Dataset
Use **preprocess.ipynb** to convert nii.gz format to npy.

## Training
Use **Training.ipynb** for training network.

Use **Finetune.ipynb** for training network with different configuration combination.

## Evaluation

Run **SavePrediction.ipynb** first.

Note: 

1. Change pred_save_dir, gt_save_dir
2. **For submission**: Add **seg_file_name = base_file_name.replace('_gt.nii', '_seg.nii.gz')** 
3. **For evaluation**: Comment **seg_file_name = base_file_name.replace('_gt.nii', '_seg.nii.gz')**

Run **Evaluation.ipynb** to get evaluation result.

Run **Visualize_results.ipynb** to visualize the ground truth and predicted masks.

Note:

1. Filename is Timestamp related. Run from start everytime.

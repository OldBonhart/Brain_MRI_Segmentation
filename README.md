# Brain MRI Segmentation

### Motivation:

MR imaging is a powerful tool for representing the soft tissue, organs and also three-dimensional visualization inside of the human body. 

Brain tissue classification or segmentation is used for detection and diagnosis of normal and pathological tissues such as MS tissue abnormalities and tumors.

Furthermore, brain image segmentation plays an important role in clinical diagnostic tools and treatment procedures such as diagnosis and follow-up and also 3D brain visualization for measuring the volume of different tissues in brain such as Gray and White Matter, Thalamus, Amygdala, Hippocampus etc. 

### Formulation of the problem:
Each pixel should be labeled “1” if it is an interesting area in the image, and “0” if not.

### Dataset:
Available [here](https://www.kaggle.com/mateuszbuda/lgg-mri-segmentation)
<p>
<img src="https://github.com/OldBonhart/Brain_MRI_Segmentation/blob/master/dataset.png" width=500 height=409>
</p>

### Solution:
[Brain_MRI_Data_Visualization_UNet_FPN.ipynb](https://github.com/OldBonhart/Brain_MRI_Segmentation/blob/master/brain_mri_data_visualization_unet_fpn.ipynb)[<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1pTsn_iCfflONwKG7n5ChJFFCEH0SE8dl)<br>

### Result:

<p>
<img src="https://github.com/OldBonhart/Brain_MRI_Segmentation/blob/master/predictions_of_unet_with_resnext50_backbone.gif" width=665 height=462>
</p>

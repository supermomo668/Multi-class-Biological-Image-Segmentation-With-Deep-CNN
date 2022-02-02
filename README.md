# Multi-class-Biological-Image-Segmentation
Demonstration of Eye image segmentation using popular segmentation framework U-net to custom double U-net: from preparation, training, analysis

workflow order
Data Preparation & Visualization.ipynb

0. Data Preparation & Visualization.ipynb
1. L2_model-training.ipynb
2. L2-Testing& Analysis.ipynb

***File Structure***

<br />../(parent folder)
<br />├── code
<br />│   ├── 0. Data Preparation & Visualization.ipynb
<br />│   ├── 1. L2_model-training.ipynb
<br />│   ├── 2. L2-Testing& Analysis.ipynb
<br />│   └── U2-net_PT-Custom.ipynb
<br />├── L2-coding challenge submission.pdf
<br />├── L2-data
<br />│   ├── Coding Challenge Image Example2a.png
<br />│   ├── Coding Challenge Image Example2b.png
<br />│   ├── data_index.csv
<br />│   ├── generator
<br />│   │   ├── U2net_transfer-vgg
<br />│   │   │   └── test_generator.pkl
<br />│   │   ├── Unet_transfer-FPN
<br />│   │   │   └── test_generator.pkl
<br />│   │   └── Unet_transfer-vgg
<br />│   │       └── test_generator.pkl
<br />│   ├── testing_set
<br />│   │   ├── data_index.csv
<br />│   │   ├── images
<br />│   │   │   ├── 000008437_Ycrop_Hres_L.png
<br />│   │   │   ├── 000008491_Ycrop_Hres_R.png
<br />│       │   ├── ....(Your testing images)
<br />│   │   ├── masks
<br />│   │   │   ├── 000008437_Ycrop_Hres_L.png
<br />│   │   │   ├── 000008491_Ycrop_Hres_R.png
<br />│       │   ├── ....(Your test mask images)
<br />│   │   ├── masks-input
<br />│   │   │   ├── 000008437_Ycrop_Hres_L.png
<br />│   │   │   ├── 000008491_Ycrop_Hres_R.png
<br />│   │   │   ├── ..... (produced by code)
<br />│   │   └── metadata
<br />│   │       ├── 000008437_Ycrop_Hres_L.yaml
<br />│   │       ├── 000008491_Ycrop_Hres_R.yaml
<br />│   │       ├── .... (Optional meta data containing your Ground Gruth)
<br />│   └── training_set
<br />│       ├── data_index.csv
<br />│       ├── images
<br />│       │   ├── 000008372_Ycrop_Hres_L.png
<br />│       │   ├── 000008373_Ycrop_Hres_R.png
<br />│       │   ├── ....(Your training input images)
<br />├── Models
<br />│   ├── U2net_transfer-vgg
<br />│   ├── Unet_transfer-FPN
<br />│   └── Unet_transfer-vgg
<br />└── Results
<br />    ├── Model-FPN_transfer-vgg (pre only)_.E106-L.h5-errors.csv
<br />    └── Model-FPN_transfer-vgg (pre only)_.E54-L.h5-iou.csv

<br />22 directories

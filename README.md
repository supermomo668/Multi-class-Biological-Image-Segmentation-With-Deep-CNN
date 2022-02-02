# Multi-class-Biological-Image-Segmentation
Demonstration of Eye image segmentation using popular segmentation framework U-net to custom double U-net: from preparation, training, analysis

workflow order
Data Preparation & Visualization.ipynb

0. Data Preparation & Visualization.ipynb
1. L2_model-training.ipynb
2. L2-Testing& Analysis.ipynb

*** File Structure ***
../(parent folder)
├── code
│   ├── 0. Data Preparation & Visualization.ipynb
│   ├── 1. L2_model-training.ipynb
│   ├── 2. L2-Testing& Analysis.ipynb
│   └── U2-net_PT-Custom.ipynb
├── L2-coding challenge submission.pdf
├── L2-data
│   ├── Coding Challenge Image Example2a.png
│   ├── Coding Challenge Image Example2b.png
│   ├── data_index.csv
│   ├── generator
│   │   ├── U2net_transfer-vgg
│   │   │   └── test_generator.pkl
│   │   ├── Unet_transfer-FPN
│   │   │   └── test_generator.pkl
│   │   └── Unet_transfer-vgg
│   │       └── test_generator.pkl
│   ├── testing_set
│   │   ├── data_index.csv
│   │   ├── images
│   │   │   ├── 000008437_Ycrop_Hres_L.png
│   │   │   ├── 000008491_Ycrop_Hres_R.png
│       │   ├── ....(Your testing images)
│   │   ├── masks
│   │   │   ├── 000008437_Ycrop_Hres_L.png
│   │   │   ├── 000008491_Ycrop_Hres_R.png
│       │   ├── ....(Your test mask images)
│   │   ├── masks-input
│   │   │   ├── 000008437_Ycrop_Hres_L.png
│   │   │   ├── 000008491_Ycrop_Hres_R.png
│   │   │   ├── ..... (produced by code)
│   │   └── metadata
│   │       ├── 000008437_Ycrop_Hres_L.yaml
│   │       ├── 000008491_Ycrop_Hres_R.yaml
│   │       ├── .... (Optional meta data containing your Ground Gruth)
│   └── training_set
│       ├── data_index.csv
│       ├── images
│       │   ├── 000008372_Ycrop_Hres_L.png
│       │   ├── 000008373_Ycrop_Hres_R.png
│       │   ├── ....(Your training input images)
├── Models
│   ├── U2net_transfer-vgg
│   ├── Unet_transfer-FPN
│   └── Unet_transfer-vgg
└── Results
    ├── Model-FPN_transfer-vgg (pre only)_.E106-L.h5-errors.csv
    └── Model-FPN_transfer-vgg (pre only)_.E54-L.h5-iou.csv

22 directories

# Cross-Diveces UI Diff Dataset


  We collected and marked some screenshots of different devices on the same App page to study cross-device GUI problems. This dataset is used for cross-device compatibility testing research and cross-device regression testing.
  
  The dataset was obtained from Baidu Netdisk, Baidu App, and Baidu Tieba. 23, 24, and 18 pages were respectively captured from the three Apps on ten different devices. The entire dataset contains 725 pairs of screenshots, of which 424 pairs have visual differences and 301 pairs have no visual differences.
  

## The directory tree of the dataset

├── BaiduApp
│   ├── diff
│   ├── label.csv
│   └── same
├── BaiduNetdisk
│   ├── diff
│   ├── label.csv
│   └── same
└── BaiduTieba
    ├── diff
    ├── label.csv
    └── same
    
- diff: There is difference in the image
-same: There is no difference in the image
-label.csv: The type and location of the difference label. Each row in label.csv represents the information of a pair of images, which is composed of 4 fields: base image path, test image path, whether there is difference, and the type and location information of difference area 

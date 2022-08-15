# Cross-Diveces UI Diff Dataset

  This dataset is presented by the article: [***Cross-Device Difference Detector for Mobile Application GUI Compatibility Testing***](https://www.computer.org/csdl/proceedings-article/icstw/2022/962800a253/1E2wtNUTP1e). If you use this dataset, please quote the following information: *Ren Y, Gu Y, Ma Z, et al. Cross-Device Difference Detector for Mobile Application GUI Compatibility Testing[C]//2022 IEEE International Conference on Software Testing, Verification and Validation Workshops (ICSTW). IEEE, 2022: 253-260.*

  We collected and marked some screenshots of different devices on the same App page to study cross-device GUI problems. This dataset is used for cross-device compatibility testing research and cross-device regression testing.
  
  The dataset was obtained from Baidu Netdisk, Baidu App, and Baidu Tieba. 23, 24, and 18 pages were respectively captured from the three Apps on ten different devices. The entire dataset contains 725 pairs of screenshots, of which 424 pairs have visual differences and 301 pairs have no visual differences.
 
 App Name | App Version | Scene Page | Number of Devices | Number of pictures
 :-------:|:-----------:|:----------:|:---------------:|:------------------:|
 Baidu NetDisk | 11.16.3 | 23 | 10 | 230
 Baidu App | 13.2.0.10 | 24 | 10 | 240
 Baidu Tieba | 12.17.1.0 | 18 | 9 | 162
 
 
 Device Information Sheet
 
  Device Name | OS Version | Resolution  | Screen Size(inch)
 :-----------:|:----------:|:-----------:|:-----------------:|
 HuaweiP30 | Harmony 2.0 | 1080*2340 | 6.1 
 HuaweiP40Pro | Harmony 2.0 | 1200*2640 | 6.58 
 Xiaomi11 | Android 11.0 | 1440*3200 | 6.81 
 Xiaomi10 | Android 10.0 | 1080*2400 | 6.67 
 HuaweiP20 | Android 10.0 | 1080*2244 | 5.8 
 HonorV20 | Android 10.0 | 1080*2310 | 6.4 
 HonorV40 | Android 10.0 | 1236*2676 | 6.72
 Xiaomi8 | Android 9.0 | 1080*2248 | 6.21
 HonorV10 | Android 8.0 | 1080*2160 | 5.99 
 HonorV8 | Android 7.0 | 1080*2244 | 5.7 
 
  

## The directory tree of the dataset

|── BaiduApp </br>
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |── diff</br>
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |── label.csv</br>
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |── same</br>
|── BaiduNetdisk</br>
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |── diff</br>
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |── label.csv</br>
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |── same</br>
|── BaiduTieba</br>
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |── diff</br>
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |── label.csv</br>
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |── same</br>


    
* ___./diff/___: There is difference in the image
* ___./same/___: There is no difference in the image
* ___.label.csv___: The type and location of the difference label. Each row in label.csv represents the information of a pair of images, which is composed of 4 fields:
  * base image path
  * test image path
  * whether there is difference
  * the type and location information of difference area 

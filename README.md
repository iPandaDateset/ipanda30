# ipanda30 dataset
This dataset can be obtained in the following ways:  
[BaiduNetDisk](https://pan.baidu.com/s/1tiAEmFPKPqwED7FJCNF8Gg)  
[GoolgelDrive](https://drive.google.com/file/d/15oN_PWWxmKknn8SSsOrFsslO9wYfgOB3/view?usp=sharing)  
The iPanda-30 dataset consists of 3,552 images of 30 individual giant pandas with the number of images per panda between 54 and 220. It is randomly divided into the training set and testing set with 2,120 and 1,432 images, respectively.  
The directory structure of iPanda-30 is as follows:  

```
----|train  
    ----|00_wuyi  
        ----|00_v001_f000825_BS2015.jpg  
        ----|00_v002_f000510_BS2015.jpg  
        ----|......  
        ----|......  
        ----|00_v217_f002070_BS2015.jpg  
    ----|01_sa  
    ... ...  
    ... ...  
    ----|29_yayun  
----|test  
    ----|00_wuyi  
    ----|01_sa  
    ... ...  
    ... ...  
    ----|29_yayun  
```

There are 30 subfolders in the train or test folder. Each subfolder represents a certain category. The file name shows the label and name of the panda. For example, "00_wuyi" means the panda name is "wuyi", and the label is 0. The corresponding panda images in this category are stored in this subfolder.   

For the image named as "00_v001_f000825_BS2015.jpg", "00" is the label; "v001" is the video sequence number; "f000825" is the video frame number; "BS2015" is the collection address and year.

# ipanda30 dataset
This dataset can be obtained in the following ways:  
[BaiduNetDisk](https://pan.baidu.com/s/1YPI5KbAQK92gM7agvkWBpA)  
[GoolgelDrive](https://drive.google.com/open?id=1ZVAyyZzKbRcr_cjUe79wsSrhJ2y5DUbs) 

!(https://github.com/iPandaDateset/ipanda30/blob/master/ipanda30.png)
**Figure:** Sample images and statistics of the iPanda30 dataset. Statistics are formatted as identity, #*images*  ( #*images-in-training*/#*images-in-testing* )

The iPanda-30 dataset consists of 3,552 images of 30 individual giant pandas with the number of images per panda between 54 and 220.   
The directory structure of iPanda-30 is as follows:  

```

----|00_wuyi  
    ----|00_v001_f000825_BS2015.jpg  
    ----|00_v002_f000510_BS2015.jpg  
    ----|......  
    ----|......  
    ----|00_v217_f002070_BS2015.jpg  
----|01_sa 
    ----|01_v004_f000190_BS2018.jpg  
    ----|01_v004_f000245_BS2018.jpg  
----|... ...  
----|... ... 
----|... ... 
----|29_yayun
    ----|......  
 
```

There are 30 subfolders in the iPanda30.zip folder. Each subfolder represents a certain category. The file name shows the label and name of the panda. For example, "00_wuyi" means the panda name is "wuyi", and the label is 0. The corresponding panda images in this category are stored in this subfolder.   

For the image named as "00_v001_f000825_BS2015.jpg", "00" is the label; "v001" is the video sequence number; "f000825" is the video frame number; "BS2015" is the collection address and year.


Initially, we randomly divide the iPanda30 dataset into the training set and testing set with 2,120 and 1,432 images, respectively.  This division result was recorded in the split0_train.txt and split0_test.txt, respectively. 
Similarly, we further divide the dataset into five different subsets recorded in split#_train.txt and split#_test.txt (# is 1 to 5).

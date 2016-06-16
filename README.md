## Data Pre-processing

Use SimpleCV

### Process

1. [Catoon-ify Image](https://github.com/DongjunLee/TIL-MAL/blob/master/Image%20Processing/catoon-ify.md)
2. Scale Image 128x128
3. Data Augmentation

### Example.

#### For DCGAN Training.

![display](images/dcgan_sample.png)  
DCGAN 모델을 Training 하기위한 이미지.

#### For Image Analysis.

![display](images/image_analysis_sample.png)  
DCGAN을 통해서 생성되는 이미지.

![display](https://github.com/DongjunLee/TIL-MAL/blob/master/Image%20Processing/original.png)  
원본

![display](https://github.com/DongjunLee/TIL-MAL/raw/master/Image%20Processing/Morphological.png)
dilate -> erode  

![display](https://github.com/DongjunLee/TIL-MAL/raw/master/Image%20Processing/Filter+%20Morphological.png)  
median x 15 -> bilateral x 30 -> dilate -> erode

Camelyon16 
task1:Whole Slide level prediction(Binary classification problem)  

task2:Find metastasis location(Segmentation problem)  

## 1.MIT
### mission: clssification
![MIT_FrameWork](https://github.com/yzh741/Medical-Image-contest/blob/master/image-store/MIT.png)
### Preprocessing  
Tissue region segmentation (Otsu’s method of foreground segmentation)
* Randomly extract patches (256 x 256) on the tissue region
    - Tumor slide : 1K positive and 1K negative from each slide 
    - Normal slide: 1K negative from each slide 
    - ~290K training patches
    - Make predictions and construct heatmaps 
    - Extract additional ~60K training patches from false positive regions  
    - 290K + 60K = 350K training patches in total  
    
### DATA AUGMENTATION
* Randomly crop a 224 x 224 sub-region and flip patches  horizontally  
### Train Network
* GoogLeNet(best)
* VGG16
* FaceNet
* AlexNet
### post-processing
* extracting 28 higher level features from heatmaps
* using random forest classifier

## 2.Exb
### mission: clssification
![MIT_FrameWork](https://github.com/yzh741/Medical-Image-contest/blob/master/image-store/exb.png)

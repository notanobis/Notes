#ASAT 

## [A Forest Fire Detection System Based on Ensemble Learning](https://www.mdpi.com/1999-4907/12/2/217)
[[Neural network]]

## Datasets
1. [BowFire](https://bitbucket.org/gbdi/bowfire-dataset/downloads/)
2. [FD-dataset](http://www.nnmtl.cn/EFDNet/)
3. [ForestryImages](https://www.forestryimages.org/browse/subthumb.cfm?sub=740)
4. [VisiFire](http://signal.ee.bilkent.edu.tr/VisiFire/)

## Learners
### Yolov5
- Inference speed & accuracy
- Reduced model size
- Location accuracy & multi-scale detection
- Propagation of low level features
- Better at long area fires than objects

### EfficientDet
- Can learn different information 
- Google's -state of the art
- Not sensitive to long area fires but more carefull (complimentary)

### EfficientNet
- Outperfomed ResNet
- Trades off between accuracy and efficiency

![[Pasted image 20220316175625.png]]
![[Pasted image 20220317013209.png]]
We compare our model with typical one-stage object detectors. As is shown in Table 3, even though Yolov5 and EfficientDet are the most powerful detectors in this task, the high false positive rate and missing detections cannot be ignored. By integrating them (2 learners), all evaluation metrics are significantly improved, but the false positive rate is increased to 51.6%, since the false positives come from both Yolov5 and EfficientDet. Under the guide of our third learner EfficientNet, the false positive rate is reduced to 0.3%. What is also worth mentioning is that, after introducing the third learner, some metrics are slightly decreased. It is because that EfficientNet wrongly treats some fire images as non-fire ones, and then ignores the object detection results, but we consider it is worthwhile to sacrifice a tiny decrease in average precision and recall for substantial improvement in the false positive rate

Αn Intelligent System For Effective Forest Fire Detection Using Spatial Data

[Αn Intelligent System For Effective Forest Fire Detection Using Spatial Data](https://arxiv.org/abs/1002.2199](https://arxiv.org/abs/1002.2199 "https://arxiv.org/abs/1002.2199)

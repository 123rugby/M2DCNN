# Convolutional Neural Networks for Task-evoked fMRI Data Classification
M2DCNN is a repository of code for A Multi-channel 2D Convolutional Neural Networks Model for Task-evoked fMRI Data Classification, using Keras (version -- ) with TensorFlow (version --) as backend.
### Publications
See the following publications for examples of this code in use:
 * **A Multi-channel 2D Convolutional Neural Networks Model for Task-evoked fMRI Data Classification.** Jinlong Hu, Yuezhen Kuang, Bin Liao, Lijie Cao, Shoubin Dong, Ping Li, (submitted)

### Codes
The codes would be updated at December 6.
#### M2D CNN

#### 3D CNN

#### 3D SepConv

#### s2D CNN

#### mv2D CNN

#### 1D CNN 

### Experiments and results
The results would be updated at December 6. 
#### Classification performance

Model	| Accuracy | Precision | F1-Score
------ | ------- | -------- | ------
PCA+SVM	| 48.94±2.36%	| 48.17±2.48%	| 0.4779±0.0232
mv2D CNN	| 63.36±2.19%	| 63.59±2.27%	| 0.6306±0.0222
3D CNN	| 82.34±1.27%	| 82.68±1.39%	| 0.8239±0.0130
3D SepConv	| 80.44±1.16%	| 80.88±1.24%	| 0.8043±0.0116
1D CNN	| 80.76±1.69%	| 80.94±1.73%	| 0.8068±0.0178
s2D CNN	| 81.80±0.89%	| 81.95±0.97%	| 0.8179±0.0094
M2D CNN	| 83.20±2.29%	| 83.63±1.87%	| 0.8321±0.0223

#### training and validation losses
2000 samples from 200 subjects:    
![loss-2000](200-Loss-mean-std-plot.png)  
5000 samples from 500 subjects：  
![loss-5000](500-Loss-mean-std-plot.png)  

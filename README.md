# Project: Weakly supervised learning-- label noise and correction


### [Full Project Description](doc/project3_desc.md)

Term: Fall 2022

+ Team #9
+ Team members
	+ Kolluri, Sameer
	+ Laddha, Shubham
	+ Li, Jenny
	+ Nguyen, Kieu-Giang
	+ Yin, Yuli

+ Project summary: In this project, we created a novel solution for image classification with noisy training labels. The team worked on building 2 models: Model I and Model II. **Model I Summary - To be updated** In Model II, we built a label-cleaning network that extracts visual features from images by utilizing a pre-trained CNN model called Inception V3. Inception V3 model was chosen because it maintains high accuracy while optimizing both memory and training time compared to other pre-trained models (AlexNet, VGGNet, ResNet). The visual features were then passed thtough a fully connected network for training. The label cleaning network is used to predict labels, which are passed through Model-I for image classification.

**Contribution statement**: Jenny and Yuli built Model-I. Kieu-Giang, Sameer and Shubham worked on Model-II. All team members participated in the computation for model evaluation. All team members approve our work presented in this GitHub repository.

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.

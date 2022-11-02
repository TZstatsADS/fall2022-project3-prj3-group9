# Applied Data Science @ Columbia
## Fall 2022
## Project 3: Weakly Supervised Learning -  Label Noise and Correction


### [Project Description](doc/project3_desc.md)

Term: Fall 2022

+ **Team members**
	+ Sameer Kolluri, ssk2258@columbia.edu
	+ Shubham Laddha, sl4983@columbia.edu
	+ Jenny Li, zl3071@columbia.edu
	+ Kieu-Giang Nguyen, kn2521@columbia.edu
	+ Yuli Yin, yy3086@columbia.edu

+ **Project summary**: In this project, we created a novel solution for image classification with noisy image labels. The team worked on building 2 models: Model I and Model II. In Model I, we tested 9 different models (5 CNN models and 4 ML models), and end up choosing InceptionV3 as the best model. In Model II, we built a label-cleaning network that extracts visual features from images by utilizing InceptionV3 again. The visual features were then passed through a fully connected network for training. The label cleaning network is used to predict labels, which are passed through Model-I for image classification. Inception V3 model was chosen for both parts because it maintains high accuracy while optimizing both memory and training time compared to other pre-trained models. In the evaluation section, we test all 3 models (baseline, model I and model II) and it shows a great improvement in performance.

+ **Contribution statement**: Yuli and Jenny developed Model I. Kieu-Giang, Sameer, and Shubham developed Model II. All team members participated in the computation for model evaluation. All team members approve our work presented in this GitHub repository.

This folder is organized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
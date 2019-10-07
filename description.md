# Proposed System

The proposed approach envisioned in this thesis exploits <b>visual<b> characteristic of fashion items to learn two relational properties between fashion items: (i) <b>visual similarity<b> and (ii) <b>visual complementariness<b>. In the following, we describe each processing step of the proposed outfit recommendation system:
  
  - Step 1 **Visual feature extraction**: The system takes as input a number of fashion items representing an outfit (the number can be different for each outfit). The process starts by extracting representative visual features from each fashion item in an outfit based on state-of-the-art CNNs. This would result in each fashion item represented by a feature vector called \textbf{item profile}. We consider several pretrained networks used in the field of visual recognition namely: AlexNet, ResNet18, GoogleNet, VGG16 and VGG19.
  
  - Step 2 **Build an outfit profile from local item profiles**: An outfit can be composed of 2 to N fashion items where N is different for each outfit. To build a predictive system on outfit level, each outfit needs to be described by a unique feature vector of fixed dimensionality. The goal of this step to aggregate local item profiles in order to build a unique outfit profile, which is essentially a feature vector of the same dimensionality of item profiles. We employed standard statistical aggregation operators based on mean, median and max in order to compute **outfit profile** for each fashion outfit in the dataset.
  
  - Step 3 **Outfit recommendation phase**: This thesis addresses the outfit compatibility prediction task in which the goal is to predict a compatibility  score for a given assembled outfit by a user. Therefore, we can treat outfit recommendation task as a binary classification task for which we make use of standard k-Nearest Neighbor (kNN) approach.
  






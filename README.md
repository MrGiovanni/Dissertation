<h1 align="center" style="margin-top: 0px;">Towards Annotation-Efficient Deep Learning for Computer-Aided Diagnosis</h1>

<a href="https://www.zongweiz.com/"><p align="center" >Zongwei Zhou</p></a>
<p align="center" >Arizona State University</p>

Advisor: Dr. Jianming Liang<br/>
Committee: Dr. Edward H. Shortliffe, Dr. Robert A. Greenes, and Dr. Baoxin Li<br/>
pdf | [defense](https://youtu.be/EQcpRikJqM0) | slides | latex<br/>

## Citing the dissertation

```
@misc{zhou2021towards,
  title={Towards Annotation-Efficient Deep Learning for Computer-Aided Diagnosis},
  author={Zhou, Zongwei},
  year={2021},
  url = "https://github.com/MrGiovanni/Dissertation",
  publisher={Arizona State University}
}
```

## Key Features

## Chapter I: Introduction

* What is Annotation?
* The Barrier: Not Enough Annotation
* Overview of Contributions

## Chapter II: A Historical Review

* The Role of Annotation
	+ Attribute Learning
	+ Categorical Learning
	+ Representation Learning
	+ Current Limitations and Future Considerations
* The Opportunity: Annotation-Efficient Deep Learning
* Related Work & Our Innovations
	+ Acquiring Necessary Annotation
	+ Designing Advanced Architectures
	+ Extracting Generic Image Features

## Chapter III: Acquiring Annotation from Human Experts
[Github](https://github.com/MrGiovanni/Active-Learning)

* Background & Motivation
* Approach & Property
	+ Selecting Based on Certainty and Consistency
	+ Handling Noisy Labels via Majority Selection
	+ Injecting Randomization into Active Selection
	+ Five Unique Properties
* Experiment & Result
	+ Benchmarking Active, Continual Fine-Tuning
	+ Assessing Eight Active Selecting Criteria
	+ Comparing Four Active Learning Strategies
	+ Cutting >80% Annotation Cost for Medical Applications
* Discussion & Conclusion
	+ What Are the Favored Prediction Patterns?
	+ How Does Intra-diversity Differ from Inter-diversity?
	+ Can Actively Selected Samples Be Automatically Balanced?
	+ How to Prevent Model Forgetting in Continual Learning?
	+ Is ACFT Generalizable to Other Models?
	+ Can We Do Better on the Cold Start Problem?
	+ Is Our Consistency Observation Useful for Other Purposes?
	+ Conclusion and Broader Impacts

## Chapter IV: Utilizing Annotation from Advanced Models ([Github](https://github.com/MrGiovanni/UNetPlusPlus))

* Background & Motivation
* Approach & Property
	+ Evolving Architectural Designs
	+ Redesigning Skip Connections
	+ Introducing Deep Supervision
	+ Two Unique Properties
* Experiment & Result
	+ Benchmarking UNet++
	+ UNet++ Outperforms U-Net in Semantic Segmentation
	+ MaskRCNN++ Tops Mask-RCNN in Instance Segmentation
	+ UNet++ Accelerates Inference Speed by Model Pruning
	+ Embedded UNet++ Surpasses Isolated U-Nets
* Discussion & Conclusion
	+ Can UNet++ Segment Lesions with Varying Sizes?
	+ How Do Multi-scale Feature Maps Aggregate in UNet++?
	+ Isolated Learning or Collaborative Learning?
	+ Conclusion and Broader Impacts

## Chapter V: Extracting Features from Unannotated Images
[miccai'19](http://www.cs.toronto.edu/~liang/Publications/ModelsGenesis/MICCAI_2019_Full.pdf) [media'21](https://arxiv.org/pdf/2004.07882.pdf) | [code](https://github.com/MrGiovanni/ModelsGenesis) | [slides](https://docs.wixstatic.com/ugd/deaea1_c5e0f8cd9cde4c3db339d866483cbcd3.pdf) | [poster](http://www.cs.toronto.edu/~liang/Publications/ModelsGenesis/Models_Genesis_Poster.pdf) | talk ([YouTube](https://youtu.be/5W_uGzBloZs), [YouKu](https://v.youku.com/v_show/id_XNDM5NjQ1ODAxMg==.html?sharefrom=iphone&sharekey=496e1494c76ed263653aa3aada61c23e6)) | [blog](https://zhuanlan.zhihu.com/p/86366534)

* Background & Motivation
* Approach & Property
	+ Learning by Image Restoration
	+ Learning from Multiple Perspectives
	+ Four Unique Properties
* Experiment & Result
	+ The Combined Learning Scheme Exceeds Each Individual
	+ Models Genesis Outperform Learning from Scratch
	+ Models Genesis Surpass Existing Pre-trained 3D Models
	+ Models Genesis Reduce Annotation Efforts by at Least 30%
	+ Models Genesis Top Any 2D/2.5D Approaches
* Discussion & Conclusion
	+ Do We Still Need a Medical ImageNet?
	+ Same-domain or Cross-domain Transfer Learning?
	+ Is Any Data Augmentation Suitable as a Transformation?
	+ Can Algorithms Autonomously Search for Transformations?
	+ Does Better Restoration Transfer Better?
	+ Can Models Genesis Detect Infected Regions from Images?
	+ Conclusion and Broader Impacts

## Chapter VI: Interpreting Medical Images

* Characteristics of Medical Images
* Clinical Needs
* Medical Application: A Case Study of PE CAD
	+ Pulmonary Embolism
	+ Generating Pulmonary Embolism Candidates
	+ Reducing Pulmonary Embolism False Positives
	+ Comparing with the State of the Art
* Discussion & Conclusion
	+ What Is the Current State of Clinical PE CAD?
	+ Conclusion and Broader Impacts

## About the Author

Zongwei Zhou<br/>

Zongwei Zhou obtained his PhD degree from Arizona State University (ASU) supervised by Dr. Jianming Liang. Zongwei holds a perfect GPA (4.0/4.0) and has received the University Graduate Fellowship twice from ASU. Drawing upon the realms of biomedical informatics, computer vision, and deep learning, his research focuses on developing novel methodologies to minimize the annotation efforts for computer-aided diagnosis and medical imaging. In addition to 11 U.S. patents pending, Zongwei has published 4 peer-reviewed clinical abstracts and over 10 peer-reviewed journal/conference articles, two of which have received the MICCAI Young Scientist Award and Elsevier-MedIA Best Paper Award. Two of his journal publications have been ranked among the most popular articles in IEEE TMI and the highest-cited article in EJNMMI Research, respectively. Furthermore, Zongwei has been awarded as the co-PI of the Bridges AI program from XSEDE. Zongwei also plays an active role in the leading societies of the computer vision and medical imaging field. He serves as a reviewer of IEEE TPAMI, MedIA, IEEE TMI, etc. and he was on the program committee for MICCAI in 2020, 2021; AAAI in 2020, 2021.

---

If you notice any typos or suggestions, do not hesitate to contact the author directly by e-mail at: giovanni.z.zhou@gmail.com
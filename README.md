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

## Table of Contents

- Introduction
	* What is Annotation?
	* The Barrier: Not Enough Annotation
	* Overview of Contributions
- A Historical Review
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
- Acquiring Annotation from Human Experts
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
	* Conclusion and Broader Impacts
	

If you notice any typos or suggestions, do not hesitate to contact the author directly by e-mail at: giovanni.z.zhou@gmail.com
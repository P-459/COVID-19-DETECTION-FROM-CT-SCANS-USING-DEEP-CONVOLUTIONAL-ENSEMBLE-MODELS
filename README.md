# COVID-19-DETECTION-FROM-CT-SCANS-USING-DEEP-CONVOLUTIONAL-ENSEMBLE-MODELS

**1.Context**
Since the outbreak of Covid-19, accurate and early detection has played a critical role in controlling the spread and imporving patient outcomes. While RT-PCR has been the gold standard, it is often limited by time delays,sensitivity issues, and logistical constraints. In contrast, CT scans offer a faster and more accessible more accessible alternative for identifying lung infections asociated with Covid-19. With advancements in deep learning, there is growing interest in applying CNNs to automate the diagnosis from CT images.

**2.Need**
**What we have:**
A dataset of CT scan images labeled for Covid-19 positive and negative cases.
**What we want:**
A robust, high-performing model that can accurately classify CT scans into COVID-19 positive or negative categories with minimal error and good generalization.

Despite the effectiveness of individual deep learning models like RestNet50, VGG16, and Xception, each has its own strengths and limitations. Ensembling these models offers a promising approach to leverage their individual capabilities for improved prediction accuracy.

**3.Task**
This work focuses on implementing and evaluating an ensemble of Restnet50,VGG16, and Xception models for the binary clssification of CT scan images. The models are trained using a carefully stratified dataset split into training, validation, testing and holdout substes to ensure unbiased performance evaluation and prevent overfitting.

**4.Objective of the Document**
> To explore the effectiveness of deep learning models (Restnet50,VGG16,Xception) in detecting COVID-19 from CT images.
> To assess the impact of model ensembling on classification accuracy.
> To document the methodology,evaluation process, and experimental results.
> To provide insights into the performance and reliability of the ensemble approach for medical diagnostics.

**5.Findings**
Individually, all three models demostrated strong performanc, with Xception slightly outperforming in terms of sensitivity.
The ensemble model achieved higher overall accuracy and robutness,reducing variance and false negatives compared to individual models.
Stratified dataset splitting contributed significantly to reliable performance assessment.

**6.Conclusion**
The study confirms that ensembling deep CNN models can substantially enhance the accuracy and reliabilty of COVID-19 detection from CT scans. The ensemble outperformed standalone models, making it a viable tool for assisting radiologists in clinical settings.

**7.Perspectives**
In the future, this approach can be extended to:
> Multi-class classification (eg: distinguishing COVID-19 from other pneumonias).
> Incorporating attention mechanisms to highlight infection regions.
> Deploying the ensemble in real-time diagnostic tools or mobile app for remote screening.
> Exploring federated learning for model training across multiple hospitals without sharing raw patients data.

This work contributes to the on-going efforts of leveraging AI in the fight against COVID-19 and lays the foundation for scalable, explainable, and deployable diagnostic solutions.

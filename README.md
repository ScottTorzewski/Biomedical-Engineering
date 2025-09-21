# 🧬 Biomedical Engineering

## *️⃣ Motivation
During my coursework at Lafayette, I chose biomedical systems as one of my ECE electives and was immediately drawn to the field. The combination of electrical and computer engineering principles with mathematical modeling, particularly through differential equations, and their application to healthcare and medicine was fascinating. While any engineering discipline contributes indirectly to society, I am motivated by the opportunity to make a more direct impact on people’s health and quality of life. The highlights below showcase several experiments and projects I have completed. Full documentation is available in the folders above.

---

## 1️⃣ Mathematical Model of Enzyme Clustering on Glucose Metabolism for Cancer Treatment
Interpreting scientific papers is a challenging but essential skill in biomedical engineering. To strengthen this ability, I analyzed “A Mathematical Model for Enzyme Clustering in Glucose Metabolism” by Miji Jeon. This paper, which applies mathematical modeling to a biological process I find particularly interesting, serves as the foundation for the discussion in this section. You can find the full reference linked at the end of the paper.

Cancer cells reprogram their metabolism to prioritize growth. This is often done by altering enzyme functions and forming clusters called glucosomes to redirect glucose metabolism to different metabolic pathways. The three metabolic pathways in this instance are glycolysis, pentose phosphate pathway, and serine biosynthesis. This study investigates how these clusters affect these key metabolic pathways by creating a mathematical model. The experiment aims to understand how changes in cluster size and enzyme activity influence cancer metabolism. If a pathway experiences an increase in activity, we can determine cancer cells rely more on those biochemical reactions. If a pathway experiences a decrease in activity, it indicates a loss of normal cellular function that can be exploited in combating cancer and potentially revealing new targets for therapy.

<br>

<p align="center">
 <img src="./Project1/Images/image8.png" alt="image8" width="800" height="800"/>
</p>

<br>

<br>

<p align="center">
 <img src="./Project1/Images/image6.png" alt="image6" width="800" height="800"/>
</p>

<br>


## 2️⃣ Comparative Analysis of Enzymatic and Non-Enzymatic Biosensors for Glucose Detection
Abstract—Glucose monitoring is essential in managing diabetes and other metabolic disorders. This drives advancements in sensor technologies for integration into electronic and wearable devices. This paper presents a comparative analysis of enzymatic and non-enzymatic electrochemical biosensors for glucose detection. Enzymatic sensors, which rely on glucose oxidase or dehydrogenase, offer high specificity and have been successfully implemented in commercial self-monitoring and continuous glucose monitoring systems. However, limitations such as enzyme degradation, oxygen dependency, and calibration requirements have led to growing interest in non-enzymatic alternatives. These fourth-generation sensors utilize metal-based catalysts (e.g., Ni, Pt, Au) to directly oxidize glucose. This offers advantages in stability, miniaturization, and reagent-free operation. The paper explores the underlying mechanisms, materials, performance metrics, and integration challenges of both approaches supported by recent literature. System-level considerations such as linearity, selectivity, detection limits, and clinical accuracy frameworks are examined to assess suitability for next-generation wearable biosensing platforms.

## 3️⃣ Biomedical Systems Laboratory Work
As part of my biomedical systems coursework, I completed a series of labs designed to measure and analyze physiological signals across multiple organ systems. Together, these projects developed my ability to integrate electrical/computer engineering tools with mathematical modeling and data analysis in the context of human health. These included: 
- Recording and processing electrocardiogram (ECG) data to detect heart rate
- Using electroencephalography (EEG) to extract alpha rhythms
- Studying cardiovascular responses to exercise
- Performing spirometry to characterize respiratory cycles, lung volumes, forced expiration, and the effects of bronchial obstruction.
---

### Electrocardiogram Recording and Heart Rate Detection
In this lab, we recorded ECG signals from a human subject using an ADInstruments PowerLab system and processed the data in MATLAB to detect heartbeats. We implemented a peak detection algorithm to calculate heart rate over time and compared the results against measurements obtained directly from LabChart. Our analysis showed consistent agreement between the algorithm and LabChart, with the subject’s heart rate generally in the 60–80 bpm range.

<br>

<p align="center">
 <img src="./Project3/images/Screenshot 2025-09-21 131935.jpg" alt="lab1" width="800" height="800"/>
</p>

<br>

---
### Electroencephalography Recording and Alpha Rhythm Extraction
In this lab, we recorded EEG signals to study two key aspects: recognizing artifacts and detecting alpha waves. First, we identified common artifacts in EEG recordings, including eye blinks, eye movements, and head motion, which often introduced large-amplitude noise beyond the normal ±50 µV range.
Next, we examined alpha rhythms (8–13 Hz), which are typically present when subjects are relaxed with eyes closed and diminish upon eye opening. While we observed spectral peaks in the alpha band during eyes-closed conditions, the expected reduction with eyes open was less pronounced in our data. This discrepancy likely stemmed from electrode placement issues and poor signal quality, but the experiment still demonstrated the characteristic frequency range of alpha activity and highlighted the importance of minimizing artifacts in EEG acquisition.


---

---


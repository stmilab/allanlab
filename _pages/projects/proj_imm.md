---
title: "STMI Lab - Project IMM"
layout: textlay
excerpt: "STMI Lab -- Project_IMM"
sitemap: false
permalink: /projects/imm/
---

# Prediction of Meal Macronutrients from Wearable Sensor Data Using Inverse Metabolic Models #

**(NSF Award IIS-2014475)**

## Description ##

In the United States, poor diet contributes to more than half of premature deaths related to cardiovascular and metabolic disease, including type 2 diabetes (T2D). At present, the number of adults developing T2D continues to rise, with over 30 million Americans living with T2D. Another 80 million are currently at-risk of progressing from pre-diabetes to T2D. Improving food choices remains a cornerstone of modern diabetes care and can decrease the risk of progression to T2D. However, at present, achieving timely and appropriate lifestyle change in adults with or at-risk of T2D is challenging. Conventional methods to record meal choice and track nutritional composition can be inaccurate (e.g., estimating protein content of a meal) and burdensome (i.e., individuals must manually enter information into a food diary). Interestingly, the blood glucose profile after a meal depends not only on the carbohydrate content but also on the amount of fat, protein, and fiber; as an example, adding fat and protein to carbohydrates generally leads to smaller increases and slower decreases in achieved glucose levels, lowering risk. This suggests that the shape of the glucose response to a meal may have the potential to indicate meal content. A unique opportunity to exploit this information is to use a continuous glucose monitor (CGM). A CGM is a small sensor that attaches to the skin and measures glucose continuously every 5-15 minutes, making it possible to automatically record the glucose responses to meals. To this aim, the investigators will conduct ambulatory studies in which people (healthy, with T2D, or at-risk of T2D) will consume a variety of conventional meals in free-living conditions while wearing a CGM and a smartwatch to assess physical activity. With data from these devices, the investigators will develop machine-learning algorithms that can predict the content of a meal. This project would be helpful to clinicians to provide new information to support positive behavior change to reduce the risk of or progression from pre-diabetes to T2D, and would make it easier for patients to passively and accurately track nutritional components of their diet, potentially leading to healthier diets and improved health.

<!-- <figure class="fourth">
  <img src="{{ site.url }}{{ site.baseurl }}/images/projpic/imm.png" style="width: 70%; float: center; margin: 10px">
</figure> -->
![]({{ site.url }}{{ site.baseurl }}/images/projpic/imm.png){: style="width: 50%"}

This project will develop new inverse metabolic models (IMMs) of the glucose response to mixed meals that can estimate the meal's macronutrient composition (carbohydrates, protein, fat, and fiber) from CGM and activity data. To account for large inter-individual variability in food metabolism, the investigators will develop IMMs that consider the phenotype of each person (e.g., anthropometric variables, gut microbiota) as well as their recent history of food intake and physical exercise. Two types of models will be developed, individualized and personalized IMMs. Individualized models are developed specifically for each person based on their own data (i.e., CGM recordings labeled with the corresponding macronutrient information), but this may require collecting a large training set per person that would be impractical in clinical settings. For this reason, the investigators will also develop personalized IMMs that leverage data from other individuals who have similar metabolic characteristics and phenotype. Accomplishing this work will require development of new deep-network recurrent architectures to estimate meals' macronutrient compositions, and attention mechanisms and transfer-learning techniques to explore and explain inter-individual variability in food metabolism. The investigators will also make available the multimodal de-identified data, including CGM recordings, anthropometric and phenotype variables, physical activity and diet entries. Such corpus, the first of its kind to be publicly released, will promote further research on computational modeling of food metabolism and diet monitoring.

## Products ##
<!-- using Chicago reference style from google scholar -->
Paromitaa, Projna, Theodora Chaspari, Seyedhooman Sajjadia, Anurag Dasa, Bobak J. Mortazavia, and Ricardo Gutierrez-Osunaa. "Personalized Meal Classification Using Continuous Glucose Monitors." (2021). [Link to paper](http://ceur-ws.org/Vol-2903/IUI21WS-HEALTHI-10.pdf)

Das, Anurag, Seyedhooman Sajjadi, Bobak Mortazavi, Theodora Chaspari, Projna Paromita, Laura Ruebush, Nicolaas Deutz, and Ricardo Gutierrez-Osuna. "A Sparse Coding Approach to Automatic Diet Monitoring with Continuous Glucose Monitors." In ICASSP 2021-2021 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), pp. 2900-2904. IEEE, 2021. [Link to paper](https://ieeexplore.ieee.org/abstract/document/9414452)

Sajjadi, Seyedhooman, Anurag Das, Ricardo Gutierrez-Osuna, Theodora Chaspari, Projna Paromita, Laura E. Ruebush, Nicolaas E. Deutz, and Bobak J. Mortazavi. "Towards The Development of Subject-Independent Inverse Metabolic Models." In ICASSP 2021-2021 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), pp. 3970-3974. IEEE, 2021. [Link to paper](https://ieeexplore.ieee.org/abstract/document/9413829)

<figure class="fourth">
  <img src="{{ site.url }}{{ site.baseurl }}/images/logopic/Logo_NSF.png" style="width: 150px">
</figure>

**[Back to Project Page]({{ site.url }}{{ site.baseurl }}/projects/)**

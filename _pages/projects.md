---
title: "STMI Lab - Projects"
layout: textlay
excerpt: "STMI Lab -- Projects"
sitemap: false
permalink: /projects/
---

# Projects #

<!-- Our overarching goal is to explore and understand new quantum states of electronic matter on the atomic scale. To do so, we use and develop novel spectroscopic-imaging scanning tunneling microscopy (SI-STM) tools to visualize the relevant quantum mechanical degrees of freedom.

Our goal is to build instruments and develop techniques that enable us to address the questions we find most interesting. This is possible thanks also to Milan's broad background with different research themes and technologies: he learned his trade in [Seamus Davis’ SI-STM lab](http://davisgroup.lassp.cornell.edu/) and with [Felix Baumberger](http://dpmc.unige.ch/gr_baumberger/index.html), and later moved as an [ETH fellow](http://www.ethfellows.ethz.ch/) to [Andreas Wallraff’s qudev lab](http://www.qudev.ethz.ch/) where he investigated coupled cavity arrays in circuit QED. We further have group members with different background and interests, working together on physics and instrumentation. -->

Here are some selected projects we currently work on:

## **Prediction of Meal Macronutrients from Wearable Sensor Data Using Inverse Metabolic Models (NSF Award IIS-2014475)** ##

### Description ###

In the United States, poor diet contributes to more than half of premature deaths related to cardiovascular and metabolic disease, including type 2 diabetes (T2D). At present, the number of adults developing T2D continues to rise, with over 30 million Americans living with T2D. Another 80 million are currently at-risk of progressing from pre-diabetes to T2D. Improving food choices remains a cornerstone of modern diabetes care and can decrease the risk of progression to T2D. However, at present, achieving timely and appropriate lifestyle change in adults with or at-risk of T2D is challenging. Conventional methods to record meal choice and track nutritional composition can be inaccurate (e.g., estimating protein content of a meal) and burdensome (i.e., individuals must manually enter information into a food diary). Interestingly, the blood glucose profile after a meal depends not only on the carbohydrate content but also on the amount of fat, protein, and fiber; as an example, adding fat and protein to carbohydrates generally leads to smaller increases and slower decreases in achieved glucose levels, lowering risk. This suggests that the shape of the glucose response to a meal may have the potential to indicate meal content. A unique opportunity to exploit this information is to use a continuous glucose monitor (CGM). A CGM is a small sensor that attaches to the skin and measures glucose continuously every 5-15 minutes, making it possible to automatically record the glucose responses to meals. To this aim, the investigators will conduct ambulatory studies in which people (healthy, with T2D, or at-risk of T2D) will consume a variety of conventional meals in free-living conditions while wearing a CGM and a smartwatch to assess physical activity. With data from these devices, the investigators will develop machine-learning algorithms that can predict the content of a meal. This project would be helpful to clinicians to provide new information to support positive behavior change to reduce the risk of or progression from pre-diabetes to T2D, and would make it easier for patients to passively and accurately track nutritional components of their diet, potentially leading to healthier diets and improved health.

This project will develop new inverse metabolic models (IMMs) of the glucose response to mixed meals that can estimate the meal's macronutrient composition (carbohydrates, protein, fat, and fiber) from CGM and activity data. To account for large inter-individual variability in food metabolism, the investigators will develop IMMs that consider the phenotype of each person (e.g., anthropometric variables, gut microbiota) as well as their recent history of food intake and physical exercise. Two types of models will be developed, individualized and personalized IMMs. Individualized models are developed specifically for each person based on their own data (i.e., CGM recordings labeled with the corresponding macronutrient information), but this may require collecting a large training set per person that would be impractical in clinical settings. For this reason, the investigators will also develop personalized IMMs that leverage data from other individuals who have similar metabolic characteristics and phenotype. Accomplishing this work will require development of new deep-network recurrent architectures to estimate meals' macronutrient compositions, and attention mechanisms and transfer-learning techniques to explore and explain inter-individual variability in food metabolism. The investigators will also make available the multimodal de-identified data, including CGM recordings, anthropometric and phenotype variables, physical activity and diet entries. Such corpus, the first of its kind to be publicly released, will promote further research on computational modeling of food metabolism and diet monitoring.

### Products ###
<!-- using Chicago reference style from google scholar -->
Paromitaa, Projna, Theodora Chasparia, Seyedhooman Sajjadia, Anurag Dasa, Bobak J. Mortazavia, and Ricardo Gutierrez-Osunaa. "Personalized Meal Classification Using Continuous Glucose Monitors." (2021). [Link to paper](http://ceur-ws.org/Vol-2903/IUI21WS-HEALTHI-10.pdf)

Das, Anurag, Seyedhooman Sajjadi, Bobak Mortazavi, Theodora Chaspari, Projna Paromita, Laura Ruebush, Nicolaas Deutz, and Ricardo Gutierrez-Osuna. "A Sparse Coding Approach to Automatic Diet Monitoring with Continuous Glucose Monitors." In ICASSP 2021-2021 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), pp. 2900-2904. IEEE, 2021. [Link to paper](https://ieeexplore.ieee.org/abstract/document/9414452)

Sajjadi, Seyedhooman, Anurag Das, Ricardo Gutierrez-Osuna, Theodora Chaspari, Projna Paromita, Laura E. Ruebush, Nicolaas E. Deutz, and Bobak J. Mortazavi. "Towards The Development of Subject-Independent Inverse Metabolic Models." In ICASSP 2021-2021 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), pp. 3970-3974. IEEE, 2021. [Link to paper](https://ieeexplore.ieee.org/abstract/document/9413829)


![NSF logo here]({{ site.url }}{{ site.baseurl }}/images/logopic/Logo_NSF.png){width=10%}
<!-- end of Project -->

<!--
**Scanning tunneling noise spectroscopy (STNS).** We have developed a novel cryogenic MHz amplifier that allows us to measure not only the average tunneling current, but also its fluctuation! This has many applications: one can detect the fluctuations of the electronic states, peculiar tunneling processes, and shot noise. We have used this instrument to discover charge trapping in the insulating layer of the cuprates, connected to the c-axis mystery, and to measure the doubling of the charge due to Andreev processes to the superfluid in a lead sample.


**Mott physics and high-temperature superconductivity.** Questions of interest include: (i), How does the Mott state collapse upon doping and how is this related to the complex phase diagram of high-temperature superconductors? (ii), What is the strange metal phase seen in correlated electron systems? Is this an exotic long-range entangled state? What is the mechanism of dissipation in that state? (iii), Why is the transition temperature in high-temperature superconductors so high? We have worked on iridates, rhodates, and cuprates.

**Nanofabricated "Smart Tips"**.
![]({{ site.url }}{{ site.baseurl }}/images/respic/SmartTip.png){: style="width: 250px; float: left; margin: 0px  10px"}
One of the  projects back from my job-proposal is to develop nanofabricated STM tips. The idea behind these “smart tips” is to use the technologies that were developed over decades in nanofabrication and make them available for scanning probe by using a nano-device instead of the traditional STM tungsten tip. One gains the flexibility of using different functionalities that are known from the fields of nanofabrication and mesoscopic physics. We are collaborating with the group Simon Groeblacher at TU Delft to realize this concept, benefitting from their unparalleled micro/nano fabrication know how.  A prototype of a smart tip is shown to the left. See publications in Microsyst Nanoeng, Nanotechnology, and PRB.

**Josephson STM.** Josephson STM has the ability to gain insight into spatial variations of the order parameter, or superfluid density. We have managed to, for the first time, use JSTM with atomic resolution on a quantum material.
We have used atomic-resolution Josephson scanning tunneling microscopy to reveal a strongly inhomogeneous superfluid in the iron-based superconductor FeTe0.55Se0.45. The results and their implications are published in Nature.

We also detected and investigated a quite particular YSR state in the same material.

**Ultra-stable SI-STM instrument.**  ![]({{ site.url }}{{ site.baseurl }}/images/respic/STMHead.png){: style="width: 250px; float: right; margin: 0px 10px"}
For SI-STM, having the most stable STM head is key. We have used finite element simulations, good choices in material science, and craftsmanship to build the most stable STM head in the world, to our knowledge. See publication in RSI.


**Strange Metals.** The strange metal phase might be the most mysterious phase of high-temperature superconductors. Here, the electrical resistivity grows linearly with temperature T in large areas of the phase diagram, with a mean free path that diminishes to a fraction of the interatomic distance. T-linear resistivity is often associated with quantum critical points and marginal-Fermi-liquid physics. In strange metals, the mystery seems to go even further: we deal with something that looks like a quantum critical phase over an extended range of the phase diagram instead of cumulating in a point. There exists no consistent theory for strange metals, leading to more adventurous new approaches including the holographic theories that use insights from gravity to explain strange metals (a recent textbook on this was written by our colleagues at Leiden University, Schalm and Zaanen).
We are part of the 'Strange Metal consortium NL' that includes the groups of Hussey, Golden, van Heumen, Zaanen, Schalm, Stoof and Vandoren. 

**Magnetic fluctuations and electron spin resonance.**
![]({{ site.url }}{{ site.baseurl }}/images/respic/SpinFluc.png){: style="width: 70%; float: center; margin: 10px"}

**Twisted bilayer graphene and other material with super-periodicities.**
We have proposed that artificial super-periodicities can lead to improved superconductivity, both because of increased density of states and because of phase space arguments (see image from our SciPost publication below). Perhaps for different reasons, twisted bilayer graphene has been shown to superconduct! We are investigate this material with the groups of Efetov, Baumberger, and van der Molen.

![]({{ site.url }}{{ site.baseurl }}/images/respic/SciPost.png){: style="width: 70%; float: center; margin: 0px"} -->

### ... and more.

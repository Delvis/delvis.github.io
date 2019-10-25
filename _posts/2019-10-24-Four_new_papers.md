---
layout: post
title: "My last 4 bioanthropology scientific papers"
description: " "
tags: [data science, osteology, forensic anthropology, machine learning, paleopathology, quantitative analysis, stature, sex estimation, geometric morphometrics]
---

Hey, I have a few new publications I want to bring your attention to.

<h3>CADOES</h3>

**d’Oliveira Coelho J**, Curate F. 2019. CADOES: An interactive machine-learning approach for sex estimation with the pelvis. *Forensic Science International*. 302:109873.

CADOES employs powerful graphical devices and 12 machine learning algorithms for estimating sex in skeletal remains using the pelvis.

<figure>
	<img src="http://osteomics.com/CADOES/LANDMARKS.png" alt="landmarks">
	<figcaption>Landmarks defining the variables used.</figcaption>
</figure>

The app is available <a href = "http://osteomics.com/CADOES/" target="_blank">at Osteomics</a>.

New paper is available <a href = "https://www.sciencedirect.com/science/article/pii/S0379073819302890" target="_blank">here</a>.

<h3>Ammer-Coelho simulator</h3>

Ammer S, **d’Oliveira Coelho J**, Cunha E. 2019. Outline Shape Analysis on the Trochlear Constriction and Olecranon Fossa of the Humerus: Insights for Sex Estimation and a New Computational Tool. *Journal of Forensic Sciences*. DOI:10.1111/1556-4029.1409.

The easiest way to understand what we did here, is to grab a humerus, look at its distal (and posterior) end, and try to estimate its sex through outline shape simulation, <a href = "http://osteomics.com/Ammer-Coelho/" target="_blank">using our app</a>! I think this is the easiest-to-apply method based in geometric morphometrics ever. Well at least to my knowledge. I created the software back in 2017, so I am glad to see the paper out finally.

<figure>
	<img src="/images/Ammer-CoelhoPCA.jpg" alt="PCA separation">
	<figcaption>PCA morphospace mined by an LDA algorithm for sex estimation</figcaption>
</figure>

<h3>SPINNE</h3>

Vilas-Boas D, Wasterlain SN, **d’Oliveira Coelho J**, Navega D, Gonçalves D. 2019. SPINNE: An app for human vertebral height estimation based on artificial neural networks. 
*Forensic Science International*. 298:121–130.

The <a href = "http://osteomics.com/SPINNE/" target="_blank">SPINNE webapp</a> together with our <a href="http://osteomics.com/raxter/" target="_blank">raxter</a> give a complete back-to-end protocol for anatomical stature estimation, even if some vertebras are missing in your individual. This is the most complete solution yet for the stature estimation problem in bioarchaeological or forensic anthropology scenarios. SPINNE uses a neural network regression approach to fill the missing values, similar to what we did previously in <a href = "http://osteomics.com/DXAGE/" target="_blank">DXAGE</a>. The paper is available <a href = "https://www.ncbi.nlm.nih.gov/pubmed/30897448" target="_blank">here</a>!

<figure>
	<img src="/images/SPINNE_CM.png" alt="correlation matrix">
	<figcaption>Correlation Matrix with all the variables.</figcaption>
</figure>

<h3>Mandibular paleopathology case</h3>

Silva A, Tomé T, Cunha C, **d’Oliveira Coelho J**, Valera A, Filipe V, Scott GR. 2018. Unilateral absence of mandibular condyle in a Bronze Age male skeleton from Portugal. *International Journal of Paleopathology*, 22: 168–172.

I contributed with some quantitative landmark-based analyses and 3D modelling for this paper.

<figure>
	<img src="/images/dice_view.png" alt="dice view">
	<figcaption>I did this 3D model of the mandible using a NextEngine Scanner.</figcaption>
</figure>

The paper described a pathological absence of the left mandibular condyle and its possible diagnoses, including subcondylar fracture, cystic defect, congenital absence, condylar aplasia and mandibular condylysis. The most likely explanation for the pathological alteration is subcondylar fracture with non-union. This mandible was likely functional, as can be inferred from dental wear and muscle attachment sites. This trauma probably occurred before adult age (male individual) when remodelling capacity is still high. <a href = "https://www.sciencedirect.com/science/article/abs/pii/S1879981717301572" target="_blank">Read more about it here</a>.
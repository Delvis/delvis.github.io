---
layout: post
title: "My most recent bioanth papers"
description: " "
tags: [data science, osteology, forensic anthropology, machine learning, paleopathology, quantitative analysis, stature, sex estimation, geometric morphometrics]
---

Hey, I have a few new publications I want to bring your attention to.

<h3>CADOES</h3>

**d’Oliveira Coelho J**, Curate F. 2019. CADOES: An interactive machine-learning approach for sex estimation with the pelvis. *Forensic Science International*. 302:109873.

CADOES employs powerful graphical devices, flexible variable selection, robust cross-validation mechanisms, and 12 machine learning algorithms for estimating sex in skeletal remains using the pelvis.

<figure>
	<img src="http://osteomics.com/CADOES/LANDMARKS.png" alt="landmarks">
	<figcaption>Landmarks defining the variables used.</figcaption>
</figure>

The app is available <a href = "http://osteomics.com/CADOES/" target="_blank">at Osteomics</a>.

New paper is available <a href = "https://www.sciencedirect.com/science/article/pii/S0379073819302890" target="_blank">here</a>.

There was media coverage about CADOES in <a href = "https://observador.pt/2019/07/29/investigadores-portugueses-criam-software-que-facilita-identificacao-do-sexo-de-esqueletos-humanos/" target="_blank">Observador</a>, <a href = "http://exameinformatica.sapo.pt/noticias/ciencia/2019-07-29-Investigadores-de-Coimbra-criam-aplicacao-que-revela-sexo-de-esqueletos" target="_blank">Exame Informática</a>, among many other portuguese magazines.

---

<h3>Ammer-Coelho simulator</h3>

Ammer S, **d’Oliveira Coelho J**, Cunha E. 2019. Outline Shape Analysis on the Trochlear Constriction and Olecranon Fossa of the Humerus: Insights for Sex Estimation and a New Computational Tool. *Journal of Forensic Sciences*. DOI:10.1111/1556-4029.1409.

The easiest way to understand what we did here, is to grab a humerus, look at its distal (and posterior) end, and try to estimate its sex through outline shape simulation, <a href = "http://osteomics.com/Ammer-Coelho/" target="_blank">using our app</a>! I think this is the easiest-to-apply method based in geometric morphometrics ever. Well at least to my knowledge. I created the software back in 2017, so I am glad to see the paper out finally. <a href = "https://onlinelibrary.wiley.com/doi/abs/10.1111/1556-4029.14096" target = "_blank">Check it here!</a>

<figure>
	<img src="/images/Ammer-CoelhoPCA.jpg" alt="PCA separation">
	<figcaption>PCA morphospace mined by an LDA algorithm for sex estimation</figcaption>
</figure>

<a href = "https://onlinelibrary.wiley.com/doi/abs/10.1111/1556-4029.14096" target="_blank">Paper available here.</a>

---

<h3>SPINNE</h3>

Vilas-Boas D, Wasterlain SN, **d’Oliveira Coelho J**, Navega D, Gonçalves D. 2019. SPINNE: An app for human vertebral height estimation based on artificial neural networks. 
*Forensic Science International*. 298:121–130.

The <a href = "http://osteomics.com/SPINNE/" target="_blank">SPINNE webapp</a> together with <a href="http://osteomics.com/raxter/" target="_blank">raxter</a> allow for a complete back-to-end protocol for anatomical stature estimation, even if some vertebras are missing in your individual. This is the most complete solution yet for the stature estimation problem in bioarchaeological or forensic anthropology scenarios. SPINNE uses a neural network regression approach to fill the missing values, similar to what we did previously in <a href = "http://osteomics.com/DXAGE/" target="_blank">DXAGE</a>. The paper is available <a href = "https://www.ncbi.nlm.nih.gov/pubmed/30897448" target="_blank">here</a>!

<figure>
	<img src="/images/SPINNE_CM.png" alt="correlation matrix">
	<figcaption>Correlation Matrix with all the variables.</figcaption>
</figure>

---

<h3>New biological profile data for the Lagos collections</h3>

Ferreira MT, Coelho C, **d'Oliveira Coelho J**, Navega D, Wasterlain SN. 2018. New data about sex and age-at-death based on the postcranial skeleton of the enslaved adult Africans found at Lagos, Portugal (15th-17th centuries). *Cadernos do GEEvH*, 7(1):7–16.

158 individuals of sub-saharan origin were excavated in an archaeological urban dump in Algarve. We re-analysed sex and age-at-death for adults (roughly 60% of the sample) using combinations of multiple methods. We provide all the dataset and results in this open access publication available at <a href = "https://geevh.jimdo.com/cadernos-do-geevh/arquivo-archive/vol-7-1/" target = "_blank">Cadernos do Grupo de Estudos de Evolução Humana</a>.

Our research team was featured on <a href = "https://elpais.com/cultura/2019/03/29/actualidad/1553848854_810812.html" target="_blank">El País!</a>

<figure>
	<img src="/images/lagos_escravo.jpg" alt="escravo">
	<figcaption>One of the individuals from the Lagos excavations.</figcaption>
</figure>

---

<h3>Mandibular paleopathology case</h3>

Silva A, Tomé T, Cunha C, **d’Oliveira Coelho J**, Valera A, Filipe V, Scott GR. 2018. Unilateral absence of mandibular condyle in a Bronze Age male skeleton from Portugal. *International Journal of Paleopathology*, 22: 168–172.

I contributed with some quantitative landmark-based analyses and 3D modelling for this paper.

<figure>
	<img src="/images/dice_view.png" alt="dice view">
	<figcaption>I did this 3D model of the mandible using a NextEngine Scanner.</figcaption>
</figure>

The paper described a pathological absence of the left mandibular condyle and its possible diagnoses, including subcondylar fracture, cystic defect, congenital absence, condylar aplasia and mandibular condylysis. The most likely explanation for the pathological alteration is subcondylar fracture with non-union. This mandible was likely functional, as can be inferred from dental wear and muscle attachment sites. This trauma probably occurred before adult age (male individual) when remodelling capacity is still high. <a href = "https://www.sciencedirect.com/science/article/abs/pii/S1879981717301572" target="_blank">Read more about it here</a>.

à bientôt.
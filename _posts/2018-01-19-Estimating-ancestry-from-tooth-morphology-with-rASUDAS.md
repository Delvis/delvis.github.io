---
layout: post
title: "Estimating ancestry from tooth morphology with rASUDAS, in the first number of Forensic Anthropology"
description: " "
tags: [data science, osteology, forensic anthropology, machine learning, biogeography, ancestry, rASUDAS, dental morphology, dental non-metrics, quantitative analysis, Arizona State University Dental Anthropology System, naive Bayes]
---



**rASUDAS** is a new web-application using a statistical framework that estimates the ancestry of unknown individuals based on their suite of tooth crown and root traits. Users can choose between 21 independent traits, scored following the well-known Arizona State University Dental Anthropology System (ASUDAS). It is powered by a world-wide reference sample representing approximately 30000 individuals from seven biogeographic regions. The statistical framework and the web application were developed using the R open source programming language. The framework uses a naive Bayes classifier to assign posterior probabilities for individual group assignment. To test the application, 150 individuals were selected from the C. G. Turner II database. In a seven-group analysis, the model correctly assigned individuals to groups 51.8% of the time (chance is 14%!). In a four-group analysis (chance = 25%), classification accuracy improved to 66.7%. With three groups, accuracy was at 72.7%. It is still necessary to validate the program using forensic cases and to augment the reference sample with modern skeletal data. However, results from the current version of rASUDAS are presented as proof of concept on the potential of dental morphology in ancestry estimation in medico-legal contexts. This software has been described in the first issue of the new scientific journal <a href = "http://journals.upress.ufl.edu/fa" target="_blank">*Forensic Anthropology*</a>. The application is available at rASUDAS is free! You can try it <a href = "http://osteomics.com/">osteomics</a>.

<figure>
	<a href="http://journals.upress.ufl.edu/fa" target="_blank"><img src="/images/ForAntUFPress.png" alt="Forensic Anthropology Journal"></a>
	<figcaption>New scientific journal: Forensic Anthropology</figcaption>
</figure>


**Why teeth?**

The incorporation of dental morphological analyses into forensic anthropological casework has several advantages:
1. there is a robust body of literature outlining the heritability, development, evolution, and population history of dental morphology, which allows for accurate interpretations of results;
2. teeth are not subject to plastic change over a lifetime; and
3. teeth are often better preserved than other parts of the skeleton; Further,
4. dental morphology represents a different aspect of the genotype and is the result of distinct evolutionary relationships that go beyond the mid-face and shape and size of the cranial vault.

The ability to incorporate more information from the skeleton when assessing ancestry is critical in creating accurate estimates of ancestry. Dental morphology couched in a statistical framework can become an integral part of the methods regularly used by forensic anthropologists in ancestry estimation.


rASUDAS is free! You can try it <a href = "http://osteomics.com/rASUDAS" target="_blank">here</a>.

Feel free to read the paper, here is a very cool historical snippet from it on how me and Navega were working on these kind of projects early on in 2015.

<figure>
	<img src="/images/rASUDAS1.PNG" alt="rASUDAS creation">
	<figcaption>Osteomics becoming part of forensic anthropology history!</figcaption>
</figure>

Congrats to my colleagues,

<a href = "http://journals.upress.ufl.edu/fa/article/view/517" target="_blank">rASUDAS: A New Web-Based Application for Estimating Ancestry from Tooth Morphology</a>

*G. Richard Scott, Marin A. Pilloud, David Navega, João d'Oliveira Coelho, Eugénia Cunha, Joel D. Irish*


**DOI:** http://dx.doi.org/10.5744/fa.2018.0003


Bo
asudas
rsrsrs

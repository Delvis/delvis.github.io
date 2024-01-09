---
layout: post
title: "First PhD chapter on fossil site remote detection"
description: "Finding fossil sites from satellite pixels"
modified: 2021-06-08
image: /images/GPL12_350m_distance_fromPickfordMammals.jpg
tags: [Geospatial Paleontology, Southeast Africa, Late Miocene, Remote Sensing, Unsupervised Learning]
---

Just published the first chapter of my PhD on remote fossil site detection using satellite images and unsupervised learning in <a href = "https://peerj.com/articles/11573/" target = "_blank">PeerJ</a>.

**d’Oliveira Coelho J**, Anemone RL, Carvalho S. 2021. Unsupervised learning of satellite images enhances discovery of late Miocene fossil sites in the Urema Rift, Gorongosa, Mozambique. *PeerJ* 9:e11573 https://doi.org/10.7717/peerj.11573

It is open acess and available at <a href = "https://peerj.com/articles/11573/" target = "_blank">https://peerj.com/articles/11573/</a>

<figure>
	<img src="https://raw.githubusercontent.com/Delvis/kmeansGorongosa/master/img/kmeansGorongosa_Figure_2.png" alt="a) GPL-1 outcrops, notice how the surrounding vegetation is far more dense and extensive than in typical fossil sites from the EARS; b) GPL-1 in high-resolution satellite image, extracted from bing.com, shows a reduction of vegetation, but outcrops are barely noticeable; c) GPL-1, in a black rectangle, appears brighter than surrounding areas, when being mapped by lower resolution Landsat 8 false colour (infrared) image, and the same happens with other fossil sites, suggesting that infrared bands might be a useful indicator of fossiliferous deposits.">
	<figcaption>The miombo woodland and the challenges it presents to fossil prospecting</figcaption>
</figure>

The paper starts by exploring the spatial and temporal gaps of the primate & hominid fossil record of Africa in the late Miocene. The Gorongosa National Park in Mozambique is shown to be a strategic location, with great potential to fill some major gaps in paleoanthropology.

<figure>
	<img src="https://raw.githubusercontent.com/Delvis/kmeansGorongosa/master/img/kmeansGorongosa_Figure_1.png" alt="(A) Time gap: during this key period the African fossil record of primates is very incomplete (evaluated through species richness); but notice the split estimates from genomics; (B) spatial gap: virtually no fossils of this age are known in southeastern Africa, notice the strategic location of Gorongosa. Data extracted from paleobiodb.org, map adapted from Bobe et al. (2018); (C) study area for k-means within the geological context of Gorongosa, adapted from Habermann et al. (2019).">
	<figcaption>The great gaps of the African late Miocene</figcaption>
</figure>

We also discuss the difficulties of surveying for new paleontological localities, specially within modern forests/woodlands as in Gorongosa, since dense vegetation cover reduces visibility (i.e. finding clues in topography and landscape).

<figure>
	<img src="https://raw.githubusercontent.com/Delvis/kmeansGorongosa/master/img/kmeansGorongosa_Figure_3.png" alt="(A) Despite the ground foliage and dense vegetation, in situ and surface evidence of fossils abound in the gully valley connecting GPL-12 to GPL-12B; (B) Systematic mapping and collecting of surface fossil finds by students of the field school; (C) Side gully (~3 m deep) exposure and shovel test pit at GPL-12. Photographs are from the Paleo-Primate Project Gorongosa archive.">
	<figcaption>Surveying for fossils in a densely vegetated context</figcaption>
</figure>

To increase the chances of a successful discovery of fossil sites, we introduced an algorithmic pipeline. 1) Download Landsat 8 satellite image ➜ 2) crop image to study area ➜ 3) clustering algorithm ➜ 4) binarize clusters and calculate variable importance using randomForest 

<figure>
	<img src="https://raw.githubusercontent.com/Delvis/kmeansGorongosa/master/img/kmeansGorongosa_Figure_4.png" alt="(1) Example of one of the seven spectral bands satellite images used in this study; (2) false colour map based on the infrared bands, after cropping to study area; (3) results of clustering using all seven spectral bands; (4) Binarize clusters for classification by selecting the cluster that contains most fossil sites as the target class (“walking back the cat”) versus all other clusters combined into a single class.">
	<figcaption>Flowchart of the algorithmic pipeline used for remote fossil site detection</figcaption>
</figure>

4 new fossil sites were discovered in Gorongosa National Park using this approach. Overall accuracy of the binarized k-means clusters was ~ 85%. This indicates the high potential of our remote sensing pipeline for exploratory paleontological surveys.

<figure>
	<img src="https://raw.githubusercontent.com/Delvis/kmeansGorongosa/master/img/kmeansGorongosa_Figure_7.png" alt="New fossil sites GPL-10, 11, 12 and 12B are documented here for the first time. Trackways of surveys during 2018 are drawn in black. Clusters 2–8 are merged into a single cluster and compared against cluster 1 (predictive cluster). Total area = 36 km2. One grid square = 1 km2. One pixel-cell = 900 m2.">
	<figcaption>Binarized classification plotting cluster 1 versus all other clusters</figcaption>
</figure>

Relative importance of spectral bands for clustering was determined using the **randomForest** algorithm, and near-infrared was the most important variable for fossil site detection, followed by other infrared bands. The visible spectrum did a poor job as an indicator of fossil sites.

<figure>
	<img src="https://raw.githubusercontent.com/Delvis/kmeansGorongosa/master/img/kmeansGorongosa_Figure_8.png" alt="Bars represent relative importance of the spectral predictors for optimally classifying all clusters as calculated by a supervised random forest algorithm (Breiman, 2001). Specific variable importance for detecting cluster 1 is shown with open circles.">
	<figcaption>Variable importance of spectral bands for clustering</figcaption>
</figure>

This tool can be used for locating new fossil sites. In Gorongosa, the discovery of the first estuarine coastal forests of the East African Rift System (EARS) fills an important paleobiogeographic gap of Africa. The new sites will be key for testing hypotheses of primate evolution in such settings.

<figure>
	<img src="/images/Figure2A_map_HQ_with_stream_network.jpg" alt="">
	<figcaption> Map of Gorongosa National Park along the East African Rift Valley, with the Cheringoma Plateau to the east and Mount Gorongosa to the northwest. The park hosts a wide range of environments. The new paleontological sites on the Cheringoma Plateau are ~95 km from the coast</figcaption>
</figure>


<h3>Abstract</h3>

**Background**

Paleoanthropological research focus still devotes most resources to areas generally known to be fossil rich instead of a strategy that first maps and identifies possible fossil sites in a given region. This leads to the paradoxical task of planning paleontological campaigns without knowing the true extent and likely potential of each fossil site and, hence, how to optimize the investment of time and resources. Yet to answer key questions in hominin evolution, paleoanthropologists must engage in fieldwork that targets substantial temporal and geographical gaps in the fossil record. How can the risk of potentially unsuccessful surveys be minimized, while maximizing the potential for successful surveys?

**Methods**

Here we present a simple and effective solution for finding fossil sites based on clustering by unsupervised learning of satellite images with the k-means algorithm and pioneer its testing in the Urema Rift, the southern termination of the East African Rift System (EARS). We focus on a relatively unknown time period critical for understanding African apes and early hominin evolution, the early part of the late Miocene, in an overlooked area of southeastern Africa, in Gorongosa National Park, Mozambique. This clustering approach highlighted priority targets for prospecting that represented only 4.49% of the total area analysed.

**Results**

Applying this method, four new fossil sites were discovered in the area, and results show an 85% accuracy in a binary classification. This indicates the high potential of a remote sensing tool for exploratory paleontological surveys by enhancing the discovery of productive fossiliferous deposits. The relative importance of spectral bands for clustering was also determined using the random forest algorithm, and near-infrared was the most important variable for fossil site detection, followed by other infrared variables. Bands in the visible spectrum performed the worst and are not likely indicators of fossil sites.

**Discussion**

We show that unsupervised learning is a useful tool for locating new fossil sites in relatively unexplored regions. Additionally, it can be used to target specific gaps in the fossil record and to increase the sample of fossil sites. In Gorongosa, the discovery of the first estuarine coastal forests of the EARS fills an important paleobiogeographic gap of Africa. These new sites will be key for testing hypotheses of primate evolution in such environmental settings.

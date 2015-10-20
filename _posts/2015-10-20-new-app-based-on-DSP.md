---
layout: post
title: "New webapp based on the DSP method"
description: "Diagnose Sexuelle Probabiliste: betteR, fasteR, strongeR"
tags: [programming, anthropology, open science, sex diagnosis, osteology]
---


Today was a very productive day. But something stood of, with a *shiny* aura around it.

That's it folks. <a href = "http://osteomics.com" target = "_blank">Osteomics</a> is releasing a new app today, on one of the 4 basic pillars of Forensic Anthropology, one that we hadn't explored yet: **sex diagnosis**. It is based on a famous article by Murail *et al*. (2005) that has probably the method with best balance between applicability and overall accuracy for sex estimation in osteology. Basically, we've implement a new interface onto the same algorithm (that has been rewritten in R). Which is now, by the way, *way faster* than the original DSP Excell-based software.

It allows a case-by-case input, if you are in the field, with your mobile phone or tablet, you can access it and estimate sex right away. If you are doing more intensive laboratory work, it also has a population input mode through **.csv** upload, and it can calculate literally thousands of cases and generate an output of results in less than a second. Currently it is solely limited by internet access. This means, that contrary to <a href = "http://projets.pacea.u-bordeaux.fr/logiciel/?id=2" target = "_blank">DSP original version</a> it is not Windows-exclusive, neither Excell-dependent!

Here is the link:

<a href = "http://apps.osteomics.com/DSP/" target = "_blank">DSP: betteR, fasteR, strongeR!</a>

Since it is still on early stage (I'll be adding a Manual with images tomorrow and other functionalities), I would be very grateful if you guys tested it out, left any commentaries or try to crack it until you find some bugs for me to correct. After this starts to look as a final product, I will update it and add it to the <a href="/software/" target = "_blank">Software section</a>.

Hugs!

**References:**

Murail P, Bruzek J, Houet F, Cunha E. 2005. DSP: A tool for probabilistic sex diagnosis using worldwide variability in hip-bone measurements. *Bulletins et mémoires de la Societé d'Anthropologie de Paris*, **17**, (3-4), 167-176.
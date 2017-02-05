---
layout: post
title: "Small world and deep neural coincidences"
description: "Or how sharing stuff on the internet makes you come across your own stuff years later"
tags: [programming, data science, entomology, deep learning]
---

Today I was trying to update myself on the state of the art of deep learning, a paradigm of machine learning that is exploding in popularity. In very few words, it grows artificial neural networks with very deep architectures (i.e. hundreds of hidden layers, thousands or millions of neurons) in an attempt to simulate or even beat human performance in a variety of tasks, for example, recognizing objects in pictures. And somehow I ended up watching this video:


<iframe width="560" height="315" src="https://www.youtube.com/embed/3lp9eN5JE2A" frameborder="0" allowfullscreen></iframe>

It is a work from the Evolving AI Lab, with Jeff Clune giving the lecture. But as he notices, most of the work presented, was done by his student, Anh Nguyen, who has some awesome publications in the field of deep learning.

Now the coolest thing, is that near the end of the video, Clune starts talking about how deep learning can be used in a generative sense. For example, you can give hundreds of pictures of a flower or a bus to your model, and then use your model to create new, never seen before, pictures of what the model understands as a flower, or a bus. Then he shows some images of the results, and its very interesting.

<figure>
	<img src="/images/deepnn_ladybugs.png" alt="7-spot ladybug">
	<figcaption>On the left, real pictures of ladybugs, on the right computer-generated images of ladybugs.</figcaption>
</figure>

Now the crazy thing. When I think about machine learning in general is hard not to see connections on how these abstract algorithms work and how we humans - a big-brain ape - think. With most algorithms, it is kind of a stretch really! Ultimately, it is hard to conceive of concepts like creativity, coming from the side of computers. But deep neural networks are a really strange metaphor for "understanding" in its general sense, and if you go too deep in the rabbit hole, the experience of thinking about all this stuff gets a bit psychedelic.

What showed up in the video you can see here: <a href="http://www.evolvingai.org/synthesizing" target="_blank">evolvingai.org/synthesizing</a>. Near the bottom there are some examples with ladybugs, cardoon flowers, fountains and other objects. I was not looking specifically at anything, but for a few seconds I got this very paranoid feeling of "something is really wrong!". It took me a few minutes to realize what it was. But then it hit me... there was a picture taken by me there!

<figure>
	<img src="/images/COCCINELLA-SEPTEMPUNCTATA.png" alt="7-spot ladybug">
	<figcaption>Coccinella setempunctata, copulating (May, 2009 - Ansião, Portugal). This is actually another picture from the same day, that I like better.</figcaption>
</figure>

So it seems I had this picture on <a href="https://www.flickr.com/photos/joaocoelho/3494485393" target="_blank">my old Flickr account</a>. And somehow, as they explain "we show the top 9 validation set images that highest activate a given neuron (left) and 9 synthetic images produced by our method (right)", this makes my picture a very ladybug-ish picture to "ladybug neurons" that were trained with thousands of ladybug pictures, or so I guess. That's so strange and hard to gasp.

Cool stuff I thought I could share.

Bye,
joaninha voa voa que o teu pai...


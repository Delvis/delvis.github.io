---
layout: page
title: Theme Setup
description: "Instructions on how to install and customize the modern Jekyll theme HPSTR."
image:
  feature: abstract-11.jpg
  credit: dargadgetz
  creditlink: http://www.dargadgetz.com/ios-7-abstract-wallpaper-pack-for-iphone-5-and-ipod-touch-retina/
share: true
---

General notes and suggestions for customizing **HPSTR**.

## Basic Setup for a new Jekyll site

1. [Install Bundler](http://bundler.io) `gem install bundler` and then install [Jekyll](http://jekyllrb.com) and all dependencies `bundle install`.
2. Fork the [HPSTR Jekyll Theme repo](https://github.com/mmistakes/hpstr-jekyll-theme/fork).
3. Clone the repo you just forked and rename it.
4. Edit `_config.yml` to personalize your site.
5. Check out the sample posts in `_posts` to see examples for pulling in large feature images, assigning categories and tags, and other YAML data.
6. Read the documentation below for further customization pointers and documentation.

<div markdown="0"><a href="https://github.com/mmistakes/hpstr-jekyll-theme/archive/master.zip" class="btn">Download the Theme</a></div>

**Pro-tip:** Delete the `gh-pages` branch after cloning and start fresh by branching off `master`. There is a bunch of garbage in `gh-pages` used for the theme's demo site that I'm guessing you don't want on your site.
{: .notice}

---

## Laboratory of Forensic Anthropology

<figure>
  <img src="http://jcoelho.com/images/lafLogo1.png" alt="Laboratório de Antropologia Forense">
  <figcaption>The idea was to recreate the vitruvian man concept, a Da Vinci's famous drawing. Instead using a skeleton to represent the main object of study for forensic anthropologists.</figcaption>
</figure>

{% highlight yaml %}
title:            Laboratório de Antropologia Forense
description:      Renovating the image of a forensic anthropology lab in the life sciences department of the University of Coimbra.

{% endhighlight %}

---

## Scientific Posters

I enjoy a lot to design scientifc poster that are clean, minimalist and easily convey useful info to the public in conferences.

{% capture images %}
  /images/TALUSposter1.png
  /images/HOTposter1.png
  /images/TALUSposter2.png
{% endcapture %}
{% include gallery images=images caption="Scientifc posters for international conferences." cols=3 %}

---
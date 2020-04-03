---
layout: page
title: Experience
subtitle: Positions occupied so far.
icon: fa-briefcase
order: 2
---
{% comment %}
Snippets
<a href="{{ theurl }}" class="icon-b fa-github"></a>
<a href="mailto:{{ themail }}" class="icon fa-envelope"></a>
{% endcomment %}


## Developer @ [DCI-NET](https://github.com/DCI-NET)
# Universidad de Guanajuato, Mexico. 2019-2020
A project emerged within the [Chemical, Electric, and Biomedical Engineering Department](http://www.dci.ugto.mx/diqeb/) of the Science and Engineering Division of the [University of Guanajuato](https://www.ugto.mx/). The purpose of it was developing a Deep Learning repository for Semantic Segmentation of Biomedical Images. Being part of the first group of undergraduate students who worked on this project, my work mainly focused on the following tasks:

1. Revision of *l'état de l'art*, finding the [MultiResUNet architecture](https://github.com/nibtehaz/MultiResUNet).
2. [Reimplementation](https://github.com/gmagannaDevelop/MyMultiResUNet) of said architecture.
3. Training and testing the repository's models using [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb). 

It is to be noted however, that I rapidly encountered the complications of training and testing Deep Learning models. For this reason the main focus of my work shifted towards developing a logging system that could automatically register  hardware specs at model instantiation time as well as every function call, notes, etc.

The system I developed is hosted [here](https://github.com/gmagannaDevelop/segnet/blob/callback_test/segnet/utils/Segmed.py). You can find a pdf manual of it (_in Spanish_) [here](/assets/docs/Segmed_Class_Example.pdf).

{% assign themail = "developeredwin@gmail.com" %}
{% assign theurl = "https://github.com/edwinb-ai" %}
My main collaborator and mentor during this period was **Edwin Bedolla _B.Sc._**<a href="{{ theurl }}" class="icon-b fa-github"></a><a href="mailto:{{ themail }}" class="icon fa-envelope"></a>


{% assign themail = "marco@marco-heinen.de" %}
## Assistant Researcher @ [U. de Guanajauato](http://www.dci.ugto.mx/)
# Under the supervision of **Marco Heinen** PhD <a href="mailto:{{ themail }}" class="icon fa-envelope"></a>



{% assign themail = "sastre@fisica.ugto.mx" %}
# Under the supervision of **Francisco Sastre** PhD <a href="mailto:{{ themail }}" class="icon fa-envelope"></a>



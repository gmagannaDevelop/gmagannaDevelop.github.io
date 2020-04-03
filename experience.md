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
<p style="text-align: justify">
A project emerged within the
<a href="http://www.dci.ugto.mx/diqeb/">
Chemical, Electric, and Biomedical Engineering Department
</a>
of the Science and Engineering Division (DCI)of the 
<a href="https://www.ugto.mx/">
University of Guanajuato
</a>.
The purpose of it was developing a Deep Learning repository 
for Semantic Segmentation of Biomedical Images. Being part of the first group of undergraduate students who worked on this project, my work mainly focused on the following tasks:
</p>

1. Revision of *l'état de l'art*, finding the [MultiResUNet architecture](https://github.com/nibtehaz/MultiResUNet).
2. [Reimplementation](https://github.com/gmagannaDevelop/MyMultiResUNet) of said architecture.
3. Training and testing the repository's models using [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb). 

<p style="text-align: justify">
It is to be noted however, that I rapidly encountered the complications of 
training and testing Deep Learning models. 
For this reason the main focus of my work shifted towards 
developing a logging system that could automatically register 
hardware specs at model instantiation time as well as every function call, notes, etc.
</p>

The system I developed is hosted [here](https://github.com/gmagannaDevelop/segnet/blob/callback_test/segnet/utils/Segmed.py). You can find a pdf manual of it (_in Spanish_) [here](/assets/docs/Segmed_Class_Example.pdf). Both the architectures and logging system were developed using [Python3](https://www.python.org/), and [Keras](https://keras.io/).


{% assign themail = "developeredwin@gmail.com" %}
{% assign theurl = "https://github.com/edwinb-ai" %}
My main collaborator and mentor during this period was **Edwin Bedolla _B.Sc._**<a href="{{ theurl }}" class="icon-b fa-github"></a><a href="mailto:{{ themail }}" class="icon fa-envelope"></a>


## Assistant Researcher @ [U. de Guanajauato](http://www.dci.ugto.mx/)

{% assign themail = "marco@marco-heinen.de" %}
# 2017-2018,  Under the supervision of **Marco Heinen** PhD <a href="mailto:{{ themail }}" class="icon fa-envelope"></a>
<p style="text-align: justify">
After finishing a PostDoc at <a href="https://www.caltech.edu/"> Caltech </a>, 
Marco Heinen became an associate professor at DCI, in the Physical Engineering Departement.
He requested Francisco Sastre to refer him to 
undergraduate students who were interested in 
Statistical mechanics and/or Computer science. 
I was amongst that group of students, we thus started working together.
With Marco my work mostly focused on the following tasks:
</p>

- Development of ideal gas simulations. Aproximating the radial distribution function with 
Monte Carlo methods for dimensions n = [1,3]. 
- Numerical and data structure optimisation research.
- Found [tcmalloc](https://github.com/google/tcmalloc), which allowed us to greatly optimise our code.
- Proposed a binary tree with an _universal end-cap_, to mitigate the memory impact of percolation simulations. 


{% assign themail = "sastre@fisica.ugto.mx" %}
# 2017 Under the supervision of **Francisco Sastre** PhD <a href="mailto:{{ themail }}" class="icon fa-envelope"></a>
After attending his "Programación Básica" lecture, Francisco Sastre kindly invited me to 
contact him once I had gained more experience programming.
Shortly after finishing the mandatory Object-oriented programming lecture,
I asked him if i could become his research assistant. My main duties as such were:

- Designing mappings from rectangular to diverse lattices and their inverses, for his molecular simulations.
- Installing, debuging and keeping up-to-date all of the software packages he used, via [MacPorts](https://www.macports.org/).
- Installing NVIDIA graphics cards on his machines to enable this CUDA-C codes to be compiled and executed.





---
title: DiabManager
author: Gustavo Magaña López, Mathis Delehouzée
icon: fa-notes-medical
layout: post
---

Continuous blood glucose monitoring systems [CGM](https://www.webmd.com/diabetes/guide/continuous-glucose-monitoring) are the state of the art in diabetes mellitus therapy. They enable patients with a superior notion of their glycaemia. Simultaneously they help physicians find underlying trends and adjust the insulin doses accordingly.

Some CGM systems are coupled with insulin pumps to enhance their potential. Medtronic offers a pump-CGM system, the [Minimed 640G](https://www.medtronic-diabetes.co.uk/insulin-pump-therapy/minimed-640g-system) which as stated on their website: "... closely mimics the way a healthy pancreas delivers basal insulin to your body. As part of the MiniMed™ system it can guide you towards better control by providing advanced protection from hypo events."

Hypoglycaemic events can be dangerous for diabetic patients in many ways. It is for this reason that [Mathis Delehouzée](https://github.com/mathisdelehouzee) and I decided to work on a system that could predict glycaemic evolution as part of our _Projet d'ingenierie informatique_, both to learn about _machine learning_ techniques and develop the basis for a system that could eventually be used by patients like me.

Here you can see an image of the actual data vs. the predictions we made using a _support vector machine_ for regression. The full report (_in French_) can be found [here]({{ 'assets/docs/Rapport_Final_DiabManager.pdf' | relative_url }}).

<span class="image right"><img src="{{ 'assets/images/DiabManager/test.png' | relative_url }}" alt="" /></span>


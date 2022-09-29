---
title: GlcJournal
author: Gustavo Magaña López
layout: post
icon: fa-mobile-alt
---

During my exchange I needed a way to effectively collect data for my _Projet d'Ingénierie Informatique_ at the [Faculté Polytechnique](https://web.umons.ac.be/fpms/fr/). For this purpose I decided to develop an App consisting of various scripts and UI files.

Creating it I explored the use of [JSON](https://www.json.org/json-en.html) and subsecuently the [JSON-Lines](http://jsonlines.org/) format. These seemed a good choice for my App's logs as the data is heterogeneous and a CSV file full of null entries would have been sub-optimal to say the least.

This "App" was developed using [Pythonista](https://omz-software.com/pythonista/), an iOS App available on the App Store that enables the iPhone/iPad to run Python scripts. This app has a built-in editor, and additional Python modules can be installed as long as they are written in pure Python. The comes with numpy included which is neat. Installing pandas as it has not been compiled for the iPhone's architecture. Doing this would require Pythonista's developers to re-write the code base (or compiling the pertinent parts of pandas) and signing it to be legally distributed via the App Store.

The GitHub repo of this app is found [here](https://github.com/gmagannaDevelop/GlcJournal). The _Projet d'Ingénierie Informatique_ final report is found [here]({{ 'assets/docs/Rapport_Final_DiabManager.pdf' | relative_url }}).

The app ultimately allowed me to log all of my insulin pump alerts and and meals to train a support vector machine and classify the results of diverse meals. The following screenshots show relevant features of the U.I.

<div class="row">
<div class="4u 12u$(mobile)">
  <div class="item">
    <a href="#" class="image fit"><img src="{{ 'assets/images/GlcJournal/main.jpeg' | relative_url }}" alt="Ipsum Feugiat" /></a>
    <header>
      <h3>Welcome screen, with various subviews and a Sync button</h3>
    </header>
  </div>
  <div class="item">
    <a href="#" class="image fit"><img src="{{ 'assets/images/GlcJournal/review.jpeg' | relative_url }}" alt="Rhoncus Semper" /></a>
    <header>
      <h3>A quick view at the last logs saved locally.</h3>
    </header>
  </div>
</div>
<div class="4u 12u$(mobile)">
  <div class="item">
    <a href="#" class="image fit"><img src="{{ 'assets/images/GlcJournal/data.jpeg' | relative_url }}" alt="Magna Nullam" /></a>
    <header>
      <h3>Saving the info related to a meal.</h3>
    </header>
  </div>
  <div class="item">
    <a href="#" class="image fit"><img src="{{ 'assets/images/GlcJournal/connection.jpeg' | relative_url }}" alt="Natoque Vitae" /></a>
    <header>
      <h3>Connecting to Google Drive to backup the logfile.</h3>
    </header>
  </div>
</div>
<div class="4u$ 12u$(mobile)">
  <div class="item">
    <a href="#" class="image fit"><img src="{{ 'assets/images/GlcJournal/alarm.jpeg' | relative_url }}" alt="Dolor Penatibus" /></a>
    <header>
      <h3>Logging a pump alarm, alert before hyperglycaemia.</h3>
    </header>
  </div>
  <div class="item">
    <a href="#" class="image fit"><img src="{{ 'assets/images/GlcJournal/saved.jpeg' | relative_url }}" alt="Orci Convallis" /></a>
    <header>
      <h3>A dialog box confirming the log</h3>
    </header>
  </div>
</div>
</div>



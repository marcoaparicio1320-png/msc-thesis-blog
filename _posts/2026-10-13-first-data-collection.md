---
layout: post
title: "First data collection at INIAV"
subtitle: "Acquiring multispectral images of apple and pear trees in a real orchard environment"
author: "Marco Pereira"
---


<h2>Visit Preparation</h2>
 
<p>Since this thesis is centred on data acquisition and structuring, it is necessary to begin with that very acquisition. Regarding datasets associated with plant leaf diseases, the vast majority are acquired in controlled environments, isolating the leaves one by one and taking the desired photographs. In our case, we want to acquire data for the datasets in a real environment and, for this, we have the support of INIAV (the National Institute for Agrarian and Veterinary Research), which has orchards with a wide diversity of pome fruit trees subject to various factors: different diseases, different nutrition regimes, and control trees as well. This allows us to acquire data from different types of trees, which gives our dataset additional robustness. The visit took place on 13 October 2026, at the INIAV orchards in Alcobaça.</p>
 
<p>Before the visit, a preliminary review of a few articles on data acquisition and structuring was carried out [1,2]. The data in these articles were acquired on plants different from those targeted in the project, namely citrus, in an orchard, and tomatoes and peppers, in a greenhouse. These articles, together with the datasets found online, allowed us to approach the preparation of the visit more carefully, knowing what might or might not work in data acquisition.</p>
 
<p>An acquisition plan was therefore defined based on the following points:</p>
 
<ul>
  <li>Take photos at 50 cm intervals up to 5 m, to determine the optimal capture distance;</li>
  <li>Take photos with and without the sky as background;</li>
  <li>Take photos from top to bottom, capturing the ground, and from bottom to top, if possible, depending on focus;</li>
  <li>Take photos from different angles, from -15º to +15º relative to a horizontal line.</li>
</ul>
 
<p>These points also took into account the characteristics of the drone, the DJI Mavic 3 Multispectral (Mavic 3M), which has an integrated multispectral camera (consisting of a 20 MP RGB camera and four 5 MP multispectral cameras, in the green, red, red edge and near-infrared bands), with some focusing limitations at certain distances, so this visit also served as a testing phase. With this first outing, we hoped to find out the optimal capture distance and which angles and backgrounds work best. We also wanted to understand whether it is possible to build a reliable dataset under more adverse weather or lighting conditions.</p>
 
<h2>Weather Conditions</h2>
 
<p>It was very sunny all day, which made it difficult to capture some images, mainly in the visible spectrum (RGB). There was also some wind, which made it harder to acquire some images, affecting focus during stronger gusts.</p>
 
<h2>INIAV Orchards</h2>
 
<p>The orchards visited belong to INIAV and are located in Alcobaça. They are divided into sections, where they are subject to different tests or show different diseases. There are also sections with different clones of various apple varieties, such as Gala, Granny Smith, Fuji, among others.</p>

<figure>
  <img src="{{ site.baseurl }}/img/VisitaINIAV/conj1.jpg"
       alt="Four views of the INIAV orchards in Alcobaça"
       style="max-width:100%;">
  <figcaption>Different sections of the INIAV orchards in Alcobaça.</figcaption>
</figure>

<p>The INIAV staff member who hosted us explained quite a few aspects of the orchards and the diseases found there, as well as the main problems associated with those diseases. They also mentioned some projects already carried out in the orchards using drones equipped with multispectral cameras, but in areas other than early disease detection.</p>

<p>This same staff member suggested that we also collect images of the clones. These will be used in this project as a dataset of healthy leaves, but could later help us understand whether different clones have different spectral signatures, making it possible to identify the clone before the tree bears fruit.</p>

<figure style="margin: 2rem 0;">
  <div style="display: flex; gap: 8px;">
    <img src="{{ site.baseurl }}/VisitaINIAV/6.jpg"
         alt="Close-up of an apple tree with red fruit and green leaves"
         style="flex: 1 1 0; min-width: 0; width: 100%; aspect-ratio: 3 / 4; object-fit: cover;">
    <img src="{{ site.baseurl }}//VisitaINIAV/5.jpg"
         alt="Row of apple trees under protective netting, seen from the middle of the aisle"
         style="flex: 1 1 0; min-width: 0; width: 100%; aspect-ratio: 3 / 4; object-fit: cover;">
    <img src="{{ site.baseurl }}//VisitaINIAV/7.jpg"
         alt="Row of apple trees under protective netting with the sun in the frame"
         style="flex: 1 1 0; min-width: 0; width: 100%; aspect-ratio: 3 / 4; object-fit: cover;">
  </div>
  <figcaption style="margin-top: 0.5rem; font-size: 0.9rem; font-style: italic;">Apple trees under protective netting at the INIAV orchards in Alcobaça.</figcaption>
</figure>


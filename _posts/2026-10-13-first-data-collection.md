---
layout: post
title: "First data collection at INIAV"
subtitle: "Acquiring multispectral images of apple and pear trees in a real orchard environment"
author: "Marco Pereira"
background: '/img/Fundo_Home_1.jpg'
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
    <img src="{{ site.baseurl }}/img/VisitaINIAV/6.jpeg"
         alt="Close-up of an apple tree with red fruit and green leaves"
         style="flex: 1 1 0; min-width: 0; width: 100%; aspect-ratio: 3 / 4; object-fit: cover;">
    <img src="{{ site.baseurl }}/img/VisitaINIAV/5.jpeg"
         alt="Row of apple trees under protective netting, seen from the middle of the aisle"
         style="flex: 1 1 0; min-width: 0; width: 100%; aspect-ratio: 3 / 4; object-fit: cover;">
    <img src="{{ site.baseurl }}/img/VisitaINIAV/7.jpeg"
         alt="Row of apple trees under protective netting with the sun in the frame"
         style="flex: 1 1 0; min-width: 0; width: 100%; aspect-ratio: 3 / 4; object-fit: cover;">
  </div>
  <figcaption style="margin-top: 0.5rem; font-size: 0.9rem; font-style: italic;">Apple trees under protective netting at the INIAV orchards in Alcobaça.</figcaption>
</figure>

<h2>Data Acquisition</h2>
 
<p>After taking a closer look at the conditions in the orchard, the acquisition method had to be reassessed, since the space between rows of trees was limited to about 3 m. A first test was therefore carried out to work out the best way to acquire the data.</p>
 
<style>
  .data-table-wrap { overflow-x: auto; margin: 2rem 0; }
  .data-table { border-collapse: collapse; width: 100%; font-size: 0.9rem; }
  .data-table caption { caption-side: top; text-align: left; font-style: italic; padding-bottom: 0.5rem; }
  .data-table th, .data-table td { text-align: left; vertical-align: top; padding: 0.5rem 0.75rem; border-bottom: 1px solid rgba(128, 128, 128, 0.4); }
  .data-table thead th { border-bottom: 2px solid rgba(128, 128, 128, 0.6); }
</style>
 
<div class="data-table-wrap">
  <table class="data-table">
    <caption>Table 1: Initial plan versus actual acquisition.</caption>
    <thead>
      <tr>
        <th></th>
        <th>Initial plan</th>
        <th>Actual acquisition</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <th scope="row">Distance</th>
        <td>50 cm to 5 m</td>
        <td>1 m to 3 m (first test), then about 1.2 m to 2.2 m </td>
      </tr>
      <tr>
        <th scope="row">Angles</th>
        <td>-15º to +15º</td>
        <td>-60º to +60º, in 30º steps</td>
      </tr>
      <tr>
        <th scope="row">Reason for the change</th>
        <td>n/a</td>
        <td>Space between rows limited to about 3 m</td>
      </tr>
    </tbody>
  </table>
</div>
 
<p>The first acquisition started about 1 m from the tree trunk and 1.5 m above the ground, increasing the distance in 50 cm steps up to 3 m. At each position, 5 photos were taken at angles from -60º to 60º in 30º steps. Then, again at 1 m from the trunk, 1 photo was taken 20 cm above the ground at a 30º angle and 1 photo at about 2 m height at a -30º angle. After this acquisition, the images were inspected on site, which showed that 1 m was too close and 3 m was too far. So, to speed up the process, a cane marked at 20 cm intervals was used as a ruler.</p>

<figure style="margin: 2rem 0;">
  <div style="display: flex; gap: 8px;">
    <img src="{{ site.baseurl }}/img/VisitaINIAV/8.jpeg"
         alt="Data acquisition at 1m from the three"
         style="flex: 1 1 0; min-width: 0; width: 100%; aspect-ratio: 3 / 4; object-fit: cover;">
    <img src="{{ site.baseurl }}/img/VisitaINIAV/9.jpeg"
         alt="Data acquisition at 20cm from the ground with 30º angle"
         style="flex: 1 1 0; min-width: 0; width: 100%; aspect-ratio: 3 / 4; object-fit: cover;">
  </div>
  <figcaption style="margin-top: 0.5rem; font-size: 0.9rem; font-style: italic;">First acquisition.</figcaption>
</figure>

<p>This led to the second acquisition phase, which kept the same procedure but started at 1 m and went up to 2 m. This phase was used to collect images of some apple and pear trees affected by <em>Stemphylium vesicarium</em> (brown spot).</p>

<style>
  .leaf-gallery { display: grid; grid-template-columns: minmax(0, 2fr) minmax(0, 1fr) minmax(0, 1fr); gap: 8px; margin: 2rem 0 0.5rem; max-width: 100%; }
  .leaf-gallery .cell { position: relative; overflow: hidden; min-width: 0; }
  .leaf-gallery .cell img { position: absolute; top: 0; left: 0; width: 100%; height: 100%; max-width: none; object-fit: cover; }
  .leaf-gallery .large { grid-row: span 2; }
  .leaf-gallery .small { aspect-ratio: 3 / 4; }
  @media (max-width: 600px) {
    .leaf-gallery { grid-template-columns: minmax(0, 1fr) minmax(0, 1fr); }
    .leaf-gallery .large { grid-column: 1 / -1; grid-row: auto; aspect-ratio: 1 / 1; }
  }
</style>
 
<figure style="margin: 0 0 2rem;">
  <div class="leaf-gallery">
    <div class="cell large">
      <img src="{{ site.baseurl }}/img/VisitaINIAV/13.jpeg"
           alt="Apple leaf with a yellow-green area and many dark, well-defined lesions">
    </div>
    <div class="cell small">
      <img src="{{ site.baseurl }}/img/VisitaINIAV/10.jpeg"
           alt="Close-up of an apple leaf with dark, velvety spots scattered across the surface">
    </div>
    <div class="cell small">
      <img src="{{ site.baseurl }}/img/VisitaINIAV/12.jpeg"
           alt="Underside of an apple leaf with olive-green blotches between the veins">
    </div>
    <div class="cell small">
      <img src="{{ site.baseurl }}/img/VisitaINIAV/14.jpeg"
           alt="Apple leaves seen from below against the sky, with darker patches on the underside">
    </div>
    <div class="cell small">
      <img src="{{ site.baseurl }}/img/VisitaINIAV/11.jpeg"
           alt="Apple leaf with a few small lesions and a bluish powdery residue on the surface">
    </div>
  </div>
  <figcaption style="margin-top: 0.5rem; font-size: 0.9rem; font-style: italic;">Disease symptoms on apple leaves at the INIAV orchards in Alcobaça.</figcaption>
</figure>

<p>Then, repeating this process, images of healthy plants were also acquired, which are needed to train the model. These trees differ from each other in the nutrients they receive.</p>
 
<p>Finally, a third acquisition phase was carried out, taking advantage of the clones of different apple varieties, which are also considered healthy plants. This phase was handled slightly differently: images were acquired of 3 trees of each clone, photographing each tree at 4 height levels and at two distances from the trunk, with no variation in angle. In the images taken at 2 m, because of the spacing between clones, it was possible to capture more than one tree per image.</p>
 
<div class="data-table-wrap">
  <table class="data-table">
    <caption>Table 2: Summary of the acquisition phases.</caption>
    <thead>
      <tr>
        <th>Phase</th>
        <th>Target</th>
        <th>Distance to trunk</th>
        <th>Height</th>
        <th>Angles</th>
        <th>Notes</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <th scope="row">1. Initial test</th>
        <td>Test tree</td>
        <td>1 m to 3 m, every 50 cm</td>
        <td>1.5 m</td>
        <td>-60º to 60º, in 30º steps</td>
        <td>Extra photos at 1 m from the trunk: one at 20 cm above the ground (30º) and another at about 2 m height (-30º). 1 m was too close and 3 m was too far</td>
      </tr>
      <tr>
        <th scope="row">2a. Diseased trees</th>
        <td>Apple and pear trees affected by <em>Stemphylium vesicarium</em> (brown spot)</td>
        <td>1 m to 2 m</td>
        <td>1.5 m</td>
        <td>-60º to 60º, in 30º steps</td>
        <td>Cane used as a ruler, marked every 20 cm</td>
      </tr>
      <tr>
        <th scope="row">2b. Healthy trees</th>
        <td>Healthy trees with different nutrient regimes</td>
        <td>1 m to 2 m</td>
        <td>1.5 m</td>
        <td>-60º to 60º, in 30º steps</td>
        <td>Healthy plant data for model training</td>
      </tr>
      <tr>
        <th scope="row">3. Clones</th>
        <td>3 trees of each clone <strong>(confirm)</strong></td>
        <td>1.5 m and 2 m</td>
        <td>60 cm, 1.5 m, 1.8 m and 2.2 m</td>
        <td>No variation in angle</td>
        <td>At 2 m, more than one tree fits in each image. Used as a healthy dataset and to study spectral signatures</td>
      </tr>
    </tbody>
  </table>
</div>

<p>In total, more than 600 images were collected for each of the spectra. Each image will later be split into several images by tree region, which increases the size of the dataset by at least 10 times.</p>
 
<p>After the acquisition, some of the results were inspected, and they were not satisfactory in RGB: the vast majority of the images were either very blurry or, because of the natural lighting, did not allow the content to be made out. The cause of the blur has not yet been identified. However, when the same images are viewed in other spectra, they show some quality, which will allow us to start working in more depth on this dataset.</p>
 
<p>There is also the limitation that we are at the end of the harvest season: the trees no longer have fruit, and the leaves no longer receive as many nutrients as at other times of the year, since they are getting ready to fall.</p>
 
<p>The INIAV staff member also provided some infected branches, which will be used to find out whether better results can be obtained in a controlled lighting environment. They also invited the team to return, if possible, next year to collect new images when new foliage starts to appear.</p>
 
<h2>Future Work</h2>
 
<p>Having already a good number of images in the dataset, the focus of the next two weeks will be:</p>
 
<ul>
  <li>Defining the folder structure and the file naming convention;</li>
  <li>Reviewing more literature on multispectral imaging and disease detection.</li>
</ul>
 
<p>The folder structure will be based on the articles already mentioned and will be able to accommodate data acquired in the future.</p>
 
<h2>References</h2>
 
<p>[1] R. Edizkan et al., “Longitudinal multispectral image dataset for ToBRFV disease detection in tomato and pepper plants,” <em>Data in Brief</em>, vol. XX, Art. no. 112927, Jun. 2026, doi: 10.1016/j.dib.2026.112927.</p>
 
<p>[2] L. R. Porto, F. Abdelghafour, A. M. G. Tommaselli, and N. N. Imai, “Field-based and close-range multispectral imaging dataset for Huanglongbing (HLB) detection in orange trees: A resource for machine learning and digital agriculture,” <em>Data in Brief</em>, vol. XX, Art. no. 112899, May 2026, doi: 10.1016/j.dib.2026.112899.</p>

---
layout: post
author: Myriam Boualami
title : "The « death of distance » hypothesis"
permalink: /projects/test/
tags: [streaming platform, urban hierarchies, big data analysis]
---

<style>
.tabs {
  display: flex;
  gap: 0.5rem;
  margin-bottom: 1rem;
}

.tab-button {
  cursor: pointer;
  padding: 0.3rem 1rem;       /* espace autour du texte */
  border: 1px solid #ccc;
  border-radius: 6px;         /* coins arrondis */
  background: #f5f5f5;
  user-select: none;
  transition: background 0.2s, transform 0.1s;
}

.tab-button:hover {
  background: #e8e8e8;
  transform: translateY(-1px); /* léger effet visuel au survol */
}

.tab-button.active {
  background: #ddd;
  border-color: #999;
  font-weight: bold;
}

.tab-content {
  display: none;              /* masqué par défaut */
  padding: 1rem 1.5rem;       /* haut/bas = 1rem, gauche/droite = 1.5rem */
  border: 1px solid #ccc;     /* ajoute un cadre autour du contenu */
  border-radius: 8px;         /* coins arrondis du cadre */
  background: #f9f9f9;        /* couleur de fond optionnelle */
  margin-top: 0.5rem;         /* espace au-dessus du contenu pour séparer des onglets */
}

.tab-content.active {
  display: block;             /* affichage de l’onglet actif */
}
</style>


## Geography of innovation

*This research was translated into a roundtable, fostering a dialogue between diverse industry stakeholders and providing a data-driven framework to address sector-wide challenges.*

<div class="tabs">
  <span class="tab-button active" onclick="openTab('tab1', this)">Abstract</span>
  <span class="tab-button" onclick="openTab('tab2', this)">Method</span>
  <span class="tab-button" onclick="openTab('tab3', this)">Data</span>
</div>

<div id="tab1" class="tab-content active">
With the rise of digital platforms, the barriers to publishing music have never been lower, and in principle, the path to success has been democratised: any artist can share their work online, and any listener, anywhere, can discover it. Yet the music industry has long been structured by gatekeeping, where success depended on being in the right place and knowing the right people. Has digitisation truly dissolved these barriers, or do geography and social ties still matter?
</div>

<div id="tab2" class="tab-content">
Sample « rising stars » and analyse as opposed to « super stars ». Build typology of success with curve fitting. Network analysis for proximity index.
</div>

<div id="tab3" class="tab-content">
Full listening histories of 50k randomly selected users from January 2020 to December 2022.
</div>

<script>
function openTab(id, el) {
  document.querySelectorAll('.tab-content').forEach(c => c.classList.remove('active'));
  document.getElementById(id).classList.add('active');

  document.querySelectorAll('.tab-button').forEach(b => b.classList.remove('active'));
  el.classList.add('active');
}
</script>

This project takes the “death of distance” hypothesis and applies it to music, asking whether digitisation has truly dissolved spatial hierarchies. We uncover an intriguing contradiction : a simultaneous process of **centralisation and decentralisation** in music scenes. The Paris region, the French music industry's historic hub, remains more influential than ever. At the same time, rural regions that historically struggled to produce notable acts are now finally generating successful artists, often at levels proportional to their population. This emergence of talent from previously underrepresented areas highlights a **new geographical diversification of success** in the French music scene. The main losers of this dual movement are intermediate scenes, large cities outside Paris that historically competed with the capital and now struggle to achieve the same level of success. 

<p align="center">
<a href="https://raw.githubusercontent.com/m-boualami/m-boualami.github.io/refs/heads/master/images/carto.png" target="_blank">
  <img src="https://raw.githubusercontent.com/m-boualami/m-boualami.github.io/refs/heads/master/images/carto.png" width="300"/>
</a>
</p>
<p align="center">
  <em>click to expand</em>
</p>

<p align="center">
  <em>reader's note : hot-spots and cold-spots of successful rap artists in France</em>
</p>

Moreover, we examined how artists’ embeddedness in their regional scene (i.e, the degree to which their social network is locally concentrated) relates to the longevity of their success. We found that artists in the Paris region tend to exhibit a high degree of localness, whereas most other regions show little to none. The main exception is the Provence-Alpes-Côte d'Azur region, historically France’s second rap hub : artists with highly local networks were more likely to lose their audience, while those whose networks were oriented toward Paris tended to continue growing. This suggests that, even with the geographical decentralization of success, **connections to Paris remain crucial**.

<p align="center">
<a href="https://raw.githubusercontent.com/m-boualami/m-boualami.github.io/refs/heads/master/images/collab_prox.png" target="_blank">
  <img src="https://raw.githubusercontent.com/m-boualami/m-boualami.github.io/refs/heads/master/images/collab_prox.png" width="300"/>
</a>
</p>
<p align="center">
  <em>click to expand</em>
</p>

<p align="center">
  <em>reader's note : relation between localness of social network and type of long-term success (1=local)</em>
</p>

This project is one of the first to empirically investigate, at a very fine-grained level, the “death of distance” hypothesis in France, bringing together two seemingly opposing perspectives that, as the results show, are not actually contradictory.

[Open-access print (to be published in november 2025)](https://cnmlab.fr/publications/){:target="_blank"}

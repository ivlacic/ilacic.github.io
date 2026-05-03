---
permalink: /
title: "Hi, I'm Ivan!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div class="page-spacer"></div>
<div class="intro-text">
<p><span class="emoji">👋🏼</span> I'm a linguist with a background in morphology and morphosemantics.</p>
<p><span class="emoji">🎓</span> I earned my PhD from the University of Bologna in April 2026, with a thesis on empirical approaches to rivalry in Italian intensifying prefixation.</p>
<p><span class="emoji">🔬</span> My research interests lie primarily in derivational (evaluative) morphology, morphosemantics, and quantitative/computational approaches to natural languages.</p>
</div>

## News

<ul class="news-list" id="news-list">
  <li class="news-item">
    <span class="news-date">Apr 2026</span>
    A paper titled <em>Linearization in cumulative intensifying prefixation: An information-theoretic perspective</em>, co-authored with M. Verdelli, has been accepted for an oral presentation at the <a href="https://nytud.hun-ren.hu/en/event/22nd-international-morphology-meeting-2"><em>22nd International Morphology Meeting</em></a>, to be held this June in Budapest.
  </li>
  <li class="news-item">
    <span class="news-date">Apr 2026</span>
    Presented preliminary results of <em>A paradigmatic approach to semantic transparency in derivation: From resource construction to large-scale modeling</em>, co-authored with R. Huyghe, at the workshop <a href="https://www.unicatt.it/en/events/events/milan/2026/Linking-morphology.html"><em>Linking Morphology and Semantics: Meaning in Word Formation Resources</em></a> at the Catholic University of the Sacred Heart (Milan).
  </li>
  <li class="news-item">
    <span class="news-date">Apr 2026</span>
    Successfully defended my PhD dissertation with the highest distinction (<em>eccellente con lode</em>) 🍾.
  </li>
  <li class="news-item">
    <span class="news-date">Dec 2025</span>
    PhD dissertation positively reviewed; defense scheduled for April.
  </li>
  <li class="news-item">
    <span class="news-date">Dec 2025</span>
    Delivered an invited lecture titled <a href="https://www.uzh.ch/de/events/agenda.html?group=70&event=65276"><em>Affix rivalry and ordering in Italian: Quantitative evidence from intensifying prefixation</em></a> at the University of Zurich (host: F. Gardani).
  </li>
  <li class="news-item extra-news" style="display:none;">
    <span class="news-date">Sep 2025</span>
    Presented <a href="https://www.researchgate.net/publication/395260826_InTens_-_A_dataset_of_Italian_intensified_derivatives_Description_and_application_in_a_productivity_study"><em>InTens – a dataset of Italian intensified derivatives: Description and application in a productivity study</em></a> at the Fifth International Workshop on Resources and Tools for Derivational Morphology (DeriMo).
  </li>
  <li class="news-item extra-news" style="display:none;">
    <span class="news-date">Aug 2025</span>
    Presented a poster titled <a href="https://www.researchgate.net/publication/395133094_Affix_rivalry_reconsidered_The_role_of_non-canonical_features_in_statistical_modeling_of_evaluative_morphology"><em>Affix rivalry reconsidered: The role of non-canonical linguistic features in statistical modeling of evaluative morphology</em></a> at the 58th Annual Meeting of the Societas Linguistica Europaea.
  </li>
  <li class="news-item extra-news" style="display:none;">
    <span class="news-date">Jun 2025</span>
    Presented <a href="https://www.upjs.sk/app/uploads/sites/7/2024/11/ABSTRACTS-EVALUATIVE-MORPHOLOGY-WORKSHOP.pdf"><em>Rivalry in Italian intensifying prefixation: An analysis of discriminative features</em></a> at the workshop <em>Latest developments in evaluative morphology</em> (Word-Formation Theories VII & Typology and Universals in Word-Formation VI).
  </li>
  <li class="news-item extra-news" style="display:none;">
    <span class="news-date">Jun 2025</span>
    Presented <a href="https://conference.unizd.hr/mmm14/programme/"><em>Modeling productivity and semantic transparency of rival affixes: The case of Italian intensifying prefixes</em></a> at the 14th Mediterranean Morphology Meeting.
  </li>
  <li class="news-item extra-news" style="display:none;">
    <span class="news-date">May 2025</span>
    Presented <a href="https://corpora.ficlit.unibo.it/CLUB/FILES/CLUBday2025_Programma.pdf"><em>Machine learning al servizio della morfologia: Due analisi di classificazione</em></a> at CLUB (Circolo Linguistico dell'Università di Bologna) Day 2025.
  </li>
  <li class="news-item extra-news" style="display:none;">
    <span class="news-date">Jan 2025</span>
    Presented <a href="https://aclanthology.org/2025.gwc-1.34/"><em>Deriving semantic classes of Italian adjectives via word embeddings: A large-scale investigation</em></a> (with L. Pannitto) at the 13th International Global Wordnet Conference.
  </li>
</ul>

<div class="btn-wrap">
  <button class="more-btn" id="toggle-btn" onclick="toggleNews()">Show More ↓</button>
</div>

<style>
.news-list { list-style: none; padding: 0; }
.news-item {
  font-size: 0.95em;
  margin-bottom: 10px;
  padding-left: 10px;
  border-left: 3px solid #d8e0e8;
  line-height: 1.5;
}
.news-date {
  font-weight: bold;
  color: #007532;
  margin-right: 10px;
}
.btn-wrap { text-align: left; margin-top: 15px; }
.more-btn {
  border: 1px solid #2980b9;
  color: #2980b9;
  padding: 3px 12px;
  border-radius: 12px;
  cursor: pointer;
  font-size: 0.75em;
  background: none;
}
</style>

<script>
function toggleNews() {
  var items = document.querySelectorAll('.extra-news');
  var btn = document.getElementById('toggle-btn');
  var expanded = btn.getAttribute('data-expanded') === 'true';
  items.forEach(function(item) {
    item.style.display = expanded ? 'none' : 'list-item';
  });
  btn.textContent = expanded ? 'Show More ↓' : 'Show Less ↑';
  btn.setAttribute('data-expanded', !expanded);
}
</script>

## Contact

For discussions, collaborations, or general inquiries, don't hesitate to get in touch.
My contact details are available through the links in the sidebar.


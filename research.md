---
title: Research
---

<h1 id="research">Research</h1>

<p class="page-description">I’m writing a dissertation on the concept of conscious experience, arguing that our 'first-personal' understanding of conscious experience is continuous with our 'third-personal' understanding.</p>

<h2>Recent and Upcoming Talks</h2>

{% comment %}{% assign talks = site.data.talks | where_exp: "date", "date !< site.time" %} {% endcomment %}
{% for talk in site.data.cv.talks %}

<div class="talk row">
  {% if talk.date %}
  <div class="talk-date col">{{ talk.date | date: "%b %d" }}</div>
  {% else %}
  <div class="talk-date col">{{ talk.start_date | date: "%b" }}</div>
  {% endif %}
  <div class="col">
    <div class="talk-venue">{{ talk.venue }}</div>
    <p class="talk-title">{{ talk.title }}</p>
  </div>
</div>

{% endfor %}

<h2>Current Work</h2>

<p class="item-title">Strange Experience: <span class="paper-subtitle">Why Experience Without Access Makes No Sense</span></p>

<div class="item-description">
<p>I introduce a challenge to the view that thinking about minds in a first-personal, how-it-feels way is cleanly separable from thinking about minds in a third-personal, how-it-works way. To show this, I discuss the ‘contrapositive’ of widely-discussed zombie cases: phenomenology without function (rather than function without phenomenology.)</p>
<div class="little-links">
	<a href="assets/Kernion - Strange Experience.pdf">Draft</a> ・ <a href="assets/Kernion - Strange Experience - Pacific APA Handout.pdf">Talk Handout</a>
</div>
</div>

<div class="card bg-faded">
<div class="card-block"><p style="margin-bottom:0; font-size:10pt;">Take my super short <a href="https://docs.google.com/forms/d/e/1FAIpQLSfKN9CzRFSTkLHfXIUNBZ7sVlA_J6t5qm7LIkx086wBxs3pHQ/viewform?usp=sf_link">Strange Experience Survey</a> to log your intuitions about my central test case. (Or see <a href="https://docs.google.com/forms/d/e/1FAIpQLSfKN9CzRFSTkLHfXIUNBZ7sVlA_J6t5qm7LIkx086wBxs3pHQ/viewanalytics">the results</a>).</p></div></div>

<p class="item-title">The Mental Measurement Problem: <span class="paper-subtitle">The Frictionless Epistemology of Conceptual Dualism</span></p>
<div class="item-description">
<p>I try to show how a conceptual gap between first-personal data and third-personal data leads to insurmountable methodological difficulties for a science of mind.</p>
<p>(Draft available on request.)</p>

<p class="item-title">The Conceptual Interaction Problem: <span class="paper-subtitle">The Impossible Metaphysics of Conceptual Dualism</span></p>
<div class="item-description">
<p>I try to show how a conceptual gap between the functional and the phenomenal makes any metaphysical link between the two unintelligible. In short, we run into a conceptual interaction problem that mirrors the old, familiar substance interaction problem.</p>
<p>(Draft in progress.)</p>
</div>
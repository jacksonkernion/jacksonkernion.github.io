---
title: Research
---

<h1 id="research">Research</h1>

<p class="page-description">I’m writing a dissertation on the concept of conscious experience, arguing that the ‘first-personal’ and 'first-personal' phenomenal aspects of the mind cannot be <em>conceptually</em> divorced from certain ‘third-personal’, functional aspects of the mind. In jargon form: that a mental state is p-conscious a priori entails that that state is a-conscious.</p>

<h2>Upcoming Talks</h2>

{% comment %}{% assign talks = site.data.talks | where_exp: "date", "date !< site.time" %} {% endcomment %}
{% for talk in site.data.cv.talks %}

<div class="talk row">
  {% if talk.date %}
  <div class="talk-date col">{{ talk.date | date: "%b %d" }}</div>
  {% elseif talk.start_date %}
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
<div class="card-block"><p style="margin-bottom:0; font-size:10pt;">Take my <a href="">Strange Experience Survey</a> to log your intuitions about my central test case (and see the current results).</p></div></div>

<p class="item-title">The Mental Measurement Problem: <span class="paper-subtitle">The Frictionless Epistemology of Conceptual Dualism</span></p>

<div class="item-description">
<p>I try to show how a conceptual gap between first-personal data and third-personal data about the mind leads to insurmountable methodological difficulties for a science of mind.</p>
<p>[DRAFT AVAILABLE ON REQUEST]</p>
</div>
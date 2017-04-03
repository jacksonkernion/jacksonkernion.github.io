---
title: Research
---

<h1 id="research">Research</h1>

<p class="page-description">I’m writing a dissertation on the concept of conscious experience, arguing that the ‘first-personal’ and 'first-personal' phenomenal aspects of the mind cannot be <em>conceptually</em> divorced from certain ‘third-personal’, functional aspects of the mind. In jargon form: that a mental state is p-conscious a priori entails that that state is a-conscious.</p>

<h2>Upcoming Talks</h2>

{% assign talks = site.data.talks | where_exp: "date", "date !< site.time" %}
{% for talk in talks %}

<div class="talk row">
  <div class="talk-date col">{{ talk.date | date: "%b %d" }}</div>
  <div class="col">
    <div class="talk-venue">{{ talk.venue }}</div>
    <p class="talk-title">{{ talk.title }}</p>
  </div>
</div>

{% endfor %}

<h2>Current Work</h2>

<p class="item-title">Strange Experience: Why Experience Without Access Makes No Sense</p>

<div class="item-description">
<p>I introduce a challenge to the view that thinking about minds in a first-personal, how-it-feels way is cleanly separable from thinking about minds in a third-personal, how-it-works way. To show this, I discuss the ‘contrapositive’ of widely-discussed zombie cases: phenomenology without function (rather than function without phenomenology.)</p>
<div class="little-links">
	<a href="assets/Kernion - Strange Experience.pdf">Draft</a> ・ <a href="assets/Kernion - Strange Experience - Pacific APA Handout.pdf">Talk Handout</a>
</div>
</div>

<div class="card bg-faded">
<div class="card-block"><p style="margin-bottom:0; font-size:10pt;">Take my <a href="">Strange Experience Survey</a> to log your intuitions about my central test case (and see the current results).</p></div></div>

<p class="item-title">The Mental Measurement Problem: The Frictionless Epistemology of Conceptual Dualism</p>

<div class="item-description">
<p>I try to show how a conceptual gap between first-personal data and third-personal data about the mind leads to insurmountable methodological difficulties for a science of mind.</p>
<div class="little-links">
	<p>[DRAFT AVAILABLE ON REQUEST]</p>
</div>
</div>
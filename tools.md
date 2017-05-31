---
title: Tools
description: I keep up a coding hobby by building tools for academics.
tools:
  - title: Paper Grader
    image: papergrader.jpg
    description: This is a simple tool that helps streamline the paper-grading process. Students submit their papers at a unique assignment URL, teachers mark up the papers online, and all graded papers can be returned with one click.
    links: <a href="{{a.link}}">Website</a> ・ <a href="http://papergrader.org/demo">Demo</a></p>
---

{% for tool in tools %}

<div class="row mb-3">
  <div class="col-12 col-md-4 push-md-8 text-center">
    <img src="assets/images/{{ tool.image }}" class="rounded img-fluid tools-img mt-md-0 mb-md-0 mt-4 mb-4">
  </div>
  <div class="col-12, col-md-8 pull-md-4">
    <p class="item-title">{{tool.title}}</p>
    <p>{{tool.description}}</p>
    <p class="little-links">tool.links</p>
  </div>
</div>

{% endfor %}

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

<div class="row mb-3">
  <div class="col-12 col-md-4 push-md-8 text-center">
    <img src="assets/images/papergrader.jpg" class="rounded img-fluid tools-img mt-md-0 mb-md-0 mt-4 mb-4">
  </div>
  <div class="col-12, col-md-8 pull-md-4">
    <p class="item-title">Paper Grader</p>
    <p>This is a simple tool that helps streamline the paper-grading process. Students submit their papers at a unique assignment URL, teacherspaper mark up these is done via a clean online interface, and all graded papers can be returned with one click.</p>
    <p class="little-links"><a href="http://papergrader.org">Website</a> ・ <a href="http://papergrader.org/demo">Demo</a></p>
  </div>
</div>

<div class="row mb-3">
  <div class="col-12 col-md-4 push-md-8 text-center">
    <img src="assets/images/gsiassigner.jpg" class="rounded img-fluid tools-img mt-md-0 mb-md-0 mt-4 mb-4">
  </div>
  <div class="col-12, col-md-8 pull-md-4">
    <p class="item-title">GSI Assigner</p>
    <p>As part of an effort by the Berkeley grad students to improve on the way graduate student instructors (GSIs) were assigned to courses, I put together a website that collects teaching preferences and recommends optimal, stable assignments (using an algorithm inspired by work on the stable marriage problem).</p>
    <!-- <p class="little-links"><a href="http://gsiassigner.herokuapp.com">View Website</a></p> -->
  </div>
</div>

<div class="row mb-3">
  <div class="col-12 col-md-4 push-md-8 text-center">
    <img src="assets/images/deductivelogic.jpg" class="rounded img-fluid tools-img mt-md-0 mb-md-0 mt-4 mb-4">
  </div>
  <div class="col-12, col-md-8 pull-md-4">
    <p class="item-title">deductivelogic.org</p>
    <p>I built this for Harvard's introductory deductive logic class. Teachers can create interactive problem sets that automatically check students work.</p>
    <p class="little-links"><a href="http://deductivelogic.org">Website</a> ・ <a href="http://deductivelogic.org/psets/demo">Demo</a></p>
  </div>
</div>

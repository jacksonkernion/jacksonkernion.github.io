
<div class="row about-container">
  <div class="profile col-12 col-sm-4 push-sm-8 text-center">
    <img src="assets/images/profile.jpg" class="rounded img-fluid">
    <div class="contact-links">
      <div class="email">jacksonkernion@gmail.com</div>
      <div class="social-links">
        <a href="https://www.facebook.com/jackson.kernion"><i class="fa fa-facebook" aria-hidden="true"></i></a> 
        <a href="https://twitter.com/JacksonKernion"><i class="fa fa-twitter" aria-hidden="true"></i></a> 
        <a href="https://github.com/jacksonkernion"><i class="fa fa-github" aria-hidden="true"></i></a> 
      </div>
    </div>
  </div>
  <div class="col-12 col-sm-8 pull-sm-4 short-bio">
    <p>I’m a Philosophy PhD student at UC Berkeley, working primarily in philosophy of mind, epistemology, and philosophy of science.</p>
    <p>I graduated from Harvard in 2012 with a philosophy degree in the interdisciplinary Mind, Brain, and Behavior program.</p>
  </div>
</div>

<div class="page-divider"></div>

## Recent + Upcoming Talks

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

<!-- 

Later...
- "Some things I imagine a visitor to the website might want to know about me:"
	- I grew up in Pittsburgh, PA, where I ran cross country and sang in musicals at a giant suburban public high school.
	- I went to Harvard for undergrad, where I graduated in 2012 with a philosophy degree in the interdisciplinary Mind, Brain, and Behavior program.
		- In addition to leading that program's undergrad extracurricular organization (HSMBB) ...
		- "I have a background in software engineering..."
		- Acting/ a capella
		- (Met my future wife)
	- After sophomore year, I traveled through Nepal 
- Hobbies/interests?
- "I graduated from Harvard in 2012 with MBB degree
- "I have a background in software engineering..."

-->
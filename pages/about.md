---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**
<div style="font-size: 20px; line-height: 1.6">

<p>Howdy, That's me <strong>{{ site.author.name }}</strong>. I am <span style="color: black; font-size: 95%;">24</span> years old 👋 


{% if debug == true %}
  <p style="color: red;">#</p>
{% else %}
  <p style="color: green;">#</p>
{% endif %}

<img src="/assets/images/fr.svg" class="flag-icon" alt="France Flag"> 
<img src="/assets/images/us.svg" class="flag-icon" alt="US Flag">
</p>

<p>I am a <span style="font-font-weight: bold; font-weight: 700;"> Franco-American </span>  dual citizen open to work opportunities in both the USA and the European Union.</p>

<p>I recently graduated from <span style="font-font-weight: bold; font-weight: 700;">EPITA School of Engineering and Computer Science </span> with a concentration in Image Processing and Synthesis.</p>

<p>Although my background is technical, I am <span style="color: black; font-size: 95%;">shifting</span> my focus toward opportunities beyond my major—there’s simply so much to explore.</p>

<p>I’ve gained experience through internships: one as a full-stack developer at a startup, and another as a data scientist at a private bank.</p>

<p>I am also known for helping my relatives with tech-related stuff.</p>

<p>I have a particular interest in <span style="font-font-weight: bold; font-weight: 700;">VR</span> and its applications.</p>

<p>My hobbies include running, racket sports, chess, puzzles, games, and Asian culture.</p>

<p>Fun fact: I make good salad dressing.</p>

</div>

<p style="opacity: 0.05; transition: opacity 0.3s;" onmouseover="this.style.opacity='0'" onmouseout="this.textContent = ''">
If I where to be a food, I would be an onion</p>

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<br> Note on skills: 

X > 70% means I have learned it in school.

X > 80% means I have used what I learned in my internships

X > 90% advanced knowledge => frequent usage 

<h3 style="text-align: center; font-size: 2em; font-weight: bold;">Education</h3>

<div class="row">
{% include about/education.html %}
</div>


<h3 style="text-align: center; font-size: 2em; font-weight: bold;">Internships</h3>


<div class="row">
{% include about/pro_experience.html %}
</div>


To know more about my personality and softskills: [click me](/loop2/about)
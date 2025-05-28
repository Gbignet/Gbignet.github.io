---
layout: page
title: About
permalink: /layer3/about
weight: 3
---

# **About Me**



Howdy, That's me **{{ site.author.name }}** :wave:,<br>


{% if debug == true %}
  <p style="color: red;">#</p>

{% else %}
  <p style="color: red;">#</p>
{% endif %}


<img src="/assets/images/fr.svg" class="flag-icon" alt="France Flag"> <img src="/assets/images/us.svg" class="flag-icon" alt="US Flag">
I am a franco-american double nationality job candidate   open to work in the USA and the European Union. 
I recently graduated at  EPITA School of Engineering and Computer Science with a concentration in Image processing and synthesis.
I have experience thanks to an internship as a full-stack developper at a startup and another as a data scientist in a private bank

I have a particular interest in VR and its applications.

My hobbies includes running, Racket Sports, chess, puzzles, games and Asian Culture

Fun fact: I make good salad dressing

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
---
layout: page
title: About
permalink: loop2/about/
weight: 2
---

# **About Me**
<div style="font-size: 20px; line-height: 1.6">



Howdy, That's me <strong>{{ site.author.name }}</strong> :wave:,<br>


{% if debug == true %}
  <p style="color: red;">[DEBUG MODE ENABLED]</p>

{% else %}
  <p style="color: green;">$</p>
{% endif %}



<img src="/assets/images/fr.svg" class="flag-icon" alt="France Flag"> <img src="/assets/images/us.svg" class="flag-icon" alt="US Flag">
<p>I am a <span style="font-font-weight: bold; font-weight: 700;"> Franco-American </span> double nationality open to work opportunities in both the USA and the European Union. </p>

<p>I recently graduated from <span style="font-font-weight: bold; font-weight: 700;">EPITA School of Engineering and Computer Science </span> with a concentration in Image processing and synthesis.</p>

<p>I am open for any tech oriented opportunities</p>

<p>I’ve gained experience through internships, one as a full-stack developer at a startup, and another as a data scientist at a private bank.
I am also known for helping my relatives with tech related stuff</p>

<p>I have a particular interest in <span style="font-font-weight: bold; font-weight: 700;">VR</span> and its applications.</p>

<p>My hobbies includes working out, Badminton, antichess, "sokoban" puzzles and learning about japan.</p>

<p>
Fun fact: I love making <span style="color: black; font-size: 95%;">puzzles</span>

</p>
</div>

<p style="opacity: 0.01; transition: opacity 0.3s;" onmouseover="this.style.opacity='0'" onmouseout="this.textContent = ''">
Each have a different... /layer we descend one more</p>


<div class="row">
{% include about/skills.html title="Main Interest" source=site.data.loop2-interest %}
{% include about/skills.html title="Soft Skills" source=site.data.loop2-soft-skills %}
</div>



[back](/loop2)
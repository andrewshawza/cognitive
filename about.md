---
bg: "owl.jpg"
layout: page
title: "About"
crawlertitle: "Why and how this blog was created"
permalink: /about/
summary: "About this blog"
active: about
---

Geek & online product guy. Living in digital and working in eCom. South African now living in the German countryside. Dad, music lover, sport mad, drummer & vegan.

*The official LinkedIn blab:*

> I am a multi-skilled and qualified product management leader with extensive expertise in product development, digital solutions, cross-function team management, product strategy and analysis.

  <ul>
        {% if site.social-twitter %}
          <li><a href="https://twitter.com/{{ site.social-twitter }}" target="_blank"><i class="fa fa-twitter" aria-hidden="true"></i></a></li>
        {% else %}
          <li><a href="https://twitter.com/artemsheludko_" target="_blank"><i class="fa fa-twitter" aria-hidden="true"></i></a></li>
        {% endif %}
        {% if site.social-facebook %}
          <li><a href="https://facebook.com/{{ site.social-facebook }}" target="_blank"><i class="fa fa-facebook" aria-hidden="true"></i></a></li>
        {% else %}
          <li><a href="https://facebook.com/" target="_blank"><i class="fa fa-facebook" aria-hidden="true"></i></a></li>
        {% endif %}
        {% if site.social-github %}
          <li class="github"><a href="http://github.com/{{site.social-github}}" target="_blank"><i class="fa fa-github"></i></a></li>
        {% else %}
          <li class="github"><a href="http://github.com/" target="_blank"><i class="fa fa-github" aria-hidden="true"></i></a></li>
        {% endif %}
        {% if site.social-linkedin %}
          <li class="linkedin"><a href="https://in.linkedin.com/in/{{site.social-linkedin}}" target="_blank"><i class="fa fa-linkedin"></i></a></li>
        {% else %}
          <li class="linkedin"><a href="https://in.linkedin.com/" target="_blank"><i class="fa fa-linkedin" aria-hidden="true"></i></a></li>
        {% endif %}
        {% if site.social-email %}
          <li class="email"><a href="mailto:{{site.social-email}}"><i class="fa fa-envelope-o"></i></a></li>
        {% else %}
          <li class="email"><a href="mailto:example.david@blog.com"><i class="fa fa-envelope-o" aria-hidden="true"></i></a></li>
        {% endif %}
      </ul>





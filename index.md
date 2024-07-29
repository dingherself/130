---
layout: default
title: Home
group: navigation
order: 1
---

<p style="margin-top: 1.5rem;" align="center"><a href="https://webcomicname.com/post/615550458383286272"><img class="img-fluid" src="https://64.media.tumblr.com/824f4191f085d5ce4d399d0f2d5e0fd7/235a3357fa7d461d-f3/s2048x3072/5ba76fe75121dce8cdb285d68a58b824306a9be7.png" alt="Comic strip; alt text follows the image below."></a></p>

<p style="text-align: right; margin-top: -0.25rem; margin-bottom:1rem; font-size: 0.95rem;"><a data-bs-toggle="collapse" href="#comic" role="button" aria-expanded="false" aria-controls="comic">Alt Text</a> | <a href="https://webcomicname.com/post/615550458383286272" target="_blank" rel="noopener noreferrer">Credit</a></p>
<div class="collapse" id="comic">
  <div class="card card-body">
    <p><em>Comic strip from left to right</em>: Orange person says to pink person: “Love is made of two halves [emoji of a red heart separating into two halves].” / Orange person hands over their half of the red heart to pink person: “Here is my half.” / Pink person reveals that their half of the heart is five times bigger than the orange person’s and so does not fit: “Oh no.”</p>
  </div>
</div>

<h1 style="margin-bottom: 0.875rem;">Welcome to {{ site.course_title | smartify }}!</h1>

{{ site.course_number }}, {{ site.semester | smartify }}\
{{ site.meeting_time }}, {{ site.classroom | smartify }}

{% if site.ta_title %}
<div class="row no-gutters gx-0">
  <div class="col-12 col-md-6">
{% endif %}
    <script language="JavaScript" type="text/javascript">
      var g = "edu";
      var o = "arizona";
      var c = ".";
      var a = "din";
      var t = " ";
      var s = "@";
      document.write("<p><strong>Instructor</strong>: <a href='{{ site.instructor_website }}'>{{ site.instructor | smartify }}</a> (they/she)<br /><strong>Email</strong>:" + t + "<a href='" + "mail" + "to:" + a + s + o + c + g + "'>" + a + s + o + c + g + "</a><br /><strong>Office</strong>: {{ site.office }}<br /><strong>Office hours</strong>: {{ site.office_hours }}<br />" + "</p>");
    </script>
    <noscript><p><strong>Instructor</strong>: <a href='{{ site.instructor_website }}'>{{ site.instructor | smartify }}</a> (they/she)<br /><strong>Email</strong>:[you must enable JavaScript in your web browser to view the email address]<br /><strong>Office</strong>: {{ site.office }}<br /><strong>Office hours</strong>: {{ site.office_hours }}<br /></p></noscript>
{% if site.ta_title %}
  </div>

  <div class="col-12 col-md-6">
    <script language="JavaScript" type="text/javascript">
      var g = "edu";
      var o = "arizona";
      var c = ".";
      var i = "{{ site.ta_netid }}";
      var t = " ";
      var s = "@";
      document.write("<p><strong>{{ site.ta_title}}</strong>: {{ site.ta_name | smartify }}<br /><strong>Email</strong>:" + t + "<a href='" + "mail" + "to:" + i + s + o + c + g + "'>" + i + s + o + c + g + "</a><br /><strong>Office</strong>: {{ site.ta_office }}<br /><strong>Office hours</strong>: {{ site.ta_office_hours }}<br />" + "</p>");
    </script>
    <noscript><p><strong>Grader</strong>: Ryan Hauger (he/him)<br /><strong>Email</strong>:[you must enable JavaScript in your web browser to view the email address]<br /><strong>Office</strong>: TBD<br /><strong>Office hours</strong>: By appointment<br /></p></noscript>
  </div>
</div>
{% endif %}

What is sex? Is it a mere accident that the English term "sex" refers to both an activity and a system of categorization? How does sex relate to gender and love, and how might the experiences of queer and trans people both complicate and illuminate these connections? What counts as having sex in the first place, and what counts as having good sex? How should we think about consent, desire, objectification, and sexualization in connection to sexual autonomy and gender equality? This course surveys these central questions about sex, gender, and love, and in so doing, aims to introduce students to the burgeoning interdisciplinary field of social philosophy.

<p align="center"><strong><a href="{{ site.baseurl }}{% link syllabus.md %}">syllabus</a></strong> &#124; <strong><a href="{{ site.baseurl }}{% link schedule.html %}">schedule</a></strong> &#124; <strong><a href="{{ site.learning_site}}">D2L site</a></strong></p>
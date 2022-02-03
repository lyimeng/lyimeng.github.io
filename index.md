## Yimeng Liu Resume
<div id="content">
  Undergraduate Student,
  Undergraduate Researcher,
  Department of Mathematics,
  Virginia Polytechnic Institute and State University

{% include resume.html content="This is my sample resume under html." %}
{% endinclude %}
## Course History
<ul>
{% for h in site.data.history %}
  <li>
    <a href="https://github.com/{{ h.name }}">
      {{ h.gpa }}
    </a>
  </li>
{% endfor %}
</ul>

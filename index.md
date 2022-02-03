## {{page.title}}
<div id="content">
  Undergraduate Student,
  Undergraduate Researcher,
  Department of Mathematics,
  Virginia Polytechnic Institute and State University

{% include resume.html content="This is my sample resume under html." %}
<h2 class = "section-header">Course History</h2>
<ul>
{% for h in site.data.history %}
  <li>
    <a href="https://github.com/{{ h.name }}">
      {{ h.gpa }}
    </a>
  </li>
{% endfor %}
</ul>

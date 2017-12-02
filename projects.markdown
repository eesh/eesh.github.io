---
title: Projects
---

# Projects

##### My skills are mostly focused in Android development but I've done quite a bit of web development as well.


<div class="container-fluid">

  <br />

  {% assign newrow = 'true' %}

  {% for project in site.categories.projects %}

  {% if newrow == 'true' %}
    <div class="row">
      <div class="col-md-6">
        <div class="panel">
          <div class="row">
            <div class="col-md-3 vcenter">
              <img src="images/{{ project.logo }}" style="margin: 15px" class="img-responsive">
            </div>
            <div class="col-md-9">
              <h4>{{ project.title }}</h4>
              <a href="{{ project.url }}" class="btn btn-primary">View</a>&nbsp;<a href="{{ project.github }}" class="btn btn-success">Github</a>
              <br />
              <br />
              <p>{{ project.short_desc }}</p>
            </div>
          </div>
        </div>
      </div>
      {% assign newrow = 'false' %}
  {% else %}
      <div class="col-md-6">
        <div class="panel">
          <div class="row">
            <div class="col-md-3">
              <img src="images/{{ project.logo }}" style="margin: 15px" class="project-thumbnail">
            </div>
            <div class="col-md-9">
              <h4>{{ project.title }}</h4>
              <a href="{{ project.url }}" class="btn btn-primary">View</a>&nbsp;<a href="{{ project.github }}" class="btn btn-success">Github</a>
              <br />
              <br />
              <p>{{ project.short_desc }}</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    {% assign newrow = 'true' %}
  {% endif %}
  {% endfor %}

</div>

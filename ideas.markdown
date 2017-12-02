---
title: My ideas
---

# Ideas and Shower thoughts

##### Mostly shower thoughts because I usually get my ideas while I take a shower. So without further ado here are my ideas!

<br />

<div class="container-fluid">
{% for post in site.categories.ideas %}

  <div class="row">
    <div class="col-md-9">
      <div class="panel panel-default">
        <div class="panel-heading">
          <h3 class="panel-title"><a href="{{ post.url }}">{{ post.title }}</a></h3>
        </div>
        <div class="panel-body">
          {{ post.short_text | markdownify }}
        </div>
      </div>
    </div>
  </div>
    <br />
{% endfor %}
</div>

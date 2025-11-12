### Ship Designs

{% for page in site.pages %}
  {% if page.categories contains 'shipdesign' %}
* [{{page.title}}]({{page.url}})
  {% endif %}
{% endfor %}

### Ship Systems---Basic Rules

{% for page in site.pages %}
  {% if page.categories contains 'ship system'
     and page.categories contains 'basic rules' %}
* [{{page.title}}]({{page.url}})
  {% endif %}
{% endfor %}

### Ship Systems---Advanced Rules

{% for page in site.pages %}
  {% if page.categories contains 'ship system'
     and page.categories contains 'advanced rules' %}
* [{{page.title}}]({{page.url}})
  {% endif %}
{% endfor %}

### Ship Systems---More Rules

{% for page in site.pages %}
  {% if page.categories contains 'ship system'
     and page.categories contains 'more rules' %}
* [{{page.title}}]({{page.url}})
  {% endif %}
{% endfor %}

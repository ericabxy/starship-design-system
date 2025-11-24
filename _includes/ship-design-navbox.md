<table role='navigation'>
  <tr>
    <th colspan='2'>Ship Design Navigation Table</th>
  </tr>
  <tr>
    <th>Basic Design</th>
    <td>
      {% for doc in site.ship_systems %}
        {% if doc.categories contains "basic design" %}
          <a href="{{ site.url }}{{ site.baseurl }}{{ doc.url }}">{{ doc.title }}</a>
          {% unless forloop.last %}&bull;{% endunless %}
        {% endif %}
      {% endfor %}
    </td>
  </tr>
  <tr>
    <th>Advanced Design</th>
    <td>
      {% for doc in site.ship_systems %}
        {% if doc.categories contains "advanced design" %}
          <a href="{{ site.url }}{{ site.baseurl }}{{ doc.url }}">{{ doc.title }}</a>
          {% unless forloop.last %}&bull;{% endunless %}
        {% endif %}
      {% endfor %}
    </td>
  </tr>
  <tr>
    <th>Experimental Design</th>
    <td>
      {% for doc in site.ship_systems %}
        {% if doc.categories contains "experimental design" %}
          <a href="{{ site.url }}{{ site.baseurl }}{{ doc.url }}">{{ doc.title }}</a>
          {% unless forloop.last %}&bull;{% endunless %}
        {% endif %}
      {% endfor %}
    </td>
  </tr>
</table>

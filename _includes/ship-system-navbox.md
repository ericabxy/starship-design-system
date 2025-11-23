<table>
  <tr>
    <th colspan='2'>Ship Systems</th>
  </tr>
  <tr>
    <th>Core Rules</th>
    <td>
      {% for doc in site.ship_systems %}
        {% if doc.categories contains "core rules" %}
          <a href="{{ site.url }}{{ site.baseurl }}{{ doc.url }}">{{ doc.title }}</a>
          {% unless forloop.last %}&bull;{% endunless %}
        {% endif %}
      {% endfor %}
    </td>
  </tr>
  <tr>
    <th>Advanced Rules</th>
    <td>
      {% for doc in site.ship_systems %}
        {% if doc.categories contains "advanced rules" %}
          <a href="{{ site.url }}{{ site.baseurl }}{{ doc.url }}">{{ doc.title }}</a>
          {% unless forloop.last %}&bull;{% endunless %}
        {% endif %}
      {% endfor %}
    </td>
  </tr>
  <tr>
    <th>Experimental Rules</th>
    <td>
      {% for doc in site.ship_systems %}
        {% if doc.categories contains "experimental rules" %}
          <a href="{{ site.url }}{{ site.baseurl }}{{ doc.url }}">{{ doc.title }}</a>
          {% unless forloop.last %}&bull;{% endunless %}
        {% endif %}
      {% endfor %}
    </td>
  </tr>
</table>

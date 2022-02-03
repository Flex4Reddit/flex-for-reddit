{% assign items = {{include.data}} %}
{% for item in items -%}
{% assign src = item.path | prepend: "/assets/images/" | relative_url %}
[![{{item.alt}}]({{src}}){:.gallery-{{items.size}}}]({{src}})
{%- endfor %}
{:.text-center}

---
title: inventory
---
# inventory
This is my inventory system. Here all items are documented and Linked to their projects. This is mostly for management purposes.

In the future it shall be possible to borrow items.

![inventory management](inventory-management.md)

<ul>
{% for page in site.html_pages %}
    <li><a href="{{ page.url }}">{{ page.title }}</a></li>
{% endfor %}
</ul>

---
layout: page
title: events
permalink: /events/
---

<p>Here is a list of our upcoming events. :-)</p>
<p>Todos nuestros eventos están abiertos al público en general. No requiere ningún conocimiento técnico, se recomienda que cualquier persona con un interés en Python para participar.</p>
    
{% if site.events %}
<ul>
{% for event in site.events reversed %}
    <li>
        <p><a href="{{ event.url }}">{{ event.title }}</a></p>
    </li>
{% endfor %}
</ul>
{% endif %}


<div id="events" class="row">
    <div class="col-lg-4 col-md-4">
        <div class="embed-responsive embed-responsive-4by3">
            <iframe class="embed-responsive-item" src="https://calendar.google.com/calendar/embed?showTitle=0&amp;showPrint=0&amp;showCalendars=0&amp;height=350&amp;wkst=1&amp;bgcolor=%23FFFFFF&amp;src=vtnpeo5tlcuv0l4jdgq4bpfbn8%40group.calendar.google.com&amp;color=%23B1365F&amp;ctz=America%2FSao_Paulo" style="border-width:0" frameborder="0" scrolling="no"></iframe>
        </div>
        <h4 id="events">Eventos</h4>
        <p class="text-justify">Todos nuestros eventos están abiertos al público en general. No requiere ningún conocimiento técnico, se recomienda que cualquier persona con un interés en Python para participar.</p>
        <p class="text-justify">Para obtener información sobre las próximas reuniones de PyLadies Mendoza, seguirnos en nuestras redes sociales podrá agregar a nuestro calendario de Google en su calendario.</p>
    </div>
</div>

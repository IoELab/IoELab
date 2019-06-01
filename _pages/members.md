---
layout: page
title: members/成员
permalink: /members/
description:
---

{% for member in site.members %}

{% if member.redirect %}
<div class="member ">
    <div class="thumbnail">
        <a href="{{ member.redirect }}" target="_blank">
        {% if member.img %}
        <img class="thumbnail" src="{{ member.img | prepend: site.baseurl | prepend: site.url }}"/>
        {% else %}
        <div class="thumbnail blankbox"></div>
        {% endif %}    
        <span>
            <h1>{{ member.title }}</h1>
            <br/>
            <p>{{ member.description }}</p>
        </span>
        </a>
    </div>
</div>
{% else %}

<div class="member ">
    <div class="thumbnail">
        <a href="{{ member.url | prepend: site.baseurl | prepend: site.url }}">
        {% if member.img %}
        <img class="thumbnail" src="{{ member.img | prepend: site.baseurl | prepend: site.url }}" />
        {% else %}
        <div class="thumbnail blankbox"></div>
        {% endif %}    
        <span>
            <h1>{{ member.title }}</h1>
            <br/>
            <p>{{ member.description }}</p>
        </span>
        </a>
    </div>
</div>

{% endif %}

{% endfor %}

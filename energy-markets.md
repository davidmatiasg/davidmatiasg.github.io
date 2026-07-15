---
layout: default
title: Energy markets
permalink: /energy-markets/
---

# Energy markets

<figure style="margin: 0 0 1.5rem 0;">
  <img src="/assets/img/nga_keelmen_heaving_in_coals_by_moonlight_1942.9.86.jpg"
       alt="Keelmen Heaving in Coals by Moonlight, J.M.W. Turner, 1835" style="width:100%; border-radius:4px;">
  <figcaption class="muted" style="font-size:0.8rem; margin-top:0.4rem;">
    J.M.W. Turner, <em>Keelmen Heaving in Coals by Moonlight</em>, 1835. National Gallery of Art, Washington (open access).
  </figcaption>
</figure>

My opinions are my own.

---

## Posts

<ul class="post-list">
  {% assign posts = site.energy_posts | sort: "date" | reverse %}
  {% for post in posts %}
    <li class="post-item">
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span class="muted"> — {{ post.date | date: "%Y-%m-%d" }}</span>
      {% if post.excerpt %}
        <div class="muted" style="margin-top:6px;">{{ post.excerpt | strip_html | truncate: 160 }}</div>
      {% endif %}
    </li>
  {% endfor %}
</ul>

---

## Blog

Longer-form commentary is moving to a Substack — link coming soon.

---

## Blog writing (Spanish)

At the Inter-American Development Bank (IDB), I regularly collaborate with colleagues to write short, policy-oriented pieces on energy issues in Latin America and the Caribbean. Below is a curated list of my posts (in Spanish).

### Electricity losses & sector sustainability
- [¿Qué hacer para reducir y controlar las pérdidas eléctricas en América Latina y el Caribe?](https://www.iadb.org/es/blog/energia/que-hacer-para-reducir-y-controlar-las-perdidas-electricas-en-america-latina-y-el-caribe)
- [Pérdidas eléctricas en América Latina y el Caribe: un problema crónico para la sostenibilidad del sector](https://www.iadb.org/es/blog/energia/perdidas-electricas-en-america-latina-y-el-caribe-un-problema-cronico-para-la-sostenibilidad-del)

### Energy transition
- [Transformar el futuro: Acelerando la transición energética en América Latina y el Caribe](https://www.iadb.org/es/blog/energia/transformar-el-futuro-acelerando-la-transicion-energetica-en-america-latina-y-el-caribe)
- [Tres costos asociados con la transición energética y qué podemos hacer para mitigarlos](https://blogs.iadb.org/energia/es/tres-costos-asociados-con-la-transicion-energetica-y-que-podemos-hacer-para-mitigarlos/)

### Emissions, growth, and inflation dynamics
- [Emisiones CO₂ en América Latina y el Caribe: perspectivas regionales](https://www.iadb.org/es/blog/energia/emisiones-co2-en-america-latina-y-el-caribe-perspectivas-regionales)
- [¿Cómo se relacionan las emisiones CO₂ y el crecimiento económico en América Latina y el Caribe?](https://www.iadb.org/es/blog/energia/como-se-relacionan-las-emisiones-co2-y-el-crecimiento-economico-en-america-latina-y-el-caribe)

### Demand and post-COVID recovery
- [¿Cómo se comporta la demanda de electricidad de los países de la región durante la recuperación económica pos-covid-19?](https://www.iadb.org/es/blog/energia/como-se-comporta-la-demanda-de-electricidad-de-los-paises-de-la-region-durante-la-recuperacion)

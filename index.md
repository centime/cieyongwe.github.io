---
layout: home
---


## Une compagnie

Yongwé est une compagnie de spectacles vivants basée à Kourou, avec un pied en Guyane et l'autre en Normandie. Découvrez ici notre première création, Dilo, un spectacle de poésie musicale joué sur l'eau. Tenez-vous au courant et réservez pour les prochaines dates, découvrez nos prochains projets et les créations en cours !



<span id="creations" style="margin:30px"></span>

## Nos créations

C'est les trucs finis blablablabla ou pas ceci cela

<div class="projets columns is-centered is-multiline is-mobile">
  {% for project in site.data.tournee %}
    <div class="column has-text-centered is-paddingless is-marginless is-one-third-widescreen is-one-third-desktop is-one-fifth-fullhd is-one-third-tablet is-two-fifths-mobile is-three-quarters-touch"
      id="project-card">
      <a href="{{project.link}}">
      <div class="has-background-black card">
        <figure class="image is-3by1" style="background-image: url('{{project.image}}');">
        </figure>
        <div class="card-content">
          <h1 class="title has-text-white is-size-4">{{ project.name }}</h1>
          <p class="has-text-white has-text-weight-light content">{{ project.description | truncate: 80}}</p>
        </div>
      </div>
      </a>
    </div>
  {% endfor %}
</div>

<span id="action-culturelle" style="margin:30px"></span>

## Notre action culturelle

C'est les trucs finis blablablabla ou pas ceci cela

<div class="projets columns is-centered is-multiline is-mobile">
  {% for project in site.data.projects %}
    <div class="column has-text-centered is-paddingless is-marginless is-one-third-widescreen is-one-third-desktop is-one-fifth-fullhd is-one-third-tablet is-two-fifths-mobile is-three-quarters-touch"
      id="project-card">
      <a href="{{project.link}}">
      <div class="has-background-black card">
        <figure class="image is-3by1" style="background-image: url('{{project.image}}');">
        </figure>
        <div class="card-content">
          <h1 class="title has-text-white is-size-4">{{ project.name }}</h1>
          <p class="has-text-white has-text-weight-light content">{{ project.description | truncate: 80}}</p>
        </div>
      </div>
      </a>
    </div>
  {% endfor %}
</div>

## La compagnie





<div class="projets columns is-centered is-multiline is-mobile">
  {% for project in site.data.en-tournee %}
    <div class="column has-text-centered is-paddingless is-marginless is-one-third-widescreen is-one-third-desktop is-one-fifth-fullhd is-one-third-tablet is-two-fifths-mobile is-three-quarters-touch"
      id="project-card">
      <a href="{{project.link}}">
      <div class="has-background-black card">
        <figure class="image is-3by1" style="background-image: url('{{project.image}}');">
        </figure>
        <div class="card-content">
          <h1 class="title has-text-white is-size-4">{{ project.name }}</h1>
          <p class="has-text-white has-text-weight-light content">{{ project.description | truncate: 80}}</p>
        </div>
      </div>
      </a>
    </div>
  {% endfor %}
</div>
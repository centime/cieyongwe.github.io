---
layout: home
---


## Une compagnie

Yongwé est une compagnie de spectacles vivants basée à Kourou, avec un pied en Guyane et l’autre en Normandie. Découvrez ici les spectacles en tournée et en création, réservez pour les prochaines dates, découvrez nos projets en territoire.


<span id="creations" style="margin:30px"></span>

## Nos créations

A la croisée du théâtre, de la musique et de la poésie, les créations de la compagnie se nourrissent d’une lecture sensible de nos environnements et de questionnements autour des notions de culture et de territoire.

<div class="projets columns is-centered is-multiline is-mobile">
  {% for project in site.data.creations %}
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

Dans les créations en territoire, nous rencontrons des publics lors d’ateliers d’écriture et de création sonore et musicale. Nous récoltons une parole, un ressenti, un regard sur le monde qui nous entoure. De ces rencontres émergent des créations participatives mouvantes.

<div class="projets columns is-centered is-multiline is-mobile">
  {% for project in site.data.action-culturelle %}
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
  {% for project in site.data.la-compagnie %}
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
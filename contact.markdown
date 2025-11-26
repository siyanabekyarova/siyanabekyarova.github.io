---
layout: page
title: Свържете се с нас
permalink: /contact/
---

<link rel="stylesheet" href="/assets/tailwind.css">
<link rel="stylesheet" href="/assets/custom.css">

<section class="page-hero">
  <p class="eyebrow">Да говорим за вашия проект</p>
  <h1>Свържете се с нас</h1>
  <p class="lead">Ще отговорим в рамките на работния ден с оферта и ориентировъчен срок.</p>
</section>

<section class="section contact-section">
  <div class="contact-grid">
    <div class="card contact-card transition-transform duration-200 hover:-translate-y-1 hover:shadow-2xl">
      <h2>Контакти</h2>
      <p><strong>Адрес:</strong> {{ site.address }}</p>
      <p><strong>Телефон:</strong> <a href="tel:{{ site.phone | replace: ' ', '' }}">{{ site.phone }}</a></p>
      <p><strong>Email:</strong> <a href="mailto:{{ site.email }}">{{ site.email }}</a></p>
      {% if site.facebook_url %}
      <p><strong>Facebook:</strong> <a href="{{ site.facebook_url }}" target="_blank" rel="noopener">Prime Print</a></p>
      {% endif %}
      <p class="muted">Работно време: пон–пет, 09:00 – 18:00</p>
      <div class="contact-actions">
        <a class="btn btn-primary" href="tel:0887425816">Позвънете</a>
        <a class="btn btn-ghost" href="mailto:primeprint@abv.bg">Изпратете имейл</a>
      </div>
    </div>
    <div class="card map-card overflow-hidden transition-transform duration-200 hover:-translate-y-1 hover:shadow-2xl">
      <h2>Намерете ни</h2>
      <div class="map-embed">
        <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d528.853578125269!2d23.350981834279807!3d42.66868693927371!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!5e1!3m2!1sen!2sbg!4v1695807829213!5m2!1sen!2sbg" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
      </div>
    </div>
  </div>
</section>

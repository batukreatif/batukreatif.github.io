---
language: id
layout: product
title: Split Face
description: Description in &amp; Split Face
keyword: keyword in Split Face
image: /images/SPLIT-FACE-12-Rosso.jpg
---
<div class="site-intro">
    <h1>
        Split Face
    </h1>
    <p>
        Our wide classic collection of textured Natural Veneer for wall applications will give your home a luxurious look with a classic touch. With our Mix and Match option you can create your unique pattern. We gauge, mesh and panel mount all our classic products to make installation easier. The colors of the illustrations may vary with respect to the original pieces.
    </p>
</div>
<div class="action-hint quick">Scroll or drag to Right explore.</div>
<div class="action-hint-for-touch">Swipe right to explore.</div>
<!-- Swiper -->
<div class="swiper-container" id="main">
    <div class="swiper-wrapper">
    	{% for item in site.data-2-classic-style-split-face %}
        <div class="swiper-slide type-1">
			<div class="whole item" id="work-11" style="background-image: url({{ item.image }});">
			    <div class="work-caption">
			        <h3>{{ item.title }}</h3>
			        <p class="work-client">{{ item.sub-title }}</p>
			    </div>
			    <a href="{{ item.url }}">view more</a>
			</div>
		</div>
        {% endfor %}
</div>
<div id="call-to-action">
    <h2>Any other ideas?</h2>
    <p>There are questions and other creative ideas to beautify your home, contact us immediately.</p>
</div>
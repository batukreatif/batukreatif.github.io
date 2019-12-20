---
language: id
layout: product
title: Polished Honed
description: Description in &amp; Polished Honed
keyword: keyword in Polished Honed
image: /images/polished-honed.jpg
---
<div class="site-intro">
    <h1>
        Polished & Honed
    </h1>
    <p>Sizes available 12″x24″ and 24″x24″x 1/2″ call for stock availability and color Our wide modern collection of Cut to Size textured Natural Tiles
for walls and floors will leave your home looking classy and welcoming, with their dramatic style and gleaming shine creating a tailored finish up to 48”x48”. Colors are not limited to what is previewed in this section. Pick any of our colors and specify
the size needed.</p>
</div>
<div class="action-hint quick">Scroll or drag to Right explore.</div>
<div class="action-hint-for-touch">Swipe right to explore.</div>
<!-- Swiper -->
<div class="swiper-container" id="main">
    <div class="swiper-wrapper">
    	{% for item in site.data-1-modern-style-polished-honed %}
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
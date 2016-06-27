---
layout: default
name: Improbable
title: Presenting Improbable
image: improbable.png
level: silver
description: Improbable grants you the tools to build a world where everything matters. Where lasting scars tell stories of epic battles. Where a seed planted yesterday grows into today's tree, tomorrow's forest. Where killing that monster really does save the town. Where people are more than players, experiences are more than games.
website: https://improbable.io
twitter: Improbableio
github: improbable-io
hackapi: true
---
<div class="content">
	<div class="container">
		<div class="row">
			<div class="col-md-12">
        <div class="row" >
          <div class="col-sm-4" >
            <img src="/assets/img/{{ page.image }}" width="100%" />
            {% if page.tagline %}<p><em>{{ page.tagline }}</em></p>{% endif %}
            {% if page.website %}<p class="text-left"><a href='{{ page.website }}'><i class="fa fa-globe"></i> {{ page.website }}</a></p>{% endif %}
            {% if page.twitter %}<p class="text-left"><a href='https://twitter.com/{{ page.twitter }}'><i class="fa fa-twitter"></i> @{{ page.twitter }}</a></p>{% endif %}
            {% if page.github %}<p class="text-left"><a href='https://github.com/{{ page.github }}'><i class="fa fa-github"></i> {{ page.github }}</a></p>{% endif %}
          </div>
          <div class="col-sm-8">
            <h1>Presenting {{ page.name }}</h1>
            <h2>About Improbable:</h2>
            <p>Improbable grants you the tools to build a world where everything matters. Where lasting scars tell stories of epic battles. Where a seed planted yesterday grows into today's tree, tomorrow's forest. Where killing that monster really does save the town. Where people are more than players, experiences are more than games.</p>

            <p>SpatialOS is a developer platform to build seamless worlds of unprecedented scale, inhabited by entities with complex, adaptive behaviors. SpatialOS helps you make every action count, with physics-driven interactions and full persistence, whilst handling dynamic scaling and fault tolerance so you never see a server, and your players never see a loading screen.</p>

            <h2>Why are we sponsoring:</h2>
            <p>Improbable believes that game developers can change the world with their experiences, and there's no better place to create the crazy games no one would have thought of than at a hackathon. We support Hackference to help give you a space to see your worlds come to life. Drop by and have a chat with our developer advocate, Joe Nash, or tweet him at <a href="https://twitter.com/jna_sh" >@jna_sh</a>.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

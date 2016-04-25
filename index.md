---
layout: home 
permalink: /
image:
  feature: industrie2.png
  
---
<div class="grid">
  <div class="col-2-4">
     <div class="home_tile">
		  <h2 class="post-title">12 Partner</h2>
		  <p class="post-excerpt">Projektpartner aus verschiedenen Industriezweigen, aus der IT sowie aus der Wissenschaft stellen sich der gemeinsamen Aufgabe, konkrete Industrie 4.0 Lösungen umzusetzen.</p>
	</div>
     <div class="home_tile">
		  <h2 class="post-title">4 Anwendungsbereiche</h2>
		  <p class="post-excerpt">In den Anwendungsbereichen <i>Automatisierte Montageanlagen, Abfüllanlagen, Manuelle Montage sowie CNC-Bearbeitungszentren</i> setzt <strong>CyProAssist</strong> innovative Assistenzlösungen um.</p>
	</div>
  </div>
  
  <div class="col-2-4">
	<div class="home_tile">
		  <h2 class="post-title">Modulares Assistenzsystem</h2>
		  <p class="post-excerpt">Mit <strong>FriendlyImprover</strong> entwickeln die Projektpartner ein gemeinsames modulares Assistenzsystem für die Produktion.</p>
	</div>
	<div class="home_tile">
		  <h2 class="post-title">Übertragbarkeit</h2>
		  <p class="post-excerpt">Der in <strong>CyProAssist</strong> entwickelte Lösungsbaukasten soll explizit auch auf neue Anwendungsbereiche übertragbar sein.</p>
	</div>
	</div>

</div>

<h5>NEUESTE BEITRÄGE </h5>

<div class="tiles" style="">
{% for post in site.categories.articles %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
---
---

## Sponsors

The AppSec Israel Conference and Workshops can only take place thanks to the generous support of our sponsors!   


### Interested in becoming a sponsor for {{ site.title }}? 

Whether you have a product to showcase, you're offering a service, or you are recruiting - sponsoring the OWASP AppSec Israel Conference gets you the right exposure.   
This year we are expecting well over 1,000+ attendees! Our audience includes security professionals, developers, managers, and more.

Sponsorship also helps support the OWASP community, and ensures that we can keep on making our conferences better and better. Sponsorship fees are intended to cover the costs of the conference only. If anything is left over, this is used to support the ongoing Chapter activity and improve the Conference even more. Since the Conference is open to all and not funded by ticket sales, we need your support to enable us to put on a great conference.

We are now offering several tiers of premium sponsorship, and various a la carte opportunities.   

There is also a cost-effective “Community Supporter” option for non-profits, government offices, small startups, and anyone else that wishes to support the community (Community Supporter level does not get a booth at the conference).  

Details on the available sponsorship options are in our **[Sponsorship Prospectus]({{ site.url }}/assets/AppSecIL2023Sponsorships.pdf)**.  

For more details and to confirm your sponsorship, please contact [Ori Troyna](mailto:ori.troyna@owasp.org) or [Avi D](mailto:avi.douglen@owasp.org).   

{% if site.data.sponsors.diamond %}
### Diamond Sponsor 
<div class="sponsor-tier">
  {% for sponsor in site.data.sponsors.diamond %}
	<span class="sponsor diamond-sponsor">
	  <a href="{{ sponsor.url }}" title="{{ sponsor.name }}" target="_blank">
		{% if sponsor.image == blank %}
		  <p>{{ sponsor.name }}</p>
		{% else %} 
		  <img src="assets/img/Sponsors/{{ sponsor.image }}"> 
		{% endif %}
	  </a>
	</span>
{% endfor %}
</div>
{% endif %}

{% if site.data.sponsors.platinum %}
### Platinum Sponsor 
<div class="sponsor-tier">
  {% for sponsor in site.data.sponsors.platinum %}
	<span class="sponsor platinum-sponsor">
	  <a href="{{ sponsor.url }}" title="{{ sponsor.name }}" target="_blank">
		{% if sponsor.image == blank %}
		  <p>{{ sponsor.name }}</p>
		{% else %} 
		  <img src="assets/img/Sponsors/{{ sponsor.image }}"> 
		{% endif %}
	  </a>
	</span>
{% endfor %}
</div>
{% endif %}

{% if site.data.sponsors.gold %}
#### Gold Sponsors 
<div class="sponsor-tier">
  {% for sponsor in site.data.sponsors.gold %}
	  <span class="sponsor gold-sponsor">
		<a href="{{ sponsor.url }}" title="{{ sponsor.name }}" target="_blank">
		  {% if sponsor.image == %}
			<span>{{ sponsor.name }}</span>
		  {% else %} 
			<img src="assets/img/Sponsors/{{ sponsor.image }}">
		  {% endif %}
		</a>
	  </span>
  {% endfor %}
</div>
{% endif %}

{% if site.data.sponsors.silver %}
##### Silver Sponsors
<div class="sponsor-tier">
  {% for sponsor in site.data.sponsors.silver %}
	<span class="sponsor silver-sponsor">
	  <a href="{{ sponsor.url }}" title="{{ sponsor.name }}" target="_blank">
		{% if sponsor.image == %}
		  <span>{{ sponsor.name }}</span>
		{% else %} 
		  <img src="assets/img/Sponsors/{{ sponsor.image }}"> 
		{% endif %}
	  </a>
	</span>
{% endfor %}
</div>
{% endif %}

{% if site.data.sponsors.bronze %}
###### Bronze Sponsors
<div class="sponsor-tier">
  {% for sponsor in site.data.sponsors.bronze %}
	<span class="sponsor bronze-sponsor">
	  <a href="{{ sponsor.url }}" title="{{ sponsor.name }}" target="_blank">
		{% if sponsor.image == %}
		  <span>{{ sponsor.name }}</span>
		{% else %} 
		  <img src="assets/img/Sponsors/{{ sponsor.image }}"> 
		{% endif %}
	  </a>
	</span>
{% endfor %}
</div>
{% endif %}

{% if site.data.sponsors.community %}
####### Community Supporters
<div class="sponsor-tier">
  {% for sponsor in site.data.sponsors.community %}
	<span class="sponsor community-sponsor">
	  <a href="{{ sponsor.url }}" title="{{ sponsor.name }}" target="_blank">
		{% if sponsor.image == %}
		  <span>{{ sponsor.name }}</span>
		{% else %} 
		  <img src="assets/img/Sponsors/{{ sponsor.image }}"> 
		{% endif %}
	  </a>
	</span>
{% endfor %}
</div>
{% endif %}

{% if site.data.sponsors.alacarte %}
####### A La Carte Sponsorships
<div class="sponsor-tier">
  {% for sponsor in site.data.sponsors.alacarte %}
	<span class="sponsor alacarte-sponsor">
	  <span>{{ sponsor.type }}</span>  <hr />
	  <a href="{{ sponsor.url }}" title="{{ sponsor.name }}" target="_blank">
		{% if sponsor.image == %}
		  <span>{{ sponsor.name }}</span>
		{% else %} 
		  <img src="assets/img/Sponsors/{{ sponsor.image }}"> 
		{% endif %}
	  </a>
	</span>
{% endfor %}
</div>
{% endif %}

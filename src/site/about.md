---
title: About Us
layout: layouts/base.njk
subtitle: SILVERTRACS SYSTEMS
---


Silvertracs has two divisions:

##  Development and Manufacturing of Power Quality Monitoring Equipments

Silvertracs manufactures Power Quality Monitoring Instruments such as:

- Power Quality Analyzers
- Power, Harmonics & Energy Measuring Equipment
- High Frequency Noise Detectors
- Environment Monitoring Equipment
- Line Ground Analyzers
- Power Quality & Environment Monitoring Stations
- Ground Fault Monitor
- DB Monitor, etc.

Many of this equipment are used in-house for the Power Quality Consultancy services that is being offered. Continuous development is pursued based on feed back obtained by the ‘on-field’ experience.   All equipment is calibrated with traceability to ETDC/ NPL standards.


## Consultancy Services

- Power Quality and Grounding.
- Environmental – for Data Centers and Critical Application areas.
- Air Quality.
- Energy Audits

<p style="text-align:justify">Silvertracs Consultancy has so far done more then 4,500 studies in the above mentioned categories. Silvertracs gives maximum effort to provide prompt and reliable service with a commitment to customer service and satisfaction, strive to maintain a high degree of business integrity. The reflection of our commitment can be seen in the form of a large client base that we have. Companies, large and small, expect quality service and we have been there to provide it.</p>

Commitment makes this company what it is and it will always be the driving force behind us. We're not satisfied until you are.

<hr />

## Links

<ul>
	<li>
		<a href="\">Home</a>
	</li>
</ul>
<ul class="listing">
{%- for page in collections.post -%}
  <li>
    <a href="{{ page.url }}">{{ page.data.title }}</a>
  </li>
{%- endfor -%}
</ul>
<ul class="listing">
{%- for page in collections.post -%}
  <li>
    <a href="{{ page.url }}">{{ page.data.title }}</a>
  </li>
{%- endfor -%}
</ul>
<ul>
	<li>
		<a href="\contact-us">Contact Us</a>
	</li>
</ul>



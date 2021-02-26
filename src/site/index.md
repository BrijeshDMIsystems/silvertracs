---
title: Silvertracs
layout: layouts/base.njk
---
Consultants: Power Quality Analysis, Environment, Indoor Air Quality & Energy Audits<br /> Manufacturers: Power Quality & Energy  Measuring Instruments
<div align="center">
<img src="https://images.unsplash.com/photo-1580821100192-39130fdc17bf?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1267&q=80" width="99%" height="99%" />
</div>
<hr />

Silvertracs Systems started in 1991 has been actively involved in the field of Power Quality, Grounding and Environment for critical and sensitive Electronic Equipment. Silvertracs has two divisions:

##  Development and Manufacturing of Power Quality, Energy & Environment Monitoring Equipment

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


## Consultancy Services offered in:

- Power Quality and Grounding.
- Environmental – for Data Centers and Critical Application areas.
- Air Quality.
- Energy Audits

Silvertracs has so far done more then 4,500 studies in the above mentioned categories. Silvertracs gives maximum effort to provide prompt and reliable service with a commitment to customer service and satisfaction, strive to maintain a high degree of business integrity. The reflection of our commitment can be seen in the form of a large client base that we have. Companies, large and small, expect quality service and we have been there to provide it. 

Commitment makes this company what it is and it will always be the driving force behind us. We're not satisfied until you are.

<hr />

The pages found in in the posts

<ul class="listing">
{%- for page in collections.post -%}
  <li>
    <a href="{{ page.url }}">{{ page.data.title }}</a> -
    <time datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</time>
  </li>
{%- endfor -%}
</ul>

## Links from an external data source

These links were sourced from [hawksworx.com](https://www.hawksworx.com/feed.json) at build time.

<ul class="listing">
{%- for item in hawksworx.entries.slice(0,5) -%}
  <li>
    <a href="{{ item.link }}">{{ item.title }}</a>
  </li>
{%- endfor -%}
</ul>


## Prerequisite

- [Node and NPM](https://nodejs.org/)

## Running locally

```bash
# install the dependencies
npm install

# External data sources can be stashed locally
npm run seed

# It will then be available locally for building with
npm run start
```

## Add some Netlify helpers
Netlify Dev adds the ability to use Netlify redirects, proxies, and serverless functions.

```bash
# install the Netlify CLI in order to get Netlify Dev
npm install -g netlify-cli

# run a local server with some added Netlify sugar in front of Eleventy
netlify dev
```

A serverless functions pipeline is included via Netlify Dev. By running `netlify dev` you'll be able to execute any of your serverless functions directly like this:

- [/.netlify/functions/hello](/.netlify/functions/hello)
- [/.netlify/functions/fetch-joke](/.netlify/functions/fetch-joke)

### Redirects and proxies

Netlify's Redirects API can provide friendlier URLs as proxies to these URLs.

- [/api/hello](/api/hello)
- [/api/fetch-joke](/api/fetch-joke)





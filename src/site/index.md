---
title: Silvertracs
subtitle: <b>SILVERTRACS SYSTEMS</b>
layout: layouts/base.njk
---
Consultants: Power Quality Analysis, Environment, Indoor Air Quality & Energy Audits<br /> Manufacturers: Power Quality & Energy  Measuring Instruments
<div align="center">
<img src="https://images.unsplash.com/photo-1580821100192-39130fdc17bf?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1267&q=80" width="99%" height="99%" />
</div>
<hr />

<table style="float:center"; border= "0px solid black"; width="100%">
<thead>
<tr>
<th width="50%">We solve problems:</th>
<th width="50%">Causing:</th>
</tr>
</thead>

<tbody>
<tr>
<td>Power Quality</td>
<td>Component Failure</td>
</tr>
<tr>
<td>Energy Consumption</td>
<td>System Hanging / rebooting</td>
</tr>
<tr>
<td>Computer Room -Cooling</td>
<td>Production loss</td>
</tr>
<tr>
<td>Air Distribution</td>
<td>Failures caused due to corrosion</td>
</tr>
<tr>
<td>Air Quality</td>
<td>High Electricity bills</td>
</tr>
<tr>
<td></td>
<td>Nuisance tripping</td>
</tr>
<tr>
<td></td>
<td>Fire Hazards</td>
</tr>
<tr>
<td></td>
<td>Electric Shock</td>
</tr>
<tr>
<td></td>
<td>ESD</td>
</tr>
<tr>
<td></td>
<td>Magnetic Field Interference</td>
</tr>
</tbody>
</table>
<hr />
<br />

Technology advancement has reached a stage where almost in all areas micro–electronics has come to play a role. Computers, Data Processing, Computerized Numerical Control Machines, Measuring Systems and Quality Control Systems, Process Control and Industrial Automation, Medical Systems and Communication etc., all of them incorporate advanced electronics. Power and healthy environment plays a major role. 

Poor power quality, Environmental conditions, impure air, etc., affects the reliable operation of computers and computer-based equipment, which are now cannot be lived without. The loss of productivity resulting from computer equipment failure, miscalculations and downtime is a major worry. Loss in production and money spent in component replacement if estimated would be enormous. 

<b>Silvertracs Systems</b> started in 1991 has been addressing Power Quality, Environmental, Air Quality & Energy Conservation problems and has specialized in the following business sectors: 

##	Industry Specific Solutions 

- Software Development Centers
- BPO / Call Centers
- Data Centers and Disaster Recovery sites
- Telecommunication Industries
- EDP Centers
- Health Care and Hospitals (Medical Health)
- Bank / FIs / Stock Exchanges
- Industry Process Control and Automation (CNC Machines and Robots)
- R & D - Defense and Educational

<br />
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






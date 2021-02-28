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


## Links

<ul class="listing">
{%- for page in collections.post -%}
  <li>
    <a href="{{ page.url }}">{{ page.data.title }}</a> -
    <time datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</time>
  </li>
{%- endfor -%}
</ul>


## Hosting

This site is deployed by, and hosted by [Netlify](https://www.netlify.com).

<div class="nakedLink">

Latest deploy status: [![Netlify Status](https://api.netlify.com/api/v1/badges/056b4a67-70e6-4af4-9be5-dee151b8e906/deploy-status)](https://app.netlify.com/sites/eleventyone/deploys)

</div>

## One-click deploy

To get your own instance of this [Eleventy](https://11ty.io) starter project cloned and deploying to [Netlify](https://www.netlify.com) very quickly, just click the button below and follow the instructions.

<div class="nakedLink">

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/philhawksworth/eleventyone)

</div>
<div>
<img src="https://images.unsplash.com/photo-1580821100192-39130fdc17bf?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1267&q=80" width="50%" height="50%" />
</div>

## 👆 Wait, what happens when I click that button?

Good question. Here's what it will do...

1. Netlify will clone the [git repository]({{pkg.repository.url}}) of this project into your GitHub account. You will be asked for the required permissions to add the repo for you.
2. They'll create a new site for you in Netlify, and configure it to use your shiny new repo. Right away you'll be able to deploy changes simply by pushing changes to your repo.
3. That's it really.
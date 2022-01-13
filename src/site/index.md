 ---
title: EleventyOne
subtitle: A project scaffold for getting building with Eleventy quickly.
layout: layouts/base.njk
---


## This site is a starting point

From this point we should already have:

- [Eleventy](https://11ty.io) with a skeleton site
- A date format filter for Nunjucks
- Sass pipeline
- JS pipeline
- JS [search index](/search.json) generator
- Serverless (FaaS) development pipeline with Netlify Functions for Lambda


## Post pages

The pages found in in the posts

<ul class="listing">
{%- for page in collections.post -%}
  <li>
    <a href="{{ page.url }}">{{ page.data.title }}</a> -
    <time datetime="{{ page.date }}">{{ page.date | dateDisplay }}</time>
  </li>
{%- endfor -%}
</ul>

<!-- Start Square Appointments Embed code -->
<a target="_top" style="
background-color: transparent;
border: 2px solid #7e18d7;
color: #7e18d7;
height: 40px;
text-transform: uppercase;
font-family: 'Square Market', sans-serif;
letter-spacing: 1px;
line-height: 38px;
padding: 0 28px;
border-radius: 0;
font-weight: 500;
font-size: 14px;
cursor: pointer;
display: inline-block;
" href="https://squareup.com/appointments/book/0n2h21al9pbhvi/LSEERDAVDN1GS/start" rel="nofollow">Book Lesson</a>
<!-- End Square Appointments Embed code -->

<!-- Start Square Appointments Embed code --><a style=" background-color: #006aff; color: white; height: 40px; text-transform: uppercase; font-family: 'Square Market', 'helvetica neue', helvetica, arial, sans-serif; letter-spacing: 1px; line-height: 38px; padding: 0 28px; border-radius: 3px; font-weight: 500; font-size: 14px; cursor: pointer; display: inline-block; " href="https://squareup.com/appointments/buyer/widget/3pqy45boib3wpz/LSEERDAVDN1GS">Book an Appointment</a><!-- End Square Appointments Embed code -->

<!-- Start Square Appointments Embed code --><a style=" background-color: #006aff; color: white; height: 40px; text-transform: uppercase; font-family: 'Square Market', 'helvetica neue', helvetica, arial, sans-serif; letter-spacing: 1px; line-height: 38px; padding: 0 28px; border-radius: 3px; font-weight: 500; font-size: 14px; cursor: pointer; display: inline-block; " href="https://squareup.com/appointments/buyer/widget/3pqy45boib3wpz/LSEERDAVDN1GS">Book an Appointment</a><!-- End Square Appointments Embed code -->

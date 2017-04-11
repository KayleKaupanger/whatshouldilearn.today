---
layout: post
title: Collapsible Headings in Wordpress - No Plugin required
cover: cover.jpg
date:   2017-04-10 12:00:00
categories: posts
---

## Pure CSS/HTML Div

Wordpress without plugins can be an exhuasting effort.  After being assigned a project with limited plugins, I had to search for a solution using pure CSS & HTML.

I have found that '<summary>' and '<detail>' tags are easiest for this exact purpose. o css is required at all as the collapsing and showing are part of the tags definition/formatting.

Example:

<script async src="//jsfiddle.net/auz3ge8e/1/embed/html/"></script>

Result:


<details>
  <summary>This is the Collapsible Heading</summary>
  Content goes here.
</details>


## Looking for something better?

We can use CSS and a little more HTML to achieve a more professional look. 

<iframe width="100%" height="300" src="//jsfiddle.net/resende4/uoy6mf2h/1/embedded/html/" allowfullscreen="allowfullscreen" frameborder="0"></iframe>

<iframe width="100%" height="300" src="//jsfiddle.net/resende4/uoy6mf2h/1/embedded/css/" allowfullscreen="allowfullscreen" frameborder="0"></iframe>

<iframe width="100%" height="300" src="//jsfiddle.net/resende4/uoy6mf2h/1/embedded/result/" allowfullscreen="allowfullscreen" frameborder="0"></iframe>

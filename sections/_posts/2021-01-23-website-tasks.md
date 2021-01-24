---
layout: post
title: Website Todo
subtitle: What needs to get done on the website to make it usable for the team website
tags: [website, team, pr, media]
---

# Overview of Features

Site Features we'll need for the *real* team website:

* Theme of Website
  * Bring in cool programmer background from https://3189.team
  * Make the website dark-themed
    * Make sure all elements can still be rendered (e.g. they don't have black-on-black artifacts)
    * Pick out good dark-theme and team colors (our team color is green [#something])
* Layout of Website
  * Bring in each of the department pages as part of the _config.yml:navbar-links variable.
    * Programming
    * Mechanical
    * CAD
    * Electrical
    * Business/Media
  * Create a [Collection](https://jekyllrb.com/docs/collections/) for each department to describe each member.
    * Create the `collection` variable element in `_config.yml`
    * Create the `_<collection name>` folder in `sections`.
    * Add posts formatted as `yyyy-mm-dd-name-of-post.md`
    * Add in page for each member and use [Front Matter](https://jekyllrb.com/docs/front-matter/) to describe member name and year?
  * Create a contributions/sponsers page and populate with sponsers for this year.
    * Create a collection and post in collection for each sponser?
  * Create media page
      * Add social media pictures
      * Add in any newsletter links
      * Add in any other PR media
  * Create contact us and resources page
* Document editing the website and how to add in content
---
layout: post
title: How to build a personal website with Github Pages and Jekyll
date: 2023-09-17
description: Your digital mind palace.
tags: code
categories: guide
giscus_comments: true
related_posts: false
related_publications: false 
---

I was longing for a place to share my experience and thoughts about various topics including but not limited to my research interest in software engineering. While social media penetrates deeply into everyone's life, I find personal websites much less scoially interactive and potentially more efficient in attracting like-minded people. I finally have my own website built with GitHub pages and Jekyll, following the instructions in the [al-folio template](https://github.com/alshedivat/al-folio) (Sep 2023). Below are some tips that might be useful for those who would like to quickly establish the groundwork for their digital mind palace.

* Why GitHub pages
  * A default domain name
  * Automatic deployment via GitHub Actions
  * Easy integration with static site generators like Jekyll

* Why Jekyll
  * Developer-friendly and customizable templates

* My set up
  * MacBook with Apple M1 Max
  * Git
  * Docker and docker-compose

Note: since macOS does not support many linux commands, I need to manually install docker-compose as detailed on the [Docker website](https://docs.docker.com/compose/install/linux/#install-the-plugin-manually). The `docker-compose` command was not recognized untill I ticked off the "Use Docker Compose V2" option in the settings of Docker Desktop.

* Key steps
  * Set up Docker and docker-compose
  * Make a new repository with the template repository and rename it as requried by the [GitHub pages](https://pages.github.com/).
  * Change the url in the file `_config.yml`
  * Test the website locally with `$ docker-compose up`.
  * Set up the auto-deployment by enabling GithHub Actions.
  * Push your commits, wait till the workflows in `Actions` finish, and go to your website `https://username.github.io`.

Enjoy :D


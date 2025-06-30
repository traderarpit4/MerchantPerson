---
title: Home
layout: home
---
# About
This website serves as a personal playground for experiments with different dev tools and stuff. The site is meant to serve as a reference for services and solutions I use to maintain and improve my infrastructure. Whether it's learning something new or keeping track of ongoing projects, this site is my hub for sharing progress and resources.

# Services
## The Campfire Discord Server
The Campfire Discord server (or Guild as they want to call it) is a wonderful little community founded by myself and MarsInOrbit, currently run by a really awesome group of our friends. 

I might eventually spool up a little wiki or something for the Campfire Roleplay once it's launched. Don't worry, it'll happen. Eventually(tm)...

### The Campfire Minecraft Server
Campfire MC is a server that's been around since around 2014-2015, and under my ownership since 2019.

    Minecraft Server IP: mc.merchantperson.org
    Minecraft Version: 1.21.1
    Style: Vanilla

### Element // Matrix
Currently working on deploying Element web and Matrix as a secure backup for Campfire using the [Matrix-Docker-Ansible-Deploy] Playbook. It definitely wasn't a mild nightmare trying to set it up.

   Element Web: (Coming soon.)

Are you a member of Campfire and would like to join the Matrix server for testing?

### Uptime Kuma
Useful little tool to make sure that everything is up and running the way that it should be. Mostly tells me when the Minecraft server is offline. 

Campfire MC Uptime Kuma can be found at [Minecraft Uptime]. This will be expanded to some other services eventually(tm). Most of the infrastructure, including Uptime Kuma run off of one(ish) server.

## MerchantPerson.org Website
This website is built using [Jekyll] with the[^1] [Just the Docs] template. Will eventually need to figure out a way to build/push to the Matrix server to deploy but that's a problem for future me. 

### Licensing and Attribution

{: .fs-1 } 
This repository is licensed under the [MIT License]. You are generally free to reuse or extend upon this code as you see fit; just include the original copy of the license (which is preserved when you "make a template"). While it's not necessary, we'd love to hear from you if you do use this template, and how we can improve it for future use!

{: .fs-1 } 
The deployment GitHub Actions workflow is heavily based on GitHub's mixed-party [starter workflows]. A copy of their MIT License is available in [actions/starter-workflows].

----

[^1]: Flashbang warning.

[Matrix-Docker-Ansible-Deploy]: https://github.com/spantaleev/matrix-docker-ansible-deploy/tree/master
[Minecraft Uptime]: https://kuma.merchantperson.org/status/campfiremc

[Jekyll]: https://jekyllrb.com
[Just the Docs]: https://just-the-docs.github.io/just-the-docs/
[GitHub Pages]: https://docs.github.com/en/pages

[MIT License]: https://en.wikipedia.org/wiki/MIT_License
[starter workflows]: https://github.com/actions/starter-workflows/blob/main/pages/jekyll.yml
[actions/starter-workflows]: https://github.com/actions/starter-workflows/blob/main/LICENSE
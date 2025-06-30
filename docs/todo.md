---
layout: default
title: To Do
# nav_enabled: true
---

# To Do List
The current to do list, broken down by project. 

### Misc
- [ ] Upgrade the VPS? 
    * Might need to do this because it does seem to be using 20% without the Matrix services running or utilised. 
- [ ] Nuke that "master" branch for the website pull request.
- [ ] Add a page dedicated to linking to the various tools used to make this site and the various other services run through this site. 
- [ ] Deploy Portainer for sanity and tracking Docker Containers

### Element // Matrix 
- [ ] Finish experimental deployment of the Matrix Server
    - [ ] Build/push MerchantPerson.org pages to the Matrix server as static pages.
    - [x] Enable and test optional Matrix features. 
        - [ ] Test voice call feature
    - [ ] Setup MDAD to serve a static page
        - [ ] Create an automation to build and publish this site to the folder serving the static page
            - [ ] Use AUX (found in MASH) to simplify the process for managing this
            - [ ] Find a service or some code that monitors 
        - [ ] Figure out some other way to serve a static site that plays well with MDAD
            - [ ] See if there's a way to use GitHub Pages for that deployment

- [ ] Clean up the Ansible Playbook workspace and redeploy the server onto MerchantPerson.org.

- [ ] Contribute to MDAD playbook by creating a simple installer?
    * Something that guides you through a variety of the choices you'll have to make, and what's important about them to help configure the playbook for you. 
    * Basically holds your hand through the guidance that's already written on the configuration guide.
        * This is mostly a brain dump, not even sure it'll make sense later. 

### Mother-of-All-Self-Hosting Ansible Playbook
- [ ] Run MASH
    - [ ] See if Outline is the way to go for the Wiki
    - [ ] Play with NextCloud
        This will require some optimisation for performance.
    - [ ] See if Headscale works for a personal VPN
    - [ ] Uptime Kuma (reinstall, reconfig, deploy)

### Minecraft
- [ ] Update the Minecraft server to 1.21.5 (or latest)
- [ ] Fix perms, remove old players and keep new joins from modifying the world
    - [ ] Clean server rebuild? 
- [ ] Re-implement private chests
- [ ] World map
- [ ] Geyser

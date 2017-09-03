---
author: Priyank Trivedi
date: 2017-07-30 00:00:00 +0000
linktitle: Ansible - Automation Swiss Knife
title: Ansible - Automation Swiss Knife
highlight: true
tags:
- ansible
- automation
- devops

---


This blog post is an introduction to different components of Ansible - an automation tool that I am using at Zenatix to automate some of the DevOps stuff. It's a pretty useful tool and has been very helpful to me. I needed something really simple and that's why I opted for Ansible.

### So What's Ansible ?

Ansible is an automation system. With Ansible, you can handle configurations, perform ad-hoc commands across your servers, copy files to-and-fro from your machines. Tool like Ansible completely takes away the effort of writing custom scripts to perform trivial tasks to be orchestrated across your architecture.

### Core components

<div><p>Ansible Inventory - One should think of ansible inventories as logical grouping of servers which are to be managed by a sysadmin.<br></p>
  <figure>
  <img src="ansible_inventory.jpg" style="width:100%"><figcaption><br>Ansible Playbooks - One should think of Ansible Playbooks as a collection of commands that a sysadmin would run on servers mentioned in Ansible Inventory.<br></figcaption><figcaption></figcaption></figure>
  <figure><img src="/uploads/2017/09/03/Screen%20Shot%202017-09-03%20at%2011.33.41%20PM.png"><br><br>Ansible Modules - One should think of Ansible Modules as the in-built packages which are available for a sysadmin to use in Ansible Playbooks and then run them on the servers which are mentioned in Ansible Inventory.<br>
  </figure>
  <figure>
  <img src="/uploads/2017/09/03/Screen%20Shot%202017-09-03%20at%2011.33.32%20PM.png" class=" forestry--none" style="float: none;">
</figure>
  </div>
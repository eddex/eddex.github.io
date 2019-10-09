---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
description: ""
categories: []
dropCap: true # first letter of post dropped capital (big letter)
displayInMenu: false
displayInList: true
draft: true
resources:
- name: featuredImage
  src: ""
  params:
    description: "{{ replace .Name "-" " " | title }}"
---
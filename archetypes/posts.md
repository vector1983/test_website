---
title: '{{ replace .Name "-" " " | title }}'
date: {{ .Date }}
draft: false
author: wei hu
categories:
- Personal
- Thoughts
tags:
- software
- html
year: "{{ dateFormat "2006" .Date }}"
month: '{{ dateFormat "2006/01" .Date }}'
---

you can write your posts context here!
<!--more-->

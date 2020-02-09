---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
year: "{{ now.Format "2006" }}"
month: "{{ now.Format "2006/01" }}"
day: "{{ now.Format "2006/01/02" }}"
draft: false
categories: []
tags: []
people: []
---


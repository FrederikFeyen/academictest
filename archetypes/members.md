---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
url: "{{ replace .Name "-" " " | title | lower}}"
categories : ["members", "staff"]
layout: staff
---



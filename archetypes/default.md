---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
slug: "{{ .Name }}" # be sure to manually add /YEAR/MONTH/ to the beginning of the slug, ie. /2020/02/
date: "{{ dateFormat "2006-01-02" .Date }}"
draft: false # change to true if you don't want to publish right away
description: ""

tags: []

image: '' # default width is 1280
thumbnail: '' # default size should be 500x500
credit: '' # this is the link to the page the image came from 

comment: true
---
<!--more-->

---

*Comments or thoughts? Let me know on [Twitter](https://twitter.com/adamtervort/).*

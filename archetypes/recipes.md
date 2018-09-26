---
title: "{{ replace .Name "-" " " | title }}"
draft: true
date: "{{.Date}}"
image: ""
keywords: ["key", "words"]
tags: ["one", "two"]
type: "recipes"
authors: ["YOURNAME"]
firstletter: "A"
time:
  value: 4
  unit: "h"
timeactive:
  value: 30
  unit: "min"
ingredients:
 ingredient1:
  unit : g
  quantity: 300
  comment: "Useful information (e.q peeled, diced etc.)"
 ingredient2:
  unit : g
  quantity: 200
steps:
  intro: "Short introduction"
  1:
    title: "Title"
    explanation: "short explanation (1-2 sentences "
    ingredients:
      ingredient1:
        scale: 1
        comment: "Useful information (e.q. peeled)"
---

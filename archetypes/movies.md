---
title: "{{ replace .Name "-" " " | title }}"
slug: "{{ .Name | urlize }}"
poster: "/posters/{{ .Name }}.jpg"
release_year: "2025"
genres: ["Drama"]
director: "Director Name"
cast:
  - "Actor One"
  - "Actor Two"
rating: "0/10"
trailer: ""
summary: "Short summary here..."
---

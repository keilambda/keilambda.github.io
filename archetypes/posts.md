---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
slug: {{ .Name | urlize }}
type: articles
draft: true
categories:
  - default
tags:
  - default
---

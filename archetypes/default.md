---
title: "{{ replace .Name "-" " " | title }}"
date: {{ now.Format (default "2006-01-02 15:04:05" .Site.Params.dateFmt) }}
draft: true
categories:
  - Uncategorized
author: "Manoel Augusto"
tags:
  - tag1
  - tag2
  - tag3
description: "Uma breve descrição do post"
---

# {{ replace .Name "-" " " | title }}


---
title: '{{ replace .File.ContentBaseName "-" " " | humanize }}'
date: '{{ .Date }}'
effectiveDate: ''
draft: true
---

# {{ replace .File.ContentBaseName "-" " " | humanize }}

Добавьте согласованный текст документа и дату вступления в силу.

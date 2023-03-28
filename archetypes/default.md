---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
date: {{ .Date | time.Format ":date_long" }}
draft: true
---

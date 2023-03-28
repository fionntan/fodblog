---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
date: {{ .Date | time.Format ":date_long"  }}
description: ''
image: images/cctv.jpeg
draft: true
---
{{ .Date | time.Format ":date_long"  }}

---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
date: {{ .Date | time.Format ":date_long"  }}
image: images/writer.jpeg
menu:
  main:
    name: "About"
---
{{ .Date | time.Format ":date_long"  }}
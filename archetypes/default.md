---
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
date: {{ .Date }}
featured_image: /images/{{ replace .File.ContentBaseName "-" " " | title }}/thumb.png
draft: true
categories:
- category
tags:
- category
comments: false
shouMeta: true
showActions: false
---

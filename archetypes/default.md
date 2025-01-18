+++
[params]
  author = 'John Smith'
date = '{{ .Date }}'
draft = true
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
description = ""
show_reading_time = true
featured_image = ""
categories = []
tags = []
+++

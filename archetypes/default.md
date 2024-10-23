+++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = {{ .Date }}
year = {{ .Date | dateFormat "2006" }}
draft = true
+++

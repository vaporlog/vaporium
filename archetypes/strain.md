---
date: '{{ .Date }}'
draft: true
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
strain_id: "{{ .File.ContentBaseName }}"
name: "{{ replace .File.ContentBaseName "-" " " | title }}"
strain_type: "Hybrid" # Indica / Sativa / Hybrid
thc: 0
cbd: 0
terpenes: []
aromas: [] # e.g., Citrus, Earthy, Pine
effects: [] # e.g., Relaxing, Creative, Euphoria
lineage: "" # Parentage
link_reference: ""
---
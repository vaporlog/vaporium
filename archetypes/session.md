---
date: '{{ .Date }}'
draft: true
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
strain: "" # Reference to the strain_id
author: ""
email_author: ""
vaporizer: ""
temperature: 0 # in °C
session_duration: "" # e.g., 10 min
aromas: [] # e.g., Herbal, Spicy, Fruity
flavors: [] # e.g., Pine, Woody, Sweet
activities: [] # e.g., Gaming, Reading, Nature, Social
rating: 0 # 1 to 10 scale
mood: [] # Feelings or mood, e.g., Relaxed, Euphoric, Creative, Focused
---
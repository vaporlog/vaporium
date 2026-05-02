---
title: "How to Collaborate"
url: "/collaborate/"
summary: "Learn how to contribute with new strains or session logs to the encyclopedia."
---

Vaporium is a community project. Your experiences help others find the perfect vaporization setup. You can contribute in two ways:

## 1. GitHub Pull Request

For those familiar with Git, the best way to contribute is by sending a Pull Request directly to our repository.

1. **Fork** the repository: [Vaporium](https://github.com/vaporlog/vaporium)
2. **Add** your `.md` file to the `content/strains/` or `content/sessions/` folder.
3. **Submit** your Pull Request.

## 2. Submit by Email

If you are not a developer, you can send us an email with the details of your strain or session. 

Please send the data in **YML (Front Matter)** format to: **unalumnodel02@gmail.com**

---

## Data Templates

Copy and fill these templates in your submission to ensure the data is processed correctly.

### New Strain Template
```yaml
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
```

### New Session Template
```yaml
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
```
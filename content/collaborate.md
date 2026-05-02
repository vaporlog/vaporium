---
title: "How to Collaborate"
url: "/collaborate/"
summary: "Learn how to contribute with new strains or session logs to the encyclopedia."
---

Vaporium is a community project. Your experiences help others find the perfect vaporization setup. You can contribute in two ways:

## 1. GitHub Pull Request

For those familiar with Git, the best way to contribute is by sending a Pull Request directly to our repository.

1. **Fork** the repository: [Vaporium](https://github.com/vaporium/vaporium)
2. **Add** your `.md` file to the `content/strains/` or `content/sessions/` folder.
3. **Submit** your Pull Request.

## 2. Submit by Email

If you are not a developer, you can send us an email with the details of your strain or session. 

Please send the data in **YML (Front Matter)** format to: **alumnodel02@gmail.com**

---

## Data Templates

Copy and fill these templates in your submission to ensure the data is processed correctly.

### New Strain Template
```yaml
---
name: "Strain Name"
strain_type: "Hybrid" # Indica / Sativa / Hybrid
thc: 0
cbd: 0
terpenes: ["Myrcene", "Limonene"]
aromas: ["Pine", "Citrus"]
effects: ["Relaxing", "Creative"]
lineage: "Parent A x Parent B"
link_reference: "Leafly URL"
---
```

### New Session Template
```yaml
---
strain: "strain-id" # e.g. blue-dream
author: "Your Name"
vaporizer: "Device Name"
temperature: 180
session_duration: "10 min"
aromas: ["Herbal"]
flavors: ["Sweet"]
activities: ["Gaming"]
rating: 8 # 1 to 10 scale
mood: ["Relaxed"]
---
```
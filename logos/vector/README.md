# 📐 Vector Logos Directory (`/logos/vector/`)

[cite_start]This directory houses the raw, editable, and infinitely scalable vector logos for NexusCore-SLIATE[cite: 15, 19]. [cite_start]These are primarily utilized by the **Software Engineering Team** for direct integration into production web headers (such as `web-nexuscore-portal`) to guarantee sharp rendering at any resolution[cite: 32, 41, 64].

## 📁 Allowed File Formats
* [cite_start]**`.svg` (Scalable Vector Graphics):** Mandatory for web portal production[cite: 44].
* [cite_start]**`.fig` / `.ai`:** Raw editable design files for internal UI/UX changes[cite: 19, 63].

## 🏷️ Asset Naming Standard
All files must be saved in lower-case, hyphenated formats:
* [cite_start]`nexuscore-logo-dark.svg` (Optimized for dark backgrounds) [cite: 18]
* `nexuscore-logo-light.svg` (Optimized for light documentation pages)
* [cite_start]`nexuscore-symbol-isolated.svg` (The geometric emblem without typography) 

## 🚀 Frontend Implementation (CDN Access)
Developers should pull assets dynamically from this repository using the raw GitHub user content delivery path:
```html
<img src="[https://raw.githubusercontent.com/nexuscore-sliate/des-brand-assets/main/logos/vector/nexuscore-logo-dark.svg](https://raw.githubusercontent.com/nexuscore-sliate/des-brand-assets/main/logos/vector/nexuscore-logo-dark.svg)" alt="NexusCore Logo" />

---
author: ["Aditya Telange"]
title: "Code Syntax Guide"
date: "2019-03-10"
description: "Sample article showcasing basic code syntax and formatting for HTML elements."
summary: "Sample article showcasing basic code syntax and formatting for HTML elements."
tags: ["markdown", "syntax", "code", "gist"]
categories: ["themes", "syntax"]
series: ["Themes Guide"]
ShowToc: true
TocOpen: true
---

# Hugo + papermod Site

```jsx
sudo snap install hugo
hugo new site quickstart
cd quickstart
git init

git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke
echo "theme = 'ananke'" >> hugo.toml
 hugo server --bind "0.0.0.0" --port 8080
```

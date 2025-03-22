---
title: Guidelines to use github in WSL
date: 2024-10-07 08:16:26
tags:
---
Bonjour! It's my easy guideline to start with github!
--- Update after 42 piscine
I've learnt a lot from the piscine, with git being a crucial tool.
虽然我有时候会忘记git push（甚至是在考试中）
## Init
``` bash
mkdir new_project
cd new_project
git init
```

## Commit
``` bash
touch README.md
git add README.md
git commit -m "Add README file"
```

## Push
``` bash
git remote add origin <repository_URL>
git branch -M main
git push -u origin main
```
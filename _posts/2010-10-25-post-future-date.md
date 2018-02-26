---
title: "Post: Future Date"
subtitle: "Subtitle Goes Here"
date: 9999-12-31
categories:
  - Post
last_modified_at: 2017-03-09T12:45:25-05:00
image: /images/big-ben.jpg
---

This post lives in the future and is dated {{ page.date | date: "%c" }}. It should only appear when Jekyll builds your project with the `--future` flag.

```bash
jekyll build --future
```
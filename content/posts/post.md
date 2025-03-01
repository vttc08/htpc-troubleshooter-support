---
title: "Notes about settings up this webpage"
date: 2023-10-05T12:00:00Z
draft: false
tags: ["hugo", "example", "markdown"]
categories: ["example"]
---

This is documentation on how to setup and run this webpage.

## Introduction

Download Hugo.
https://gohugo.io/installation/

The page will reside in `support` subpath which will be bundled by FastAPI.

Building the page
```bash
hugo build --baseURL=http://${HOST}:${PORT}/support -d ../support
```

## Features

- **Simple**: Easy to write and manage content.
- **Fast**: Hugo is optimized for speed.
- **Flexible**: Customize your site with themes and plugins.

## Conclusion

Thank you for reading my first post. Stay tuned for more updates!

```bash
hugo server -D
```
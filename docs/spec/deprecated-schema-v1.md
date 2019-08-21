---
title: Update deprecated schema v1 images
description: Update deprecated schema v1 iamges
keywords: registry, on-prem, images, tags, repository, distribution, api, advanced, manifest
---

Updating an image mainfest from schema 1 to schema 2 is done by downloading an
image, applying schema 2, and then reuploading the image. However, this is a not
a catch-all solution. There may be several other steps to ensure your container
runs successfully, several of which are outlined below.

### Update FROM statement

Try updating the `FROM` statement in your `Dockerfile`.

### Here is a second Issues

here is some text.

### Here is a third issue

here is more text.

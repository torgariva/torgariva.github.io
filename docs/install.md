---
layout: page
title: Pfsense
description: >
  How you install Hydejack depends on whether you start a new site,
  or change the theme of an existing site.
hide_description: true
sitemap: false
---

Reinstalar pkg desde los ports:
Puedes intentar reinstalar pkg utilizando el sistema de ports. Primero, actualiza tus ports:

``` 
portsnap fetch update
```

Luego, navega al directorio de pkg y reinstálalo:

```
cd /usr/ports/ports-mgmt/pkg
make deinstall
make reinstall
```
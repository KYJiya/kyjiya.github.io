---
layout: post
title: "ERROR [internal] load metadata for docker.io/library/golang:1.14.1-alpine3.11"
subtitle: ""
date: 2021-09-27 00:16:13 -0400
background: '/img/posts/07.jpg'
---
# ERROR [internal] load metadata for docker.io/library/golang:1.14.1-alpine3.11
<br>

## Working Quick-Fix

disabling the buildkit feature by configuring the Docker Engine via Docker Desktop solves this issue.
```
"features": {
    "buildkit": false
  }

```

###### * 출처 : <https://github.com/docker/for-win/issues/11261>

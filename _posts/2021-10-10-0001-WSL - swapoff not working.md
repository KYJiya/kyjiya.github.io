---
layout: post
title: "swapoff not working in docker desktop linux image based on wsl"
subtitle: ""
date: 2021-10-09 00:16:13 -0400
background: '/img/posts/07.jpg'
---
# wsl 기반 docker desktop으로 구동한 linux에서 swapoff가 동작하지 않을 때.
<br>

## C:\Users\\\<UserName>\ 아래에 .wslconfig 파일을 생성한 후 다음과 같이 설정한다.
```

[wsl2]
swap=0

```


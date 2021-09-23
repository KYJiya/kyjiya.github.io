---
layout: post
title: "kube-apiserver install via snap"
subtitle: ""
date: 2021-09-13 20:16:13 -0400
background: '/img/posts/07.jpg'
---
# Snap을 통해 kube-apiserver를 설치해 보자.
<br>
```
$ sudo snap install kube-apiserver
kube-apiserver 1.21.4 from Canonical✓ installed

```

## 확인
```
$ kube-apiserver --version
Kubernetes v1.22.2

```

## wsl2 ubuntu에서 재시작하는 경우 snapd를 다시 활성화 한 뒤 체크

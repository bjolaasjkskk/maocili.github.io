---
layout: post
title: cannot load github.com/hashicorp/consul/api: ambiguous import
subtitle: consul安装多个版本导致的import冲突，已解决
date: 2019-10-26
author: Maocili
header-img: img/post-bg-debug.jpg
catalog: true
tags:
  - golang
  - consul
  - 服务注册
  - 报错处理
  - go mod

---

## go version

go version go1.13

### build error info

> build command-line-arguments: cannot load github.com/hashicorp/consul/api: ambiguous import: found > github.com/hashicorp/consul/api in multiple modules:
>
> github.com/hashicorp/consul v1.4.2 (C:\Users\Administrator\go\pkg\mod\github.com\hashicorp\consul@v1.4.2\api)
>
> github.com/hashicorp/consul/api v1.0.1 (C:\Users\Administrator\go\pkg\mod\github.com\hashicorp\consul\api@v1.0.1)

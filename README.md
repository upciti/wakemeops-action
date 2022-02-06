![cicd](https://github.com/upciti/wakemeops-action/actions/workflows/cicd.yml/badge.svg)

# wakemeops-action

:warning: **This action is currently unstable. Do not use it in production.**

:warning: **Running this action inside containers is currently not supported.**

## Introduction

This action lets you easily install packages from the WakeMeOps Debian repository on linux runners.

WakeMeOps is a Debian repository containing - among other things - up-to-date devops tools such as kubectl, kustomize, helm, helmfile, ... 

For more information see https://docs.wakemeops.com and https://github.com/upciti/wakemeops.

## Usage example

```yaml
- name: Install dependencies
  uses: upciti/wakemeops-action@v1
  with:
    packages: |
      helm=3.7.2*
      kustomize=4.4.1*
      kubectl=1.22.4*
```

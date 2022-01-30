# wakemeops-action

**Note: This action is currently unstable. Do not use it in production.**

## Usage

```yaml
- name: Install stuff
  uses: upciti/wakemeops-action@main
  with:
    packages: |
      helm=3.7.2*
      kustomize=4.4.1*
      kubectl=1.22.4*
```

# Go hooks for pre-commit

[Go](https://golang.org) tools package for [pre-commit](http://pre-commit.com).

## Using go tools with pre-commit

```yaml
-   repo: git://github.com/jsnider-mtu/pre-commit-golang
    rev: v0.0.1
    hooks:
    -   id: fmt
    -   id: vet
    -   id: fix
```

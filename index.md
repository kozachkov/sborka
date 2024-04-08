---
lang: ru
layout: home
lang-ref: index
---

# Сборка

- [Ящик (docker)]({{ site.baseurl }}/docker/index)

## make

Содержимое Makefile:

```bash
abc:
    ls -laht .
```

При выполнении `make abc` из расположения, где есть этот Makefile, будет
выполнено указание `ls -laht .`.

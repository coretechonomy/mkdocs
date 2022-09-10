# mkdocs

## Getting started:

```bash
podman build -t squidfunk/mkdocs-material . 
podman run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material
```
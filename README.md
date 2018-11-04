Install [reveal-md](https://github.com/webpro/reveal-md)

```shell
npm install -g reveal-md
```

## Produce a static site

```shell
reveal-md beyondJava8.md --theme assets/nipa-night.css --static _site --static-dirs=assets
```

## Create a live presentation

```shell
reveal-md beyondJava8.md -w --theme nipa-night.css
```

# Repo for http://scribe.webbucket.io/

This site is setup to be able to be deployed to Dokku

## Building

You need to install the theme
```sh
git submodule update --init --recursive
```


Install [Hugo](https://gohugo.io/)

`brew install hugo`  if you have homebrew

 and run:

```sh
hugo # to build the website

hugo server #to build and serve the website at localhost:1313
```


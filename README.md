# vue-template - Nice approaches to use in VueJS projects ❤️

Hi, everyone! 👋

This is a nice repo with some approaches to use in VueJS (2.x | 3.x) projects.

If you wanna, let's get in touch! 

## Summary

- Approaches

1. [Creating breadcrumb](#Breadcrumb) 
2. [Creating multi layouts on Vue SPAs](Multi-Layouts) 
3. [Loading application smartly](#Loading-application-smartly)

- Config

2. [Pre-requirements](#Installation)

## Breadcrumb

Here, you will find two approaches to creating breadcrum with VueJS and VueRotuer, the first idea is to create keys at route config and treat it in breadcrumb itself. Regarding secondapproach, the idea is to create a breadcrumb state and change it at route changing.

- [Seeing codebase here](https://github.com/open-ish/vue2-template/tree/feat/add-breadcrumb) 
- [You can also watch a video about it here](https://youtu.be/6G2fM9r8fJs) 🎥

## Multi Layouts

[Useful case](https://github.com/open-ish/nutris) - [article](https://dev.to/tassiofront/criando-multi-layouts-em-spa-s-vue-2-x-ou-3-x-5dfm)


## Loading application smartly

Sometimes do you have problems with async global information, including using this information in another async request? This approach might help you!

- [Seeing codebase here](https://github.com/open-ish/vue2-template/tree/feat/sensible-data-first/src)

### Installation

#### Project setup
```
yarn install
```

#### Compiles and hot-reloads for development
```
yarn serve
```

#### Compiles and minifies for production
```
yarn build
```

#### Run your unit tests
```
yarn test:unit
```

#### Lints and fixes files
```
yarn lint
```

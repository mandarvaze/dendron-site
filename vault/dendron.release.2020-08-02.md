---
id: e32aa1e2-9780-4183-927e-2f46372050aa
title: '2020-08-02 Release Notes'
desc: ''
updated: 1596374984386
created: 1596374984386
published: false
---


# 2020-08-02 Release Notes (version 0.5)

{{note}}

These release notes are summary of the more notable changes, for the full list, please look at our [CHANGELOG](https://github.com/dendronhq/dendron/blob/master/CHANGELOG.md)

## Legend

- 🚧 experimental

## Commands

Dendron has a series of builtin commands. They are all prefixed with `Dendron:` and can be accessed through the [command prompt](https://www.dendron.so/notes/c6fd6bc4-7f75-4cbb-8f34-f7b99bfe2d50.html#command-bar).

### Add Doctor Command 
([d4fa71c](https://github.com/dendronhq/dendron/commit/d4fa71cd839782587d47a3ba1b0f7e89742e7ffe)) ([docs](https://www.dendron.so/notes/eea2b078-1acc-4071-a14e-18299fc28f47.html#doctor))


This makes sure your workspace is up to date. It will execute the following actions:
- add ids and titles to the frontmatter of all notes that are missing it
- setup a `docs` folder if it doesn't exist. Required if you want to [[publish | dendron.topic.publishing]] your notes

<a href="https://www.loom.com/share/bd045f708f8e474193de8e3de0dc820f"> 
<img style="" src="https://cdn.loom.com/sessions/thumbnails/bd045f708f8e474193de8e3de0dc820f-with-play.gif"> 
</a>


### Add ShowHelp Command 
([ecf3c68](https://github.com/dendronhq/dendron/commit/ecf3c6822848834d9a00e373d1c59b6628e7f4df))([docs](https://www.dendron.so/notes/eea2b078-1acc-4071-a14e-18299fc28f47.html#show-help))

Dendron will open your current browser to the [[quickstart | dendron.quickstart]] page. 

<a href="https://www.loom.com/share/b81ce02f30b84d79b92584f339184a00">
<img style="" src="https://cdn.loom.com/sessions/thumbnails/b81ce02f30b84d79b92584f339184a00-with-play.gif"> 
</a>


## Pods

Pods are the mechanisms Dendron uses to import and export notes. Dendron has a different pod depending on where you are getting and publishing your data to. 

### Support publishing Vaults as Jekyll Page 
([e063732](https://github.com/dendronhq/dendron/commit/e063732d1ff082dd8520a479926e7ceb1b0893ab)) ([docs](https://www.dendron.so/notes/73d395c9-5041-4d0d-9db7-080d9586136e.html))
- custom dendron-jekyll theme
- convert wiki-links to markdown links while building site
- support custom root when publishing a site
- Publish local images when publishing site

### Setup initial workspace to be ready for publishing ([e1242b4](https://github.com/dendronhq/dendron/commit/e1242b494cc91b3284053b54dccecc4e4686ab7d))

## Schemas

### Use lookups to view and create schemas ([19b4677](https://github.com/dendronhq/dendron/commit/19b46770fe6a842831692563de96ff4a823df871)) ([docs](https://www.dendron.so/notes/a7c3a810-28c8-4b47-96a6-8156b1524af3.html#schemas))
  - it's now possible to perform lookup on schemas in addition to notes

### Support deleting schemas ([7e6730a](https://github.com/dendronhq/dendron/commit/7e6730a9c3f804d7c039cf74495493839c910fed)) ([docs](https://www.dendron.so/notes/a7c3a810-28c8-4b47-96a6-8156b1524af3.html#schemas))
  - what you create you can also take away

### Support schema templates ([0205d66](https://github.com/dendronhq/dendron/commit/0205d66fc4538361322ffeabb3e532f0d541b775)) ([docs](https://www.dendron.so/notes/c5e5adde-5459-409b-b34d-a0d75cbb1052.html#schema-templates))

## Fixes
- issue with journal names on windows ([d0bfe7f](https://github.com/dendronhq/dendron/commit/d0bfe7fb0288e8610fc4b177ee85697a8ebc3efe))
- stub nodes should keep parents when deleted ([f32f291](https://github.com/dendronhq/dendron/commit/f32f291bc7a1ddd6c542483730e2db74b400dafa))
- issue with urls in published site ([0ac8e75](https://github.com/dendronhq/dendron/commit/0ac8e75c95a9c4760e12bb301fc5b66b011ef0fb))

## Enhancements
- CI/CD testing ([d6ce68c](https://github.com/dendronhq/dendron/commit/d6ce68c720d7e8c96d7f4bb6ab390c1bd52c5218))
  - Dendron now has continuous integration tests for all pushes. ![](https://travis-ci.com/dendronhq/dendron.svg?branch=master)
  - Tests run on mac, linux and windows which means moving forward, there should be fewer OS related issues

- simpler schema syntax ([d53ddb](https://github.com/dendronhq/dendron/commit/d53ddb73bfacc3f769db88cfd4f482a706dcb6dd))

## Docs
- update quickstart doc ([aec0fe0](https://github.com/dendronhq/dendron/commit/aec0fe0939239d84f5b7ebd9ebae57a09bcdae43))

## Next

## Thank You

Last and most of all, a big **thanks** to all these people that contributed issues and suggestions during this release.

- [Alexis Argyris](https://github.com/alexisargyris)
- [Jay A. Patel](https://github.com/jayp)
- [Kiran Pathakota](https://github.com/kpathakota)
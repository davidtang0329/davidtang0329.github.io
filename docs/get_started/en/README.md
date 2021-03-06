---
title: open source static doc site generator teedoc
keywords: teedoc, markdown, jupyter notebook, html, document generation, alternative gitbook, website generation, static website, static blog
desc: teedoc, open source static doc site generator, convert markdown or jupyter notbook into html static web pages, used for personal or corporate website building, blog building, database building, wiki, etc.
---


Official website: [teedoc.neucrack.com](https://teedoc.neucrack.com/) or [teedoc.github.io](https://teedoc.github.io/)
Source file of this document: [github.com/teedoc/teedoc.github.io](https://github.com/teedoc/teedoc.github.io)
Source code: [https://github.com/teedoc/teedoc](https://github.com/teedoc/teedoc) Welcome star

Convert documents in `Markdown` or `Jupyter Notebook` format into `HTML` static web pages

`teedoc` can be used in the following scenarios:
* Build a document website, and it is best to support multiple documents (for example, you have two books called `Python Learning` and `C++ Learning`, they have separate directories, and `teedoc` is the library)
* Documents and web pages coexist, support custom `HTML` pages
* Build a `WiKi` website
* Build a personal or corporate knowledge base
* Build a personal or corporate website
* Blog

If you encounter problems during use, you can find similar problems in [here](https://github.com/teedoc/teedoc/issues) (you need to register and log in to github) to find similar issues, or create an issue


## Features

- [x] Multi-document support
- [x] Simple to use, cross-platform, only dependent on `Python3`
- [x] No database required, all static pages of the website
- [x] The deployment is simple, the generated website is a fully static page, which can be directly copied to the server or uploaded to a third party organization for deployment
- [x] Easy to write, using [Markdown syntax](./syntax/syntax_markdown.md)编写
- [x] [Jupyter notebook support]((./syntax/syntax_jupyter.ipynb))
- [x] HTML support, you can directly use HTML to write pages, with great freedom
- [x] Plug-in support
- [x] Multi-theme support (implemented by plug-in)
- [x] Control the style accurate to the page through css (implemented by customizing the id and class of each page)
- [x] Multi-level directory support(infinite levels)
- [x] Multi-language support (manual translation) (Internationalization/i18n)
- [x] Multilingual support (translation plugin)
- [x] Multi-version support (implementation method is the same as multi-language)
- [x] Search support
- [x] SEO friendly
- [x] Real-time preview of changes
- [x] Parallel build, faster build speed
- [x] Blog support
- [x] Switch from gitbook is easy, just config `route` and convert `SUMMARY.md` by `summary2yaml` command
- [x] Comments(Plugins), e.g. `gitalk`


## Demo

[This website](https://teedoc.github.io/) is generated using `teedoc`, what you see now is what the generated website looks like.

In addition, there are other websites that use `teedoc`, please see [here](./usage/sites.md) for details


## Similar tools

In fact, there are many tools of this type, but each one is slightly different. Just choose one according to your needs.

If you have choice difficulties, you are recommended to use teedoc if you meet some of the following conditions:
* Used as a document website? You have a lot of document sites in your hand, want to unify them into one site? Also websites in various languages? Use `teedoc`
* Use `Jupyter notebook` to write documents or code? Decisively choose teedoc
* Does the function meet your needs?
* Does the interface meet your aesthetics (you can customize `css`, or change the theme plug-in)
* Familiar with `Python`? Plug-ins and functions can be customized at any time

Other similar tools:
* `docusaurus`: `teedoc`'s `UI` layout is almost similar to it, but it is written by `vue`, `teedoc` is native `js`, if you are using `vue`, you can consider this
* `gitbook`: a tool that used to be very useful, but it is no longer maintained by the government, and it is switched to commercial use. It is not recommended to use it
* `docsify`: only one page is needed, `markdown` is rendered in the browser, instead of pre-rendered as `HTML`, the advantage is that it is lightweight, but `SEO` is not very friendly, you can use its `SSR` function, ` nodejs` written
* `readthedocs(Sphinx)`: In fact, it uses `Sphinx` as a generation tool. The official website documentation of `Python` is generated by this tool. Many open source projects use tools. `readthedocs` is just a public document website. You don’t need to build your own website, you can start writing documents after registering and logging in, and it is friendly to `RST` format support
* `mkdoc`: It is also a tool written by `python`. It is easy to use and has many plugins. If your document is a single language document, you can use this tool


## Some usage suggestions

* Add `Generate with teedoc` in footer to help more people discover teedoc and promote the growth of the project
* Use the template project to start a new document project, you can run it first, and then modify it according to your own needs, so that you can get started faster



## Quick start

Visit[quick start](./usage/quick_start.md) to install and quick start


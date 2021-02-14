# Week 3

> I'm currently using Operator Mono for my editor font.  
> Yes I paid the $200 for it.  
>
> — [Wes Bos](https://wesbos.com/uses)

[![](https://imgs.xkcd.com/comics/real_programmers.png)](https://xkcd.com/378/)

> Real Programmers by [**xkcd**](https://xkcd.com)

## Table of Contents

* [Slides](#slides)
* [Assignments](#assignments)
* [Hand in](#hand-in)

## Slides

_Coming Soon™_

## Assignments

### Local

![Local Banner](assets/banners/banner-local.jpg)

> Research and update your personal development setup to optimize your workflow

#### Synopsis

- **Time**: 2:00h
- **Due**: before week 4

You can theoretically write code in about anything that will allow you to write
text. That being said, your choice of tooling greatly affects your productivity.
Development software comes in all shapes and sizes, from basic text-editors to
full blown [IDEs](https://www.codecademy.com/articles/what-is-an-ide). Besides
editors, there's numerous tools and extensions available that'll help you writing better code.

#### Assignment

**Research the world of development tooling, and document the research in your
wiki.** Look into the following subjects, and describe why you think it's useful
(or not) and if/how you're using it in your own work:

- Text Editors Themes (f.e. [color themes][color], [fonts](fonts))
- Text Editor Settings (f.e. [settings.json][settings])
- Text Editors Extensions (f.e. [extensions marketplace][extensions])
- CLI's and configurations (f.e. [prompts][prompt], [aliases][alias], [colors][])

#### Additional resources

* [Syntax.fm VSCode extensions and themes](https://syntax.fm/show/161/hasty-treat-vscode-extensions-and-themes)

_Optional_: Many developers create a repo with what are known as `dotfiles`. An export of all their configuration files. You can try to set-up your own if you feel a bit adventurous. Here are two examples from [Mathias][mathias] and [Danny][danny].

---

### Linting

![Linting Banner](assets/banners/banner-linting.jpg)

> Install additional tools to help you write consistent code

#### Synopsis

- **Time**: 4:00h
- **Due**: before week 4

Besides editors, there's numerous tools available that'll help you _'cleanup'_ your code, like linters, beautifiers, and (type-)checkers. They can be broadly categorised  in two categories: **linters** and **formatters**. 

* Linters; help you catch **syntax errors** (f.e. ESLint, Stylelint, Markdownlint)
* Formatters; helps you **format** you code (f.e. Prettier, Editorconfig)

#### Additional resources

* [Linting with EsLint by The Coding Train](https://www.youtube.com/watch?v=clzTwZgMlqE)
* [ESLint + Prettier + VS Code by Wes Bos](https://www.youtube.com/watch?v=lHAeK8t94as)

#### Assignment

Try to implement atleast **one linter** and **one formatter** in your project Additionally research what they do and document the research in your wiki. 

_Pro Tip™_: Most linters are often available as extensions in text-editors. You install the extensions and the only thing you additionally have to do is to create a configuration file to tell the extension what rules to check for.

---

### Build

![Build Banner](assets/banners/banner-build.jpg)

> Research and implement a build tool in your project

Note: **This exercise is mainly for people from the _zwarte piste_.**. It's very useful to be aware of the various build tools and how they can help your project, but it's ok if it's a bit too much for now to start using.

#### Synopsis

- **Time**: 3:00h
- **Due**: before week 4

Build tools are additional tooling you can use in your project and are mostly used for _automating_ tasks or _transforming_ code. For example the CSS preprocessor _Sass_ which gives 'default' CSS more features and abilities. You write `.scss` files which get compiled to `.css` which can be read by a browser.

* Preprocessors: [Sass][sass], [PostCSS][postcss]
* Bundlers: [Browserify][browserify], [Rollup][rollup]

#### Assignment

Try to implement and research atleast **one build tool** in your project and  document in your wiki. Often times you can implement build tools by playing around with your start scripts in the package.json (concurrently or npm-run-all can help). 

_Pro Tip™_: Build tools (or asset pipelines) can get complex very easily. When you end up using multiple build tools in the same project, you'll quickly find that you need an additional tool (e.g. [Gulp][gulp], [Webpack][webpack]) to orchestrate all these different pieces. Don't start using these until you really have to, as they can be very overwhelming to configure properly if you're not already comfortable with the various build-tools and steps.

## Concept

**Continue working on your Job Story and feature you are going to build for _Blok Tech_.**  
Improve the front-end interface of your feature, spend some time on animation and interactivity etc.

## Hand In

1. **Push your Changes**  
   Commit and push any progress in your repo. Document all research you did in
   your wiki.

2. **Create an Issue**  
   Mark this assignment as completed by opening an issue on our
   [Issue Tracker](https://github.com/cmda-bt/pt-course-20-21/issues/new/choose).
   Fill in the issue template of `week-3` with the correct information.

3. **Feedback**  
   Any thoughts/feelings/concerns/opinions about these assignments? Let us know!
   We optimize these classes year-to-year, so your feedback is invaluable in
   making this course better.

[color]: https://code.visualstudio.com/docs/getstarted/themes
[fonts]: https://coding-fonts.css-tricks.com
[settings]: https://code.visualstudio.com/docs/getstarted/settings
[extensions]: https://marketplace.visualstudio.com
[prompt]: https://github.com/denysdovhan/spaceship-prompt
[alias]: http://zsh.sourceforge.net/Intro/intro_8.html
[colors]: https://osxdaily.com/2013/02/05/improve-terminal-appearance-mac-os-x/
[mathias]: https://github.com/mathiasbynens/dotfiles
[danny]: https://github.com/dandevri/dotfil.es
[webpack]: https://webpack.js.org/guides/getting-started/
[gulp]: https://gulpjs.com
[sass]: https://sass-lang.com
[postcss]: https://postcss.org
[browserify]: http://browserify.org
[rollup]: https://www.rollupjs.org/guide/en/

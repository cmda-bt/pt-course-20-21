# Week 4: Deployment & Production Setup

> No Deploy Fridays
>
> — [@iamdevloper](https://twitter.com/iamdevloper/status/1108993784132587520)

[![](assets/covers/deploying.png)](https://www.youtube.com/watch?v=5p8wTOr8AbU)

## Table of Contents

* [Slides](#slides)
* [Assignments](#assignments)
* [Hand in](#hand-in)
## Slides

* [Lab-4][lab4]

## Assignments

### Refactor

![Refactor Banner](assets/banners/banner-refactor.jpg)

> Ensure your code (and repo in general) is neat-o

#### Synopsis
- **Time**: 3h-4h (depending on your work so far)
- **Due**: before week 5

> Anyone can write code that a computer can understand. Good programmers write
> code that humans can understand.
>
> [Martin Fowler](https://twitter.com/martinfowler/status/1067179181140844544)

The code you write will be _executed_ by computers, but it will exclusively be
_read_ by humans. Therefore, it's critical that your code is easy to read,
understand, and "mentally parse". Go back into your work so far and make sure
that everything you've done so far is easy to understand for "outsiders" to your
project.
#### Assignment

* **Pick (minimum) 5 of the Clean Code JavaScript concepts** from the GitHub repo and refactor parts of your client and or server-side JavaScript code. Additionally clean-up any other code that needs refactoring. **Document what you refactored with _before_ and _after_ code blocks in your wiki.**
* **Tweak or set-up additional linters** (see week-3) in your project. It will further help you spot any inconsistenties in your code. 
* **Ask your support group to review your work**, and optimize your code
based on the questions they ask. It can be surprisingly difficult to find problems in work you're too familiar with. 

##### Further Reading

* [Clean Code by Robert C. Martin][clean]
* [Learning JavaScript Design Patterns by Addy Osmani][patterns]

### Deploy your App!

![Deploy Banner](assets/banners/banner-deploy.jpg)

> Put your app on the web!

#### Synopsis
- **Time**: 2h (depending on what platform you pick)
- **Due**: before week 5

Deploy your web app to a _hosting service_. This'll allow others to view your
app on the web! There are various options available, but we recommend looking at the following:

- [Vercel](https://vercel.com): By far the easiest and fastest way to deploy.
- Platform As A Service:
  [Heroku](https://devcenter.heroku.com/articles/getting-started-with-nodejs):
  needs more config then Vercel but is more powerful.
- Virtual Private Server [DigitalOcean](https://www.digitalocean.com/): The most
  hardcore way to-go. They just provide an empty linux and you need to set-up on
  your own.

Before you put anything online for the world to see, make sure you have:

- put your private variables in a `.env` file, and that you have this file
  listed in `.gitignore`;
- ignored `node_modules` from git by putting it in `.gitignore`
- check your `run scripts`, most deployment services will give errors if those are not set-up correctly

## Concept

**Continue working on your Job Story and feature you are going to build for _Blok Tech_.**  
Improve the front-end interface of your feature, improve the quality of the code, write documentation etc.

## Hand In

1. **Push your Changes**  
   Commit and push any progress in your repo. Document all research you did in
   your wiki.

2. **Create an Issue**  
   Mark this assignment as completed by opening an issue on our
   [Issue Tracker](https://github.com/cmda-bt/pt-course-20-21/issues/new/choose).
   Fill in the issue template of `week-4` with the correct information.

3. **Feedback**  
   Any thoughts/feelings/concerns/opinions about these assignments? Let us know!
   We optimize these classes year-to-year, so your feedback is invaluable in
   making this course better.

[clean]: https://www.oreilly.com/library/view/clean-code-a/9780136083238/
[patterns]: https://addyosmani.com/resources/essentialjsdesignpatterns/book/
[lab4]: /slides/pt_20-21_lab-4.pdf
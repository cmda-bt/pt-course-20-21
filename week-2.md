# Week-2

> How does Mr. Potato Head (dev edition 0.0.1) remove his mustache?
>
> git stache pop
> — [**@ABSphreak**][quote-author]

[![][inspiration-cover]][inspiration-link]

> A curated list of awesome Github Profile READMEs by [**@abhisheknaiidu**][inspiration-author].

## Table of Contents

* [Slides](#slides)
* [Assignments](#assignments)
* [Hand in](#hand-in)

## Slides
* [Lab-2][lab2]

## Assignments

### Docs

![Docs Banner](assets/banners/banner-docs.jpg)

> Learn how to use markdown and writing docs and readme's.

#### Synopsis

*  **Time**: 2:00h
*  **Goals**: subgoal 2
*  **Due**: before week 3

Take a couple of hours to learn how to write documentation and how `markdown (.md)` works. Follow the interactive tutorials and look at the Markdown Cheat Sheets.

1. Watch Wes Bos his [**Mastering Markdown**][markdown] course.
2. Try the [**interactive markdown tutorials**](interactive)

#### Assignment

Once you feel comfortable with markdown start writing the `readme.md` on your repo of the matching-application. Think about what to include in the readme.md. What does somebody who wants to look at your project want to know? Document how to install the project? Document what your features does? If you want to go even further look at what [_community files_][community] you can include in your repo.

***Optional:** As of recent GitHub allows you to create a [_profile_ `readme.md`][profile] which you can customize. It's a great way to explore some of the [more advanced features of markdown](advanced).

### Git It

![Git Banner](assets/banners/banner-git.jpg)

> Learn how to use Git trough the command line

#### Synopsis

*  **Time**: 4:00h
*  **Goals**: subgoal 3
*  **Due**: before week 3

Take a couple of hours to learn about Git stategies and version control with Git using the Command Line.

1. Take ± 30 minutes to learn Git [through Katacoda's interactive tutorial][katacoda]. It’s pretty sweet. Follow scenario 1 (and 2 if you have enough time).
2. Look at some of the common git commands on the [Git Tips][tips] and [Git Flight Rules][flight] repo's. Try out some of the commands and write down your favourite commands.
3. Read [how to write a git commit message][message] by Chris Beams
4. Read about [different Git Strategies][strategy] by Seth Robertson

***Optional:** There are many additional CLI tools to make working with Git even more fun. Like [gitmoji][emoji] or [gitstandup][standup]. You can search on GitHub and install more tools if you feel adventourus.

#### Assignment

Implement **your git strategy**. How are you going to write commit messages? Are you going to make branches? Are you going to use issues or projects? _Don't forget to document your research and final strategy to your wiki_. Start using the command line to version control your matching-application. Just see how you like it and what the benefits are to using Git on the terminal. You can always switch back to version control trough your editor or a GUI.


### Building
![Building Banner](assets/banners/banner-building.jpg)

> Start building out the interface (html & css) of your matching-app feature.

#### Synopsis

*  **Time**: 6:00h
*  **Due**: before week 3

#### Assignment

Based on the concept, job story, requirement list and wireframe from the previous week start building out the front-end of the feature you are going to make for the matching-application. You can build the interface with the **templating engine** as you learned in back-end as opposed to 'plain' HTML & CSS.

* Turn your wireframe **into HTML pages**. Do a HTML breakdown of your wireframe and use semantic HTML as learned in previous courses.
* Add **presentational CSS** to set-up some basic style. Think about colors, fonts, lay-out, responsiveness. 
* Add **interaction and statess**, make sure it feels like an actual webpage. Add states to interactive elements, maybe add some animations and transitions.
* Don't forget to think about the **flow of your application** (zero states, happy flow, error states). Do you need multiple pages?

## Hand In

1. **Push your changes:**  
Commit any code progess in your repository on GitHub under your username in your own matching-app repository. Also write down any technical and design research you did in your wiki.

1. **Create an issue:**  
Mark this assignment as complete by opening an issue on our [GitHub issue tracker][issues]. Fill in the issue template of `week-2` with the correct information. Include what progress you made in the description of the issue.

3. **Feedback:**  
Let us know what you thought of the homework, what part you spend a lot of time on and give us any feedback. Your assignment will be reviewed by teachers and student assistants, so expect people to read it and be ready for tips and tops!

[inspiration-cover]: assets/covers/profile.png
[inspiration-link]: https://github.com/abhisheknaiidu/awesome-github-profile-readme
[inspiration-author]: https://github.com/abhisheknaiidu
[quote-author]: https://github.com/ABSphreak

[issues]: https://github.com/cmda-bt/pt-course-20-21/issues/new/choose
[lab2]: /slides/pt_20-21_lab-2.pdf

[markdown]: https://www.youtube.com/watch?v=Je5w18nn-e8&list=PLu8EoSxDXHP7v7K5nZSMo9XWidbJ_Bns3
[community]: https://opensource.guide/code-of-conduct/
[interactive]: https://www.markdowntutorial.com/
[katacoda]: https://www.katacoda.com/courses/git
[tips]: https://github.com/git-tips/tips
[flight]: https://github.com/k88hudson/git-flight-rules/
[message]: https://chris.beams.io/posts/git-commit/
[emoji]: https://gitmoji.dev
[standup]: https://github.com/kamranahmedse/git-standup
[profile]: https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme
[advanced]: https://github.com/abhisheknaiidu/awesome-github-profile-readme
[strategy]: https://sethrobertson.github.io/GitBestPractices/#workflow

# Week-1

> stash it, pop it, grep it, move it, config, prune it, format-patch it, add it, reset, add it, show it, git help reflog, pull --rebase it
>
> — [**@DLX**][quote-author]

[![][inspiration-cover]][inspiration-link]

> Build your own Octocat by [**@github**][inspiration-author].

## Table of Contents

* [Slides](#slides)
* [Assignments](#assignments)
* [Hand in](#hand-in)

## Slides
* [Lab-1][lab1]

## Assignments

### Octocat

![Octocat Banner](assets/banners/banner-octocat.jpg)

> Learn the basics of Git and the social coding platform GitHub.

#### Synopsis

*  **Time**: 3:00h
*  **Goals**: subgoal 1, subgoal 2
*  **Due**: before week 2

Take a couple of hours to understand what open-source means and how GitHub and Git works. It's not a ton of reading material, these are usually short articles you can read in ~7/8 minutes.

1. Read chapters [**1.1, 1.2 & 1.3**][gitbook] of the _Pro Git Online Book_.
2. Read [**Understanding the GitHub Flow**][flow] and do the exercises in the [**Hello World**](https://guides.github.com/activities/hello-world/) guides on _guides.github_.
3. Read the _Creating your wiki_ section in the [**Documenting your Project**][wiki] guide.
4. Read the [_Starting an Open Source Project_][os] and [_The Legal Side of Open Source_][legal].

#### Assignment

Once you feel comfortable with basic GitHub concepts apply them to your own project. Create a repository for your matching-application, add a [`license`][license] and a `readme.md` (we'll fill it in later) and create a `wiki` to document your research. Explore some of the features you just read about, click trough the interface and settings of your just created repository.

### Terminal

![Terminal Banner](assets/banners/banner-terminal.jpg)

> Learn the basics of navigating the command line.

#### Synopsis

*  **Time**: 3:00h
*  **Goals**: subgoal 1, subgoal 2
*  **Due**: before week 2

Take a couple of hours to understand the basics of the Terminal. Troughout the other courses (especially back-end) we'll be doing a ton with the terminal so it's good to understand how to navigate it. 

1. Follow ['A Designer’s Guide to the Terminal'][guidecli]
2. Watch the [Command Line Basics video][wesboscli] of Wes Bos his CLI course.

#### Assignment

We have created a short interactive tutorial to see if you know your away around the command line! Upon completion you'll be given a code. Write that down! We'll ask you to include it in your GitHub issues once you completed. Here are the instructions on how to start the tutorial:

<details>
  <summary><strong>CLI interactive tutorial install guide</strong></summary>
  <p>Create a directory (folder) named 'run' on your computer and in that folder create a file  called <code>tutorial.sh</code> (you can use touch for this) and paste the contents of <a href="https://gist.github.com/dandevri/9568a8dff8f572a0ea67627445aca5b2">this GitHub Gist</a> into the file.</p>
  <p>Change to that directory where tutorial.sh is in. Now run that script with the command <code>bash tutorial.sh</code></p>
  <p>The tutorial should now start in your terminal!</p>
</details>


### Concept

![Concept Banner](assets/banners/banner-concept.jpg)

> Work on the concept of your matching-application by creating a job story and requirements list.

#### Synopsis

*  **Time**: 6:00h
*  **Goals**: subgoal 1, subgoal 2
*  **Due**: before week 2

Think about what feature you are going to work on for the individual part of this project. 

1. Write ~5 [Job Stories][jobs] (to generate ideas) and pick one to continue working on.
2. 'Split up' your Job Story into concrete requirements (taks) by making a [requirements list][requirements]
3. Think about your concept and target audience. It always helps to have one core audience you will be designing for. For example; sport fanatics to match people based on sports, netflixers to match people based on what series they want to watch etc.
4. Create a small [wireframe (napkin quality)][wireframe] to roughly sketch out how your interface should look.

#### Assignment

Document all this research things in your wiki. Teachers will give feedback on your concept in the next lesson. Remember we are not a UCD or NPD course but thinking about your concept for a bit will help you get clear on what you are going to build. So don't make full design documents, writing them down in your wiki is enough.

## Hand In

1. **Push your changes:**  
Commit any code progess in your repository on GitHub under your username in your own matching-app repository. _Write down all the technical research you did, your Concept, Job Story and Requirements List in your wiki._

2. **Create an issue:**  
Mark this assignment as complete by opening an issue on our [GitHub issue tracker][issues]. Fill in the issue template of `week-1.md` with the correct information. Include what progress you made in the description of the issue.

3. **Feedback:**  
Let us know what you thought of the homework, what part you spend a lot of time on and give us any feedback. Your assignment will be reviewed by teachers and student assistants, so expect people to read it and be ready for tips and tops!

[inspiration-cover]: assets/covers/octocat.png
[inspiration-link]: https://myoctocat.com
[inspiration-author]: https://twitter.com/github
[quote-author]: https://twitter.com/DLX

[issues]: https://github.com/cmda-bt/pt-course-20-21/issues/new/choose
[lab1]: /slides/pt_20-21_lab-1.pdf

[wesboscli]: https://www.youtube.com/watch?v=DP218aBHm1Q
[guidecli]: https://react.design/terminal

[gitbook]: https://git-scm.com/book/en/v2
[flow]: https://guides.github.com/introduction/flow/
[wiki]: https://guides.github.com/features/wikis/#creating-your-wiki
[os]: https://opensource.guide/starting-a-project/
[legal]: https://opensource.guide/legal/
[license]: https://choosealicense.com

[wireframe]: https://www.cmdmethods.nl/cards/stepping-stones/design-specification
[requirements]: https://www.cmdmethods.nl/cards/stepping-stones/requirement-list
[jobs]: https://jtbd.info/replacing-the-user-story-with-the-job-story-af7cdee10c27

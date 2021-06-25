 # ![Project Tech - Course 2020-2021][banner]

> **Note**: Project-tech has concluded for 2020/2021. Next year will be a new, changed, curriculum. Have a look at the [`/examples`](/examples) folder to see some results from this year. A big thank you to our all our students, student assistants and teachers!

## Table of Content

*   [Synopsis](#synopsis)
*   [Description](#description)
*   [Communication](#communication)
*   [Goals](#goals)
*   [Grade](#grade)
*   [Programme](#programme)
*   [Conduct](#conduct)
*   [Statements](#statements)
*   [License](#license)

## Synopsis

The course **Project-tech** is given at [**@CMDA**][cmda] in 2021 between February 3 and June 26.

*   **Course**: [Project Tech][course] (`2000PTEC16`)
*   **Coordinator(s)**: [Danny de Vries][dangit] - d.de.vries4@hva.nl and [Rijk van Zanten][rijkgit] - r.vanzanten@hva.nl
*   **Lecturers**: [Danny de Vries][dangit] ([**@dandevri**][danweb]), [Ivo Nijhuis][ivogit] ([**@ivo-online**][ivogit]), [Robert Spier][robgit] ([**roberrrt-s**][robgit]) and [Rijk van Zanten][rijkgit] ([**@rijkvanzanten**][rijkgit])
*   **Credit**: 5 ECTS
*   **Academic year**: 2020-2021
*   **Period**: Quarter 3 (spring)
*   **University**: [Amsterdam University of Applied Sciences][university]
*   **Programme**: [Communication and Multimedia Design][cmd] (full time bachelor CROHO: `34092`)
*   **Faculty**: [Digital Media and Creative Industries][faculty]
*   **Language**: Dutch instructions and English resources
*   **Entry requirements**: N/A

## Description
Project Tech is your first stepping stone to become a well-rounded web developer (or a designer with knowledge of how things are made). You'll build a dynamic prototype of a matching application. You’ll learn about the “softer” skills; reading documentation, collaboration and “harder” skills; how to use the command line, version control, build tools, and code quality.

We’ll focus on what it means to be a web deveveloper, the current landscape of that space, and topics such as privacy, security, diversity, inclusion, accessibility, communication and team work.

Projecttech is an elective course given in Quarter 3 (spring) after the core curriculum of our programme, building further on knowledge acquired in *Internetstandaarden*, *Inleiding Programmeren*, and *Blok Web*. This course is chosen alongside **Frontend 2** and **Back-end**, together making up Block Tech. 

If you’d like to continue with web development after this course, do a tech internship, choose the [Tech Track][track] for the fall semester next year, and pick [Minor Everything Web][minor] in the spring semester after that. Just a quick check if anyone actually reads this: if you see this, please send your teacher a picture of your favorite animal.

_Project-tech is part of the  CMD Amsterdam **design & build space** (technical course) that focusses on   Conceptualizing (2), Imagining and creating (3), Multidisciplinary collaboration (5) & Research (9) competences._ 

## Communication

*   [GitHub][gh] — Main source of information, slides, assignments and more
*   [Microsoft Teams][teams] — General chatter and Q&A
*   [Brightspace][brightspace] — Schedulers, rubrics and grading

> This course doesn't have office hours. Teachers have limited time to help you outside of class. Attendance to class is not compulsory. 80% of success in this course is showing up, so show up and come prepared with your questions. 
  

If you have questions:

*   Read the manual for the technology in question
    ([Git](https://git-scm.com/docs),
    [GitHub](https://guides.github.com),
    [Bash](https://www.gnu.org/software/bash/manual/),
    [VSCode](https://code.visualstudio.com/Docs))
*   [Browse examples][examples]
*   [Search StackOverflow][stackoverflow]
*   [Use a search engine like DuckDuckGo][duckduckgo]
*   [Ask questions on MS Teams][teams] (don't ask to ask and no hello)

> Asking good questions is a skill. [Don't ask to ask][ask] and [no hello][hello]. Read more about asking questions and being helpful in the [`docs`](/docs) folder.


## Goals

### Main goals

The main goals in this course:

* You can design and develop a dynamic matching web application
* You can use version control using Git and GitHub
* You can navigate the terminal and set-up your own development environment
* You can write documentation that other developers understand
* You can explain your code and the cohesion of your application
* You can recognise good quality code, collaborate and review other people's code

### Sub goals

In practice you’ll learn to:

* <a name="subgoal-1"></a>
    Version control with Git ([**week 1**][w1])
*  <a name="subgoal-2"></a>
    Write docs in markdown ([**week 1**][w1])
* <a name="subgoal-3"></a>
    Navigate the command line ([**week 2**][w2])
* <a name="subgoal-4"></a>
    Code quality and linting ([**week 3**][w3])
* <a name="subgoal-5"></a>
    Review code and understand code quality ([**week 4**][w4])
* <a name="subgoal-6"></a>
    Collaborate on GitHub with other developers ([**week 5**][w5])
* <a name="subgoal-6"></a>
    Learn about production environments and deployment ([**week 6**][w6])
* <a name="subgoal-7"></a>
    Learn about privacy and security issues ([**week 7+**][w7])

The below table breaks down the general time needed per week.

| Week | Effort | Topic            | Activities                                             |
| ---- | -----: | ---------------- | ------------------------------------------------------ |
| 0    |  NaN   | getting started  | [getting started][gs]                                  |
| 1    |  9:20h | github           | [lab][w1lab], [lecture][w1lec], [assignments][w1a]     |
| 2    |  9:20h | terminal       | [lab][w2lab], [lecture][w2lec], [assignments][w2a]     |
| 3    |  9:20h | linting            | [lab][w3lab], [lecture][w3lec], [assignments][w3a]     |
| 4    |  9:20h | code quality        | [lab][w4lab], [lecture][w4lec], [assignments][w4a]     |
| 5    |  NaN   | assessment 1     | [a1 (oral test)][grading]                              |
| 6    | 13:20h | prototype          | [lab][w6lab],  work on prototype                       |
| 7    | 13:20h | prototype        | [lab][w6lab],  work on prototype                       |
| 8    |  NaN   | assessment 2     | [a2 (oral test)][grading]                              |  

> Check [`rooster.hva.nl`][class] for exact class dates

## Grade

| Task                                |   Weight |
| ----------------------------------  | -------: |
| [Assessment 1][grading] (individual)|      60% |
| [Assessment 2][grading] (team)      |      40% |
| **Total**                           | **100%** |


```js
if (!a1 && !a2) {
  grade = 'GR'
} else if (a1 < 5.5 || a2 < 5.5) {
  grade = 1
} else {
  grade = (a1 * 0.6) + (a2 * 0.4)
}
```

## Programme

This course is given at [Communication and Multimedia Design][bachelor], a
design bachelor focused on interactive digital products and services.  CMD is
part of the [Faculty of Digital Media and Creative Industries][faculty] at the
[Amsterdam University of Applied Sciences][university].

Our curriculum and course material are publicly available on the Block Tech (github.com/cmda-bt) GitHub organization. We follow the global trend to make teaching materials accessible to everyone inspired by the [Open Education Global][oec].

## Conduct

This course has a [Code of Conduct][coc].  Anyone interacting with this repository, organisation, or community is bound by it. Staff and students of the Amsterdam University of Applied Sciences (Hogeschool
van Amsterdam) are additionally bound by the [Regulation Undesirable
Conduct][ruc] ([Regeling Ongewenst Gedrag][rog]).

## Statements

We are dedicated to provide you with a learning environment that is _rigorous, respectful and supportive_ so you can engage in the free exchange of ideas and commit yourself fully to the study of your discipline. To that end we are committed to enforce important AUAS policies. You can find our policies and statements (e.g. accessibility, health, plagiarism) in the `docs` folder.

## License

[MIT][] © [Danny de Vries][dangit], docs and images are [CC-BY-4.0][].

[banner]: https://cmda-bt.github.io/pt-course-20-21/assets/banner.svg
[cmd]: https://www.cmd-amsterdam.nl/english/
[cmda]: https://github.com/cmda
[dangit]: https://github.com/dandevri
[danweb]: https://github.com/dandevri
[rijkgit]: https://github.com/rijkvanzanten
[ivogit]: https://github.com/ivo-online
[robgit]: https://github.com/roberrrt-s
[node]: https://nodejs.org/en/
[mongodb]: https://www.mongodb.com/
[http]: https://tools.ietf.org/html/rfc2068
[minor]: https://cmda.github.io/minor-everything-web/
[track]: https://github.com/cmda-tt
[gh]: https://github.com/cmda-be/course-18-19
[examples]: /examples
[teams]: http://teams.microsoft.com
[brightspace]: https://dlo.mijnhva.nl/d2l/home/192551
[examples]: examples
[stackoverflow]: https://stackoverflow.com
[duckduckgo]: https://duckduckgo.com
[synopsis]: #synopsis
[grading]: grading.md
[bachelor]: https://www.cmd-amsterdam.nl/english/
[faculty]: https://www.amsterdamuas.com/faculty/fdmci/faculty-of-digital-media-and-creative-industries.html
[university]: https://www.amsterdamuas.com
[coc]: code-of-conduct.md
[ruc]: https://www.amsterdamuas.com/practical-matters/algemeen/hva-breed/juridische-zaken/legal-affairs/regulation-undesirable-conduct/regulation-undesirable-conduct.html#anker-3-complaints-authority
[rog]: https://www.hva.nl/praktisch/algemeen/hva-breed/juridische-zaken/loket-beroep-bezwaar-en-klacht/regeling-ongewenst-gedrag/regeling-ongewenst-gedrag.html?origin=gbS4rg%2FDTZuxQ6lGVF%2BN1A
[author]: https://dandevri.es
[mit]: license.md#code
[cc-by-4.0]: license.md#documentation-and-images
[faq]: https://dlo.mijnhva.nl/d2l/lms/faq/view_faq.d2l?ou=32096
[class]: https://rooster.hva.nl/
[course]: https://studiegids.hva.nl/#/cmd-vt/1/010624
[oec]: https://www.oeglobal.org
[gs]: getting-started.md

[ask]: https://dontasktoask.com
[hello]: https://nohello.net

[w1]: week-1.md
[w2]: week-2.md
[w3]: week-3.md
[w4]: week-4.md
[w5]: week-5.md
[w6]: week-6.md
[w7]: week-7.md

[w1lec]: week-1.md#lecture
[w2lec]: week-2.md#lecture
[w3lec]: week-3.md#lecture
[w4lec]: week-4.md#lecture
[w5lec]: week-5.md#lecture
[w6lec]: week-6.md#lecture

[w1lab]: week-1.md#lab
[w2lab]: week-2.md#lab
[w3lab]: week-3.md#lab
[w4lab]: week-4.md#lab
[w5lab]: week-5.md#lab
[w6lab]: week-6.md#lab

[w1a]: week-1.md#assignments
[w2a]: week-2.md#assignments
[w3a]: week-3.md#assignments
[w4a]: week-4.md#assignments

# ![Project-tech - Getting Started][banner-guide]

## Table of Contents

*   [Description](#description)
*   [Prerequisite](#Prerequisite)
*   [Installation](#installation)
*   [Communication](#communication)

## Description

👋 **Welcome to project-tech!** 

This getting started guide will get you up and running with all the software and tools you need for this course. Throughout this guide there are additional video's that further explain important topics from lectures but also show you how to install certain technology. Look for a 🎦 emoji!

## Prerequisite

### Text Editor

If you don’t have one yet, install a text editor. It doesn't really matter which one you pick, as long as you feel comfortable using it. However, we do recommend moving away from [Brackets](http://brackets.io/), other editors offer better customizability. [VSCode](https://code.visualstudio.com/) is our recommended choice but there are other.  [Atom](https://atom.io) and [Sublime](https://www.sublimetext.com) are both also good choices. 

> Take some time to [learn the interface and features of VSCode][learnvs]. If you know your way around the interface, coding will be easier. Feeling comfortable with your tools is very important when writing code.

[🎦 _Watch a video_ on how to install Text Editors.][videotext]

### GitHub

If you haven’t already, [sign up for
GitHub](https://help.github.com/articles/signing-up-for-a-new-github-account/). Take some time to set up your [GitHub profile](https://github.com/settings/profile).
Include your name, a profile picture, and a URL to your homepage. Teachers will appreciate it if you upload a representing profile and pick a username that closely resembles your real name. Silly pictures are allowed 🤪

> You’re allowed to stay anonymous online for this course by omitting sensitive information, but a good looking GitHub profile can help you get an internship or job later. 

[🎦 _Watch a video_ on how this GitHub organisation works.][videoorg]

## Installation

### CLI

*Windows:*  
If you’re on Windows, you should upgrade to _Windows 10 (1903)_ and install the Windows Subsystem for Linux using [this guide](https://www.howtogeek.com/249966/how-to-install-and-use-the-linux-bash-shell-on-windows-10/) ([or video](https://www.youtube.com/watch?v=Cvrqmq9A3tA))
. Follow it until you see “Installation successful”. Additionally you can install the [Windows Terminal][terminal] and switch to using WSL.

> Be ware that lecturers may not be able to help you with specific problems on Windows. Ask questions on MS Teams to other Windows users.

*MacOS:*  
Apple already has a terminal emulator by default to provide a command line interface. Just search for `terminal` in **spotlight** or find it in your applications folder. 

> There are other command-line interfaces out there you can download that add more feature. [Hyper](https://hyper.is/) and [iTerm](https://iterm2.com/) are very popular choices.

### Git

*Windows:*  
If you installed the [Windows Subsystem for Linux](#subshell) just now, install Git by running `apt-get install git` in Bash.

*MacOS:*  
Install Git from their website, by [downloading the latest release](https://git-scm.com).

Connect Git and GitHub together inside of the **terminal** like so:

```sh
git config --global user.name "Mona Lisa"
git config --global user.email "mona@lisa.com"
```

Use the same email for Git as you used to sign up for GitHub.

[🎦 _Watch a video_ on how to set-up gia via the terminal.][videogit]


## Communication

### Brightspace

We use our DLO Brightspace for schedulers and rubric feedback. Make sure you enroll to the **Project-tech** course, you can do so by using the [HvA courseselector][course]. It's important to **select the right class** for teachers to give you feedback and grades. If you're not sure, ask your teacher to see if you are on the correct _classlist_.

### Microsoft Teams

Sign up for our _Blok-Tech_ MS Team. **You can find the sign-up code in the announcement on Brightspace.** Join the `#project-tech` channel in our team. Get your account set up properly, add your  **real name**, **a profile picture**, and you can even set your **GitHub username** as a status message. We’ll use this info to link your GitHub and MS Teams account to our administration files.

### GitHub

GitHub is a social platform so give this repository `pt-course-20-21` [a ⭐ star][star] and start [following][follow] your teachers and fellow students!


## Introduction

**Wow, you did it! Virtual high five! 🖐** Now you can introduce yourself to your teacher and class. Open an issue on our [GitHub issue tracker][issues]. You can pick what are called `issue templates`. Pick the `Introduction` template and fill in the details, then submit.

> 🚨 Make sure you never publicly share you name and student number in combination!

Each assignment has a different template in which you can hand in your assignments for that week. This is also the place where teachers and student-assistants will give you feedback. You can use [GitHub notifications][notifications] (bell on the top right of the GitHub website) to keep track of changes.

[banner-guide]: https://cmda-bt.github.io/pt-course-20-21/assets/banner-guide.svg
[examples]: examples
[stackoverflow]: https://stackoverflow.com
[duckduckgo]: https://duckduckgo.com
[synopsis]: #synopsis
[terminal]: https://github.com/microsoft/terminal

[notifications]: https://help.github.com/en/github/managing-subscriptions-and-notifications-on-github/configuring-notifications
[course]: https://courseselector.mijnhva.nl/nl#/CourseSelector/78076118-8f51-e911-a82e-000d3a29a761/2019-2020
[star]: https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github/saving-repositories-with-stars
[follow]: https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github/following-people
[videoask]: https://www.youtube.com/watch?v=0CARthL2RPo
[videotext]: https://www.youtube.com/watch?v=a2A_AGAnNjQ
[videoorg]: https://www.youtube.com/watch?v=8w69jLPpPXM
[videogit]: https://www.youtube.com/watch?v=Qq39mizx5kE
[issues]: https://github.com/cmda-bt/pt-course-20-21/issues/new/choose
[learnvs]: https://code.visualstudio.com/learntocode
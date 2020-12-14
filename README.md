# learn4Julia


🚨 __Important notice: This course continues BAU even after Hacktoberfest__ 🚨


You can get the benefits of Hacktoberfest while learning something new 
fascinating concepts – Functional Programming with Haskell.

And we're here to help!

* 4 Pull Request to learn to program in Julia.
* 4 Pull Request to blow your mind.

## Table of Contents

 * [What is Learn4Haskell](#what-is-learn4haskell)
    * [Course Plan](#course-plan)
 * [Goals](#goals)
 * [Who can participate](#who-can-participate)
 * [What you will get from this course](#what-you-will-get-from-this-course)
 * [How to get started](#how-to-get-started)
    * [Installing Haskell](#installing-haskell)
    * [Haskell IDE](#haskell-ide)
    * [How to develop](#how-to-develop)
 * [Who we are](#who-we-are)
 * [How can you help](#how-can-you-help)

## What is Learn4Haskell

Learn4Haskell is a GitHub-located course that will get you into the Haskell
Functional Programming world in just 4 Pull Requests.

This course is organised as a coding project. So you can complete
the course without needing to exit your editor.

This works in the following way. When you decide to start the project, all you
need to do is to fork the project. We have prepared 4 separate modules — chapters.
Each part contains educational material and lots of examples that we provide in
a simple form that doesn't require you to know anything about functional programming beforehand.
Also, each chapter contains several exercises on everything that is
explained by us. You can solve the tasks on your way and at the end open a PR to
your fork with this chapter's solution and summon us (by shouting out our
nicknames there). We would be happy to give you feedback on your progress,
explain problematic concepts or just support you mentally!

Each chapter contains unique information and covers different topics. We suggest
going through them in order. However, if you think that some of the chapters
are already familiar to you, feel free to skip onto the next one.
If you would like to talk to us, you can even rely on PRs for the chapter you
have questions about.

Chapters are stuffed with information but are aimed to be completed
without additional resources. You may spend an evening per chapter, but we swear
it's worth it!

At the end of the course, you should be able to independently create and read
basic Haskell code and understand Monads and other famous concepts of Functional
Programming.

### Course Plan

Here is a more concrete plan of the mystical 4 Chapters we prepared for
you. These are the highlights of each part.

* __Chapter One__ – What is Haskell, what are its particularities, basic Haskell
  syntax, functions, types, expressions.
* __Chapter Two__ – FP concepts in the language, immutability, pattern matching,
  recursion, polymorphism, laziness, Higher-ordered functions, partial
  applications, eta-reduction.
* __Chapter Three__ – Focus on Types. Type aliases, ADTs, Product types and
  Records, Sum types and Enumerations, Newtypes, Typeclasses.
* __Chapter Four__ – Kinds. Three monsters of functional programming: Functor, Applicative,
  Monad.

## Goals

We created the Learn4Haskell project in pursuit of the following goals:

* Help others to learn Haskell
* Give a beginner-friendly and self-consistent course with theory and practice
  in the same place
* Explain Haskell topics before each task, but strive to be concise and useful
  at the same time. It's a tough balance!
* Help people who want to participate in Hacktoberfest and Open-Source, but also
  want to learn new things during this process
* Provide review and feedback on solutions, so people are never alone in this
  challenging yet exciting journey!
* Give people who completed this course all the necessary understandings to
  be able to work with basic projects that use standard features. We also intend
  that you have a strong basis on what they should do to be able to continue their functional programming
  studies.

## Who can participate

Everyone!

We welcome everyone and would be happy to assist you in this journey!

The course is intended for people who don't know Haskell or know only language
basics, though.

If you are already an experienced Haskell developer and have come here for learning
advanced topics, this course might not be that for you. But you still can help us!
Your feedback and suggestions would be helpful for us as well as for the
language newcomers who decide to work with this course.

## What you will get from this course

This course has many benefits upon completion. Check them out to be sure that it fits
your expectations!

Participation in this course would give you:

 * 4 Pull Requests required for Hacktoberfest completion
 * Basic knowledge of the most functional programming language
 * Understanding of the functional programming concepts that you would be able to use in your
   day-to-day life afterwards
 * On-the-fly feedback and help from experienced Haskell developers and educators
 * Interesting challenges
 * Fun!

Honestly, this seems like a pretty rad deal!

## How to get started

Starting to learn Haskell with Learn4Haskell is a piece of cake!

1. [Fork this repository](https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github/fork-a-repo).
2. :warning: Add the `hacktoberfest` topic to your fork. Otherwise, [your PRs won't count](https://hacktoberfest.digitalocean.com/hacktoberfest-update).
3. Enable GitHub Actions for your forked repository.
    * Visit: https://github.com/<YOUR_GITHUB_USERNAME>/learn4haskell/actions
4. [Install the Haskell compiler](#installing-haskell).
5. Open the `src/Chapter1.hs` file, and start learning and solving tasks!
6. After you finish the first chapter (or any other chapter, or even if you are
   stuck in the middle), open
   [Pull Request](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)
   __to your fork__ with the solution and mention @vrom911 and @chshersh and we
   would be on our way for the review.
 > Note, that you should open a PR for your fork of this repo, not this repo.
 > Everyone has their solutions to the included tasks, and they don't mix together
 > well in one repo 🙂

> However, if you find some bugs or problems in this repo, you can of
> open a PR to Learn4Haskell directly. We appreciate any help and feedback!

Learn4Haskell has 4 chapters that you can walk through and submit 4 pull requests to
complete the Hacktoberfest event (or just for knowledge and your enjoyment).

So, you can start right now with forking. Following this we'll describe how you can
install all the necessary items to be able to run this course locally.

### Installing Haskell

If you're on Windows, install the `haskell-dev` and `make` packages [using Chocolatey](https://chocolatey.org/install).
```shell
choco install haskell-dev make
refreshenv
```



### How to develop

The course assumes that you install Haskell tooling (GHC and Cabal), edit code
in the corresponding chapters, run GHCi (Haskell interpreter, explained in the
course) from the root of this project and load your chapters to check your code.
Don't worry, each chapter explains all the needed information!

We also provide a Makefile with commands to test your solutions locally with the included
prepared test-suite. We have also configured the CI using GitHub
Actions on Learn4Haskell to check your answers at GitHub automatically!

To run all tests for Chapter One:

```shell
make test-chapter1
```

To run tests only for basic tasks for Chapter One (without the advanced tasks):

```shell
make test-chapter1-basic
```

Similar commands are provided for all chapters from One to Four

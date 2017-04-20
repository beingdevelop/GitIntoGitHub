<h1 align="center">Git-[Into]-GitHub!</h1>

<p align="center">
<a href="https://travis-ci.org/php-school/learn-you-php">
    <img src="https://img.shields.io/travis/php-school/learn-you-php/master.svg?style=flat-square&label=Linux">
</a>
<a href="https://ci.appveyor.com/project/AydinHassan/learn-you-php">
    <img src="https://img.shields.io/appveyor/ci/AydinHassan/learn-you-php/master.svg?style=flat-square&label=Windows">
</a>
<a href="https://codecov.io/github/php-school/learn-you-php">
    <img src="https://img.shields.io/codecov/c/github/php-school/learn-you-php.svg?style=flat-square">
</a>
<a href="https://scrutinizer-ci.com/g/php-school/learn-you-php/">
    <img src="https://img.shields.io/scrutinizer/g/php-school/learn-you-php.svg?style=flat-square">
</a>
<a href="https://phpschool-team.slack.com/messages">
    <img src="https://phpschool.herokuapp.com/badge.svg">
</a>
</p>

<p align="center">
Git, simply put, is a tool to save versions of your code.Git is the most popular version control tool - something that developers use to save all relevant versions of their work to avoid moments like those. Git also makes it easy for developers to collaborate and share work with others!
</p>
<p align="center">
<img width="700" alt="GitIntoGitHub!" src="https://www.linode.com/docs/assets/git-github-workflow-1000w.png">
</p>
Git is a software that allows you to keep track of changes made to a project over time. Git works by recording the changes you make to a project, storing those changes, then allowing you to reference them as needed.

## Table of Contents
- [Tutorials](#tutorials)
    - [OOP Fundamentals](#oop-fundamentals)
    - [OOP Advanced](#oop-advanced)
    - [Object Oriented Design](#object-oriented-design)
    - [Design Patterns](#design-patterns)
    - [Refactoring](#refactoring)
    - [Architecture](#architecture)
    - [Miscellaneous](#miscellaneous)
    - [Videos](#videos)
- [Slides](#slides)
- [Courses](#courses)
- [Books](#books)
- [Some Questions](#some-questions)

  1. [Introduction](#introduction)
  2. [Variables](#variables)
  3. [Functions](#functions)
  
  ## What is GitHub?
  
  ## Introduction
![Humorous image of software quality estimation as a count of how many expletives
you shout when reading code](https://www.linode.com/docs/assets/git-github-workflow-1000w.png)

  Software engineering principles, from Robert C. Martin's book
[*Clean Code*](https://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882),
adapted for JavaScript. This is not a style guide. It's a guide to producing
[readable, reusable, and refactorable](https://github.com/ryanmcdermott/3rs-of-software-architecture) software in JavaScript.


## **Variables**
### Use meaningful and pronounceable variable names

**Bad:**
```javascript
const yyyymmdstr = moment().format('YYYY/MM/DD');
```

**Good:**
```javascript
const currentDate = moment().format('YYYY/MM/DD');
```
**[⬆ back to top](#table-of-contents)**

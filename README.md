# WEB DEVELOPMENT ROADMAP (2022)
<!-- ============================================================================= -->
Some of the topics in this roadmap are still being updated. Thus, topics in the [Table of Contents](#table-of-contents) that have the symbol "⚠" are not fully completed.
<!-- ============================================================================= -->
## Introduction
The roadmap proposed here is meant for those that are getting started with web development and have a general interest towards it. Whether you're getting started or an experienced developer, this document can be useful to learning the topics that you need to know to be successful in web development. No previous knowledge is required. However, an open mind is appreciated as there will a lot of topics covered within this roadmap.
<!-- ============================================================================= -->
## How To Read This Document
I suggest reading this document in sequence starting from the beginning at [Understanding the Internet](#understanding-the-internet) and ending on [insert topic here](#insert-topic-here). Each topic may require background knowledge of the previous topics. If this is the case, it will be highlighted in the Prerequisite heading.

The topics covered within the roadmap will be in the following format:
1. **Prerequisite**
2. **What** is it?
3. **Why** it's important
4. **How much** I need to know
5. **Resources**
6. **Time frame**

Feel to start wherever you'd like. :)
<!-- ============================================================================= -->
## Table of Contents
  - [Understanding the Internet](#understanding-the-internet)
  - [What is front-end? ⚠](#what-is-front-end)
  - [HTML](#html)
  - [CSS](#css)
  - [JavaScript](#javascript)
  - [React (JavaScript Library)](#react-javascript-library)
  - [Redux ⚠](#redux)
  - [HTTP, HTTPS ⚠](#http-https)
  - [CORS ⚠](#cors)
  - [Git](#git)
  - [GitHub ⚠](#github)
  - [What is back-end? ⚠](#what-is-back-end)
  - [Node.js ⚠](#nodejs)
  - [Express (Node.js framework) ⚠](#express-nodejs-framework)
  - [What is a Database? ⚠](#what-is-a-database)
  - [MongoDB ⚠](#mongodb)
  - [Extended Learning ⚠](#extended-learning)
<!-- ============================================================================= -->
## Understanding the Internet
### 1. Prerequisite
N/A
### 2. What is it?
In simple terms, it is a network of computers connected together from all over the world.
### 3. Why it's important
As these computers are connected, this means that we are able to send information from one computer to another. This is important in web development because we, as web developers, develop websites and in order for someone else on another computer to see the website you built, the website has to be sent to their computer.
### 4. How much I need to know?
I've simplified the above explanation of the internet so that you can understand the main idea of the idea (which is the sending of information). IMO, the explanation in [3. Why it's important](#3-why-its-important) is enough for web development. It's not required that you know exactly how the internet infrastructure is set up or how it first got started. However, I do believe that you should come back to this and understand the internet to have a better grasp of how the internet works through the [resources](#5-resources) listed.
### 5. Resources
- The internet, explained ([https://www.vox.com/2014/6/16/18076282/the-internet][understanding-the-internet-resource-0])
- How Does the Internet Work: A Step-by-Step Pictorial ([https://www.hp.com/us-en/shop/tech-takes/how-does-the-internet-work][understanding-the-internet-resource-1])
- Internet ([https://techterms.com/definition/internet][understanding-the-internet-resource-2])
### 6. Time frame
~ 30mins

<!-- understanding the internet links -->
[understanding-the-internet-resource-0]: https://www.vox.com/2014/6/16/18076282/the-internet
[understanding-the-internet-resource-1]: https://www.hp.com/us-en/shop/tech-takes/how-does-the-internet-work
[understanding-the-internet-resource-2]: https://techterms.com/definition/internet
<!-- ============================================================================= -->
## What is front-end?
### 1. Prerequisite
N/A
### 2. What is it?
### 3. Why it's important
### 4. How much I need to know?
### 5. Resources
### 6. Time frame
<!-- ============================================================================= -->
## HTML
### 1. Prerequisite
N/A
### 2. What is it?
Think of HTML as the blueprints to a website. Whatever elements (buttons, text, lines, etc.) we want to add to a website, we use HTML to add it. It is used to describe the structure of a website. HTML stands for Hyper Text Markup Language. Hyper Text is just text with links to other websites or web pages and Markup Language is just the electronic document in a standard text-encoding system that is used to structure the website or web page.
### 3. Why it's important
As stated in [2. What is it?](2-what-is-it-1), HTML is used to describe the structure of a website. It is the standard Markup Language that is used for writing websites. Hence, it is what you will be using as well.
### 4. How much I need to know?
As this is the standard for writing websites or web pages, it is important to learn the basics and even the best practices of HTML.

***First, let's start off with the basics***. You can learn all of these from [W3Schools HTML Tutorial][html-resource-2]. You will need to learn about:
- HTML syntax
- tags
  - script (when we start using JavaScript)
- attributes
  - class (when we start using CSS)
  - id
- styles
- colour
- comments
- elements
  - head
  - body
  - headings
  - paragraphs
  - styles
  - links
  - forms
    - labels
    - input types
  - tables
  - lists

***When it comes to best practices***, there is a lot to consider, but I will only suggest the following two:
- semantic HTML / HTML semantics
- accessibility

You can learn these from [W3Schools HTML Tutorial][html-resource-2]. If you want to learn more about HTML best practices, you can check out the following link: [https://github.com/hail2u/html-best-practices][html-resource-3]

***As an addition***, I recommend learning about the DOM in using the following link [https://www.w3schools.com/js/js_htmldom.asp][html-resource-4]
### 5. Resources
**What HTML is?**
- What is HyperText ([https://www.w3.org/WhatIs.html][html-resource-0])
- Markup Language ([https://www.britannica.com/technology/markup-language][html-resource-1])

**Learning HTML**
- W3Schools HTML Tutorial ([https://www.w3schools.com/html/default.asp][html-resource-2])
- Best Practices ([https://github.com/hail2u/html-best-practices][html-resource-3])
### 6. Time frame
~ 1 week

<!-- html links -->
[html-resource-0]: https://www.w3.org/WhatIs.html
[html-resource-1]: https://www.britannica.com/technology/markup-language
[html-resource-2]: https://www.w3schools.com/html/default.asp
[html-resource-3]: https://github.com/hail2u/html-best-practices
[html-resource-4]: https://www.w3schools.com/js/js_htmldom.asp
<!-- ============================================================================= -->
## CSS
### 1. Prerequisite
N/A
### 2. What is it?
CSS is a language that is specifies how elements in an HTML document will look to the user.
### 3. Why it's important
The default presentation (styles) that elements have are plain and dull so CSS is used to style the elements on an HTML document the way you want. Styling is one the important aspects that define a user's experience on a website. Thus, CSS is critical to any website or web page.
### 4. How much I need to know?
Here, you can get away with learning the basics of CSS. However, I recommend learning the advanced techniques as well.

The basics can be learned on [W3Schools][css-resource-0]. They include the following:
- CSS syntax
- selectors
- comments
- colour
- padding
- margin
- borders
- height/width
- display

However, for the advanced techniques, and an overall better understanding of CSS, I suggest to learn from the following link [https://web.dev/learn/css/][css-resource-1]. Going through all the modules in the link will widen your perspective on the styles CSS is capable of and build a strong foundation when working on designing a website or web page.
### 5. Resources
- CSS Tutorial ([https://www.w3schools.com/css/default.asp][css-resource-0])
- Learn CSS ([https://web.dev/learn/css/][css-resource-1])
### 6. Time frame
~ 1 week to learn the basics
<br>
~ 3-4 weeks to learn the basics and advanced techniques

<!-- css links -->
[css-resource-0]: https://www.w3schools.com/css/default.asp
[css-resource-1]: https://web.dev/learn/css/
<!-- ============================================================================= -->
## JavaScript
### 1. Prerequisite
N/A
### 2. What is it?
JavaScript is the most popular programming language. It is easy to learn compared to many other programming languages. You may come across JavaScript being associated with ES5 or ES6/ES2015 (ES is short for EcmaScript). These are the version standards that JavaScript has to abide by. Meaning that EcmaScript forms the basis of JavaScript as it standardizes the language.
### 3. Why it's important
JavaScript is a programming language that is meant to be used to program the behaviour of a web page. By using JavaScript for your web page, you enable the ability to make the web page interactive. This allows users to engage with the web page by seeing a response to the actions they perform (button click, typing, etc.).
### 4. How much I need to know?
To understand more about JavaScript and EcmaScript, refer to the following link: [https://www.freecodecamp.org/news/whats-the-difference-between-javascript-and-ecmascript-cba48c73a2b5/][js-resource-0]

It is required to know what a DOM is, refer to the following link: [https://www.w3schools.com/js/js_htmldom.asp][js-resource-1]

In modern web development (using a JavaScript framework), it's not required to know how to manipulate the DOM using vanilla JavaScript. Thus, DOM manipulation with vanilla JS will not be considered here. It is required to understand the basics of a programming language using JavaScript instead. All of which can be learned using the following link: [https://www.w3schools.com/js/default.asp][js-resource-2]

It is required to understand the following: 
- JavaScript syntax
- statements
- comments
- variables
- let
- const
- operators
- arithmetic
- assignment
- data types
- functions
- arrow functions
- objects
- booleans
- conditions
- for loops
- while loops
- sets
- maps
- type conversion
- strings
- string methods
- numbers
- number methods
- arrays
- array methods
- array iteration
- date formats
- hoisting
- classes
- constructor
- this keyword
- promises
- async/await

On top of understanding the above material, I recommend learning the best practices while using JavaScript as outlined in the following link: [https://www.w3schools.com/js/js_best_practices.asp][js-resource-3]
### 5. Resources
- What’s the difference between JavaScript and ECMAScript? ([https://www.freecodecamp.org/news/whats-the-difference-between-javascript-and-ecmascript-cba48c73a2b5/][js-resource-0])
- JavaScript HTML DOM ([https://www.w3schools.com/js/js_htmldom.asp][js-resource-1])
- JavaScript Tutorial ([https://www.w3schools.com/js/default.asp][js-resource-2])
- JavaScript Best Practices ([https://www.w3schools.com/js/js_best_practices.asp][js-resource-3])
### 6. Time frame
~ 2 weeks

<!-- javascript links -->
[js-resource-0]: https://www.freecodecamp.org/news/whats-the-difference-between-javascript-and-ecmascript-cba48c73a2b5/
[js-resource-1]: https://www.w3schools.com/js/js_htmldom.asp
[js-resource-2]: https://www.w3schools.com/js/default.asp
[js-resource-3]: https://www.w3schools.com/js/js_best_practices.asp
<!-- ============================================================================= -->
## React (JavaScript Library)
### 1. Prerequisite
- JavaScript, with ES6
### 2. What is it?
React is a JavaScript library for building user interfaces. React revolves around the idea of building encapsulated components, where each component manages their own state.
### 3. Why it's important
According to StackOverflow's 2021 developer survey, React was the most commonly used web framework and is the most wanted framework as well. Aside from popularity, it makes use of reusing components and optimizing renders of the DOM by using what React calls the virtual DOM.
### 4. How much I need to know?
Up until now, it was fine using the interactive environment offered by W3Schools in their tutorials. However, I highly recommend setting up a local environment for React on your computer as it will introduce you to a tool (NPM (node package manager) or yarn) that will give you access to the vast amount of JavaScript libraries available online. To perform the set up on your computer, follow "Setup Option 2: Local Development Environment" in the following link: [https://reactjs.org/tutorial/tutorial.html#setup-for-the-tutorial][react-resource-2]

For React, it is required that you learn the "Main Concepts" as outlined on the offical React website [https://reactjs.org/docs/hello-world.html][react-resource-3]. This includes:
- JSX
- rendering elements
- components and props
- state and lifecycle (focus on function components)
- handling events
- conditional rendering
- lists and keys
- forms
- lifting state up
- composition vs inheritance
- thinking in react

There are many great resources to get started with React. I recommend learning React either by following the tutorial on the official React website [https://reactjs.org/tutorial/tutorial.html][react-resource-2] or by following along with the following video by Kent C. Dodds, creator of React Testing Library: [https://egghead.io/courses/the-beginner-s-guide-to-react][react-resource-1]
### 5. Resources
- StackOverflow's 2021 developer survey, most popular technologies ([https://insights.stackoverflow.com/survey/2021#most-popular-technologies-webframe][react-resource-0])
- The beginner's guide to React, Kent C. Dodds ([https://egghead.io/courses/the-beginner-s-guide-to-react][react-resource-1])
- Setup React Tutorial ([https://reactjs.org/tutorial/tutorial.html#setup-for-the-tutorial][react-resource-2])
- React main concepts ([https://reactjs.org/docs/hello-world.html][react-resource-3])
### 6. Time frame
~ 2 weeks

<!-- react links -->
[react-resource-0]: https://insights.stackoverflow.com/survey/2021#most-popular-technologies-webframe
[react-resource-1]: https://egghead.io/courses/the-beginner-s-guide-to-react
[react-resource-2]: https://reactjs.org/tutorial/tutorial.html#setup-for-the-tutorial
[react-resource-3]: https://reactjs.org/docs/hello-world.html
<!-- ============================================================================= -->
## Redux
### 1. Prerequisite
- React ([main concepts][react-resource-3]) 
### 2. What is it?
### 3. Why it's important
### 4. How much I need to know?
### 5. Resources
### 6. Time frame

[]:
[]:
[]:
<!-- ============================================================================= -->
## HTTP, HTTPS
### 1. Prerequisite
- React ([main concepts][react-resource-3]) 
### 2. What is it?
### 3. Why it's important
### 4. How much I need to know?
### 5. Resources
### 6. Time frame

[]:
[]:
[]:
<!-- ============================================================================= -->
## CORS
### 1. Prerequisite
- React ([main concepts][react-resource-3]) 
### 2. What is it?
### 3. Why it's important
### 4. How much I need to know?
### 5. Resources
### 6. Time frame

[]:
[]:
[]:
<!-- ============================================================================= -->
## Git
### 1. Prerequisite
- Download and install Git ([https://github.com/git-guides/install-git](https://github.com/git-guides/install-git))
### 2. What is it?
Git is a free and open source distributed [version control system][git-resource-0]. It is used to separate an application's main code from the code that will be developed for a feature or a bugfix. Once the feature or bugfix is coded, it is ready to be merged with the main code.
### 3. Why it's important
Git allows you to separate an application's main code from the code that will be developed for a feature or a bugfix. This separation of concerns allows many developers to work on the same application, at the same time. It is also used to track the changes to the code.
### 4. How much I need to know?
Git's "branching" strategy is important to know. The branching strategy starts with the application's main code. We can branch off from the application's main code, which is like creating a snapshot of the main code and with the snapshot, you can make changes to it. Git is the de facto standard when it comes to version control. Thus it is required to know how it works and some of the basics. To learn more about Git and how it works, refer to the following topics and links:
- branches ([https://www.atlassian.com/git/tutorials/using-branches][git-resource-1])
- git checkout ([https://www.atlassian.com/git/tutorials/using-branches/git-checkout][git-resource-2])
- git merge ([https://www.atlassian.com/git/tutorials/using-branches/git-merge][git-resource-3])
- merge conflicts ([https://www.atlassian.com/git/tutorials/using-branches/merge-conflicts][git-resource-4])
- syncing ([https://www.atlassian.com/git/tutorials/syncing][git-resource-5])
- git fetch ([https://www.atlassian.com/git/tutorials/syncing/git-fetch][git-resource-6])
- git push ([https://www.atlassian.com/git/tutorials/syncing/git-push][git-resource-7])
- git pull ([https://www.atlassian.com/git/tutorials/syncing/git-pull][git-resource-8])

Git is a command line tool, however, it is integrated with many IDE's to make it friendlier to use. However, I recommend learning the Git using the command line to understand the different commands that exists.

After learning the Git concepts and some of the Git commands, I recommend going through each of the sections under "Getting Started". From each of the sections, you will learn the remaining Git commands that are commonly used by many software developers. The sections are found here: [https://www.atlassian.com/git/tutorials/setting-up-a-repository][git-resource-9] and sections include:
- setting up a repository
- saving changes
- inspecting a repository
- undoing changes
- rewriting history

### 5. Resources
- branches ([https://www.atlassian.com/git/tutorials/using-branches][git-resource-1])
- git checkout ([https://www.atlassian.com/git/tutorials/using-branches/git-checkout][git-resource-2])
- git merge ([https://www.atlassian.com/git/tutorials/using-branches/git-merge][git-resource-3])
- merge conflicts ([https://www.atlassian.com/git/tutorials/using-branches/merge-conflicts][git-resource-4])
- syncing ([https://www.atlassian.com/git/tutorials/syncing][git-resource-5])
- git fetch ([https://www.atlassian.com/git/tutorials/syncing/git-fetch][git-resource-6])
- git push ([https://www.atlassian.com/git/tutorials/syncing/git-push][git-resource-7])
- git pull ([https://www.atlassian.com/git/tutorials/syncing/git-pull][git-resource-8])
### 6. Time frame
~ 1 week

[git-resource-0]: https://www.atlassian.com/git/tutorials/what-is-version-control
[git-resource-1]: https://www.atlassian.com/git/tutorials/using-branches
[git-resource-2]: https://www.atlassian.com/git/tutorials/using-branches/git-checkout
[git-resource-3]: https://www.atlassian.com/git/tutorials/using-branches/git-merge
[git-resource-4]: https://www.atlassian.com/git/tutorials/using-branches/merge-conflicts
[git-resource-5]: https://www.atlassian.com/git/tutorials/syncing
[git-resource-6]: https://www.atlassian.com/git/tutorials/syncing/git-fetch
[git-resource-7]: https://www.atlassian.com/git/tutorials/syncing/git-push
[git-resource-8]: https://www.atlassian.com/git/tutorials/syncing/git-pull
[git-resource-9]: https://www.atlassian.com/git/tutorials/setting-up-a-repository
<!-- ============================================================================= -->
## GitHub
### 1. Prerequisite
- [Git](#git)
### 2. What is it?
### 3. Why it's important
### 4. How much I need to know?
### 5. Resources
### 6. Time frame

[]:
[]:
[]:
<!-- ============================================================================= -->
## What is back-end?
### 1. Prerequisite
N/A
### 2. What is it?
### 3. Why it's important
### 4. How much I need to know?
### 5. Resources
### 6. Time frame
<!-- ============================================================================= -->
## Node.js
### 1. Prerequisite
N/A
### 2. What is it?
### 3. Why it's important
### 4. How much I need to know?
### 5. Resources
### 6. Time frame
<!-- ============================================================================= -->
## Express (Node.js framework)
### 1. Prerequisite
N/A
### 2. What is it?
### 3. Why it's important
### 4. How much I need to know?
### 5. Resources
### 6. Time frame
<!-- ============================================================================= -->
## What is a Database?
### 1. Prerequisite
N/A
### 2. What is it?
### 3. Why it's important
### 4. How much I need to know?
### 5. Resources
### 6. Time frame
<!-- ============================================================================= -->
## MongoDB
### 1. Prerequisite
N/A
### 2. What is it?
### 3. Why it's important
### 4. How much I need to know?
### 5. Resources
### 6. Time frame
<!-- ============================================================================= -->
## Extended Learning
### Frontend
### Backend
### Database

<!-- ============================================================================= -->
# SIMPLE WEB DEVELOPMENT ROADMAP (2022)
<!-- ============================================================================= -->
❗ Some of the topics in this roadmap are still being updated. Thus, topics in the [Table of Contents](#table-of-contents) that have the symbol "⚠" are not fully completed.
<!-- ============================================================================= -->
## Introduction
The roadmap proposed here is meant for those that are getting started with web development and have a general interest towards it. Whether you're getting started or an experienced developer, this document can be useful to learning the topics that you need to know to be successful in web development. No previous knowledge is required. However, an open mind is appreciated as there will a lot of topics covered within this roadmap.
<!-- ============================================================================= -->
## How To Read This Document
I suggest reading this document in sequence starting from the beginning at [Understanding the Internet](#understanding-the-internet) and ending on [What is a Database?](#what-is-a-database). Each topic may require background knowledge of the previous topics. If this is the case, it will be highlighted in the Prerequisite heading.

The topics covered within the roadmap will be in the following format:
1. **Prerequisite**
2. **What** is it?
3. **Why** it's important
4. **How much** I need to know
5. **Resources** (links that were mentioned in the topic or to learn more about it)
6. **Time frame**

Feel to start wherever you'd like. :)
<!-- ============================================================================= -->
## Table of Contents
  - [Understanding the Internet](#understanding-the-internet)
  - [What is frontend?](#what-is-frontend)
    - [HTML](#html)
    - [CSS](#css)
    - [JavaScript](#javascript)
    - [React (JavaScript Library)](#react-javascript-library)
    - [Redux, Redux Toolkit](#redux-redux-toolkit)
    - [HTTP, HTTPS](#http-https)
    - [CORS](#cors)
  - [Git](#git)
  - [GitHub](#github)
  - [What is backend?](#what-is-backend)
    - [Node.js](#nodejs)
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
## What is frontend?
### 1. Prerequisite
- [Understanding the Internet](#understanding-the-internet)
### 2. What is it?
Frontend is the information that a user sees when they access a website. During the process that a user enters a url to a website, another computer sends back information (I will be skipping DNS in this example, to simplify the explanation) in the form of HTML, CSS, and JavaScript. This information is understood by the browser to display the the exact layout and design the web developer intends the website page to be displayed.
### 3. Why it's important
As the frontend is what the user will see, and as per the explanation in [What is it?](#2-what-is-it-1), it is thus required to know HTML, CSS, and JavaScript (with a JavaScript library/framework such as React, Angular, or Vue).
### 4. How much I need to know?
This may vary with every person, but in this roadmap, I give an outline of a path and what I believe should be known in each of the topics for a frontend developer.
### 5. Resources
- [HTML](#html)
- [CSS](#css)
- [JavaScript](#javascript)
- [React](#react-javascript-library)
- [Redux, Redux Toolkit](#redux-redux-toolkit)
- [HTTP, HTTPS](#http-https)
- [CORS](#cors)
### 6. Time frame
N/A
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
- [JavaScript](#javascript), with ES6
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

As an addition, React introduces an idea of a [virtual DOM][react-resource-4]. I would also suggest learning this as well.

There are many great resources to get started with React. I recommend learning React either by following the tutorial on the official React website [https://reactjs.org/tutorial/tutorial.html][react-resource-2] or by following along with the following video by Kent C. Dodds, creator of React Testing Library: [https://egghead.io/courses/the-beginner-s-guide-to-react][react-resource-1]
### 5. Resources
- StackOverflow's 2021 developer survey, most popular technologies ([https://insights.stackoverflow.com/survey/2021#most-popular-technologies-webframe][react-resource-0])
- The beginner's guide to React, Kent C. Dodds ([https://egghead.io/courses/the-beginner-s-guide-to-react][react-resource-1])
- Setup React Tutorial ([https://reactjs.org/tutorial/tutorial.html#setup-for-the-tutorial][react-resource-2])
- React main concepts ([https://reactjs.org/docs/hello-world.html][react-resource-3])
- React Virtual DOM ([https://reactjs.org/docs/faq-internals.html#:~:text=The%20virtual%20DOM%20(VDOM)%20is,This%20process%20is%20called%20reconciliation.&text=They%20may%20also%20be%20considered,virtual%20DOM%E2%80%9D%20implementation%20in%20React.][react-resource-4])
### 6. Time frame
~ 2 weeks

<!-- react links -->
[react-resource-0]: https://insights.stackoverflow.com/survey/2021#most-popular-technologies-webframe
[react-resource-1]: https://egghead.io/courses/the-beginner-s-guide-to-react
[react-resource-2]: https://reactjs.org/tutorial/tutorial.html#setup-for-the-tutorial
[react-resource-3]: https://reactjs.org/docs/hello-world.html
[react-resource-4]: https://reactjs.org/docs/faq-internals.html#:~:text=The%20virtual%20DOM%20(VDOM)%20is,This%20process%20is%20called%20reconciliation.&text=They%20may%20also%20be%20considered,virtual%20DOM%E2%80%9D%20implementation%20in%20React.
<!-- ============================================================================= -->
## Redux, Redux Toolkit
### 1. Prerequisite
- React ([main concepts][react-resource-3])
### 2. What is it?
Redux is a *predictable* state container. It is used in React development to maintain states between different components. Redux Toolkit, a library for writing Redux, is the recommended approach to writing Redux logic.
### 3. Why it's important
As React applications become more complex, a state container allows certain states to persist throughout the application. Often, state is usually contained within the component, and when the component is taken down from the DOM, the state is lost. With Redux, we can maintain the state inside a container and modify it preditably with predefined "actions".
### 4. How much I need to know?
To get started with Redux, I suggest reading the following link to get an introduction into using Redux and Redux Toolkit ([https://redux.js.org/introduction/getting-started][redux-resource-0]).

For an overview of Redux, refer to the following link: [(https://redux.js.org/tutorials/fundamentals/part-1-overview)][redux-resource-1]

At the core of Redux, you must understand its ideas:
- state
- actions
- dispatch
- reducers
- selectors
- store

The following resources below can be used to understand the ideas outlined above:
- [https://redux.js.org/tutorials/fundamentals/part-2-concepts-data-flow][redux-resource-2]
- [https://redux.js.org/tutorials/fundamentals/part-3-state-actions-reducers][redux-resource-3]
- [https://redux.js.org/tutorials/fundamentals/part-4-store][redux-resource-4]
### 5. Resources
- Getting Started with Redux ([https://redux.js.org/introduction/getting-started][redux-resource-0])
- Redux Overview ([https://redux.js.org/tutorials/fundamentals/part-1-overview][redux-resource-1])
- Concepts and data flow ([https://redux.js.org/tutorials/fundamentals/part-2-concepts-data-flow][redux-resource-2])
- State, Actions, and Reducers ([https://redux.js.org/tutorials/fundamentals/part-3-state-actions-reducers][redux-resource-3])
- Redux Store ([https://redux.js.org/tutorials/fundamentals/part-4-store][redux-resource-4])
### 6. Time frame
~ 1 week

[redux-resource-0]: https://redux.js.org/introduction/getting-started
[redux-resource-1]: https://redux.js.org/tutorials/fundamentals/part-1-overview
[redux-resource-2]: https://redux.js.org/tutorials/fundamentals/part-2-concepts-data-flow
[redux-resource-3]: https://redux.js.org/tutorials/fundamentals/part-3-state-actions-reducers
[redux-resource-4]: https://redux.js.org/tutorials/fundamentals/part-4-store
<!-- ============================================================================= -->
## HTTP, HTTPS
### 1. Prerequisite
- [Understanding the Internet](#understanding-the-internet)
### 2. What is it?
HTTP is an application-layer protocol for sending hypermedia documents, such as HTML, over the network. We can also send information in the form of XML or JSON, and media types such as images or videos.

HTTPS is the same as HTTP, with the addition that the data that is sent is being encrypted using a public key and decrypted using a private key. 
### 3. Why it's important
HTTP is the protocol that is widely used to send information between a client and a server. It standardizes the format the information should be sent during a client and server interaction.

HTTPS, on the other hand, prevents the information that is sent to be seen in plain text by hackers intercepting the information that is being sent. Instead, they will see an encrypted message used with the public key and only the server will be able to decrypt this message as they will have the private key.
### 4. How much I need to know?
With HTTP, It is required to know the basics, which includes:
- HTTP request
  - HTTP method
  - url
  - headers
  - version of the HTTP protocol
  - optional request body
- HTTP response
  - status code
  - status message
  - headers
  - version of the HTTP protocol
  - optional response body

It is also required to know the aspects of HTTP, which includes:
- HTTP is simple
- HTTP is extensible
- HTTP is stateless, but not sessionless
- HTTP and connections

All of the above can be learned from the following link: [https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview][http-https-resource-0]

When it comes to HTTPS, I recommend understanding the encryption technique used. You can find out more about that in the following link: [https://www.cloudflare.com/en-ca/learning/ssl/how-does-public-key-encryption-work/][http-https-resource-1]
### 5. Resources
- An overview of HTTP ([https://developer.mozilla.org/en-US/docs/Web/HTTP][http-https-resource-0])
- How does public key encryption work? ([https://www.cloudflare.com/en-ca/learning/ssl/how-does-public-key-encryption-work/][http-https-resource-1])
### 6. Time frame
~ 2 day

[http-https-resource-0]: https://developer.mozilla.org/en-US/docs/Web/HTTP
[http-https-resource-1]: https://www.cloudflare.com/en-ca/learning/ssl/how-does-public-key-encryption-work/
<!-- ============================================================================= -->
## CORS
### 1. Prerequisite
- [HTTP](#http-https)
### 2. What is it?
Cross origin resource sharing (CORS) uses HTTP headers to indicate which origins () can access the server.
### 3. Why it's important
By default (due to security reasons), browsers do not permit the use of other resources from other origins other than its own (website.com/frontend must call website.com/backend, cannot call websites.com/backend). However, by specifying a specific header in the client response with the value of the client's origin, we allow the server resource to be used by the client's origin.
### 4. How much I need to know?
There isn't much to know about CORS. However, if the above explanation doesn't cut it for you, the following YouTube video by WebDevSimplified does a good job showing you how it works: [https://www.youtube.com/watch?v=PNtFSVU-YTI][cors-resource-1]

If you want learn more about CORS, refer to the following link: [https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS][cors-resource-0]
### 5. Resources
- Cross-Origin Resource Sharing (CORS) ([https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS][cors-resource-0])
- WebDevSimplified Learn CORS In 6 Minutes ([https://www.youtube.com/watch?v=PNtFSVU-YTI][cors-resource-1])
### 6. Time frame
~ 1 hour

[cors-resource-0]: https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS
[cors-resource-1]: https://www.youtube.com/watch?v=PNtFSVU-YTI
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
GitHub is a platform that can be used as a repository for the code that you write. How do you add the code you write from your computer to GitHub? With Git. A repository is nothing but a folder on GitHub that contains all the files for your application.
### 3. Why it's important
GitHub is free to use and is widely used in open-source projects. It is also easy to use and contains many other tools like hosting with GitHub Pages, sharing code snippets with Git Gist, or continuous integration workflows with GitHub Actions.
### 4. How much I need to know?
Knowing how to setup your code repo with GitHub is a must. However, we must setup Git with GitHub. You can use the following to learn how: [https://docs.github.com/en/get-started/quickstart/set-up-git][github-resource-0]. The setup will include authentication with GitHub from Git. There will be two approaches: connecting over HTTPS (recommended by GitHub) and connecting over SSH. Either approach is fine.

- Setting authentication (HTTPS): [https://docs.github.com/en/get-started/getting-started-with-git/caching-your-github-credentials-in-git][github-resource-1]
- Setting authentication (SSH):  [https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent][github-resource-2]

Once Git has been setup, you're now ready to create a repository and add your code to it. You can learn how to do that with the following link: [https://docs.github.com/en/get-started/importing-your-projects-to-github/importing-source-code-to-github/adding-an-existing-project-to-github-using-the-command-line][github-resource-3].

This is also where you need to know common Git commands such as:
- `git add` ([https://www.atlassian.com/git/tutorials/saving-changes#:~:text=The%20git%20add%20command%20adds,until%20you%20run%20git%20commit%20.][github-resource-4])
- `git commit` ([https://www.atlassian.com/git/tutorials/saving-changes/git-commit][github-resource-5])
### 5. Resources
- Set up Git ([https://docs.github.com/en/get-started/quickstart/set-up-git][github-resource-0])
- GitHub CLI ([https://docs.github.com/en/get-started/getting-started-with-git/caching-your-github-credentials-in-git][github-resource-1])
- Generating a new SSH key and adding it to the ssh-agent ([https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent][github-resource-2])
- Adding an existing project to GitHub using the command line ([https://docs.github.com/en/get-started/importing-your-projects-to-github/importing-source-code-to-github/adding-an-existing-project-to-github-using-the-command-line][github-resource-3])
- Saving changes ([https://www.atlassian.com/git/tutorials/saving-changes#:~:text=The%20git%20add%20command%20adds,until%20you%20run%20git%20commit%20.][github-resource-4])
- Git commit ([https://www.atlassian.com/git/tutorials/saving-changes/git-commit][github-resource-5])
### 6. Time frame
~ 3 days

[github-resource-0]: https://docs.github.com/en/get-started/quickstart/set-up-git
[github-resource-1]: https://docs.github.com/en/get-started/getting-started-with-git/caching-your-github-credentials-in-git
[github-resource-2]: https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent
[github-resource-3]: https://docs.github.com/en/get-started/importing-your-projects-to-github/importing-source-code-to-github/adding-an-existing-project-to-github-using-the-command-line
[github-resource-4]: https://www.atlassian.com/git/tutorials/saving-changes#:~:text=The%20git%20add%20command%20adds,until%20you%20run%20git%20commit%20.
[github-resource-5]: https://www.atlassian.com/git/tutorials/saving-changes/git-commit
<!-- ============================================================================= -->
## What is backend?
### 1. Prerequisite
- [Understanding the Internet](#understanding-the-internet)
### 2. What is it?
Backend is the place where information is being saved or information is being accessed (from database(s) or from APIs). As backend code does not have an interface for users to see, users will not be seeing this on their browsers at all.
### 3. Why it's important
As mentioned, the backend is the place where information is being saved or information is being accessed (from database(s) or from APIs). This information is then passed to the frontend to be used.

Knowing what the backend is capable of also allows us to separate concerns from the frontend, hence why many job postings mention "frontend" or "backend" or even "fullstack" (knowing both frontend and backend) engineers.
### 4. How much I need to know?
This may vary with every person, but in this roadmap, I give an outline of a path with the minimum requirements of what I believe should be known for a backend developer.
### 5. Resources
- [Node.js](#nodejs)
- [Express (Node.js framework)](#express-nodejs-framework)
### 6. Time frame
<!-- ============================================================================= -->
## Node.js
### 1. Prerequisite
- [JavaScript](#javascript)
### 2. What is it?
In the simplest explanation, Node.js is a JavaScript runtime environment used to read JavaScript code on the backend. Node.js allows code that is written in JavaScript to run on the server.
### 3. Why it's important
JavaScript normally cannot run without a browser, but with Node.js, it is possible. Not only that, but JavaScript is a simple programming language and gives a friendly introduction to backend development when starting with web development or coming from frontend development.
### 4. How much I need to know?
If you have npm on your computer, you already node installed. However, if this is not the case, you can install it [here][nodejs-resource-1] and click the one labeled LTS (Long term support).

Although I've given a simple explanation of Node.js, the specifics about the runtime environment must be understood to use Node.js to its full potential. Thus it is required to understand the following concepts of Node.js:
- single threaded
- asynchronous and event-driven

The above can be learned using the following link: [https://www.infoworld.com/article/3210589/what-is-nodejs-javascript-runtime-explained.html][nodejs-resource-0]

To learn the capabilities of Node.js, I recommend following the all the modules outlined in the following link. It covers many of the important modules such as `fs`, `path`, `os`, `events`, and `http`, as well as understanding `process.nextTick()`, buffers and streams: [https://nodejs.dev/learn](nodejs-resource-2)

### 5. Resources
- Node installation ([https://nodejs.org/en/][nodejs-resource-1])
- What is Node.js? The JavaScript runtime explained ([https://www.infoworld.com/article/3210589/what-is-nodejs-javascript-runtime-explained.html][nodejs-resource-0])
- Introduction to Node.js ([https://nodejs.dev/learn][nodejs-resource-2])
### 6. Time frame
~ 2 weeks

[nodejs-resource-0]: https://www.infoworld.com/article/3210589/what-is-nodejs-javascript-runtime-explained.html
[nodejs-resource-1]: https://nodejs.org/en/
[nodejs-resource-2]: https://nodejs.dev/learn
<!-- ============================================================================= -->
## Express (Node.js framework)
### 1. Prerequisite
- [Node.js](#nodejs)
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
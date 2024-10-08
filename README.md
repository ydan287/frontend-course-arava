## Abstract

Welcome to our exciting and engaging 10-step program for aspiring front-end developers! This course is designed to be self-paced and hands-on, allowing you to build the same application multiple times, each time incorporating new and advanced technologies. You'll start with basic vanilla JavaScript and gradually move on to creating a simple server and integrating a database.

Throughout the program, you'll acquire essential skills in JavaScript, server-side development, and database management. Additionally, you'll learn best practices for code reviews and continuous integration.

You'll also learn how to deploy your applications to production using services like GitHub Pages. 

By the end of the program, you'll have a fully deployed, professional-looking web application to showcase in your portfolio, giving you a great start in your web development career.

## How to work with this repo (READ ME!)

1. You should fork this repo into a **private** repo and start working on the steps. The folder structure should look something like this:
```plaintext
project-root/
├── 01-vanillaJs/
├── 02-webpack/
├── 03-local-storage/
├── 04-cookies/
├── 05-event-loop/
├── 06-bind/
├── 07-hoisting/
├── 08-server/
├── 09-database/
├── 10-crud/
├── 11-deployment/
├── 12-ci-cd/
└── 13-final-project/
```

1. All commits should be done as a PR. This is important so the mentor can do code review even after the fact (after a PR was merged so it won't block the trainee) 
2. After each step is completed the mentor should do the most comperhensive and harsh code review they can possibly do. The success of this program is mostly relies on good and teaching code reviews. 
3. After each code review the trainee is expected to fix all comments.
4. You should advance to the next step only after all the code review rejects has been fixed. In case the trainee is blocked by the mentor they should fill their time by learning and gaining more knowledge either by reading / watching videos / practicing coding challenges / etc.. ideas can be found [here](##deadtime-tasks)

## Dev Enviroment (installations for MAC)
* Git - create a github user and fork this repo.
* Node
* Home-brew
* IDE vscode
* ZSH
* Oh my zsh
* Iterm2 ow warp

## Dev Enviroment (installations for Widnows)
* follow this [guide](https://learn.microsoft.com/en-us/windows/web/#wsl-terminal-package-manager-docker-desktop)
* Git - create a github user and fork this repo.
* Node
* Home-brew
* IDE vscode
* Warp

## Deadtime tasks

Coding games and Katas:
* https://www.codewars.com/
An online programing game (I didn't do that.. if u do plz let me know how was it)
* https://adventofcode.com/
* https://alexnisnevich.github.io/untrusted/
* https://screeps.com/
* https://www.codingame.com
* read everythign u can in mdn****

YouTube:

If you're into videos, you can and should subscribe to some of these youtube channels. Just look for an interesting talk and watch as you learn:

* [How the event loop works](https://www.youtube.com/watch?v=8aGhZQkoFbQ) A must watch for any FED
* [Sergey's "Must watch list"](https://github.com/bolshchikov/js-must-watch)
* [JS Conf](https://www.youtube.com/user/jsconfeu/videos?view=0&sort=dd&flow=list&live_view=500) (probably the biggest js conf)
* Nice dude that explains design patterns and features in a fun way. [link](https://www.youtube.com/channel/UCO1cgjhGzsSYb1rsB4bFe4Q/videos)
* [React Europe](https://www.youtube.com/channel/UCorlLn2oZfgOJ-FUcF2eZ1A)


## Step 1: 
Your first task will be to write a simple todo app.  For now it will be client only. You can only use html, vanilla js and css (no other lib like react/angular/lodash/jquery are allowed).

The app should support:
* Adding a new todo item
* Editing an existing todo item
* Deleting a todo item
* Showing the list of all todo items
* Mark a todo item as done.

To achieve it you will need to learn:
* Flex layout in css 
  * https://flexboxfroggy.com/
  * http://www.flexboxdefense.com/
  * https://flukeout.github.io/
* what is the dom (document object model)
* js dom manipulation 
* html syntax

You can find a lot of information about each of these items. Remember to always read the manual on the mdn site (Mozilla developer network) and not w3c school.

Videos that I want you to watch in this step:
* [What the heck is the event loop anyway?](https://www.youtube.com/watch?v=8aGhZQkoFbQ)

## Step 2 (Deadline - DD/MM)

To learn:
* Webpack
* [Build your own Webpack](https://www.youtube.com/watch?v=a1HS3-YkJnY)
* Localstorage 
* Cookies
* Localstorage vs cookies
* What are the differences between LS and cookies
    * When should we use LS and when should we use cookies
    * What are the different types of cookies
* Bind
* Hoisting

With the mentor
* [Bind exercise](https://jsbin.com/kenayubile/edit?js,console)
* Hoisting exercise - TBD

Todo:
* Use localstorage to save the todos - refresh should not lose the todos
* Use webpack as your bundler

## Step 3 (Deadline - DD/MM)

To learn:
* Semver - read all about it
* Source map loader vs devtool
* Chrome debugger
* Prototype (read about prototypical inheritance) 

Todo:
* Add source maps to your project
* Change css to be jss (css inside js)

With the mentor:
* [Currying](https://jsbin.com/dumiyakoko/edit?js,console)

## Step 4 (Deadline - DD/MM)

Learn about:
* Http protocol
  * 1 way communication
  * http methods
  * Https
* Learn what is private/public key (RSA)
* Web socket protocol
* Server + express
    * Learn about express library
* Fetch API
  * Read [this blogpost](https://shahata.medium.com/why-i-wont-be-using-fetch-api-in-my-apps-6900e6c6fe78)

Todo:

Write the todo app again, this time with a server. The server should hold the todos in its memory (no need for localstorage). Use webpack, XHR
Use axios, 

## Step 5 (Deadline - DD/MM) - Look mommy I’ve written an actual piece of software you can actually use!

Todo:

* Install "edit this cookie" extension
* Make it a server for “everyone” (cookies and userIds, HTTP cookie)
* Push to heroku
* Use free redis [add-on](https://elements.heroku.com/addons/heroku-redis), Mongo atlas or any other db preference


## Step 6 (Deadline - DD/MM)
To learn:
* Typescript

Todo:
* Typescript everything from scratch

## Step 7 (Deadline - DD/MM)
To learn:
* Signed vs Encrypted
* JWT
* Symmetric vs asymmetric encryption
  * Using asymmetric to exchange symmetric keys
  * Read about pros & cons of symmetric vs asymmetric

Todo:

In this step you can use the app from the previous step.
* replace your cookie with a JWT cookie
* login/logout - design in a sequence diagram (learn about sequence diagram as well if you don’t know what this is)


## Step 8 (Deadline - DD/MM) - Welcome to React!
To learn:
* React - do the [getting started tutorial](https://reactjs.org/tutorial/tutorial.html) (only in case you don't know react)
* Learn about hooks

Todo:
Write the todo app from scratch with React.

## Step 9 (Deadline - DD/MM) - Testing!

To Learn: TDD - [watch](https://www.youtube.com/watch?v=Jv2uxzhPFl4)
Todo:

* React tests using jest
* React-testing-library 
* At least 1 e2e test using puppeteer

## Step 10 (Deadline - DD/MM) - Final Project!! Welcome to Wix!
In the final project the Student will choose design and implement its own app for his portfolio with the teachers assistance and consult.
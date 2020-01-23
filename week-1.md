# Week 1 

> Always bet on JavaScript.
>
> — [**@BrendanEich**][quote-author]

[![][inspiration-cover]][inspiration-link]

> Visualisation of npm dependencies by [**@anvaka**][inspiration-author].

## Table of Contents

*  [Slides](#slides)
*  [Theory](#theory)
*  [Playground](#playground)
*  [Assignments](#assignments)
*  [Hand in](#hand-in)

## Slides
* Lecture-1
* Lab-1

## Theory
Before you start you'll probably want to read a bit about **Node,** the **JavaScript engine,** and **client vs. server-side**. We'll cover this in the lecture but make sure you fully understand these concept, the resources below can help.

* [_Introduction to Node.js_][intro-node]
* [_Differences between Node.js and the Browser_][node-browser]
* [_The V8 JavaScript engine_][v8-engine]
* [_The Fundamentals - Server Side_][syntax]
* [_The JavaScript engine visualized_][visual]

[🎦 _Watch a video_ about the browser versus Node.js.][videonode]  
[🎦 _Watch a video_ about Modules.][videomodule]

## Playground
You can do these exercises before you start working on the assignments to get comfortable with the topics covered in class. The below workshoppers are interactive, self guided lesson modules, from [NodeSchool][nodeschool].

* [Learn the basics of Node (workshopper)](https://github.com/workshopper/learnyounode)
* [How to NPM (workshopper)](https://github.com/workshopper/how-to-npm)
* [The basics of Express.js (workshopper)](https://github.com/azat-co/expressworks)
* [freeCodeCamp - Managing Packages with NPM (exercises)](https://www.freecodecamp.org/learn)
* [freeCodeCamp - Basic Node and Express (exercises)](https://www.freecodecamp.org/learn)

## Assignments

### Package
![Package Banner](/assets/banners/package.jpg)
>Learn the basics of node modules and npm packages and setup a boilerplate for your own feature.


#### Synopsis

*  **Time**: 4:00h
*  **Goals**: subgoal 1, subgoal 2
*  **Due**: before week 2

1. Create the boilerplate for the node app you are going to create. Include a `package.json` with a correct name, version, dependencies, and other metadata. See npm’s documentation on [`package.json`](https://docs.npmjs.com/files/package.json).
For examples of `package.json` files, see
[`repeat-string`](https://github.com/jonschlinkert/repeat-string/blob/master/package.json),
[`longest-streak`](https://github.com/wooorm/longest-streak/blob/master/package.json),
or [`skin-tone`](https://github.com/sindresorhus/skin-tone/blob/master/package.json).

2. Look trough the NPM registry and install a package from [npm][npmjs] that would be helpful for your job story and try it out in `index.js`. Not sure what package to pick? You can try playing around with [`camelcase`][camelcase] or [`lodash`][lodash] to get comfortable requiring packages and using them.

3. Improve the _developer experience_ of your application. Look for so called 'developer dependencies' on NPM. [`nodemon`](https://nodemon.io/) is a good example, it will monitor for any changes in your source and automatically restart your server. Perfect for development.

4. Create some [`run scripts`](https://docs.npmjs.com/misc/scripts) in your `package.json` to **start**, **serve** or **build** your application.

**Ask yourself upon completion:**
* How does  `require` work under the hood?
* What's the difference between `dependencies` and `devDependencies`?
* What are the differences between `global` and `local` dependencies?
* What tasks can you run with `npm run scripts`?

**Additional resources**
* [Introduction to NPM Scripts][intro-npm]
* [Npm global or local packages][global]

[🎦 _Watch a video_ about Node Packages.][videopackage]  
[🎦 _Watch a demo_ about NPM.][videonpm]   

### Serve

![Hello World Server banner](/assets/banners/serve.jpg)
> In this assignment you’ll build a static file server with a little help from Express.

#### Synopsis

*  **Time**: 4:00h
*  **Goals**: subgoal 1, subgoal 2
*  **Due**: before week 2

#### Description
Create a server that handles routes and serves static files in Node.js. Feel free to write your server from scratch if you feel adventurous, otherwise [`express`](https://expressjs.com/) is your best option.

*   Have a couple of different `routes` (e.g. `/about` `/contact`)
*   Respond with a `404 Not Found` if you go to a route that doesn't exist.
*   Serve `static files` such as JavaScript and CSS but also media files such as images

**Ask yourself upon completion:**
* How does the `app instance` work? What makes it possible you can do things like `app.get` or `app.listen`?
* What are the `req` and `res` parameters?
* The confusing part is that your laptop is both the client and the server. It's a `local development` environment.

**Additional resources**
* [Basic Routing](https://expressjs.com/en/starter/basic-routing.html)
* [Static Files](https://expressjs.com/en/starter/static-files.html)

## Hand-in

1. **Push your changes:**  
Hand in your progess in your repository on GitHub under your username.

1. **Create an issue:**  
Mark this assignment as complete by opening an issue on our [GitHub issue tracker][issues]. Fill in the issue template with the correct information. Include what you did in the description of the issue.

1. **Feedback:**  
Let us know what you thought of the homework, what part you spend a lot of time on and give us any feedback. Your project will be reviewed and receive feedback, so expect people to read it, and be ready for tips and tops!

[quote-author]: https://twitter.com/BrendanEich
[inspiration-cover]: assets/images/npmgraph.png
[inspiration-link]: http://npm.anvaka.com/#/view/2d/express
[inspiration-author]: https://github.com/anvaka

[intro-node]: https://nodejs.dev/introduction-to-nodejs
[node-browser]: https://nodejs.dev/differences-between-nodejs-and-the-browser
[v8-engine]: https://nodejs.dev/the-v8-javascript-engine
[npm]: https://nodejs.dev/an-introduction-to-the-npm-package-manager

[npmjs]: https://www.npmjs.com/
[camelcase]: https://www.npmjs.com/package/camelcase
[lodash]: https://www.npmjs.com/package/lodash
[nodeschool]: https://nodeschool.io/
[intro-npm]: https://www.freecodecamp.org/news/introduction-to-npm-scripts-1dbb2ae01633/
[global]: https://nodejs.dev/npm-global-or-local-packages
[issues]: https://github.com/cmda-bt/be-course-18-19/issues/new/choose
[visual]: https://dev.to/lydiahallie/javascript-visualized-the-javascript-engine-4cdf
[syntax]: https://syntax.fm/show/188/the-fundamentals-server-side

[videonode]: https://www.youtube.com/watch?v=HAE-iYJ8_14
[videopackage]: https://www.youtube.com/watch?v=jgtXhdxVisw
[videomodule]: https://www.youtube.com/watch?v=t64md6HAztU
[videonpm]: https://www.youtube.com/watch?v=tdqXTNqNrr0


# HTML5 Boot Camp

## The future of Web Applications is here!

Are you ready for it?

### **Index**

1. [Objective](#objective)

2. [Who Should Attend](#who-should-attend)

3. [Duration](#duration)

4. [Technical Assistance](#technical-assistance)

5. [Performance Measurement](#performance-measurement)

6. [Handling advanced Developers](#handling-advanced-developers)

7. [Tools](#tools)

8. [General Guidelines](#general-guidelines)

9. [Learning Days](#learning-days)

    * [Topic 0: HTML & CSS Basics](#topic0)

    * [Topic 1: JavaScript, and DOM APIs](#topic1)

    * [Topic 2: OOP and Inheritance in JavaScript](#topic2)

    * [Topic 3: HTML5 APIs](#topic3)

    * [Topic 4: UI - ReactJS](#topic4)

    * [Topic 5: MVC - AngularJS](#topic5)


10. [Your First Project Starts Now](#your-first-project-starts-now)
11. [Moving Forward](#forward)

### **Objective**

This course teaches the basics of modern Web UI development.
We want to help you create the best of breed user experiences, gaming, and mobile applications.

→ [index](#index)

### **Who Should Attend**

The training will start at a low level, and does not require in depth knowledge of the platform in question.
Desirable participant profile: trainees and outside Globant candidates.
A basic knowledge on HTML, CSS, and JavaScript is desired, though.

→ [index](#index)

### **Duration**

Four/five weeks total.

Three weeks for guided learning and one/two weeks for app development.

→ [index](#index)

### **Technical Assistance**

You can contact other bootcamp participants or any available tutor if you need technical assistance.
We will create one chat for bootcamp members only, and another one for bootcamp members and tutors when bootcamp starts.

### **Performance Measurement**

1.  Code reviews after each practice and sprint

2.  Checkpoint completion after Learning stage with your assigned tutor

→ [index](#index)


### **Handling Advanced Developers**

Developers that move faster than average can go ahead and complete as much exercises as they want.

→ [index](#index)

### **Tools**

1.  At least, three different browsers installed on the developer machine. As Example:

    *   Chrome
    *   Firefox
    *   Android browser using Android's emulator


2.  Any IDE available for Web Development.

    *   [Atom](https://atom.io/)
    *   [Visual Studio Code](https://code.visualstudio.com/)
    *   [SublimeText](http://www.sublimetext.com/)

3.  Google Hangouts for calls. Skype might be required too.

4.  Create your own [GitHub](https://github.com/) account. Follow this [guideline](https://help.github.com/articles/set-up-git) to setup your account.

5.  [NodeJS](http://nodejs.org/).

6.  NodeJS server.

    *   Install `http-server` globally, by running `npm install -g http-server`.
    *   To start the server, from a command line interface, run `http-server` in the directory where you will clone the startup repo.
    *   Open your web browser and point to localhost:PORT (the `http-server` should have outputted the number of PORT you should use)

7.  Fork [Startup repository](https://github.com/globant-ui/startup) to use as a base to host the project code.

→ [index](#index)

### **General Guidelines**

The boot camp is organized in the following way:

1.  The first three weeks will be used for intensive self learning.
    Each topic will have reading and practices parts.
    Tutors will be available to answer technical questions.

2.  The next week will be used to develop an application following a life process.

3.  All the exercises must work within a mobile environment.

4.  Team play is encouraged but the work might be evaluated per person (depending on number of bootcamp students).

5.  All code and documentation must be in English.

6.  Code must adhere to Globant’s UI [HTML](https://github.com/globant-ui/html-style-guide), [CSS](https://github.com/globant-ui/css-style-guide) and [JavaScript](https://github.com/globant-ui/JavaScript-style-guide) coding guidelines.

→ [index](#index)

### **Learning Days**

Each day you will grab the fundamentals of the key building blocks for the next generation mobile apps: yeah, web apps! Web apps powered by the latest, and coolest toolkits, and techniques.

On each learning day you will have to:

1.  **Read:** We will provide you with documentation related with current sprint content so you can have a background reference, guide and examples to complete the following practice.

2.  **Practice:** You will implement the previously gathered knowledge in simple coding activities.
    Most important task numbers are listed in the "*Key Points*" section for each day and they should get most of your attention.
    If you feel you don’t have enough time to complete all tasks, start with these ones when possible.

3.  **Commit:** You will commit all your code as soon as you finish each exercise. If not you must commit your work in a daily basis.

#### **Introduction**

At high level you could see the keys as:

![technologies logos](assets/html5-css-javascript.png "The platform")

HTML describes the content semantics and structure of a web page. It was designed as a markup language, if you know XML, you could consider HTML as a subset of XML with a predefined semantic.

On the other hand, CSS allows to define the look and feel of the content. It's used to set colors on HTML elements, customize sizes, define the layout of the document content, among others. (e.x. "The following list of elements must be shown as a menu", "The main title of the page should use this particular font").

JavaScript is a programming language that runs in all Web Browsers. Using JavaScript we can create full-fledge web applications.

Now that you know which are the three pilars of a web application's UI, it's time to dive into them.

<h4 id="topic0">Topic 0 - HTML & CSS Basics</h4>

This topic is hosted in a different repository, you can find it in [HTML & CSS Basics](https://github.com/globant-ui/css-lab)

→ [index](#index)

<h4 id="topic1">Topic 1 - JavaScript, and DOM APIs</h4>

**Reading**

1.  Beginner: Eloquent JavaScript 2nd Edition [basic tutorial](https://eloquentjavascript.net/) (in case you need it!)

2.  Beginner to advance: [Speaking JavaScript: An In-Depth Guide for Programmers](http://speakingjs.com/)

3.  Recommended: [devdocs.io](https://devdocs.io/) to check Web platform documentation around JavaScript, frameworks, Browser APIs, etc

**Extra documentation**

*   MDN JavaScript Reference: [https://developer.mozilla.org/en/JavaScript/Reference](https://developer.mozilla.org/en/JavaScript/Reference)

*   Web Platform Documentation Project: [https://webplatform.github.io/](https://webplatform.github.io/)

*   Understanding ECMAScript 6: [https://leanpub.com/understandinges6/read](https://leanpub.com/understandinges6/read)

*   [ECMAScript® 2015 Language Specification](https://www.ecma-international.org/ecma-262/6.0/) *For really advanced developers*

*   CORS: [https://www.html5rocks.com/en/tutorials/cors/](https://www.html5rocks.com/en/tutorials/cors/)

*   Using Chrome console to debug JavaScript [https://developer.chrome.com/devtools/docs/console](https://developer.chrome.com/devtools/docs/console)

**Practice**

*Latest IE, Chrome and Firefox browser should be used. All exercises must be done with ECMAScript 6 syntax.*

1.  Creating our index page with some sections.

    *   Create a file called `index.html` with the correct doctype and some random content.

    *   Add a stylesheet to the HTML file and use it to center the texts of all `section` elements.

    *   Add a hidden `section` with `Hello World` inside of it.

    *   When the page finished loading the section must fade in.

2.  Adding some events

    *   Add a button below the `section` to your index page.

    *   Create a function that showcases an alert message when called.

    *   Attach a click event to the created button which calls the function previously created.


3.  Data fetching

    *   Create a function to get the response from [http://api.icndb.com/jokes/random](http://api.icndb.com/jokes/random).

    *   Replace the button's click event with this new function.

    *   Write the response inside the `section` element.

    *   Create a reusable function to perform AJAX calls. This function must accept a `config` object and return an ES6 Promise.

    *   If a server error occurs `section` content must turn red.

    *   **Hint:** Use the XMLHttpRequest to fetch data from the service.

4.  Data fetching with parameters

    *   Create a function to get the response from [https://api.github.com/search/repositories](https://api.github.com/search/repositories) with parameters `q = 'JavaScript'`.

    *   Showcase a list of repositories, provided by the service, in the right side of the screen.

    *   **Hint:** `ul` must be used to list the repositories.

    *   Add an input with `type="text"` to perform a search for any value.

5.  W3C

    *   Validate your page using W3C validator: [https://addons.mozilla.org/en-US/firefox/addon/web-developer/](https://addons.mozilla.org/en-US/firefox/addon/web-developer/)

6.  DOM manipulation

    *   Write a function that takes as input a matrix of data and outputs a DOM structure representing a table. Attach it to the body of a given page.

    *   **Hint:** use `document.createElement`, `document.createTextNode`, and `Node.appendChild` methods.

**Key Points:**

1, 3, 4, 6

→ [index](#index)

<h4 id="topic2">Topic 2 - Design Patterns and OOP in JavaScript</h4>

In this Topic we will focus on learning how JavaScript approaches Object-Oriented programming.

If you come from Java, or .NET you will find yourself a little bit lost at the beggining.
ECMAScript6 provides a layer of syntactic sugar over the previous version (5.1) that is expected to simplify the language.

**Reading**

1. Understand how *prototypes* works in ECMAScript 5.1 [http://yehudakatz.com/2011/08/12/understanding-prototypes-in-javascript/](http://yehudakatz.com/2011/08/12/understanding-prototypes-in-javascript/)

2. ECMAScript 6 New Features: [http://es6-features.org/](http://es6-features.org/). You can compare ECMAScript 5 and 6 code.

3. Read the Chapter on JavaScript classes from [*Understanding ECMAScript6*](https://leanpub.com/understandinges6/read#leanpub-auto-classes)

4. Read about [ES6 Modules](https://ponyfoo.com/articles/es6-modules-in-depth)  

5. Extra: Read about AMD, CommonJS, and ES6 Modules [Writing Modular JavaScript](https://addyosmani.com/blog/writing-modular-javascript/)

6. An overview on all the features ECMAScript provides [https://github.com/lukehoban/es6features](https://github.com/lukehoban/es6features)

**Practice**

1.  Creating classes

    *   Create a Movie Class with the following structure

        <table>
            <tr>
                <td>Movie</td>
            </tr>
            <tr>
                <td>
                    - title <br />
                    - year <br />
                    - duration
                </td>
            </tr>
            <tr>
                <td>
                    + constructor(name, year, duration) <br />
                    + play() <br />
                    + pause()<br />
                    + resume()
                </td>
            </tr>
        </table>

    *   Instantiate some of your favorite movies and play with them in the console.

    *   Create an Actor class with the following structure

        <table>
            <tr>
                <td>Actor</td>
            </tr>
            <tr>
                <td>
                    - name <br />
                    - age
                </td>
            </tr>
            <tr>
                <td>
                    + constructor(name, age)
                </td>
            </tr>
        </table>

    *   Create a class called EventEmitter with the following structure

        <table>
            <tr>
                <td>EventEmitter</td>
            </tr>
            <tr>
                <td>
                    + constructor()<br />
                    + on(eventName, callback) <br />
                    + emit(eventName)<br />
                    + off(eventName, callback)
                </td>
            </tr>
        </table>

        The `on` method will receive a eventName and a callback or **listener** that will be executed each time a that event is triggered.

        The `emit` method will trigger events to be consumed by other functions or objects.

        The `off` method will delete previously defined event listeners.

2.  Class inheritance

    *   Make the Movie class a subclass of EventEmitter and use the inherited methods to publish `play`, `pause` and `resume` events when the related method is called.

3.  Working with classes

    *   Add a method to Movie as `addCast(cast)` that allows the addition of one or more Actors to a movie. It must work if provided with more than one Actor at the same time.

        You should be able to do something like

        ```js
        const terminator = new Movie('Terminator I', 1985, 60);
        const arnold = new Actor('Arnold Schwarzenegger', 50);
        const actors = [
            new Actor('Paul Winfield', 50),
            new Actor('Michael Biehn', 50),
            new Actor('Linda Hamilton', 50)
        ];

        terminator.addCast(arnold);
        terminator.addCast(otherCast);
        ```

    *   Create a Logger class with the following structure

        <table>
            <tr>
                <td>Logger</td>
            </tr>
            <tr>
                <td>
                    + constructor()<br />
                    + log(info)
                </td>
            </tr>
        </table>

        After creating this class make an instance of Logger and make it listen to Movie's `play` event.

        As example you must end with something like

        ```js
        const terminator = new Movie('Terminator I', 1985, 60);

        ...

        terminator.play(); // output: The 'play' event has been emitted
        ```

4.  Mixins

    *   Create an object called social, defining the methods `share(friendName)` and `like(friendName)` that generates the following output `{friendName} likes/share {movieName}`.

        Then extend a movie with it to have access to this methods.

        You should end with something like

        ```js
        const ironman = new Movie(...);

        ...

        ironman.share('Mike Blossom');
        ```

        **Hint:** A mixin is not a class which will be instantiated later on. Use a way to extend some object methods into another object. Template literals might be useful to generate the required output.

5.  ES6 Modules

    *   Split all your classes into different files.

    *   Using babel create a single JS bundle.

    **Hint:** check out [this](https://babeljs.io/docs/usage/cli/)

**Key Points**

3, 4, 5, 6

→ [index](#index)

<h4 id="topic3">Topic 3 - HTML5 APIs</h4>

**Reading**

1. Take a glimpse into HTML5 APIs: [http://www.html5rocks.com/en/](http://www.html5rocks.com/en/)

2. Now, take a deep dive into HTML5: [http://diveintohtml5.info/](http://diveintohtml5.info/) (optional)

3. Understand the capabilities the Web has to offer right now [https://whatwebcando.today/](https://whatwebcando.today/)

**Practice**

1.  Storages

    *   Create a page with a textarea and a save button.

    *   Save textarea content's when the user clicks on save. Use both localStorage and IndexedDB.

    *   Add a clear button to erase saved content.

2.  Drag and Drop

    *   Add drag and drop support to load text files.


3.  WebSockets

    *   Open a web socket and test it against [this service](http://www.websocket.org/echo.html).


4.  SVG

    *   Create a web page with a SVG element to show a vector graphic.
        Make sure you understand when is better to use SVG instead of bitmaps, and viceversa.


5.  Canvas

    *   Create a web page with a canvas element. Upon page load draw basic geometric figures with random colors and strokes.

    *   Using the Canvas API, animate a rectangle's position on the screen. Make sure not to use setTimeout but requestTimeFrame to perform the animation.

**Key Points**

1, 2, 3, 4

→ [index](#index)

<h4 id="topic4">Topic 4 - ReactJS</h4>

**Reading**

1. First [ReactJS Hello World](https://reactjs.org/docs/hello-world.html) then [Thinking in React](https://reactjs.org/docs/thinking-in-react.html).

2. Understand [Props & States](https://github.com/uberVU/react-guide/blob/master/props-vs-state.md).

3. Install [Create React App](https://github.com/facebook/create-react-app) and get familiar with it.

4. Read about some ReactJS's [Best Practices, Patterns & Anti-patters](https://github.com/planningcenter/react-patterns).

5. Check some ReactJS's [Test utilities](https://reactjs.org/docs/test-utils.html).

**Extra reading**

* [Full guide on ReactJS](https://scotch.io/tutorials/learning-react-getting-started-and-concepts).

* Readings on lifecycle methods: [React Lifecycle Methods- how and when to use them](https://engineering.musefind.com/react-lifecycle-methods-how-and-when-to-use-them-2111a1b692b1),
[Understanding the React Component Lifecycle](http://busypeoples.github.io/post/react-component-lifecycle/)


**Practice**

1. Create the needed components to allow the user create a new Movie.

2. Create the needed components to show a list of your favorite Movies.

3. Create the needed components to allow the user edit a Movie.

4. Update the movie listing to allow the user delete movies.

5. Refactor the application to use Redux

**Tips**
- First, try to think which should be your app structure (in terms of components).
- Second, figure out which component should handle the movies.
- You should create a component when trying to create a view (a view is also a component).

**Key Points**

1, 2, 5

→ [index](#index)

<h4 id="topic5">Topic 5 - Angular</h4>

**Reading**

1. Read Angular's [Tutorial](https://angular.io/tutorial) and the [QuickStart guide](https://angular.io/guide/quickstart).

2. [Creating your first Angular 2+ component](https://toddmotto.com/creating-your-first-angular-2-component).

3. Check your code to comply with Angular's [Style Guide](https://angular.io/guide/styleguide).

4. Learn how to create unit tests for your angular applications [https://angular.io/guide/testing](https://angular.io/guide/testing)

5. [Codecraft tutorial on Angular 5](https://codecraft.tv/courses/angular/quickstart/overview/)

6. Get familiar with the [Angular CLI](https://github.com/angular/angular-cli) tool.

**Practice**

1. Create a movie listing with your favorite movies. Data should be persisted in localhost.

2. Show movie details in a separate details view.

3. Allow to add / edit / remove movies from the list.

4. Configure Jasmine+karma and write tests for your application.

**Key Points**

1, 2, 3

→ [index](#index)

### Your First Project Starts Now

**It’s time for the real thing**

You will work on a project to achieve a fully working mobile web app developed in JavaScript and using the latest tags and APIs available in HTML5.

You will apply all the knowledge obtained during the learning weeks.

Will you be able to consult documentation? Of course!

You will be able to use any resource you know that helps you complete your project, be it going back to documentation sites, tutorials or just googling what you need. Luckily the web has plenty of awesome resources waiting for you to grasp them!

**Reviews**

Tutors will give you feedback at the end of the project by reviewing and commenting your committed code in GitHub.

→ [index](#index)


<h3 id="forward">Moving Forward</h3>

Here's a list of resources, tools and tips to continue your learning path. This is meant for more advanced students and developers who wish to continue learning and need a little guidance. Feel free to play with them!

- [Learning Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)
- [Introduction to React Router](https://github.com/ReactTraining/react-router/blob/v3/docs/Introduction.md)
- [Understanding redux](https://redux.js.org/introduction/motivation)
- [Observables in Angular](https://angular.io/guide/observables)
- [Webpack concepts](https://webpack.js.org/concepts/) and the [webpack getting started guide](https://webpack.js.org/guides/getting-started/)

→ [index](#index)
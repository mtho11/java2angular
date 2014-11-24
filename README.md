# java2angular

#### From Java(GWT) To Angular (learning resources)


Perhaps the hardest part when first starting Angular development (especially when coming from something like java) is new toolsets and ecosystem. Everything is foreign. Fortunately, all the tools are quite easy to use. Certainly, easier to learn than the java ecosystem if you had to start learning java. 
These tools include:
* WebIDE or Editor (need the proper plugins to make these tools useful)
* Grunt (ant-like build tool) or Gulp - Only concerned with build tasks no version/dependency mgmt)
* bower (maven-like package management with dependency management)
* karma (unit test) - the karma unit test run a magnitude faster than GWT unit tests.
* Protractor (integration test)
* [Optional] ES6 or Typescript transpiler to give java devs a more familiar syntax with classes/modules and optional type safety (with Typescript). With these tools you can come close to the GWT environment in terms of type safety but still get the agility of javascript tools).
* [Optional] little bit of node.js and npm (as many of the above cli tools use it)

IMO, the breakout of build lifecycle seperate from the verioning/dependency mgmt makes for a much more robust build system than maven that combines the two.

And these supporting technologies that the tools use or enable:
* Angular.js (of course)
* CSS, HTML5 (browser debugging, Bootstrap for responsive layouts)
* Responsive layouts (optional: depending if you are targeting mobile)
* RESTful backend integration
* Javascript (a whole lot of this)
* Javascript and Angular libs (this is where the real power comes from)

_Don't be scared you can learn this in pieces!_

Angular is quite straight forward to learn if you have had to use MVC frameworks before. The two-way binding practically eliminates any management of models and views. The controllers provide the functionality to the view separating the controller logic from the view. This makes the view (the DOM) a declarative clean view without any javascript handlers gumming up the view. And this makes testing easier to as we can just test the controller.

The best way to start with an overview of Angular is [Angular in 20ish minutes](https://www.youtube.com/watch?v=tnXO-i7944M). After that, time spent on the excellent [Egghead.io Videos](https://egghead.io/technologies/angularjs?order=ASC) is well worth it. The Egghead series is a short and concise series of videos lasting only a few minutes focusing on just a single topic (and most have the source code as well).
Here is a list of Angular Learning Resources:
* [Curated List of Egghead.io lessons from Thinkster.io](https://thinkster.io/angulartutorial/a-better-way-to-learn-angularjs/)
* [Introduction to Angular in 50 Examples](https://www.youtube.com/watch?v=TRrL5j3MIvo)
* [Shaping up with Angular JS](https://www.codeschool.com/courses/shaping-up-with-angular-js)

#### Editors
To start out we need an editor or IDE to make it easy to navigate your project and provide code completions to an environment we have not committed to memory yet...

Editors & IDEs is where things get very personal. Whatever camp you fall into you will have your own reasons based on functionality most important to you. The purpose of this page is just to make you aware of the plugins that might make or break your experience with a particular tool.

1. [WebStorm] (http://www.jetbrains.com/webstorm/)
This is my favorite to work in because it feels to me like it has the most features. Full disclosure -- I'm very biased because I have worked with [IntelliJ Idea](http://www.jetbrains.com/idea/) (IDE for java) for many years so WebStorm is a natural for me.
[WebStorm Tips & Tricks](https://www.youtube.com/watch?v=leKbqNpgoNQ)
[WebStrom Video Tutorials](https://www.youtube.com/watch?v=PNZJox8pkls&list=PLQ176FUIyIUb0zTe7k4ZKkhMsR-slKu3w)

2. [Sublime Text](http://www.sublimetext.com/)
If you are just starting out and want something that is powerful but lightweight, Sublime is a good recommendation. This tool really shines with the proper plugins to take advantage of javascript and angular.js code completion.
[Best of Sublime Text 3](http://scotch.io/bar-talk/best-of-sublime-text-3-features-plugins-and-settings)

3. [Atom](https://atom.io/)
This is a Sublime Text clone new comer from the github guys. It is very hackable and should have many plugins once it matures a little bit. I'm keeping my eye on this one to overtake Sublime Text.

4. Eclipse
I have not used eclipse in years (and don't care to) so I really can't comment.


 

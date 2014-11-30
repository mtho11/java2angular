# java2angular

#### From Java(GWT) To Angular (learning resources)

Perhaps the hardest part when first starting Angular development (especially when coming from something like java) is new toolsets and ecosystem. Everything is foreign. Fortunately, all the tools are quite easy to use along with being lightweight and agile. Certainly, easier to learn than the java ecosystem if you had to start learning java and its ecosystem. However, in addition to learning javascript and Angular js there is the new toolchain (which is rapidly changing).

These tools include:
* WebIDE or Editor (need the proper plugins to make these tools useful). __As a javas developer, I had no desire to touch javascript until it had proper IDE support.__
* [Grunt](http://gruntjs.com/) (ant-like build tool) or [Gulp](http://gulpjs.com/) - Only concerned with build tasks no version/dependency mgmt)
* [bower](http://bower.io/) (maven-like package management with dependency management)
* [karma](http://karma-runner.github.io/0.12/index.html) (unit test) - the karma unit test run a magnitude faster than GWT unit tests.
* [Protractor](http://angular.github.io/protractor/#/) (integration test) integration testing for angular with the ability to get at the angular specific pieces
* [Optional] ES6 or Typescript transpiler to give java devs a more familiar syntax with classes/modules and optional type safety (with Typescript). With these tools you can come close to the GWT environment in terms of type safety but still get the agility of javascript tools).
* [Optional] little bit of node.js and npm (as many of the above cli tools use it)

IMO, the breakout of build lifecycle([grunt](http://gruntjs.com/)) seperate from the verioning/dependency mgmt([bower](http://bower.io/)) makes for a much more robust build system than maven that combines the two.

And these supporting technologies that the tools use or enable:
* Angular.js (of course)
* CSS, HTML5 (browser debugging, Bootstrap for responsive layouts)
* Really get to know [Chrome Dev Tools](https://developer.chrome.com/devtools) (its invaluable)
* Responsive layouts (optional: depending if you are targeting mobile)
* RESTful backend integration with json
* Javascript (a whole lot of this) -- too many resources to discuss here
* Javascript and Angular libs (this is where the real power comes from)

_Don't be scared you can learn this in pieces!_

Angular is quite straight forward to learn if you have had to use MVC frameworks before. The two-way binding practically eliminates any management of models and views. The controllers provide the functionality to the view separating the controller logic from the view. This makes the view (the DOM) a declarative clean view without any javascript handlers gumming up the view. And this makes testing easier to as we can just test the controller.

Here is a list of Angular Learning Resources (one good thing about Angular is that there are a bazillion resources):
* [Angular in 20ish minutes](https://www.youtube.com/watch?v=tnXO-i7944M). Great overview of Angular.
* [Angular Seed Project](https://github.com/angular/angular-seed) A simple starter project.
* [Curated List of Egghead.io lessons from Thinkster.io](https://thinkster.io/angulartutorial/a-better-way-to-learn-angularjs/)
* [Egghead.io Videos](https://egghead.io/technologies/angularjs?order=ASC)These short videos cover pretty much everything. Very comprehensive.
* [Shaping up with Angular JS](https://www.codeschool.com/courses/shaping-up-with-angular-js)
* [Introduction to Angular in 50 Examples](https://www.youtube.com/watch?v=TRrL5j3MIvo) If you like to see examples of code here are 50 examples of how to do things (there is another 50 examples after that as well)
* [Understanding Scopes](https://github.com/angular/angular.js/wiki/Understanding-Scopes) In depth coverage of scopes. Must Read.
* [Pitfalls using scopes](http://thenittygritty.co/angularjs-pitfalls-using-scopes) Scoping issues to watch out for.
* [Using Yeoman: a rails-like generator for Angular](http://www.sitepoint.com/kickstart-your-angularjs-development-with-yeoman-grunt-and-bower/) Setting up your project is half the battle. Yeoman makes this simple as it brings together many tools to create a highly productive tooling environment.
* [Angular in Patterns](https://github.com/mgechev/angularjs-in-patterns) For those of us who like patterns, here is an angular version.
* [Factory vs. Service vs. Provider](http://tylermcginnis.com/angularjs-factory-vs-service-vs-provider/) After you have written your first controller the next question will be this. 
* [Controller As and the vm variable](http://www.johnpapa.net/angularjss-controller-as-and-the-vm-variable/)
* [Debugging AngularJS in the Console](http://ionicframework.com/blog/angularjs-console/) Some very useful techniques for getting at Angular objects in the browser Console.
* [ngModules](http://ngmodules.org/) Looking for a specific angular library to do something. Look no further.

Trying to learn Angular directly from Typescript was difficult for me because there is not many resources on Angular/Typescript and all the many examples for Angular (and there are MANY) are in Javascript. It is hard enough to learn a framework but to add the language translation (and different idioms) makes the task much more difficult. So my advice is to start learning Angular with Javascript until you feel comfortable then switch to using Typescript. The good news is that Typescript will actually feel more natural to Java developers than Javascript. With classes and modules you can think in terms of [GoF design patterns](https://github.com/torokmark/design_patterns_in_typescript) like you did with Java instead of foreign [Javacript design patterns](http://addyosmani.com/resources/essentialjsdesignpatterns/book/). The type safety  and modern language syntax (ES6) are really a joy to have back and make it comparable to GWT on that aspect. So we get type safety when we need it (optionally) and syntax that is more concise than java along with frameworks and environments that are agile and on the forefront of UI technology -- for the win.

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
I have not used eclipse in years (and don't care to) so I really can't comment. [Submit a pull request if you have any info]


 

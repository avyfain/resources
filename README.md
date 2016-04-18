# Resources

A collection of various awesome resources for future reference. Inspired by [awesome](https://github.com/sindresorhus/awesome)

**Table of Contents**

  - [Introduction](#introduction)
  - [Programming](#programming)
    - [General](#general)
    - [Project Management](#project-management)
    - [Python](#python)
    - [Ruby](#ruby)
    - [Machine Learning](#machine-learning)
    - [Experiments, and other fun stuff](#experiments-and-other-fun-stuff)

##Introduction
##Programming
###General
* **Articles**
    - [FizzBuzz in too much detail](http://www.tomdalling.com/blog/software-design/fizzbuzz-in-too-much-detail/), **Tom Dalling**   
    Industrial quality engineered software.... YAGNI!

    - [Revenge of the Nerds](http://www.paulgraham.com/icad.html), **Paul Graham**  
    An opinionated comparison of programming languages. Picking the right tools for the task, and why your boss will always pick the "Industry Standard".

    - [The Magestic Monolith](https://m.signalvnoise.com/the-majestic-monolith-29166d022228), **David Heinemeier Hansson**  
    Sometimes, microservices are not the answer. IMO, that's most times.

    - [A Bad Citizen in Javaland](http://darrenhobbs.com/2006/04/22/a-bad-citizen-in-javaland/), **Darren Hobbs**  
    OOP is not inherently bad, bad OO programmers are.

    - [The Economics of Software Correctness](http://www.drmaciver.com/2015/10/the-economics-of-software-correctness/), **David R. MacIver**  
    The reason behind your buggy software boils down to economic incentives.

    - [The Wrong Abstraction](http://www.sandimetz.com/blog/2016/1/20/the-wrong-abstraction), **Sandi Metz**   
    Old code is subject to the sunk cost fallacy, and a bad abstraction that gets dragged along becomes spaghetti. Avoid it.

    - [Falsehoods Programmers Believe About Names](http://www.kalzumeus.com/2010/06/17/falsehoods-programmers-believe-about-names/), **Patrick McKenzie**   
    Handling names is hard. Stop making assumptions.

    - [Dizzying but invisible depth](https://plus.google.com/+JeanBaptisteQueru/posts/dfydM2Cnepe), **Jean-Baptiste Quéru**  
    You just went to the Google home page. Simple, isn't it? What just *actually* happened? (There is also a [crowdsourced version](https://github.com/alex/what-happens-when) of this worth checking out)

    - [Why I Hate Frameworks](http://discuss.joelonsoftware.com/?joel.3.219431.12), **Benji Smith**   
    You needed a hammer, but ended up with a Hammer Factory Factory Factory™.

    - [The Law of Leaky Abstractions](http://www.joelonsoftware.com/articles/LeakyAbstractions.html), **Joel Spolsky**   
    All non-trivial abstractions, to some degree, are leaky. They fail. Sometimes a little, sometimes a lot.

    - [The Duct Tape Programmer](http://www.joelonsoftware.com/items/2009/09/23.html), **Joel Spolsky**   
    Stop overengineering things.

    - [The 12 Factor App](http://12factor.net/), **Adam Wiggins**   
    Methodology for building SaaS web apps with declarative setup, clean contracts and continuous deployment on the cloud for maximum portability, agility and scalability.

* **Videos**
    - [Wat](https://www.destroyallsoftware.com/talks/wat), **Gary Bernhardt**  
    Unexpected behavior that makes you think: "WAT!?"

    - [The Future of Programming](https://www.youtube.com/watch?v=8pTEmbeENF4), **Bret Victor**  
    1973 meets 2013 ([Slides](http://worrydream.com/dbx/))

###Project Management
* **Articles**
    - [Heisenberg Developers](http://mikehadlow.blogspot.cl/2014/06/heisenberg-developers.html), **Mike Hadlow**   
    Measuring how much is getting done affects the development process: "You can not observe a developer without altering their behavior."

###Python
* **Articles**
    - [Pragmatic Unicode](http://nedbatchelder.com/text/unipain.html), **Ned Batchelder**

    - [How the heck does async/await work in Python 3.5?](http://www.snarky.ca/how-the-heck-does-async-await-work-in-python-3-5), **Brett Cannon**  
    An explanation of concurrent programming, and how it works. Still need to wrap my head around this.

    - [Why `print` became a function in Python 3](http://www.snarky.ca/why-print-became-a-function-in-python-3), **Brett Cannon**  
    Functions are composable. The old print? It wasn't.

    - [Why Python 3 Exists](http://www.snarky.ca/why-python-3-exists), **Brett Cannon**  
    And more importantly, why is it backwards incompatible?

    - [Iterables vs. Iterators vs. Generators](http://nvie.com/posts/iterators-vs-generators/), **Vincent Driessen**   
    A little pocket reference on iterables, iterators and generators.

    - [Python is not Java](http://dirtsimple.org/2004/12/python-is-not-java.html), **Phillip Eby**  
    different strokes for different folks

    - [Advanced use of Python decorators and metaclasses](http://blog.thedigitalcatonline.com/blog/2014/10/14/decorators-and-metaclasses/), **Leonardo Giordiani**  
    Making use of python's more advanced features to solve a toy problem. Override a few dunder methods and get _magic_ in return.

    - [10 Myths of Enterprise Python](https://www.paypal-engineering.com/2014/12/10/10-myths-of-enterprise-python/) **Mahmoud Hashemi**  
    Python is old, compiles to bytecode, is secure, isn't just for scripting, is strongly typed, is fast, scales, supports concurrency, developers like it, and it works for big projects. And that's all 10.

    - [Python with context managers](http://jeffknupp.com/blog/2016/03/07/python-with-context-managers/), **Jeff Knupp**   
    Context managers are one of python's most interesting pieces of syntactic sugar. Knupp explains a few ways to use and define them.

    - [Counting Things in Python: A History](http://treyhunner.com/2015/11/counting-things-in-python/), **Trey Hunner**   
    "Counting Things" as a case study of python's evolution.

    - [Five Easy Pieces: Simple Python Non-Patterns](http://www.aleax.it/5ep.html), **Alex Martelli**   
    Singletons vs. Borgs

    - [The Bottom-Line Single Main Difference Between Python 2 and 3](http://migrateup.com/main-difference-python-3/), **Aaron Maxwell**  
    Python 3 makes it easier to develop high quality software.

    - [Pythonic means idiomatic and tasteful](http://www.pixelmonkey.org/2010/11/03/pythonic-means-idiomatic-and-tasteful), **Andrew Montalenti**  
    Readability counts

    - [Iterate with a sentinel value](http://blog.amir.rachum.com/blog/2013/11/10/python-tips-iterate-with-a-sentinel-value/), **Amir Rachum**  
    You can use the iter function in a for loop to loop until a known value is returned.  

    - [Start Writing More Classes](http://lucumr.pocoo.org/2013/2/13/moar-classes/), **Armin Ronacher**   
    Stop hiding complexity. Decouple, and expose IO. (see also: Jack Diederich's [Stop Writing Classes](https://www.youtube.com/watch?v=o9pEzgHorH0) and Brandon Rhodes' [Clean Architecture](http://rhodesmill.org/brandon/talks/#clean-architecture-python)).


* **Videos**
    - [Python Concurrency From the Ground Up](https://www.youtube.com/watch?v=MCs5OvhV9S4), **David Beazley**, PyCon US 2015   
   Threads, event loops, and coroutines: deconstructed and explained  

    - [Stop Writing Classes](https://www.youtube.com/watch?v=o9pEzgHorH0), **Jack Diederich**, PyCon 2012  
    Get rid of cruft, YAGNI, and thoughtful refactoring with the end user in mind (see also, Armin Ronacher's [Start Writing More Classes](http://lucumr.pocoo.org/2013/2/13/moar-classes/)).

    - [Beyond PEP 8](https://www.youtube.com/watch?v=wf-BqAjZb8M), **Raymond Hettinger**, PyCon 2015  
    Best practices for beautiful intelligible code.

   - [Transforming Code into Beautiful, Idiomatic Python](https://www.youtube.com/watch?v=OSGv2VnC0go), **Raymond Hettinger**, PyCon US 2013  
   Improve existing code through a series of code transformations

   - [A Python Æsthetic: Beauty and Why I Python](https://www.youtube.com/watch?v=x-kB2o8sd5c), **Brandon Rhodes**  
   The python community makes an effort to write beautiful, readable code. Be a part of it.

    - [All Your Ducks In A Row: Data Structures in the Std Lib and Beyond](https://www.youtube.com/watch?v=fYlnfvKVDoM), **Brandon Rhodes**  
    Learn the inner workings of data structures in Python, which work in a different way than the classics.

    - [Python Design Patterns 1](https://www.youtube.com/watch?v=Er5K_nR5lDQ), **Brandon Rhodes**  
   Gang of Four patterns in modern Python programming ([Slides](http://rhodesmill.org/brandon/slides/2012-07-pyohio/)).

    - [The Clean Architecture in Python](https://www.youtube.com/watch?v=DJtef410XaM), **Brandon Rhodes**  
   Improve your tests and *actually* decouple your code by isolating I/O instead of hiding it. ([Slides](http://rhodesmill.org/brandon/slides/2014-07-pyohio/clean-architecture/)).

###Ruby
* **Articles**
    - [The Ruby on Rails Doctrine](rubyonrails.org/doctrine), **David Heinemeier Hansson**  
    The pillars of Ruby on Rails, and a manifesto to sustain its success into the future.

###Machine Learning  
* **Books**
    - [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/index.html), **Michael Nielsen**

* **Articles**
    - [Understanding Convolution in Deep Learning](http://timdettmers.com/2015/03/26/convolution-deep-learning/), **Tim Dettmers**

    - [The state of Computer Vision and AI: we are really, really far away](http://karpathy.github.io/2012/10/22/state-of-computer-vision/), **Andrej Karpathy**

    - [A Word is Worth a Thousand Vectors](http://multithreaded.stitchfix.com/blog/2015/03/11/word-is-worth-a-thousand-vectors/), **Chris Moody**

    - [Neural Networks, Manifolds, and Topology](http://colah.github.io/posts/2014-03-NN-Manifolds-Topology/), **Christopher Olah**

    - [Visualizing MNIST: An Exploration of Dimensionality Reduction](http://colah.github.io/posts/2014-10-Visualizing-MNIST/), **Christopher Olah**

    - [A Neural Network in 11 lines of Python](http://iamtrask.github.io/2015/07/12/basic-python-network/) ([Part 1](https://iamtrask.github.io/2015/07/12/basic-python-network/), [Part 2](https://iamtrask.github.io/2015/07/27/python-network-part2/)), **Andrew Trask**

###Experiments, and other fun stuff  
* **Other**
    - [Measuring Pi with Lentils and Python](https://civisanalytics.com/blog/data-science/2014/08/13/measuring-pi-with-lentils-and-python/), **Michelangelo D'Agostino** (Python)

    - [Switching Eds: Face swapping with Python, dlib, and OpenCV](http://matthewearl.github.io/2015/07/28/switching-eds-with-python/), **Mathew Earl** (Python)

    - [What a Deep Neural Network thinks about your #selfie](http://karpathy.github.io/2015/10/25/selfie/), **Andrej Karpathy**

    - [Let's Code About Bike Locks](http://nbviewer.ipython.org/url/norvig.com/ipython/Fred%20Buns.ipynb), **Peter Norvig** (Python)

    - [Solving Every Sudoku Puzzle](http://norvig.com/sudoku.html), **Peter Norvig** (Python)

    - [How to Write a Spelling Corrector](http://norvig.com/spell-correct.html), **Peter Norvig** (Python)

    - [Probability, Paradox, and the Reasonable Person Principle](http://nbviewer.jupyter.org/url/norvig.com/ipython/Probability.ipynb), **Peter Norvig** (Python)

    - [The Traveling Salesman with Simulated Annealing, R, and Shiny](http://toddwschneider.com/posts/traveling-salesman-with-simulated-annealing-r-and-shiny/), **Todd W. Schneider** (R)

    - [A Tale of Twenty-Two Million Citi Bike Rides: Analyzing the NYC Bike Share System](http://toddwschneider.com/posts/a-tale-of-twenty-two-million-citi-bikes-analyzing-the-nyc-bike-share-system/), **Todd W. Schneider** (R)

    - [A Statistical Analysis of All Hacker News Submissions](http://minimaxir.com/2014/02/hacking-hacker-news/), **Max Woolf** (Python)

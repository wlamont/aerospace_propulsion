#[Aerospace Propulsion](https://github.com/wlamont/aerospace_propulsion)
#### *An Open-Source and Pythonic Textbook*

It is an exciting time to be an aerospace engineer.   Aerospace start-ups like Elon Musk's SpaceX and Jeff Bezos' Blue Origins are bringing new ideas and energy to the final frontier.  We are literally in the midst of a second space race: space race 2.0.  This new space race is not occuring between Nations for geopolitical reasons but between companies for market reasons.  Each company in this race is trying to drastically reduce space travel cost while simultaneously improving reliability and safety.   That is what is happening in the space part of aerospace.  On the aero side, or aviation side, Boeing, Airbus, COMAC, Bombardier, Embraer and Gulfstream (to name a few)  are working on next generation aircraft that will be more fuel efficient and will provide a more enjoyable travel experience.  These new planes will require new engines that are quieter, more fuel efficient and reliable, and which produce lower pollutant emissions.   The major engine manufacturers (GE, Rolls-Royce, and Pratt and Whitney) are working on the challenge.

This textbook is for a hypothetical course: a course I wish had existed when I was a student and a course I may teach in the future if I end up back in academia.  This textbook is intended for upper year engineering undergraduate students interested in aerospace propulsion.  The student should have some familiarity with fluid mechanics, thermodynamics, chemistry and a programming language (preferably Python).    This hypothetical course is only intended to last one semester.  For the serious student enrolled or enrolling in graduate studies this book can still provide a good introduction.



I have split the book into four main chapters:


Contents
------


The below chapters are rendered via the *nbviewer* at
[nbviewer.ipython.org/](http://nbviewer.ipython.org/), and is read-only and rendered in real-time.
Interactive notebooks + examples can be downloaded by cloning! 


* [**Chapter 1: Background:**](http://nbviewer.ipython.org/github/wlamont/aerospace_propulsion/blob/master/Chapter01_background/Chapter01_background.ipynb)  Will focus on the necessary knowledge required for the subsequent chapters.  This material will be an abridged version of two courses: gas dynamics and combustion. 

* [**Chapter 2: Air Breathing**](http://nbviewer.ipython.org/github/wlamont/aerospace_propulsion/blob/master/Chapter02_air_breathing/Chapter02_air_breathing.ipynb) 
Will focus on the aviation side of aerospace propulsion and will strictly deal with gas turbines (jet engines).
    
* [**Chapter 3: Rockets**]
Will focus on the three main types of rockets: solid, liquid and hybrid.  Also detail work on the rocket nozzle, which generates most of the thrust, will be presented.
    
* [**Chapter 4: Advanced Systems**]
Will introduce concepts and systems that have not yet been commercialized.
  
    
Using the book
-------

The book can be read in three different ways, starting from most recommended to least recommended: 

1. The most recommended option is to clone the repository to download the .ipynb files to your local machine. If you have IPython installed, you can view the 
chapters in your browser *plus* edit and run the code provided (and try some practice questions). This is the preferred option to read
this book, though it comes with some dependencies. 
    -  IPython v0.13 (or greater) is a requirement to view the ipynb files. It can be downloaded [here](http://ipython.org/). IPython notebooks can be run by `(your-virtualenv) ~/path/to/the/book/Chapter1_Introduction $ ipython notebook`
    -  For Linux users, you should not have a problem installing NumPy, SciPy, Matplotlib and PyMC. For Windows users, check out [pre-compiled versions](http://www.lfd.uci.edu/~gohlke/pythonlibs/) if you have difficulty. 
    -  In the styles/ directory are a number of files (.matplotlirc) that used to make things pretty. These are not only designed for the book, but they offer many improvements over the default settings of matplotlib.
2. The second, preferred, option is to use the nbviewer.ipython.org site, which display IPython notebooks in the browser ([example](http://nbviewer.ipython.org/urls/raw.github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/master/Chapter1_Introduction/Chapter1_Introduction.ipynb)).
The contents are updated synchronously as commits are made to the book. You can use the Contents section above to link to the chapters.
 
3. PDFs are the least-prefered method to read the book, as pdf's are static and non-interactive. If PDFs are desired, they can be created dynamically using the [nbconvert](https://github.com/ipython/nbconvert) utility.
 

Installation and configuration
------

If you would like to run the IPython notebooks locally, (option 1. above), you'll need to install the following:

-  IPython 0.13+ is a requirement to view the ipynb files. It can be downloaded [here](http://ipython.org/ipython-doc/dev/install/index.html) 
- Necessary packages are NumPy, SciPy and Matplotlib.   
   -  For Linux/OSX users, you should not have a problem installing the above, [*except for Matplotlib on OSX*](http://www.penandpants.com/2012/02/24/install-python/).
   -  For Windows users, check out [pre-compiled versions](http://www.lfd.uci.edu/~gohlke/pythonlibs/) if you have difficulty. 

- New to Python or IPython, and help with the namespaces? Check out [this answer](http://stackoverflow.com/questions/12987624/confusion-between-numpy-scipy-matplotlib-and-pylab). 





Development
------

This book has an unusual development design. The content is open-sourced, meaning anyone can be an author. 
Authors submit content or revisions using the GitHub interface. 

### How to contribute

####What to contribute?

-  Cleaning up Python code
-  Giving better explanations
-  Spelling/grammar mistakes
-  Suggestions
-  Contributing to the IPython notebook styles


####Commiting

-  All commits are welcome, even if they are minor ;)
-  If you are unfamiliar with Github, you can email me contributions to the email below.


Contributions and Thanks
-----

The idea of this work came from Prof. Allen Downey's [Textbook Manifesto](http://greenteapress.com/manifesto.html) and his teaching philosophy that through programming you can learn anything.  To this end my goals in writing this textbook were to keep it short and clear, and to use Python programming examples to illustrate concepts.  I tried to adhere to PEP 8  -- Style Guide for Python Code.  For the students unfamiliar with Python, I would recommend Prof. Allen Downey's [Think Python] (http://greenteapress.com/thinkpython/thinkpython.html) to get started.

Stylistic and the layout came from Cam Davidson-Pilson's [Probablistic Programming & Bayesian Methods for Hackers](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers).  Much of this README.md came directly from that work.  



####Contact
Contact the main author, Warren Lamont at warren.lamont@gmail.com 




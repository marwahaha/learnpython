---
layout: page
title: Learning Resources
comments: true
permalink: /learn/
redirect_from: learning_resources.html
---

* content
{:toc}

## Set up your computer
This is our recommended way to install Python on your system.

#### Install Jupyter
With Jupyter, you intersperse code and text in one big file called a &#34;notebook&#34;. It is very convenient to write code, test, and visualize results. Highly recommended for research use.

* Please [install Anaconda](http://continuum.io/downloads). If your lab does not have a preference, I use Python 3.
* Open the Terminal (Mac) or Command Prompt (Windows), and type ```conda install jupyter```. Follow the installation procedures.
* To run, open the Terminal (Mac) or Command Prompt (Windows) and type ```jupyter notebook```. When it&#39;s loaded, click on &#34;New&#34; (at the top right) to create a new notebook.

Please [email](mailto:marwahaha@berkeley.edu) if you have any installation issues.

#### Plaintext editor
Sublime Text is recommended, which you can [download here](http://sublimetext.com/).

#### Python 2 vs Python 3
Python 3 (released in 2008) is the newest version of Python, and most features have not changed. Most packages have been updated to Python 3 by now (2016). So, if your lab does not have a preference, I recommend using Python 3. 

There are a couple key differences for novice programmers:

* In Python 2, you can print with ```print 42``` or ```print(42)```. In Python 3, you need to use parentheses, like in ```print(42)```.
* In Python 2, division of two integers like ```5/2``` will evaluate to ```2```. (Python will drop the remainder if both numbers are integers.) Python 3 does exact division (in this example, ```2.5```). 
	* If you use Python 2 and do not want this behavior, add this line at the top of each program: ```from __future__ import division```. 






## Learning Resources
Here are a great list of learning resources when getting started with Python:


#### Beginner

* [Start here](https://try-python.appspot.com/) with this 10-minute tutorial. When it loads, type ```tutorial``` and press Enter to start.

* [Go through these exercises](https://bids.github.io/2016-01-14-berkeley/python/00-python-intro.html) (courtesy of Software Carpentry) 


#### Longer Reads

* [Python for Social Sciences](http://www-rohan.sdsu.edu/~gawron/python_for_ss/course_core/book_draft/Preface/Preface.html), a free online book by jean Mark Gawron


#### Other

* [Python at Berkeley](http://python.berkeley.edu/learning_resources.html)

* Lessons on [other topics](http://software-carpentry.org/lessons/) are available from Software Carpentry


## Past topics
* See our past topics [here](/learnpython/past).


## Suggestions
* Have something you want to add? Send an [email](mailto:marwahaha@berkeley.edu) to marwahaha@berkeley.edu.


{% highlight python %}
def hello():
    print("hello world")
{% endhighlight %}
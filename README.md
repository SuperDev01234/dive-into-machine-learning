Hi there! This guide is for you:

* You're new to Machine Learning
* You can understand and write Python code. (If you want to learn Python, try [Dive Into Python.](http://www.diveintopython.net/))

I learned Python by diving in, hacking, and *then* getting serious. I wanted to do this with Machine Learning. If this is your style, join me in getting a bit ahead of yourself.

Note: there are several fields within "Data," and Machine Learning is just one. It's good to know the context. [What is the difference between Data Analytics, Data Analysis, Data Mining, Data Science, Machine Learning, and Big Data?](http://www.quora.com/What-is-the-difference-between-Data-Analytics-Data-Analysis-Data-Mining-Data-Science-Machine-Learning-and-Big-Data-1)

# Get your feet wet!

I suggest you get your feet wet ASAP. It'll help you navigate and boost your confidence.

## Tools you'll need

- [Python](https://www.python.org/downloads/). (I'm using 2.7.5) and [pip](https://pip.pypa.io/en/latest/installing.html), the Python package manager
- [ipython](http://ipython.org/install.html), the best interactive prompt (and much more) — it's part of the reason scientists love Python. `pip install "ipython[notebook]"`
- Some scientific computing packages: `pip install scikit-learn pandas matplotlib numpy`

If you're only using Python for scientific computing, you can grab these tools in one convenient package: [Anaconda](https://store.continuum.io/cshop/anaconda/).

## Let's go!

Follow along with this tutorial. Open up `ipython` and follow along in your interactive prompt. It's a brief exercise and it'll really boost your confidence.

**[An introduction to machine learning with scikit-learn](http://scikit-learn.org/stable/tutorial/basic/tutorial.html)**

You just classified some hand-written digits! Neat huh?

[**scikit-learn**](http://scikit-learn.org/stable/index.html) is a go-to for machine learning in Python. [Some recognizable logos use it, including Spotify and Evernote.](http://scikit-learn.org/stable/testimonials/testimonials.html) Machine learning is complex, and  you're going to be very glad your tools are simple.

Once you're done with that, I encourage you to look at the [scikit-learn homepage](http://scikit-learn.org/stable/index.html) and spend about 5 minutes looking over the strategies (Classification, Regression, etc.), and their applications and algorithm names. Don't click through yet! Just get a glimpse of the vocabulary.

# Immerse yourself

## A Few Useful Things to Know about Machine Learning

This is the best single thing you can do, to start studying machine learning: read **[A Few Useful Things to Know about Machine Learning](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf)** by Pedro Domingos. It's densely packed with valuable information, but not opaque. The author understands that there's a lot of "black art" and folk wisdom, and they invite you in. (Thanks to Mansi Sheth for this resource.)

Take your time with this one. Take notes.

This whole paper is packed with meaning in value, but I want to call out two very important points:

- **Data alone is not enough.** This is where "art" meets "science" in machine-learning. Quoting Domingos: "... the need for knowledge in learning should not be surprising. Machine learning is not magic; it can’t get something from nothing. What it does is get more from less. Programming, like all engineering, is a lot of work: we have to build everything from scratch. Learning is more like farming, which lets nature do most of the work. Farmers combine seeds with nutrients to grow crops. Learners combine knowledge with data to grow programs."
- **More data beats a cleverer algorithm.** This is important to programmers. We like cool tools, sometimes even when they're the _wrong_ tools. But especially in ML, your starting point should be to [Do the Simplest Thing that Could _Possibly_ Work](http://www.artima.com/intv/simplest3.html). Quoting Domingos: "Suppose you’ve constructed the best set of features you can, but the classifiers you’re getting are still not accurate enough. What can you do now? There are two main choices: design a better learning algorithm, or gather more data. [...] As a rule of thumb, a dumb algorithm with lots and lots of data beats a clever one with modest amounts of it. (After all, machine learning is all about letting data do the heavy lifting.)"

Summarizing these two points, **data** and **knowledge** are the two keys to success. In practice, this means that unless you _have_ to increase complexity, you should continue to [Do Simple Things][]; don't rush to neural networks just because they seem cool. To improve your model, get more data, and use your knowledge (that is, apply your "art," and manipulate the data). You should spend most of your time on these steps. Optimizing your algorithm should only come after that.

TODO add Pyramid screenshot from powerpoint (see Desktop on work computer...) && credit that it was inspired by https://www.blackhat.com/docs/webcast/02192015-secure-because-math.pdf

[Do Simple Things]: http://c2.com/cgi/wiki?DoSimpleThings

## Talking Machines

Take a moment to subscribe to **[Talking Machines](http://www.thetalkingmachines.com/)**, a podcast about machine learning. It's very good, especially for a technical podcast. It's not essential, but it's a low-effort, high-yield way to learn more.

## Play to learn

Play along with at least one of these ipython notebooks. Pick one about a problem you're interested in!

- todo add titanic ones you played with
- todo add more from https://github.com/ipython/ipython/wiki/A-gallery-of-interesting-IPython-Notebooks#statistics-machine-learning-and-data-science
- todo add more from http://nb.bianp.net/sort/views/
- ClickSecurity's "data hacking" series (thanks Aaron Baillargeon!)
	- [Detect Algorithmically Generated Domains](http://nbviewer.ipython.org/github/ClickSecurity/data_hacking/blob/master/dga_detection/DGA_Domain_Detection.ipynb) 
	- [Detect SQL Injection](http://nbviewer.ipython.org/github/ClickSecurity/data_hacking/blob/master/sql_injection/sql_injection.ipynb)
- [An Introduction to Supervised Learning via Scikit Learn](http://bugra.github.io/work/notes/2014-11-22/an-introduction-to-supervised-learning-scikit-learn/)
- [An Introduction to Unsupervised Learning via Scikit Learn](http://bugra.github.io/work/notes/2014-11-16/an-introduction-to-unsupervised-learning-scikit-learn/)
- Data science (TODO - should these be moved down to special section...? i.e. I think all these notebooks up here should be the IMMERSIVE ones?)
	- [Practical Data Science](http://radimrehurek.com/data_science_python/)
	- [Learn Data Science (an entire self-directed course!)](http://learnds.com/)

There are more places to find great ipython notebooks:

* [A Gallery of Interesting IPython notebooks (wiki page on GitHub): Statistics, Machine Learning and Data Science](https://github.com/ipython/ipython/wiki/A-gallery-of-interesting-IPython-Notebooks#statistics-machine-learning-and-data-science)
* http://nb.bianp.net/sort/views/

# Dive Deeper: Coursework

## Your main course

**[Prof. Andrew Ng (Stanford)'s online course _Machine Learning_]( https://www.coursera.org/course/ml) is the free online course I see recommended the most.**

It's helpful if you decide on a pet project to play around with, as you go, so you have a way to apply your knowledge. You could use one of these [Awesome Public Datasets](https://github.com/caesar0301/awesome-public-datasets). And remember, ipython notebook is your friend.

Also, the book _[Elements of Statistical Learning](http://statweb.stanford.edu/~tibs/ElemStatLearn/)_ comes up frequently, but is usually referred to as a "reference" not an introduction. It's free, so download or bookmark it!

### Alternative main courses

Other free online courses I've [seen recommended](https://docs.google.com/document/d/1YN6BVdReNAYc8B0fjQ84yzDflqmeEPj7S0Xc-9_26R0/):

* [Advanced Statistical Computing (Vanderbilt, BIOS366)](http://stronginference.com/Bios366/lectures.html) -- great option, highly interactive (lots of ipython notebook)
* [Data Science (Harvard, CS109)](http://cs109.github.io/2014/)
* [Data Science (General Assembly)](https://github.com/justmarkham/DAT3)

## Learn Pandas well

If you're focusing on Python, you should get more familiar with Pandas.

* [10 Minutes to Pandas](http://pandas.pydata.org/pandas-docs/stable/10min.html)
* [Things in Pandas I Wish I'd Had Known Earlier](http://nbviewer.ipython.org/github/rasbt/python_reference/blob/master/tutorials/things_in_pandas.ipynb) (ipython notebook)

Thanks [Gideon Wulfsohn](http://gideon.ml/) for [organizing these resources!](https://docs.google.com/document/d/1YN6BVdReNAYc8B0fjQ84yzDflqmeEPj7S0Xc-9_26R0)

## Cheat sheets

Bookmark these cheat sheets:

- [scikit-learn algorithm cheat sheet](http://scikit-learn.org/stable/tutorial/machine_learning_map/)
- [Metacademy: a package manager for [machine learning] knowledge](http://hunch.net/?p=2714). A mind map of machine learning concepts, with great detail on each.

## More topics

### Data Science

* **[An entire self-directed course in Data Science, as a IPython Notebook](http://learnds.com/)**
* Extremely accessible data science book: [_Data Smart_ by John Foreman](http://www.john-foreman.com/data-smart-book.html) 
* [Data Science Workflow: Overview and Challenges](http://cacm.acm.org/blogs/blog-cacm/169199-data-science-workflow-overview-and-challenges/fulltext) (read the article & the comment by Joseph McCarthy)


### Many more specialized topics

Check out [Gideon Wulfsohn](http://gideon.ml/)'s [**excellent** introduction to Machine Learning](https://docs.google.com/document/d/1YN6BVdReNAYc8B0fjQ84yzDflqmeEPj7S0Xc-9_26R0) for specialized knowledge on many topics... including [Ensemble Methods](http://www.quora.com/How-do-random-forests-work-in-laymans-terms), [Apache Spark](https://spark.apache.org/examples.html), [Neural Networks](https://www.coursera.org/course/neuralnets), [Reinforcement Learning](http://pybrain.org/), [Natural Language Processing](https://nltk.org) ([RNN](https://github.com/IndicoDataSolutions/Passage), [LDA](http://bugra.github.io/work/notes/2015-02-21/topic-modeling-for-the-uninitiated/), [Word2Vec](http://radimrehurek.com/2014/02/word2vec-tutorial/)), [Structured Prediction](https://pystruct.github.io/), [Deep Learning](https://www.youtube.com/watch?v=S75EdAcXHKk), [Distributed Systems (Hadoop Ecosystem)](http://web.stanford.edu/class/cs246/), Graphical Models ([Hidden Markov Models](http://www.autonlab.org/tutorials/hmm.html)), [Hyper Parameter Optimization](https://github.com/hyperopt/hyperopt), [GPU Acceleration (Theano)](http://deeplearning.net/software/theano/tutorial/using_gpu.html), [Computer Vision](http://deeplearning.net/tutorial/lenet.html), Internet of Things, and Visualization.

## Questions, answers, chats

For now, the best StackExchange site is  [stats.stackexchange.com – _machine-learning_.](http://stats.stackexchange.com/questions/tagged/machine-learning?sort=frequent&pageSize=15) (There's also [datascience.stackexchange.com](http://datascience.stackexchange.com/), but it's still in Beta.) And there's [/r/machinelarning](http://www.reddit.com/r/machinelearning). There are also many relevant discussions on Quora, for example: [What is the difference between Data Analytics, Data Analysis, Data Mining, Data Science, Machine Learning, and Big Data?](http://www.quora.com/What-is-the-difference-between-Data-Analytics-Data-Analysis-Data-Mining-Data-Science-Machine-Learning-and-Big-Data-1)

You should also [join the Gitter channel for scikit-learn!]( https://gitter.im/scikit-learn/scikit-learn)



# Assorted Opinions and Other Resources

The rest of the stuff that might not be structured enough for a course, but seems important to know.

## Risks

"Machine learning systems automatically learn programs from
data." Pedro Domingos, in *[A Few Useful Things to Know about Machine Learning.](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf)* The programs you generate will require maintenance. Like any way of creating programs faster, you can rack up technical debt.

Really essential:

- **[Surviving Data Science "at the Speed of Hype"](http://www.john-foreman.com/blog/surviving-data-science-at-the-speed-of-hype)** by John Foreman, Data Scientist at MailChimp
- [11 Clever Methods of Overfitting and How to Avoid Them](http://hunch.net/?p=22)

A worthwhile paper: [Machine Learning: The High-Interest Credit Card of Technical Debt.](https://static.googleusercontent.com/media/research.google.com/en/us/pubs/archive/43146.pdf) Here's the abstract:

> Machine learning offers a fantastically powerful toolkit for building complex systems quickly. This paper argues that it is dangerous to think of these quick wins as coming for free. Using the framework of technical debt, we note that it is remarkably easy to incur massive ongoing maintenance costs at the system level when applying machine learning. The goal of this paper is highlight several machine learning specific risk factors and design patterns to be avoided or refactored where possible. These include boundary erosion, entanglement, hidden feedback loops, undeclared consumers, data dependencies, changes in the external world, and a variety of system-level anti-patterns.

And a few more articles:

- [The Perilous World of Machine Learning for Fun and Profit: Pipeline Jungles and Hidden Feedback Loops](http://www.john-foreman.com/blog/the-perilous-world-of-machine-learning-for-fun-and-profit-pipeline-jungles-and-hidden-feedback-loops)
- [The High Cost of Maintaining Machine Learning Systems](http://www.kdnuggets.com/2015/01/high-cost-machine-learning-technical-debt.html)

### An anecdote from a Data Engineer at a Popular Music Streaming Service
I have a friend who was a Data Engineer at `<Redacted>` Music Streaming Service. His team focused on the machine learning they used for their recommendation systems and such.

He complained about the way they were scoring the performance of their radio feature. He said there was disagreement and worse, lack of specification, around what should be scored. He told me, they were using "no song skips" to score a recommendation as good. But why? He said, sure that indicates the recommendation wasn't *awful*, but his opinion was that you want to measure engagement: "favorites," how long they listen to this radio station, whether they come back to this station. He said measuring "no skips" doesn't work for an engaged listener; sure, they skipped 5 songs, but they found 20 they loved (and came back to the service to listen to). He asked, are we trying to please the discerning, engaged listener, or the inattentive one?

**My takeaway:** if you're using machine learning to benefit your users, you need to understand them. And you need to understand *which kind* of user you're trying to benefit, before you can score the performance of your models.

### Machine Learning in InfoSec and AppSec

There was a great BlackHat webcast on this topic, [Secure Because Math: Understanding Machine Learning-Based Security Products.](https://www.blackhat.com/html/webcast/02192015-secure-because-math.html) Slides are [there](https://www.blackhat.com/html/webcast/02192015-secure-because-math.html), [video recording is here.](https://attendee.gotowebinar.com/recording/80449431422110210)


## Big Data?

Scaling data analysis is a familiar problem now, and there's no shortage of ways to address it. [Beware needless hype and companies that want to sell you flashy, proprietary solutions.](http://www.john-foreman.com/blog/surviving-data-science-at-the-speed-of-hype) You can do it all with open-source tools. Even if you contract it, you consider looking for contractors who use known good stacks. No news here.

Here are some are some obvious tools to reach for: 

* **[Apache Spark.](https://spark.apache.org/)**
	* I mean, hell, [Spark has DataFrames and easy co-operability with pandas!](http://databricks.com/blog/2015/02/17/introducingdataframes-in-spark-for-large-scale-data-science.html)
	* Berkeley has [a course on Scalable Machine Learning, focusing on Apache Spark.](https://www.edx.org/course/scalable-machine-learning-uc-berkeleyx-cs190-1x#.VOC70VPF_lQ)
* [NetflixOSS](http://netflix.github.io/#repo) (see "Big Data Tools")
	* [Netflix: Surus and ScorePMML](http://techblog.netflix.com/2015/01/introducing-surus-and-scorepmml.html)
	* ["big data" on the NetflixOSS blog](http://techblog.netflix.com/search/label/big%20data)

Also: [10 things statistics taught us about big data analysis](http://simplystatistics.org/2014/05/22/10-things-statistics-taught-us-about-big-data-analysis/)

## Et cetera

For Machine-Learning libraries that might not be on GitHub, there's [MLOSS (Machine Learning Open Source Software)](http://mloss.org/software/). Seems to feature many academic libraries.

[Kaggle](http://www.kaggle.com/) has really exciting [competitions](http://www.kaggle.com/competitions) and a [data science job board](http://www.kaggle.com/jobs).

Lastly, here are other guides to Machine Learning:

* [How to Machine Learn](https://docs.google.com/document/d/1YN6BVdReNAYc8B0fjQ84yzDflqmeEPj7S0Xc-9_26R0/edit) by [Gideon Wulfsohn](http://gideon.ml/)
	* Features links to find meetups about ML
	* Features links to "deeper dive" specialized topics
* [Your guide here]
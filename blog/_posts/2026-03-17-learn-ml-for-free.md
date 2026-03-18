---
layout: post
title: Learn Machine Learning for Free
date: 2026-03-17
tags: computer-science education guides machine-learning
---

## So you want to learn machine learning...
Have you ever wondered how your favorite large language model is able to come up with personalized responses? How about how your streaming platform decides what movies to recommend to you? And what's the deal with those weird "I am not a robot" CAPTCHAs?

These are all examples of *machine learning*, a subfield of computer science that's all about how algorithms can learn patterns from data. Machine learning is why we can predict climate change, why your favorite shopping website knows *just* the right product for you, and why now at the airport you don't even have to show your passport anymore to get on the plane. Just step right up to the camera and have your face automatically recognized! This is not creepy at all!

<figure>
    <img src="/assets/images/nyt_airport.jpg">
    <figcaption>Facial recognition at the airport. Source: <a href="https://www.nytimes.com/2022/02/26/travel/facial-recognition-airports-customs.html">The New York Times</a></figcaption>
</figure>

### So... what even *is* machine learning?
After all, what could movie recommendations possibly have in common with boarding an airplane? The versatility in applications is one of the reasons why machine learning is such a rich field—*everyone* (in technologically developed societies) has encountered machine learning at some point and *anyone* can become a machine learning scientist! And even if you have other interests, it's very possible you will be using machine learning in some capacity. Linguists may use [natural language processing](https://en.wikipedia.org/wiki/Natural_language_processing) to understand a large corpus of textual data. Physicists may [combine machine learning with quantum mechanics](https://en.wikipedia.org/wiki/Quantum_machine_learning). What's in your burger? Even [your food](https://en.wikipedia.org/wiki/Precision_agriculture) maybe influenced by machine learning!

What do these seemingly unrelated areas have in common? The answer is *lots of data*. Whether it be books, or particles, or crop yields, machine learning can abstract patterns from the data itself. This is in contrast to [good old-fashioned artificial intelligence (GOFAI)](https://en.wikipedia.org/wiki/GOFAI), where algorithmic decisions are driven by symbolic rules rather than the underlying data.

You can think of the difference like this: in GOFAI, we apply our rules to the data. In machine learning, we learn the rules from the data itself. This has both benefits and drawbacks. On one hand, machine learning can often achieve more accurate results in comparison to GOFAI, and may mitigate some human bias. On the other hand, accurate machine learning models may require a *lot* of data, take a *lot* of time and energy to train, and is prone to errors or bias in the data itself. Whichever approach you take will depend on your specific application and your available resources.

### Let's get ready to learn!
You might be thinking: how very exciting! I'm ready to predict financial markets and make my own chatbot with machine learning. I'm going to ask you to hold onto your excitement for a moment, because we need to cover some basics.

To truly understand machine learning, you will need to understand both the underlying mathematics of how this technology works, as well as the programming skills necessary to implement them. In the rest of this article, I will lay out a path for learning the basic skills required to understand machine learning, complete with resources to do so for free. I'm going to be assuming that you have at least of high school understanding of mathematics.

## Mathematics
Though machine learning can appear almost magical, it really boils down to math. In particular, the most fundamental areas of mathematics as it pertains to machine learning are probability and statistics, calculus, and linear algebra. I'll describe them all briefly here and provide some resources where you can learn them for free!

### Probability and Statistics
*Probability* is an area of mathematics concerned with the behavior and prediction of random events. In machine learning, because we derive our rules from the data itself, we cannot always be certain that our derived rules are correct. If the data is sufficiently complex, there may even be contradictions in our dataset! So, when we are making predictions in machine learning, for example when classifying images, we almost never say with certainty "this is picture of a chihuahua." More likely, we will say something like "this is a picture of a chihuahua with 90% probability."

<figure>
    <img src="/assets/images/chihuahua.jpg">
    <figcaption>Is this a chihuahua or a muffin? Source: <a href="https://blog.cloudsight.ai/chihuahua-or-muffin-1bdf02ec1680">CloudSight</a></figcaption>
</figure>

Distinct from but related to probability is *statistics*, which applies mathematical methods to data in order to understand characteristics of a population. Often, this involves taking data from a sample and running statistical tests to see whether or not observations generalize to the larger population. Knowledge of probability is required to understand statistics, but not necessarily vice versa!

Though they are technically two different areas of mathematics, they are closely related an often taught in conjunction in college courses, so I've decided to include them together here. Here are some free resources for learning about probability and statistics:
- [StatLect](https://www.statlect.com/) (online textbook)
- [Statistics Fundamentals](https://www.youtube.com/playlist?list=PLblh5JKOoLUK0FLuzwntyYI10UQFUhsY9) by StatQuest with Josh Starmer (video series)
- [Essence of probability](https://www.youtube.com/watch?v=HZGCoVF3YvM&list=PLiAulSm0XXgvCGe63mrAkda9UQ9478YQv) by 3Blue1Brown (video series)
- [Introduction to Probability and Statistics](https://ocw.mit.edu/courses/18-05-introduction-to-probability-and-statistics-spring-2022/) by MIT OpenCourseware (online course)
- [AP Calculus](https://www.khanacademy.org/math/ap-statistics) by Khan Academy (online course)

### Calculus
*Calculus* is often described as the study of "rate of change." It is essentially the concept of *slope* from your high school algebra course, taken to the next level. Colleges (in America) typically offer three calculus courses: Calc 1, 2, and 3 correspond to derivative calculus, integral calculuss, and multivariable calculus, respectively. To understand machine learning, you will definitely want to take up until the multivariable level. This is because much of machine learning relies on the principle of *[gradient descent](https://en.wikipedia.org/wiki/Gradient_descent)*. I won't go into too much detail here, but trust me, calculus is very much needed! Here are some great free resources:
- [Essence of calculus](https://www.youtube.com/watch?v=WUvTyaaNkzM&list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr) by 3Blue1Brown (YouTube)
- [Calculus 1](https://tutorial.math.lamar.edu/Classes/CalcI/CalcI.aspx), [Calculus 2](https://tutorial.math.lamar.edu/Classes/CalcII/CalcII.aspx), and [Calculus 3](https://tutorial.math.lamar.edu/Classes/CalcIII/CalcIII.aspx) by Paul's Online Notes (online textbook)
- [Single Variable Calculus](https://ocw.mit.edu/courses/18-01sc-single-variable-calculus-fall-2010/) and [Multivariable Calculus](https://ocw.mit.edu/courses/18-02sc-multivariable-calculus-fall-2010/) by MITOpenCourseWare (online course)
- [AP Calculus AB](https://www.khanacademy.org/math/ap-calculus-ab), [AP Calculus BC](https://www.khanacademy.org/math/ap-calculus-bc) and [Multivariable Calculus](https://www.khanacademy.org/math/multivariable-calculus) by Khan Academy (online course)

### Linear Algebra
Remember in algebra class when you were given two lines and had to solve for the x and y coordinates of the intersection? This is like that, only way more variables and way more lines! And sometimes there might be no solution, or many solutions! Linear algebra takes those equations from algebra and turns them into *vectors*, and then stacks those vectors to create *matrices*. Linear algebra is important to machine learning because oftentimes you can think of machine learning as a really advanced "line of best fit" problem. Each data point is essentially a collection of variables, so a vector, which means that the entire dataset is a matrix. Then we want to computer to solve this system of equations to find the solution that best fits all our data. Pretty neat, right? Here are some free resources for studying linear algebra:
- [Essence of linear algebra](https://www.youtube.com/watch?v=fNk_zzaMoSs&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) by 3Blue1Brown (YouTube)
- [Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) by MITOpenCourseWare (MY PERSONAL FAVORITE, PROFESSOR GILBERT STRANG IS THE BEST!!)

Now that we have the mathematical bases down, let's get coding!

## Programming
What fun is learning the math if we don't get to apply it to something? This is where the programming comes in-let's get coding! The four topics I'll cover in this section are programming basics, data management, data analysis, and data visualization.

### Programming basics
To program machine learning comfortably, you will need to first get comfortable with basic principles in computer science. While your choice of programming language does not necessarily have a huge bearing on your understanding of concepts, I do recommended that if you are learning for the first time that you start with [Python](https://www.python.org/). Not only is Python extremely human-readable, making it the perfect language for beginners, it also is the most common language used for machine learning applications. Here are some good resources for learning Python:
- [Python's Getting Started Page](https://www.python.org/about/gettingstarted/)
- [Intro to computer science - Python](https://www.khanacademy.org/computing/intro-to-python-fundamentals) by Khan Academy
- [Learn Python 3](https://www.codecademy.com/learn/learn-python-3) by Codecademy
- [Python Tutor](https://pythontutor.com/) (program visualizer)

### Data structures and algorithms
This is the real "meat" of a computer science curriculum, so to speak. Data structures are different ways we can store our data, and our choice of data structure will impact things like how long it takes to access our data, or obtain certain properties of our data. Algorithms are ways we can interact with our data, for example sorting it, or searching for a particular data point, or finding an optimal solution to a problem. Similar to probability and statistics, while these are technically different concepts, they are very much related so they are often taught together. Here are some free resources for learning data structures and algorithms:
- [DSA Tutorial](https://www.w3schools.com/dsa/index.php) by W3 Schools (online textbook)
- [Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-spring-2020/) by MITOpenCourseware (online course)

And I will also briefly plug my own YouTube channel, [CS Professor of Fun](https://www.youtube.com/@CSProfessorofFun). Check it out!

### Data management
Sometimes, the data will not be formatted in a way that you like, or may be too big to process all at once. This is where data management comes into play, for example [preprocessing](https://en.wikipedia.org/wiki/Data_preprocessing). Admittedly, this is not my area of expertise, so what I can say on this is limited. Some technologies to checkout are [SQL](https://www.w3schools.com/sql/) and [PySpark](https://spark.apache.org/docs/latest/api/python/index.html).

### Data analysis
How do we actually apply machine learning models to our data? Here are some helpful libraries to know. For basic data analysis:
- [NumPy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/)

For machine learning specifically:
- [scikit-learn](https://scikit-learn.org/stable/index.html)
- [PyTorch](https://pytorch.org/)
- [TensorFlow](https://www.tensorflow.org/)

### Data Visualization
It's one thing to run the machine learning model, and another thing to understand it. Because machine learning is often a [black box](https://en.wikipedia.org/wiki/Black_box) (i.e. we don't always know what it's doing), we often rely on visualizations to help us make sense of our results. Here are some popular data visualization libraries:
- [Matplotlib](https://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/)
- [Plotly](https://plotly.com/python/)

## What's next?
In this article I briefly covered the basic mathematics and programming knowledge required for understanding machine learning. But machine learning encompasess many many subfields each with their own unique quirks. For next steps, I would recommend you get started with [StatQuest's Machine Learning playlist](https://www.youtube.com/playlist?list=PLblh5JKOoLUICTaGLRoHQDuF_7q2GfuJF). [Regression](https://en.wikipedia.org/wiki/Regression_analysis) into [neural networks](https://en.wikipedia.org/wiki/Neural_network_(machine_learning)) also provide a nice entry point. After that, the world's your oyster! Study whatever method or application you find interesting.
# WHAT IS MACHINE LEARNING?
At a very high level, machine learning is the process of teaching a computer system how to make accurate predictions when fed data.

Those predictions could be answering whether a piece of fruit in a photo is a banana or an apple, spotting people crossing the road in front of a self-driving car, whether the use of the word book in a sentence relates to a paperback or a hotel reservation, whether an email is spam, or recognizing speech accurately enough to generate captions for a YouTube video.

The key difference from traditional computer software is that a human developer hasn't written code that instructs the system how to tell the difference between the banana and the apple.

Instead a machine-learning model has been taught how to reliably discriminate between the fruits by being trained on a large amount of data, in this instance likely a huge number of images labelled as containing a banana or an apple.

# WHAT IS THE DIFFERENCE BETWEEN AI AND MACHINE LEARNING?
Machine learning may have enjoyed enormous success of late, but it is just one method for achieving artificial intelligence.

At the birth of the field of AI in the 1950s, AI was defined as any machine capable of performing a task that would typically require human intelligence.

AI systems will generally demonstrate at least some of the following traits: planning, learning, reasoning, problem solving, knowledge representation, perception, motion, and manipulation and, to a lesser extent, social intelligence and creativity.

Alongside machine learning, there are various other approaches used to build AI systems, including evolutionary computation, where algorithms undergo random mutations and combinations between generations in an attempt to "evolve" optimal solutions, and expert systems, where computers are programmed with rules that allow them to mimic the behavior of a human expert in a specific domain, for example an autopilot system flying a plane.

**WHAT ARE THE MAIN TYPES OF MACHINE LEARNING?
Machine learning is generally split into two main categories: supervised and unsupervised learning.**

# WHAT IS SUPERVISED LEARNING?
This approach basically teaches machines by example.

During training for supervised learning, systems are exposed to large amounts of labelled data, for example images of handwritten figures annotated to indicate which number they correspond to. Given sufficient examples, a supervised-learning system would learn to recognize the clusters of pixels and shapes associated with each number and eventually be able to recognize handwritten numbers, able to reliably distinguish between the numbers 9 and 4 or 6 and 8.

However, training these systems typically requires huge amounts of labelled data, with some systems needing to be exposed to millions of examples to master a task.

As a result, the datasets used to train these systems can be vast, with Google's Open Images Dataset having about nine million images, its labeled video repository YouTube-8M linking to seven million labeled videos and ImageNet, one of the early databases of this kind, having more than 14 million categorized images. The size of training datasets continues to grow, with Facebook recently announcing it had compiled 3.5 billion images publicly available on Instagram, using hashtags attached to each image as labels. Using one billion of these photos to train an image-recognition system yielded record levels of accuracy -- of 85.4 percent -- on ImageNet's benchmark.

The laborious process of labeling the datasets used in training is often carried out using crowdworking services, such as Amazon Mechanical Turk, which provides access to a large pool of low-cost labor spread across the globe. For instance, ImageNet was put together over two years by nearly 50,000 people, mainly recruited through Amazon Mechanical Turk. However, Facebook's approach of using publicly available data to train systems could provide an alternative way of training systems using billion-strong datasets without the overhead of manual labeling.


# WHAT IS UNSUPERVISED LEARNING?
In contrast, unsupervised learning tasks algorithms with identifying patterns in data, trying to spot similarities that split that data into categories.

An example might be Airbnb clustering together houses available to rent by neighborhood, or Google News grouping together stories on similar topics each day.

The algorithm isn't designed to single out specific types of data, it simply looks for data that can be grouped by its similarities, or for anomalies that stand out.

# WHAT IS SEMI-SUPERVISED LEARNING?
The importance of huge sets of labelled data for training machine-learning systems may diminish over time, due to the rise of semi-supervised learning.

As the name suggests, the approach mixes supervised and unsupervised learning. The technique relies upon using a small amount of labelled data and a large amount of unlabelled data to train systems. The labelled data is used to partially train a machine-learning model, and then that partially trained model is used to label the unlabelled data, a process called pseudo-labelling. The model is then trained on the resulting mix of the labelled and pseudo-labelled data.

The viability of semi-supervised learning has been boosted recently by Generative Adversarial Networks ( GANs), machine-learning systems that can use labelled data to generate completely new data, for example creating new images of Pokemon from existing images, which in turn can be used to help train a machine-learning model.

Were semi-supervised learning to become as effective as supervised learning, then access to huge amounts of computing power may end up being more important for successfully training machine-learning systems than access to large, labelled datasets.

# WHAT IS REINFORCEMENT LEARNING?
A way to understand reinforcement learning is to think about how someone might learn to play an old school computer game for the first time, when they aren't familiar with the rules or how to control the game. While they may be a complete novice, eventually, by looking at the relationship between the buttons they press, what happens on screen and their in-game score, their performance will get better and better.

An example of reinforcement learning is Google DeepMind's Deep Q-network, which has beaten humans in a wide range of vintage video games. The system is fed pixels from each game and determines various information about the state of the game, such as the distance between objects on screen. It then considers how the state of the game and the actions it performs in game relate to the score it achieves.

Over the process of many cycles of playing the game, eventually the system builds a model of which actions will maximize the score in which circumstance, for instance, in the case of the video game Breakout, where the paddle should be moved to in order to intercept the ball.

# HOW DOES SUPERVISED MACHINE LEARNING WORK?
Everything begins with training a machine-learning model, a mathematical function capable of repeatedly modifying how it operates until it can make accurate predictions when given fresh data.

Before training begins, you first have to choose which data to gather and decide which features of the data are important.

A hugely simplified example of what data features are is given in this explainer by Google, where a machine learning model is trained to recognize the difference between beer and wine, based on two features, the drinks' color and their alcoholic volume (ABV).

Each drink is labelled as a beer or a wine, and then the relevant data is collected, using a spectrometer to measure their color and hydrometer to measure their alcohol content.

An important point to note is that the data has to be balanced, in this instance to have a roughly equal number of examples of beer and wine.

The gathered data is then split, into a larger proportion for training, say about 70 percent, and a smaller proportion for evaluation, say the remaining 30 percent. This evaluation data allows the trained model to be tested to see how well it is likely to perform on real-world data.

Before training gets underway there will generally also be a data-preparation step, during which processes such as deduplication, normalization and error correction will be carried out.

The next step will be choosing an appropriate machine-learning model from the wide variety available. Each have strengths and weaknesses depending on the type of data, for example some are suited to handling images, some to text, and some to purely numerical data.

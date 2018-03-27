---
id: research
name: Research
heading: Research
subheading: Research&#58;
image: ""
---
# Research Interest

I am curious about our intelligent ability to learn.

Artificial Intelligence Branches:
* Machine Learning: How do machines learn?
* Evolutionary Intelligence: Natural Selection of machines
* Swarm Intelligence: How do machines learn as a society of groups?
* Natural Language Processing: How do machines read? 
* Computer Vision: How do machines see?
* Speech Processing: How do machines hear?
* Robotics: How do machines move? How do machines localize itself to know where it is in the world?
* Constraint Satisfaction Problem: How do machines plan? 
* Knowledge Representation: How do machines represent knowledge and logically reason from it? 
* Computer Graphics: How do machines imagine? Inverse of Computer Vision (opposite of seeing)

I am passionate about Artificial Intelligence, especially Machine Learning, as it helps me understand how learning works.

For instance, how do we model:
* Instantaneous Learning: How do we train a model to learn from correct examples? Ideas from Mathematical Optimization, Sampling, Variational Inference
* Delayed Learning: How do we learn by rewards and punishment? Ideas from Animal Learning, Reinforcement Learning, Optimal Control Theory, Dynamic Programming
* Credit Assignment: After we finally succeed, how do we assign credit to which path along our success was more important for our success? 
* Inference: How do we calculate probability of events given evidences? Ideas from Probabilistic Graphical Models.
* Planning: How do we plan what to do given our available information? Ideas from Markov Decision Processes, Decision Trees.
* Information: How do we calculate how much information we have gathered or could gather? Ideas from Information Theory, Uncertainty, bayesian posterior beliefs distribution, expected improvement.
* Uncertainty: How do we know if a model is uncertain in its predictions?
* Signal Processing: How do we decide if an input or data is useful information or noise? Ideas from Signal Detection Theory.
* Memory: How do we remember or forget information? ideas from Sequential Circuits in Digital Logics, to delayed processing. 
* Attention: The idea of focusing. Where to focus? When to focus? How long should we focus? Ideas from Information Retrieval
* Active Learning: Actively deciding what to learn, since it's impossible to learn everything.
* Curriculum Learning: Creating a learning syllabus so that the model learns from easy to hard problems.
* Transfer Learning: How do we transfer useful learnt information from one model to another? 
* Knowledge Distillation: How do we transfer the core information from a large model to a smaller model?
* Few Shot Learning: How do we learn from as few examples as possible? 
* Exploration vs Exhaustation: How do we decide if we should explore other decisions or dive into ones we already know?
* Semi-Supervised Learning: How do we learn about the population given a sample? 
* Imbalanced Learning: How do we learn about rare labels when our dataset is imbalanced? 
* Generative Learning: How do we learn to generate realistic data? 

Machine Learning research can be broken down into 4 steps: 
* Step 1: What is the problem? What is the type of data we are working with?
* Step 2: Modelling. What model should we use? What are the potential abilities and drawbacks of this model? 
* Step 3: How do we feasible train the model given our data?
* Step 4: Evaluation. How do we evaluate how well this model has learnt and execute its potential abilities ?

The steps above did not include purely Theoretical Machine Learning research.
Below are just some examples:
* A model must be bias to learn. 
  Intuitively, if you are an unbias learning model, you would divide your time equally between many things,
  then, you'll just be a jack of all trades and never really learn or master anything.
  You really need to be biased towards something to learn. 
  For instance, spend all your efforts working with Mathematics and ignore all other subjects to learn Mathematics.

Machine Learning Models: (not mutually exclusive)
* Nearest Neighbour: Cluster anything similar.
* Kernel Machines, Support Vector Machines: Being as far away from decision boundary as possible.
* Deep Learning, NN, CNN, RNN: Fire when you detect a useful signal.
* Reinforcement Learning: Learning from delayed feedback while planning.
* Probabilistic Graphical Models, BN, HMM, CRF: Ability to perform inference.
* Bayesian Nonparametrics, Gaussian Processes: Model complexity grows with data
* Mixture Models: Symptoms and Observations

Machine Learning Applications:
* Information Retrieval: Google, Yahoo, Search Engines
* Recommender Systems: Amazon, Netflix, Spotify
* Self-Driving Cars(includes Robotics + Computer Vision): Uber, Waymo
* Bioinformatics: Medical Diagnosis
* Machine Translation: Translate Mandarin to English
* Question Answering: Answer questions from customers.
* Image Segmentation: Amazon Go
* Object Detection: Amazon Go
* Face Detection: Facebook, Snapchat
* Style Transfer: Painting
* Anomaly Detection: NSA (jokes), Fraud Detection
* Game Playing: Google DeepMind, OpenAI

I enjoy working with applied math and code. 

* [Statement Of Purpose Fall 2016](./pdf/statementOfPurposeUofTMIE.pdf)

## MASc Research Direction
I am currently working with Sequential Active Learning for Recommender Systems.
* Machine Learning applied to Recommender Systems 
* Active Learning
* Sequential
* Bayesian

Of course, I'll need to bias my time on a very specific research, within the field of Machine Learning.
I will mainly be applying Machine Learning to tackle Recommender Systems problems.

### Problems in Recommender Systems
Within recommender systems itself, there are many interesting problems to tackle.
* Cold-Start: What item do you recommend to a new user? What if the item itself is new? 
* Sparse Rating Matrix: Very few ratings for most of the items. How do you learn in this scenario?
* Imbalanced: Rating Matrix are imbalanced. Majority of the ratings goes to the popular items.
* Semi-supervised Learning: For some applications, you only have data for items user purchased which is normally biased towards items a user likes. Hence, it is a special form of semi-supervised learning. This is also known as the One-Class problem in Recommender Systems
* Active Learning: What should you recommend to learn more about the user for personalized recommendations in future?
* Offline Evaluation: How do we evaluate recommender systems offline, without access to a real online recommender sytem.
* Content Embedding: How do we encode content information regarding users and items into useful embeddings? This also includes content like sound waves, images, geo-location.
* Session-Based Recommendation: How do we recommend in a sequence within a short browsing session?
* Sequential Recommendation: How do we account for time and order of recommendations?

### Exploration-Exploitation Tradeoff
Active learning normally requires a tradeoff between exploring new items vs exploiting popular well known items

The popular approaches to these tradeoffs are:
* Probability of Improvement
* Expected Improvement
* Entropy Search
* Thompson Sampling
* Upper Confidence Bound
* Epsilon Greedy

During the exploring phase, active learning should aim to gain as much information.
It normally gains information at regions it is uncertain about.

During the exploitation phase, active learning should recommend items it is confident about.
This means it is very certain about its recommendation.

To quantify uncertainty, we'll need to resort to full posterior estimates instead of point estimates. 
This leads to intractable Bayesian approaches.

To deal with intractable high dimensional intractable integrals, the popular approaches are:
* Conjugate Priors
* Sampling
* Variational Inference

### Sequential Machine Learning Models
I am mainly working with sequential active learning. 

Models that works great with sequence should have memory over past observations.

Models with memory:
* Recurrent Neural Networks
* Markov Decision Processes
* Reinforcement Learning

# Journals

* [ℚ-bounds consistency for the spread constraint with variable mean](https://link.springer.com/article/10.1007/s10601-016-9238-x)

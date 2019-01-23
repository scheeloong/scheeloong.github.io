---
id: research
name: Research
heading: Research
subheading: Research
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
* Delayed Reward Learning: How do we learn by delayed rewards and punishment? Ideas from Animal Learning, Reinforcement Learning, Optimal Control Theory, Dynamic Programming
* Credit Assignment: After we succeed, how do we assign credit to which path along our success was more important for our success? 
* Inference: How do we calculate probability of events given evidences? Ideas from Probabilistic Graphical Models.
* Planning: How do we plan what to do given our available information? Ideas from Markov Decision Processes, Decision Trees.
* Information: How do we calculate how much information we have gathered or could gather? Ideas from Information Theory, Uncertainty, bayesian posterior beliefs distribution, expected improvement.
* Uncertainty: How do we know if a model is uncertain in its predictions?
* Signal Processing: How do we decide if an input or data is useful information or noise? Ideas from Signal Detection Theory.
* Memory: How do we remember or forget information? ideas from Sequential Circuits in Digital Logics, to delayed processing. 
* Attention: The idea of focusing. Where to focus? When to focus? How long should we focus? Ideas from Information Retrieval. Closely connected to retrieving from memory models.
* Online Learning: Learn from data sequentially in an online manner, since data may only be available in future. 
* Active Learning: Actively deciding what to learn, and which data to annotate, since human annotators are expensive. 
* Diminishing Returns: How do we mathematically model for diminishing returns? Useful for active learning and diversity. Adaptive Submodularity, Determinantal Point Processes
* Cooperation: How do we mathematically model cooperation? Useful for Economies of Scale, relevance. Supermodularity, Ising Models 
* Positive Feedback: How do we model positive feedback or self-exciting events such as earthquakes and financial analysis? Hawkes Processes
* Exploration vs Exploitation: Trading off between exploration to learn for higher future rewards, or exploitation for current rewards. Multi-arm Bandit
* Counterfactual Reasoning: How to estimate what would happen if we took action a instead of b from b's offline data.
* Black-Box Learning: How do we learn to optimize a black-box function by querying arbitrary points. Bayesian Optimization
* Preference Learning: Learning by comparison of what a user prefers instead of the usual independence of does the user like this single training data? Also known as Learning to Rank
* Curriculum Learning: Creating a learning syllabus so that the model learns from easy to hard problems.
* Transfer Learning: How do we transfer useful learnt information from one model to another? 
* Knowledge Distillation: How do we transfer the core information from a large model to a smaller model?
* Few Shot Learning: How do we learn from as few examples as possible? 
* Semi-Supervised Learning: How do we learn about the population given a sample? 
* Imbalanced Learning: How do we learn about rare labels when our dataset is imbalanced? 
* Generative Learning: How do we learn to generate realistic data?
* Ensemble Learning: How do we combine different models together for a single task? 
* Boosting: How to sequentially learn from your mistakes? 
* Manifold Learning: How do we perform non-linear dimensionality reduction? 
* Geometric Learning: How do we learn from graph datasets such as social graphs, economic graphs, 3D Mesh graph?
* Security Machine Learning: How to learn models that are robust towards adversaries nor reveal personal information? 
* Fairness Machine Learning: How to learn models that are unbiased towards discriminatory features? 

Machine Learning research can be broken down into 4 steps: 
* Step 1: What is the problem? What is the type of data we are working with?
* Step 2: Modelling. What model should we use? What are the potential abilities and drawbacks of this model? 
* Step 3: How do we feasible train the model given our data?
* Step 4: Evaluation. How do we evaluate how well this model has learnt and execute its potential abilities ?

The steps above did not include purely Theoretical Machine Learning research.
Below are just some examples:
* No Free Lunch Theorem indicates no classifier is superior over another on all possible test sets,
  including the random classifier. 
* Bias Variance Decomposition

Machine Learning Models: (not mutually exclusive)
* Nearest Neighbour, Parametric: (e.g. KMeans) Cluster anything similar.
* Nearest Neighbour, Non-Parametric: (e.g. KNN) Complexity of decision boundaries grows with data. 
* Decision Trees: Makes interpretable decisions using greedy splitting algorithm.
* Kernel Machines, Support Vector Machines: Being as far away from decision boundary as possible.
* Deep Learning, NN, CNN, RNN: Fire when you detect a useful signal.
* Multi-armed Bandit: Learning from only the action taken (bandit feedback), and no information from others.
* Reinforcement Learning: Learning from delayed rewards while planning.
* Probabilistic Graphical Models, BN, HMM, CRF: Ability to perform inference, counterfactual inference
* Gaussian Models: Modelling real numbers linearly, 
* Linear Gaussian Models, QDA, LDA, PCA, FA, Kalman Filter: Modelling real numbers linearly.
* Dirichlet Models, Latent Dirichlet Allocation: Modelling multinomials
* Bayesian Nonparametrics, Gaussian Processes: Model complexity grows with data
* Mixture Models: Symptoms and Observations

Machine Learning Applications:
* Information Retrieval: Google Search, Yahoo Search
* Recommender Systems: Amazon, Netflix, Spotify, Google News
* Supply Chain Management (know which item are more demanded at different times of year)
* Online Advertising: Google, Facebook
* Self-Driving Cars(includes Robotics + Computer Vision): Uber, Waymo
* Bioinformatics: Medical Diagnosis
* Machine Translation: Google Translate 
* Speech Recognition: Siri, Amazon Echo, Google Home, Youtube Closed Captioning, Cortana
* Question Answering: Answer questions from customers.
* Image Segmentation: Amazon Go
* Object Detection: Amazon Go
* Face Detection: Facebook, Snapchat
* Style Transfer: 500px
* Anomaly Detection: NSA (jokes), Fraud Detection, Spam Filtering
* Game Playing: Google DeepMind, OpenAI
* Sports Analytics: Microsoft Xbox Team, NBA, Chess 
* Healthcare: Clinical Trials (which drug to test for effectiveness) 
* Dynamic Pricing: (trying out which price will earn the most revenue)
* Portfolio Management:  which company and how much investment to make
* Aerial Image Labelling: Google Maps, Crowd AI, Orbital Insight

### Problems in Recommender Systems
Within recommender systems itself, there are many interesting problems to tackle.
* Cold-Start: What item do you recommend to a new user? What if the item itself is new? 
* Sparse Rating Matrix: Very few ratings for most of the items. How do you learn in this scenario?
* Scalable Recommendation: Lots of users, lots of items. Recommendation algorithms needs to scale.
* Diversity: How to recommend a diverse set of items instead of just popular ones? Adaptive Submodularity, Determinantal Point Processes.
* Personalized: How to personalized recommendation to users instead of recommend similar items to all users?
* Imbalanced: Rating Matrix are imbalanced. Majority of the ratings goes to the popular items.
* Semi-supervised Learning: For some applications, you only have data for items user purchased which is normally biased towards items a user likes. Hence, it is a special form of semi-supervised learning. This is also known as the One-Class problem in Recommender Systems
* Content Embedding: How do we encode content information regarding users and items into useful embeddings? This also includes content like sound waves, images, geo-location.
* Image Recommendation: Embedding images and learning the features of each image based on style. 
* Natural Language Recommendation: Embedding news, product reviews and product description as content information using Language Embeddings.
* Sequential Recommendation: How do we account for time and order of recommendations?
* Session-Based Recommendation: How do we recommend in a sequence within a short browsing session?
* Active Learning: What should you recommend to learn more about the user for personalized recommendations in future?
* Offline Evaluation: How do we evaluate recommender systems offline, without access to a real online recommender sytem. Ideas from Counterfactual Reasoning.
* Bandit Recommenders: Recommend based on dynamically changing popular items such as News Recommenders.
* Graph Recommenders: Embedding social networks to features to determine similar nodes.

### Seminal Approaches to Recommender Systems
The popular existing approaches to recommender systems are

Neighbourhood Models (compares item-item vectors or user-item vectors)
* Collaborative Filtering (CF)

Matrix Factorization Rating Models (compares user and item vectors directly, optimized for rating)
* Probabilistic Matrix Factorization (PMF) 
* Singular Value Decomposition + Neighbourhood (SVD++)
* Weighted Regularized Matrix Factorization (WRMF, wALS)

Ranking Models (compares user and item vectors directly, optimized for similarity in ranking)
* Singular Value Decomposition (PureSVD, forms a basis to predict output)
* Bayesian Personalized Ranking (BPR, train using a ranking loss)
* RankALS

Linear Models (Scalable, Personalizable, creating a simple model on each user in parallel)
* Sparse Linear Models (SLIM)
* Linear Recommendation (LRec) 

Word Embedding Models (Embedding items based on co-occurrencec statistics)
* item2vec
* prod2vec

Bayesian Models (Accounting for uncertainty)
* MatchBox

Topic Models
* Latent Dirichlet Allocation

Deep Models
* RBM-CF
* AutoRec
* Collaborative Deep Learning (CDL) 
* Neural Autoregressive Distribution Estimator (CF-NADE)

Image Models
* VBPR
* CNN for Image Embedding

Sequential Models
* Markov Chain (FPMC) 
* RNN for Session Recommendation (GRU4Rec)

Bandit Models
* LinUCB

Social Models
* Graph Neural Network for knowledge graph embeddings.

## MASc Research Direction
Embedding side information for scalable recommendation.
Most existing recommender systems are still using traditional 
matrix factorization. Companies are mainly interested in enhancing 
these methods with more information, and may not be willing to
commit to try entire new approaches. 
My research is in figuring out great ways to incorporate side information
using embeddings to be used alongside these recommendations. 

Sequential Active Learning for Personalized Recommender Systems.
* Machine Learning applied to Recommender Systems 
* Sequential Models
* Online Learning
* Exploration-Exploitation Tradeoffs
* Active Learning
* Bayesian
* Offline Evaluation

### Sequential Machine Learning Models
Models that works great with sequence should have memory over past observations.

Models with memory:
* Hidden Markov Models (Generate the observations in a sequence)
* Recurrent Neural Networks (generates sequential recommendation from an input sequence)
* Markov Decision Processes (state depends on action taken)
* Reinforcement Learning (learns to explore and exploit interactively, taking into account long term rewards)

Recurrent Neural Network extensions are known to be good at modelling long sequences. 
It also generates recommendation in a sequence. 

Reinforcement Learning approaches learn from long term rewards.
It also enables us to take actively take actions on what to do.
Its actions also affect the state, which includes the state transition and reward distribution.

Work has been done to integrate the two models. 

#### Sequential Online Learning
Models should also be able to train online with variable length input.
Since, the next selected data should be able to update the model via training in an online fashion.
This means a current active test point, becomes a future training point.

### Exploration-Exploitation Tradeoff = Multi-armed Bandit
Tradeoff between exploring new items vs exploiting popular well known items

The popular approaches to these tradeoffs are:
* Probability of Improvement
* Expected Improvement
* Entropy Search
* Epsilon Greedy (include randomness in search)
* Upper Confidence Bound (prioritize uncertainty in searching)
* Thompson Sampling (search based on posterior distribution)

During the exploring phase, active learning should aim to gain as much information.
It normally gains information at regions it is uncertain about.

During the exploitation phase, active learning should recommend items it is confident about.
This means it is very certain about its recommendation.

#### Bayesian Machine Learning Models
Need to model posterior distribution of model to help in exploration-exploitation tradeoffs.

To quantify uncertainty, we'll need to resort to full posterior estimates instead of point estimates. 
This leads to intractable Bayesian approaches.

To deal with intractable high dimensional integrals, the popular approaches are:
* Conjugate Priors
* Markov Chain Monte Carlo Sampling
* Variational Inference

#### Active Learning
During exploration phase, how to explore to gain most information.

### Offline Evaluation
Access to online users are unavailable for academic researchers. 
Even if we do have access in industry, it is expensive to test on live users.
Need to be able to evaluate model offline.
Unlike simulating physics engines in games, it is impossible to simulate real user behavior as we do not know how the brain works.
Hence, evaluation models offline is a difficult research problem.
Current approaches uses Counterfactual Analysis.

# Talks

* [UTMIST Academic Talk Series 2018: Recommender Systems: Motivations, Challenges and Seminal Works](./pdf/RecommenderSystemMotivationChallengesSeminalWorks.pdf)

# Journals

* [ℚ-bounds consistency for the spread constraint with variable mean](https://link.springer.com/article/10.1007/s10601-016-9238-x)

# Preprints 
* [Noise Contrastive Estimation for Scalable Linear Models for One-Class Collaborative Filtering
](https://arxiv.org/abs/1811.00697)

I enjoy working with applied math and code. 

* [Statement Of Purpose Fall 2016](./pdf/statementOfPurposeUofTMIE.pdf)

# Introduction to Data Science & AI
-----------------------------------

# **Lecture 1** (5.09.2022, Pietro, DSAI 101)

> #### *_Sciences are primarily defined by their questions, not by their tools!_*


### What is Data Science?
- Sexiest job of the 21st century!
- Why is that?
	- More and more data is being generated
	- There is a growing demand to make sense and understand those data
- Statistics
- Math
- Critical thinking
- **_Asking questions!_**

> Data Science is the discipline that describes, predicts, and makes causal inferences, based on data.   

> Data Science is the process of extracting knowledge or insights from data (structured or unstructured).
>> **Data** -> **Information** -> **Knowledge**

> #### *The value of data is in the impact they have on desision making!*

### What is Artificial Intelligence?
-> Field of study which studies how to create computers and software that are capable of *_intelligent_* behaviour.

### Why.
As a data scientist the best question you can ask yourself is **why**. -> *_Start with the questions, not the data!_*  

- Why has this data been gathered?
- Why am i seeing this?
- Why is it visualised like this?
- Why do i see (or not see) patterns?
- What does this data represent?
- How can i make use of it?
---------------------------------
### The Data Science Process
1. **ASK** an interesting question.
	- What is the scientific *goal*?
	- What would you do with all the *data*?
	- What do you want to *predict* or *estimate*?
1. **GET** the data.
	- How were the data *sampled*?
	- Which data are *relevent*?
	- Are there *privacy* issues?
1. **EXPLORE** the data.
	- *Plot* the data.
	- Are there *anomalies*?
	- Are there *patterns*?
1. **MODEL** the data.
	- *Build* a model.
	- *Fit* the model.
	- *Validate* the model.
1. **COMMUNICATE** and **VISUALIZE** the results.
	- What did we *learn*?
	- Do the results make *sense*?
	- *_Can we tell a story?_*

### first, **DATA**
- raw facts
- recorded symbols
- unprocessed information (either structured or unstructured)
### then, **INFORMATION**
- data in context
- data with meaning, relevance
- refinement of data for the context of human use
### at last, **KNOWLEDGE**
- result of understanding information
- information with direction or intent - it facilitates a decision or an action
- *_Information put into action!_*

### EXAM type exercise
- Given the following situation:
Parking sensors are proximity sensors for road vehicles designed to alert the driver of obstacles while parking.   

a. Explain how a measure of proximity between a road vehicle and an obstacle could be transformed from data into information and then into knowledge.
   
b. Express the knowledge generated at the previous point into a rule which could be implemented into a knowledge-based system.  
> *ad a.*
>
> **Data**: measurments from the sensors (in meters for instance)  
>  
> **Information**: If the distance is < 1 meter, send a signal to the alarm  
>
> **Knowledge**: Alarm goes off alerting the driver  
>   
> *ad b.*
> 
> ```java
> int distance = sensor.read();
>
> if (distance < 1) {
> 	alert();
> }
> ```
--------------
### As a data scientist, your success is dependent on:
> 1. Asking (yourself) the **right questions**
> 1. Your ability to find the **right data** to collect.   
>
> ==IMPORTANT==
> - The methods, techniques, algorithms you are going to use depend on:
> 	1. The (research) question you want to answer.
>	1. The data available to answer that question.
	
-------------
### Exam checklist
[x] definition of data, information and knowledge

[x] link between them

[x] exercises of type above

---
# Lecture 2 (AI 101, Rachel, 6.09.2022)

### The Turing Test

The Turing test is a test of a machine's ability to exibit intelligent behaviour eqiuivalent or indistinguishable from that of a human.

Problems with the Turing test:
- Can improve chances of passing through psychological strategies
- Doesn't test 'intelligence', just responses - chinese room problem
- Humans can 'fail' to convince the judges they are not computers

Advantages of the Turing test:
- Objective notion of intelligence
- Avoids discussion of internal processes and consciousness
- Eliminates the bias in favor of living organisms

Objections to the Turing test:
- Bias toward purely symbolic problem solving task
- Constraining machine intelligence to fit human mold
	- Limited memory
	- Error prone
- Distraction from real-world problems

> With that in mind, human-like behaviour can be and is useful:
> - Entertainment industry
>	- NPC's
> - Human-like Bot Competitions
> - Chatbots giving advice on websites

### CAPTCHA
Captcha is a reverse turing test - tries to pick out the humans from the machines. (getting worse and worse though)

### Total Turing Test
- Original test: No Physical interaction
- Total Turing test:
	- Includes a video signal so the interrogator can test the subject's perceptual abilities
	- Pass Physical Object 'through the hatch'
- Suggested additional components of AI:
	- Computer vision: to percieve objects
	- Robotics: to manipulate and move them
- Completely pass as human:
	- Ex Machina for example

### More to AI than the Turing Test
Views of AI fall into four categories:

| Thinking humanly  | Thinking rationally  |
|---|---|
| *_Acting humanly_*  | *_Acting rationally_* |

The Turing test tests the ones in italics, and they are more important than thinking.

#### Thinking humanly: **cognitive modeling**
- 1960's "cognitive revolution"
	- information-processing psychology
- Requires scientific data theories of internal activities of the brain
- How to validate? Requires
	1. Predicting and testing behaviour of human subjects
	1. Direct identification from neurological data
- Both approaches (Cognitive Science and Cognitive Neuroscience) are now distinct from AI.

#### Thinking rationally: "laws of thought"
- Aristotle: what are the correct arguments/thought processes
- Greek schools developed various forms of *logic*:
*notation* and *rules of derivation* for thoughts
- Direct line through mathematics and philosophy to modern AI
	- The logicist tradition in AI hopes to create intelligent systems using logic programming
- Problems with approach:
	- Not all intelligent behaviour is mediated by logical deliberation (us, humans)
	- What is the **purpose of thinking**? What thoughts **should** i have out of all that i **could** have?
#### Acting rationally
**Rational** behaviour: doing the right thing
- The right thing: that which is expected to *maximize goal achievement, given the available information**
- Doesn't necessarily involve thinking -> reactions/reflexes (reflex action in leg) and automatic behaviours (blinking)

> **Rational programs**
> - For any given class of environments and tasks, seek the program with best performance
> - Caveat: it's never possible to create the perfect (best) program -> Computational limitations

### Foundations of AI
| Philosophy  | Logic, methods of reasoning, rationality  |
|---|---|
| Mathematics  | probaility, formal representaion, computation  |
| Economics  | utility, decision theory  |
| Neuroscience  | physical substrate for mental activity  |
| Psychology  | perception, motor control  |
| CS  | programming, building fast computers  |
| Control theory  | systems that maximize objective function over time  |
| Linguistics  | knowledge representation, grammar  |


### State of the Art
- Autonomous driving
- Logistics planning 
	- 91' Gulf War, US forces used AI logistics planning and scheduling program
	- NASA MAPGEN (Mars exploration rovers)
	- MEXAR2 (mission planning)
- Spam fighting
	- Learning algs classify over a billion messages as spam
- Vacuum cleaning (iRobot)
- Quiz show contestants! (Watson - IBM)

### But AI can't (yet) do all:
- Acting as a judge
- General game playing
- Beating us in soccer
- Conversation successful with another person for an hour
- Machine translation
---
### Exam checklist
[x] Turing test
- What?
- Why?
- Pros/Cons

[x] Thinking/Acting  Humanly/Rationally

[x] Examples of what current AI can/can't do

---
# Lecture 3 (Exploratory data analysis - Fourier analysis/complex numbers, Pietro, 8.09.2022)
### Exploratory data analysis 
- Exploratory data analysis -> an approach to analyzing data sets to summarize their characteristics and start discovering interesting patterns/structure in data.
- Results -> should not be taken as absolute truth, but as a starting point for the development of a scientific hypothesis and further study.
- First thing to do is to explore the data and get a feeling about it:
	- How are the data distributed/organized? (**visualize** your data!)
	- Descriptive statistics (mean, median, range, st. deviation)
	- Outliers?
	- Anomalies?
	- Missing values?
	- Interesting things/structures? (unsupervised learning, clustering, principal components, etc.)
### Visualize your data!
- General principle -> display data as far as possible, show the original data and try not to obscure the design of the study!
- Show as much data/information as possible!

> *Show the data, don't conceal them.*

### Critical/statistical thinking
- Learn to look at features in the data.
- You **must** learn to understand your data, look at them critically.
- Look for features that will help you find the most suitable way to handle, process, and analyze those data.

### Time series data
- TS is a sequence of points -> successive measurements made over a time interval.
- Normally represented as -> quantity/independent variable.
- Independent variable is usually time.

### Patterns in time series
- Tend to come from repetition.
- Need a different representation of the time series -> one that shows the oscillatory patters of a signal - its *_frequency_* content!

### Fourier analysis
- Study of the wat general functions may be represented or approximated by sums of simpler trigonometric functions (sin0 + cos0).
- Time series can be interpreted as "functions".
- Fourier analysis can be used to "decompose" time series into simple patterns (see point 1)
- These building blocks (sin, cos) are **periodic functions** themselves, and can tell us about the oscillatory components/repetitive patterns in a time series.
- Every (literally every possible shape) time-based pattern can be build with circles (FA)

### Complex numbers
- See notebook!;p
---
### Exam checklist
[x] Complex numbers and their representation in the complex plane

[x] Cartesian and polar form - plus transformations from one another

[x] Operations with complex numbers

[x] Exercises of type like student portal

---
# Lecture 4 (Agents, Rachel, 12.09.2022)
### What is an agent?
- Anything that can be vievew as **percieving** its **environment** through **sensors** and **acting** upon that environment through **actuators**
- Operates *autonomously*
- Humans, robots, softbots, thermostats etc.
- Abstractly [f: P* -> A]

### Examples
Human agent:
- Sensors?
	- eyes, ears
- Actuators?
	- hands, legs, mouth

Robotic agent:
- Sensors?
	- cameras and infrared range finders
- Actuators?
	- various motors
> Mars exploration rovers, Air Traffic Control (OASIS)

### Rational agents
- Should strive to "do the right thing", based on what it can percieve and the actions it can perform
- The right action -> the one that will cause the agent to be the **most succesful**

- Performance measure: An objective criterion for success
	- PM of a vacuum-cleaner agent:
		- amount of dirt cleaned
		- cleanness of the environment
		- amount of time taken
		- amount of electricity consumed
		- amount of noise generated etc.

- For each perception sequence agent should select an action that maximizes its perfomance measure.

- An agent is **autonomous** if its behaviour is determined by its own experience.

### PEAS - Performance measure, Environment, Actuators, Sensors
- First, specify the setting for intelligent agent design
> Example:
> Automated taxi driver:
> - **PM**: Safe, fast, legal, comfortable, maximize profits
> - **Environment**: Roads, other traffic, pedestrians, customers
> - **Actuators**: Steering wheel, accelerator, brake, signal, horn
> - **Sensors**: Cameras, speedometer, GPS, engine sensors, keyboard

### Environment types:
- **Fully observable** -> sensors give it access to the complete state of the environment at each point in time
	- chess, checkers
- **Partially observable**
	- poker, stratego
- **Deterministic** -> fully determined by the current state and action executed
	- chess, stratego
- **Stochastic**
	- dice roll, backgammon, bow n arrow, roulette
- **Episodic** -> divided into atomic "episodes", single action without using memory
	- image analysis, part picking
- **Sequential** 
	- game of chess, poker
- **Static** -> Environment is unchaned while agent is deliberating
	- game of chess, crossword puzzle
- **Dynamic**
	- soccer, taxi driver
- **Semidynamic** -> Environment itself does not change with time but the performance score does
- **Discrete** -> A limited number of distinct, clearly defined percepts and actions
	- chess, poker, backgammon
- **Continuous**
	- taxi driver, soccer, image processing
- **Single agent** -> An agent operating by itself in a given environment
	- crossword puzzle, part picking
- **Multi agent**
	- chess, soccer, taxi driver

> - The environment type largely determines the agent design
> - Real world is: Partially Observable, Stochastic, Sequential, Dynamic, Continuous, Multi-Agent

- **Known** vs **Unknown**
	- The environment of a poker game is **known** (rules)
	- A video game can be fully observable, but you may not know the result of an action until you try.

### Agent types
- Four basic types:
	1. Simple reflex agents
		- action based solely on current percept
		- implemented by conditional statements (if-then)
		- only works when ENV is fully observable, otherwise -> infinite loops
	1. Model-based agents
		- to tackle partially observable ENV
		- update state over time using world knowledge
	1. Goal-based agents
		- needs a goal to know which situations are desirable
		- typically in search and planning research
		- *future is taken into account*
		- more flexible; goals are represented explicitly and can be changed
	1. Utility-based agents
		- goals can be reached in different ways
		- Improves on goals:
			1. select between conflicting goals
			1. select between several goals based on likelihood of success
---
### Exam checklist
[x] What is an agent?

[x] When is it rational? autonomous?

[x] PEAS

[x] Describing environments

[x] Basic agent architectures

---
# Lecture 5 (Data mining - Pattern Recognition, Anna, 13.09.2022)
### **CR**oss **I**ndustry **S**tandard **P**rocess for **D**ata **M**ining
- CRISP-DM

![crisp](crisp.png)

### Data mining
- Data mining = identifying patterns in data
- Patterns are everywhere!
	- Traffic patterns
	- Ads
	- Human genome
	- Service to customers

### Problems suitable for data mining
- require knowledge-based decisions
- have a changing ENV
- accesible, sufficient, and relevant data
- high payoff for the right decisions
- have sub-optimal current methods
- privacy and ethics considerations important if personal data involved! (GDPR)

### Types of learning
- **Supervised learning**
> Trains a model on known input and output so that it can predict future outputs
- **Unsupervised learning**
> Finds hidden patterns or intrinsic structures in data
- **Reinforcement learning**
> Rewarding desired behaviours, punishing undesired ones, trial and error

### Data mining - tasks
- Anomaly detection (outliers, change, deviation detection)
- Association rule learning (dependency modelling)
- Clustering
- Regression
- Summarization

> ![ML](ml.png)

### Distance measures -> they help us understand the data
- A distance measure should fulfill 4 conditions:
	- d(P,Q) >= 0
	- d(P,Q) = 0 <=> P = Q
	- d(P,Q) = d(Q,P)
	- d(P,Q) <= d(P,W) + d(W,Q) (triangle inequality)
### Types of distance
- **Euclidean distance**
> ![eudis](eu.png)
- **Manhattan (Absolute) distance**
> ![manhattan](manh.png)
- **Infinity distance**
> ![infinity](inf.png)
- **Cosine distance**
> ![cosine](cos.png)
- **Edit distance**
> ![edit](edit.png)
---
### Exam checlist

[x] Problems suitable for data mining

[x] Learning types

[x] Data mining tasks

[x] Definition of a distance measure (4 coniditions)

[x] Definitions of Euclidean distance, absolute distance, infinity distance, edit distance

[x] Given two time series: know how to compute euclidean, absolute, infinity, edit distances

[x] Exercises of type homework (see slides)

---
# Lecture 6 (Data modelling - Linear Regression, Pietro, 15.09.2022)
### Data modeling - mathematical modeling
- A model is a mathematical representation of a system. An approximation of reality.
- A system is a set of things working together as parts of a mechanism or network; a complex whole
- Model can help people know, understand, or simulate a system the model represents.
- A model may help to explain and make predictions (extrapulate) about the behaviour of a system.
- **A model can be used to investigate how the real world works!**

### Mechanistic vs. Statistical models
- Mechanistic -> tries to model the realtion between input and output of a system by understanding and replicating the individ. components of the system and their interactions. They have tangible, physical aspects.
- Statistical -> seeks only to describe the data, the relation between observed input and output, without trying to replicate the real functioning of the system.

### From data to model - how to build a simple one
- Given the system you want to model and the data you collected about the behaviour of the system.
- Given some knowledge you already have on the bahaiour (theory, data mining, etc.)
- Choose a family of (statistical) models that you think well represents the system
- Find out the optimal values of the parameters of the model given the data you collected.

### Linear regression models
- **y** is the output of the model, i.e., the observations you have collected.
- **x** is the explanatory variable (regressor), a quantity the observations depend on.
- Linear regression is an approach to modeling the relationship between **y** and **x**.

### Overfitting
- Fitting model too complicated with respect to true model.
- Easy to occur with high noise: the model starts describing the random error or noise in data instead of the underlying relationship - it starts to describe exceptions in the data (classification and the curse of dimensionality).  

> ![Overfitting](model.png)

- Problem of overfitting: model too much dependent on the available observation
- It becomes useless for predicion (highly inaccurate)

> ![Overfitting2](model2.png)

### Estimation and validation go together
- A large enough model can reproduce a measured output arbitrarily well. We must verify that the model is relevant for other data - data that were not used for estimation (training the model), but were collected, gathered from the same system.

> ![plot](plot.png)
---
### Exam checklist
[x] Given the set of correlated var x and y, know how to compute the linear equation of the regression line through the data (y = ax + b)

[x] Know how to solve exercises as the one given at the end of the lecture.

---
# Lecture 7 (Search, Anna, 19.09.2022)
### Search
- Many AI approaches rely on search to find the 'best' solution to the problem.
- By searching through the possible solutions we can find the solution we need.

### Trees
- Searching a tree
	- **Breadth first search**
		- Look at the root, if not solution...
		- Look at the children, if not solution...
		- Look at the grandchildren...
		- etc.
	- **Depth first search**
		- Go as deep as you can with each path, until we reach a leaf, then backtrack up the tree, repeat.
> ![search](search.png)

### Game Tree
- Search depth *_d_* (ex chess.com!)
	- Number of state transitions (moves) from the root to the considered state position
- Branching factor *_b_*
	- Average number of succesor nodes (moves)

### Adversary search (MiniMax, Von Neumann)
- Two (or more) players, each trying to maximize their expectations (acting **rationally**)
- Player 1 is called MAX
	- Obtain the maximum result
	- Minimize that of the opponent
- Player 2 is called MIN
	- Obtain the minimum result
	- Maximize that of the opponent
### Heuristic search
- Truncate the game tree (limited search depth)
- Use a (static heuristic) evaluation function at the leaves
- Minimax (with pruning) on the reduced game tree
- Playing is solving a sequence of these game trees
---
### Exam checklist
[x] Tree terminology

[x] Using trees for search

[x] Breadth/depth first search

[x] Minimax search

[x] Pruning

---
# Lecture 8 (Logic, Rachel, 20.09.2022)
### PROLOG - a programming language with built-in search
- In PROLOG we don't need to program the computer to build and search the tree.
- This is built-in to the interpreter.
- Instead we just need to define the problem in a way which it understands.

### Entailment
- Entailment means that one thing **follows from** another
- KB |= a
- Knowledge base KB entails sentence a *if and only if*, in all worlds where the KB is true, a is true
> - Different from all the logical operators we seen so far
> - Other operators can be true in one world and false in another
> - Entailment is different. Either it entails in all worlds, or none.

> Example
> ![entail](ent.png)

### Validity and Satisfiability
A sentence is **valid** if it is true in *all* models (tautologies)

> True, A or not(A), A implies A

A sentence is **satisfiable** if it is true in *some* model 

> A or B, C

A sentence is **unsatisfiable** if it is always false (contradictions)

> A and not(A)
---
### Exam checklist
[x] What is knowledge base and inference?

[x] What is PROLOG?

[x] Basic operators and concepts of logic:
- and, or, not, bijection, implication
- entailment
- inference
- validity
- satisfiability

---
# Lecture 9 (Simulation, Anna, 22.09.2022)
### What are simulations?
- Simulations are in general approxiations of the true behaviour of the model (and the system the model represents)

### Monte Carlo simulations
- They are simulations: they need an underlying model
- The model is still deterministic, the unceirtanty is on the input to the model
- Use it to generate statistical knowledge about the output, the model, and its parameters

### The Bootstrap
- A particular type of Monte Carlo simulation
- Very useful to quantify the uncertainty assosiated with a given estimator or statistical method
##### Bootstrapping
- Take a sample with replacement from the original data (the same data point can be selected more than once
- Compute the statistics
- Repeat a large amount of times (1000 at least), assuming each sample is drawn independently of the other samples
- Compute the confidence interval from bootstrap distribution by means of bootstrap percentile method
---
### Exam checklist
[x] Uniform distribution

[x] Monte Carlo simulations

[x] Bootstrapping with replacement

[x] Exercises of the type given at slides

---
# Lecture 10 (Learning, Rachel, 26.09.2022)
### Recap: Agent Types
- Four basic types in order of increasing generality:
	1. Simple reflex agents
	1. Model-based agents
	1. Goal-based agents
	1. Utility-based agents
- All can be turned into learning agents!!!

### Learning Agents
- **Performance element**: selecting actions based on percepts
	- Corresponds to the previous agent programs
- **Learning element**: introduce improvements in performance element
	- *Critic* provides feedback on agents performance based on fixed performance standard
- **Problem generator**: suggest actions that will lead to new and informative experiences
	- Exploration vs. exploitation

> ![lagent](lagent.png)

### Learning element
- Design of a learning element is affected by:
	- Which components of the performance element are to be learned
	- What feedback is available to learn these
	- What representation is used for the components
- Type of feedback:
	- **Supervised learning** -> correct answers for each example
	- **Unsupervised learning** -> correct answers not given
	- **Reinforcement learning** -> occasional rewards

### Decision trees for Classification
- A decision tree is where:
	- Each internal node tests an attribute
	- Each branch corresponds to an attribute value
	- Each leaf node is labelled with a class (class node)

> ![tree](tree.png)

### When to consider Decision Trees
- Each instance consists of an attribute with discrete values
- The classification is over discrete values
- It is okay for the training data to contain errors - depending on the learning algorithm decision trees can be robust to classification errors in the training data.
- It is okay for the training data to contain missing values – decision trees can be used even if instances have missing attributes.

### Decision Tree Basic Algorithm
1. A ← the “best" decision attribute for a node N.
2. Assign A as decision attribute for the node N.
3. For each value of A, create new child of node N.
4. Sort training examples to leaf nodes.
5. IF training examples perfectly classified, THEN STOP, ELSE iterate over new leaf nodes.

### Entropy
- Measures the **impurity** or unpredictability of observations in the system. (measure of disorder)
- Between **0** and **1**
- Formula
> ![entropy](entropy.png)
- Example
> ![example](example.png)

### Information Gain
- **Information Gain** is the expected reduction in entropy caused by partitioning the instances from S according to a given attribute.
- Formula 
> ![informationgain](ig.png)

---
### Exam checklist
[x] How to adjust an agent to turn it into a learning agent (theory)

[x] Calculating logs of all bases on a calc with only log10 and ln

[x] Calculating Entropy

[x] Calculating Information Gain

[x] Building a decision tree by hand

[x] Turning real valued data into discrete classes

[x] The importance of a test set when learning

---
# Lecture 11 (Game Theory, Pietro, 27.09.2022)
### Game Theory
- Game theory is a branch of applied mathematics which studies the individual decisions of a subject, called a player, in situations of strategic interaction (or conflict) with other players.
- Objective for each player: maximize the personal gains (or minimize personal cost)
- It is the study of mathematical models of conflict and cooperation between intelligent, rational decision-makers

- Rational decision maker: hypothetical person that will always pick the option they predict will be the best for themselves
- John Von Neumann (1928) invented zero-sum games: One player's gain means the other player’s loss (two player games)
- Today, game theory applies to a wide range of behavioral relations, and is now an umbrella term for the science of logical decision making in humans, animals, and computers
### Useful definitions
- **Actions (strategies)**
	- All the possible things a player can do in the game
- **Payoff**
	- The benefit for a player resulting from the actions /  strategies taken by all players together
- **(2 players) Payoff (bi)matrix**
	- A (bi)matrix consisting of the payoffs for both players for all action/strategy pairs (so we need to have prior knowledge about the problem)
### Zero-sum games
- Sum of all the net winnings is equal to zero

### Dominated strategies
- For a specific player, a strategy is dominated by a second strategy if the second strategy is always at least as good and sometimes better regardless of what the opponent does
- A dominated strategy can be eliminated immediately from further consideration

### Minimax criterion
- Player 1 aims to maximize their minimum payoff (to player 1)
- Player 2 aims to minimize the maximum payoff to player 1

### Saddle point 
- The end product of this line of reasoning is that each player should play in such a way as to minimize their maximum losses whenever the resulting choice of strategy cannot be exploited by the opponent to then improve their position 
- This so-called minimax criterion is a standard criterion proposed by game theory for selecting a strategy in a zero-sum game
- In terms of the payoff matrix, it implies that player 1 should select the strategy whose minimum payoff (to player 1) is largest, whereas player 2 should choose the one whose maximum payoff to player 1 is the smallest

### Non-zerosum games: Nash equilibrium
- Each player does the best for themselves, but this might also be good for tou group
> Beautiful Mind, Nash comes up with this idea: https://www.youtube.com/watch?v=2d_dtTZQyUM
---
### Exam checklist
[x] Solving games by dominated strategies

[x] Solving games by minimax criterion

[x] Stable/unstable solutions

[x] Finding a Nash equilibrium in a game

---


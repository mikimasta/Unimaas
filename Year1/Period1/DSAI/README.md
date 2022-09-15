# Introduction to Data Science & AI
-----------------------------------

# **Lecture 1** (5.09.2022, Pietro)

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
# Lecture 2 (Rachel)

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
- Turing test
	- What?
	- Why?
	- Pros/Cons
- Thinking/Acting  Humanly/Rationally
- Examples of what current AI can/can't do
---
# Lecture 6 (Data modelling - Linear Regression, Pietro)
### Data modeling - mathematical modeling
- A model is a mathematical representation of a system. An approximation of reality.
- A system is a set of things working together as parts of a mechanism or network; a complex whole
- Model can help people know, understand, or simulate a system the model represents.
- A model may help to explain and make predictions (extrapulate) about the behaviour of a system.
- **A model can be used to investigate how the real world works!**

### Mechanistic vs. Statistical models
- Mechanistic -> tries to model the realtion between input and output of a system by understanding and replicating the individ. components of the system and their interactions. They have tangible, physical aspects.
- Statistical -> seeks only to describe the data, the realtion between observed input and output, without trying to replicate the real functioning of the system.

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
![Overfitting](model.png)

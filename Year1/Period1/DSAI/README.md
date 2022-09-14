# Introduction to Data Science & AI
-----------------------------------

## **Lecture 1** (5.09.2022, Pietro)

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
> **Information: If the distance is < 1m, send a signal to the alarm  
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
==IMPORTANT==
- The methods, techniques, algorithms you are going to use depend on:
	1. The (research) question you want to answer.
	1. The data available to answer that question.
	
-------------
### Exam checklist
[] definition of data, information and knowledge
[] link between them
[] exercises of type above


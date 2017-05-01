# CTM-Learning - Part I

In this section, we implement CTM learning for the collaborative editing systems. 
We have world assumption as following:

*Human agent*

An editor, a system designer or any kind of users of editing systems who interact with the editing sytems for correcting the documents

*Assistance agent*

An intelligence agent observes the user interaction and helps the users. 

*Environment*

TConnect Editor v0, the enviroment types is defined: 

* Fully observable (vs. partially observable)
* Deterministic (vs. stochastic)
* Episodic (vs. sequential)
* Static (vs. dynamic)
* Discrete (vs. continuous)
* Single agent (vs. multiagent)

Our environment is semi-dynamic, partially observable, stochastic, sequential, discrete and multiagent.

We assume that the human agents could be different based on their personalization.
Four basic types in order of increasing generality:
* Simple reflex agents
* Reflex agents with state
* Goal-based agents
* Utility-based agents
* All these can be turned into learning agents

Obviously, in the 1st case, if the user acts as simple reflex agent.
The A-Model in CTM method provides a very good way to learn the conditions of user action. 

















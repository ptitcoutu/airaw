# airaw
AI Real Agent Workflow

# Architecture 
## Agent Definition Registry
## Tools Registry
## Root Agent and Agent instances
Agent is a pipeline of task to achieve thanks to an Agent definition
Agent can interact with Thread

### Task origin and followup
tasks are added to Agent in two cases :
- ping from a thread
- change to its définition

### Task execution
in order to execute Task Agent have a context for the Task brought by the thread targeted by the task
Agent know just the id of the thread and the last n messages of the Thread. a tool can be called by Agent to search the Thread history to have more context 

## Thread persistance and organisation
Threads are the context history of agents
Agents can bring messages to a thread as the user can do

Thread message can have a sub-thread



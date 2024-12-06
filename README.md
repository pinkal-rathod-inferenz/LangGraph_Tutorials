# LangGraph_Tutorials
Here their is resources to access LangGraph Resources of which I explore
LangGraph Documentation 

What is LangGraph? 

LangGraph is a library for building stateful, multi-actor applications using LLMs, use to create agent and multiagent workflows. Compared to other framework It provides cycles, controllability, and persistence. 

Supports defining flows with cycles, crucial for agentic architectures, unlike traditional DAG-based solutions. As a low-level framework, it allows detailed management of flow and state for reliable agents. 

Automatically save state after each step in the graph. Pause and resume the graph execution at any point to support error recovery, human-in-the-loop workflows, time travel and more. 

Supports advanced features like loops and branching for adaptable agent workflows. 

It can be built with or without LangChain. 

It support different components such as LangGraph Server (APIs), LangGraph SDKs(Clients for APIs),LangGraph CLI(cmd type for building server), LangGraph Studio(UI/debugger). 

For Installation  

pip install -U langgraph 

 
For each Graph execution , it creates state which passed between nodes and each node updates internal state with return value after it executes. The graph updates its internal state is defined by type of graph chosen or custom function.   

For more information go to  https://langchain-ai.github.io/langgraph/#step-by-step-breakdown 

Why LangGraph? 

It really simplifies the development  : - State Management(at which state the work is stored) and Agent Coordination 

For eg.One Ai agent for wikipedia search , their are many agents where chatbot contains 

Agent 1 :- Google Search 

Agent 2: -Wiki search 

Agent 3:- VectorDB Search 

For workflows , logics so it simplifies 

 

Flexibility :- It have flexibility to define its own agent logic and communication protocols. This makes highly customized applications to specific use cases. Whether you want to build chatbot which handle user requests or multi agent system that performs complex tasks. 

 

Scalability :- Large Scale MultiAgent Application : - It can handle highvolume of interaction, interaction between agents or it will be between complex workflows. For making Enterprise level Application  

 

Fault Tolerance :- It will be able to handle errors, even if agent fails then also application is working. 

How LangGraph Implemented? 

For tutorial how basic langraph is work, 

https://github.com/pavanbelagatti/LangGraph-Chatbot-Tutorial/blob/main/LangGraph-Tutorial.ipyn 
 

 

 

 

 

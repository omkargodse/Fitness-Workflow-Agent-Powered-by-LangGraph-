# Fitness-Workflow-Agent-Powered-by-LangGraph-
Tired of generic workout plans? This small project demonstrates how to build a smart, conversational fitness agent that personalizes recommendations based on your current emotional state.

Built with LangGraph, it serves as a powerful example of an Agentic Workflow where distinct functions (greeting, classification, suggestion) work together sequentially, all powered by a shared, managed state. The project is an excellent starting point for anyone looking to understand LangGraph state management and node execution flow.

How to Run (Expected Workflow):

1. Add your OpenAI API Key in .env file
2. The script prompts the user for their name and feeling.
3. The LangGraph chain is invoked with the collected input.
4. The "Greet User" node uses the name.
5. The "Classify Mood" node categorizes the feeling.
6. The "Suggest Workout" node provides a final recommendation based on the classification.

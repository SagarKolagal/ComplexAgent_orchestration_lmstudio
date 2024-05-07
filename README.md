# Complex Agent Orchestration LMStudio

## Description
he Complex Agent Orchestration project is a Python script that utilizes OpenAI's LM Studio API to develop a conversational AI system. This script allows users to define their objectives and provide necessary file content or previous results. The opus_orchestrator function then orchestrates the tasks, delegates sub-tasks to sub-agents, refines outputs, and creates folder structures based on user objectives and interactions with AI models.

The parameters used in this script are:

Objective: The main task or goal that the user wants to achieve.

File Content: Used to pass the content of a file to the opus_orchestrator function.

Previous Results: A list containing the results of previous sub-tasks, which are used to pass the results of previous sub-tasks to the Orchestrator function.

Use Search (optional): A boolean flag that determines whether to include a search query generation step in the process. When set to True, the system will prompt the Orchestrator to generate a JSON object containing a search query.

The functionality of this script includes:


Orchestration: The AI system breaks down the objective into sub-tasks and orchestrates their completion.

Task delegation: Sub-agents are delegated tasks based on user objectives and interactions with AI models.

Output refinement: The system refines outputs to ensure they meet user requirements.

Folder structure creation: The system creates folder structures based on user objectives and interactions with AI models.

## Usage
To use this script, you can start by defining your objective and providing any necessary file content or previous results. You can then call the opus_orchestrator function with these parameters to initiate the AI system's process. The system will then orchestrate the tasks, delegate sub-tasks to sub-agents, refine outputs, and create folder structures based on your objectives and interactions with AI models.

## Requirements
- Python 3.8 or later
- OpenAI's LM Studio API

## Installation
To install the required dependencies, you can use pip:
```bash
pip install -r requirements.txt

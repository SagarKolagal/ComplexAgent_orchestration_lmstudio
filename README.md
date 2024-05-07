# Complex Agent Orchestration LMStudio

## Description
This repository contains the codebase for the Complex Agent Orchestration project developed in LMStudio. This Python script defines functions to orchestrate, delegate tasks to sub-agents, refine outputs, and create folder structures based on user objectives and interactions with AI models. It provides a conversational AI system using OpenAI's LM Studio API.

## Parameters
- **Objective:** The main task or goal that the user wants to achieve. This can include a description of the task to be completed or a specific objective to work on.
- **File Content:** Used to pass the content of a file to the opus_orchestrator function. This content is then displayed in the console output when the function is called.
- **Previous Results:** A list that contains the results of previous sub-tasks. This is used to pass the results of previous sub-tasks to the Orchestrator function so that it can consider them when breaking down the current objective into the next sub-task.
- **Use Search:** A boolean flag that determines whether to include a search query generation step in the process. When set to True, the system will prompt the Orchestrator to generate a JSON object containing a search query that can be used to gather relevant information for solving the sub-task. Defaults to False (optional).

## Functionality
The provided code snippet implements a conversational AI system using OpenAI's LM Studio API.

## Usage
To use this script, you can start by defining your objective and providing any necessary file content or previous results. You can then call the opus_orchestrator function with these parameters to initiate the AI system's process. The system will then orchestrate the tasks, delegate sub-tasks to sub-agents, refine outputs, and create folder structures based on your objectives and interactions with AI models.

## Requirements
- Python 3.8 or later
- OpenAI's LM Studio API

## Installation
To install the required dependencies, you can use pip:
```bash
pip install -r requirements.txt

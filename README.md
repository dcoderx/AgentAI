# Agentic AI

Built this simple agentic AI to explore goal-oriented systems. Shows how an agent handles research, scheduling, and writing tasks through planning and execution. Code is minimal to highlight core concepts. Demonstrates the fundamentals of agent architecture without external APIs or LLMs.

## Project Versions

This repository contains two implementations:

1. **Agent AI.ipynb**: The core implementation with basic planning and execution
2. **NLP enhanced Agent AI.ipynb**: An advanced version with NLP capabilities including:
   - Intent classification using pre-trained models
   - Entity extraction with semantic understanding
   - Natural language generation
   - Context-aware planning

The enhanced version demonstrates how NLP techniques can make agentic systems more intelligent and responsive to user goals.

## Overview

These Jupyter notebooks implement a lightweight agentic AI system that demonstrates:

- Goal-oriented behavior
- Context-aware planning
- Sequential execution of steps
- Progress tracking and status reporting

## How It Works

The agent follows a simple but effective process:
1. Accepts a goal from the user
2. Creates a plan based on the goal type (research, scheduling, writing, etc.)
3. Executes each step in sequence
4. Reports on progress and completion

In the enhanced NLP version, the agent also:
1. Analyzes the goal using pre-trained language models
2. Extracts specific entities (topics, timeframes) from the goal
3. Creates more contextually relevant plans
4. Generates natural language responses

## Examples

The notebooks include demonstrations of the agent handling:
- Research tasks
- Scheduling tasks
- Writing tasks
- Custom goals

## Running the Project

1. Clone this repository
2. Open either notebook in Jupyter or Google Colab
3. For the NLP-enhanced version, install required packages: `pip install transformers sentence-transformers nltk`
4. Run all cells to see the agent demonstrations
5. Modify the final example to test with your own goals

## Technical Concepts

These implementations demonstrate key concepts in agentic AI:
- State management
- Goal decomposition
- Task planning
- Execution monitoring
- Natural language processing (in enhanced version)
- Pre-trained model integration (in enhanced version)

## Future Improvements

While intentionally minimal, this project could be extended with:
- Integration with real tools and APIs
- More sophisticated natural language understanding
- Dynamic replanning
- Memory of past interactions
- Fine-tuning of NLP models for specific domains

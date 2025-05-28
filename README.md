# AIM Weekly Event - Google ADK, AIM Style

<p align="center">
  <img src="https://github.com/AI-Maker-Space/LLM-Dev-101/assets/37101144/d1343317-fa2f-41e1-8af1-1dbb18399719" width="200px" height="auto"/>
</p>

This repository contains a tutorial on Google's Agent Development Kit (ADK) AIM-Style.

## About Google ADK

From Google:
> ADK is a Python framework designed to streamline the development of applications powered by Large Language Models (LLMs). It offers robust building blocks for creating agents that can reason, plan, utilize tools, interact dynamically with users, and collaborate effectively within a team.

The [official documentation](https://google.github.io/adk-docs/) for this framework is exceptional and provides extensive guidance for building agent-based applications.

## What You'll Learn

This tutorial covers four comprehensive steps:

1. **Initial Setup and Configuration** - Setting up the environment with multiple AI providers
2. **Building a Simple Dice Rolling Agent** - Creating your first functional agent with tools
3. **Building a Team of Agents** - Implementing hierarchical agent delegation and coordination
4. **Adding Session State** - Managing stateful interactions and user preferences

## Prerequisites

- Python 3.13 or higher
- API keys for the following providers:
  - Google AI (Gemini models)
  - OpenAI (GPT models)
  - Anthropic (Claude models)

## Getting Started

1. Run `uv sync` to install dependencies
2. Start Jupyter notebook and ensure kernel points to `.venv`
3. Open `AIM-Google-SDK.ipynb`
4. Follow the step-by-step tutorial
5. Experiment with different models and configurations

## Dependencies

- **google-adk**: >=1.0.0 - Core Google Agent Development Kit
- **jupyter**: >=1.1.1 - Notebook environment  
- **litellm**: >=1.71.1 - Multi-provider LLM integration

## Notes

- This tutorial is modified from the official Google ADK tutorial
- The framework integrates exceptionally well with Google's ecosystem while supporting other providers
- LiteLLM integration allows seamless use of non-Google models
- The documentation quality for Google ADK is notably excellent

## Resources

- **Official Documentation**: [Google ADK Docs](https://google.github.io/adk-docs/)
- **Original Tutorial**: [Agent Team Tutorial](https://google.github.io/adk-docs/tutorials/agent-team/)
- **Runtime Documentation**: [ADK Runtime Guide](https://google.github.io/adk-docs/runtime/)
- **Events Documentation**: [ADK Events Guide](https://google.github.io/adk-docs/events/)

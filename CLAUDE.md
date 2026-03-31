# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

AI agent project built with [CrewAI](https://docs.crewai.com/) — a Python framework for orchestrating role-playing autonomous AI agents that collaborate on complex tasks.

## Status

This repository is in its initial setup phase. The codebase structure will be documented here as it develops.

## Development Setup

```bash
# Create and activate virtual environment
python -m venv .venv
source .venv/bin/activate

# Install dependencies (once requirements exist)
pip install -r requirements.txt
# or if using pyproject.toml:
pip install -e .
```

## Key CrewAI Concepts

- **Agents**: Autonomous units with roles, goals, and backstories that determine behavior
- **Tasks**: Units of work assigned to agents with expected output descriptions
- **Crew**: Orchestrates agents working together on tasks (sequential or hierarchical process)
- **Tools**: Functions agents can use to interact with external systems

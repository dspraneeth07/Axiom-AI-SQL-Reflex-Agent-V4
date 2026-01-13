# Axiom SQL Reflex Agent V4 Architecture

## Overview
This document describes the architecture of the Axiom SQL Reflex Agent V4, a system designed for intelligent SQL query generation and optimization.

## Directory Structure

### `/notebooks`
Jupyter notebooks for experimentation, analysis, and demonstrations.
- `00_env_setup.ipynb`: Environment setup and configuration

### `/agents`
Agent implementations and coordination logic.

### `/data`
Dataset storage and management.
- `/spider`: Spider dataset for training and evaluation
- `/bird`: Bird dataset for training and evaluation
- `/processed`: Preprocessed data ready for use

### `/contracts`
Schema contracts for validation and integration.
- `schema_contract.json`: Database schema validation contract
- `agent_io_contract.json`: Agent input/output contract

### `/evaluation`
Evaluation metrics, tests, and benchmarking utilities.

### `/docs`
Documentation including architecture and design specifications.

## Key Components

1. **Agents**: Core SQL generation and refinement logic
2. **Data Management**: Dataset loading and preprocessing
3. **Evaluation**: Performance metrics and quality assessment
4. **Contracts**: Interface definitions for system components

## Getting Started

1. Set up the environment using the notebook in `/notebooks/00_env_setup.ipynb`
2. Review the contracts in `/contracts` for interface specifications
3. Explore agents in `/agents` for implementation details
4. Run evaluations using utilities in `/evaluation`

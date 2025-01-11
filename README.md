# Agentic Mesh: AI-Powered Intelligent System

Agentic Mesh is an advanced AI-powered system designed to solve complex business queries using intelligent agents. This project leverages modern tools such as Poetry for dependency management, Ngrok for seamless local-to-remote sharing, MLflow for experiment tracking, and LlamaIndex for building high-performing agents with context-aware prompts.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Demo and Blog](#demo-and-blog)
- [Tech Stack](#tech-stack)
- [Setup and Installation](#setup-and-installation)
- [Feedback](#feedback)

---

## Introduction

Agentic Mesh is an end-to-end solution to manage and solve business queries by leveraging the power of intelligent agents. The system is designed to handle diverse data pipelines, execute complex tasks, and streamline the user experience through automation and intelligence.



## Features

- **Seamless Dependency Management**: Managed with Poetry to ensure hassle-free package resolution.
- **Remote Experiment Sharing**: Uses Ngrok to securely share MLflow dashboards with the team.
- **Experiment Tracking**: MLflow tracks all experiments with detailed logs for parameters, metrics, and artifacts.
- **Intelligent Agents**: Powered by LlamaIndex to perform efficient data retrieval and reasoning with customizable prompts.
- **Reproducibility**: Ensures experiments and results can be reproduced reliably.


## Demo and Blog

- **Demo Video**: [Watch the Live Demo](https://github.com/user-attachments/assets/10c1bac6-d5e4-47da-aa4b-7e6a5ea245e8)
- **Blog Post**: [Read the Detailed Blog Here]([https://your-blog-link.com](https://sahaniiianuj.medium.com/agentic-mesh-e030d3576d86))

Explore the live walkthrough of Agentic Mesh in action and learn about the complete development journey in the accompanying blog post.

---

## Tech Stack

This project leverages a well-curated tech stack for seamless development, experiment tracking, and intelligent query handling. Below is a detailed overview of the tools and technologies used:

#### **Dependency Management**
##### [Poetry](https://python-poetry.org/)
- Python dependency management and packaging tool.
- Solves dependency conflicts with `poetry.lock`.
- Ensures consistent environments across development, testing, and production.

#### **Experiment Tracking and Management**
##### [MLflow](https://mlflow.org/)
- Used for tracking experiments, logging metrics, and managing models.
- Integrated with Ngrok for remote sharing of experiment results.
- Provides reproducibility and detailed comparison across experiments.

#### **Tunneling Service**
##### [Ngrok](https://ngrok.com/)
- Exposes local servers to the internet via secure tunnels.
- Enabled sharing of MLflow tracking server with team members remotely.
- Simplifies collaboration and remote debugging.

#### **Intelligent Query Handling**
##### [LlamaIndex](https://docs.llamaindex.ai/en/stable/)
- Provides tools for indexing and querying large datasets using natural language.
- Features:
  - **Index Builders**: Structures data for efficient retrieval.
  - **Context Templates**: Fine-tuned prompts for high-accuracy responses.
  - **Agents**: Multi-step reasoning for solving complex queries.

#### **Python Libraries**
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical computing.
- **LlamaIndex**: Indexing and querying large datasets.
- **HuggingFace**: Using open source language and embedding models.
- **Asyncio**: For running concurrent fucntions while using LLamaParser.
- **Gradio**: For a quick demo of Agentic Mesh

#### **Development Environment**
- **Google Colab**: Free Tier

---

## Setup and Installation

Follow these steps to set up the project:

#### Step 1: Install Poetry

Poetry is a dependency and package manager for Python. You can install Poetry by running the following command:

```bash
curl -sSL https://install.python-poetry.org | python3 - --version 1.8.5
```

This will install Poetry version 1.8.5. Ensure that the Poetry binary is added to your system's `PATH`. To do so, append the following line to your shell configuration file (e.g., `.bashrc` or `.zshrc`):

```bash
export PATH="$HOME/.local/bin:$PATH"
```

Alternatively, you can call Poetry explicitly using its full path:

```bash
~/.local/bin/poetry --version
```

#### Step 2: Add Project Dependencies

This project uses a basic_requirements.txt file to list its dependencies. To add these dependencies to Poetry, run:

```bash
cat basic_requirements.txt | xargs -n 1 poetry add
```
This will add all required dependencies to the project.

#### Step 3: Export Dependencies to requirements.txt

Once the dependencies are added, export them to a requirements.txt file using the following command:

```
poetry export --without-hashes -f requirements.txt > requirements.txt
```
This generates a requirements.txt file that can be used to install dependencies via pip.


#### Step 4: Install Project Dependencies

Navigate to the project directory and install the required dependencies. This project uses a `requirements.txt` file generated by Poetry to manage dependencies. To install the dependencies, run:

```bash
pip install -r requirements.txt
```

#### Step 5: Running the Jupyter Notebook

Once the dependencies are installed, open the Jupyter Notebook and execute the cells sequentially. Start Jupyter Notebook with the following command:

```bash
jupyter notebook AgenticMesh.ipynb
```



## Feedback

I would love to hear your thoughts about Agentic Mesh. If you have any feedback, suggestions, or queries, feel free to reach out to me at: [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/anuj-sahani-34363725b) 

Author: [@anujsahani01](https://github.com/anujsahani01)

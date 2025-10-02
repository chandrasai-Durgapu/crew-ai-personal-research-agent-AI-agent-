# Crew AI Personal Research Agent

A personal AI-powered research assistant designed to help you organize, retrieve, and analyze research data seamlessly.

---

## Features

- Natural language querying and summarization of your research data  
- Retrieval-augmented generation (RAG) for precise answers  
- Integration with knowledge bases and document stores  
- Customizable AI assistant tailored to your research workflow  
- Easy to extend with additional data sources and tools  

---

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/crew-ai-personal-research-agent.git
   cd crew-ai-personal-research-agent
```
---

## Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
```
## Install dependencies:
```bash
pip install -r requirements.txt
```
---
## Set up environment variables:
```bash
API_KEY=your_api_key_here
OTHER_CONFIG=your_config
```
---
## Run the agent:
```bash
python main.py
```
---
## Core Components

agents/: Contains the definitions of various AI agents responsible for different tasks within the research process.

tasks/: Houses the task definitions that agents will execute, outlining specific objectives and workflows.

app.py: Serves as the main application entry point, initializing and managing the execution of agents and tasks.

crew.py: Defines the coordination logic for the AI agents, ensuring they work together effectively.

main.py: Acts as the script to launch the application, setting up necessary configurations and starting the agent workflows.

requirements.txt: Lists all the Python dependencies required to run the project.

README.md: Provides an overview of the project, setup instructions, and usage guidelines.







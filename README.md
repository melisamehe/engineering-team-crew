# EngineeringTeam Crew

Welcome to the **EngineeringTeam Crew** project, powered by [crewAI](https://crewai.com)! 🚀  
This project template helps you set up a multi-agent AI system, enabling agents to collaborate effectively on complex tasks and maximize their collective intelligence.

<img width="952" height="424" alt="trading simulation platform" src="https://github.com/user-attachments/assets/d3da41a7-d514-4c57-ac37-438d646b73b4" />
<img width="770" height="416" alt="tsp2" src="https://github.com/user-attachments/assets/c386e2a0-1d0b-43c6-b095-88da66f26d89" />


## ⚙️ Installation

Make sure you have **Python >=3.10 <3.13** installed.  
This project uses [UV](https://docs.astral.sh/uv/) for dependency management and package handling, offering a seamless setup experience.

1. Install `uv` (if not already installed):

```bash
pip install uv
```

2. Navigate to your project directory and install dependencies:

(Optional) Lock dependencies and install via CLI:
```bash
crewai install
```

3. Add Gradio to your project:
```bash
uv add gradio
```
## 🛠 Customization

- Add your OPENAI_API_KEY in the .env file.

- Configure your agents and tasks:

- src/engineering_team/config/agents.yaml → define your agents

- src/engineering_team/config/tasks.yaml → define your tasks

- Customize logic, tools, and arguments:→
src/engineering_team/crew.py

- Add custom inputs for your agents and tasks:
→src/engineering_team/main.py

## ▶️ Running the Project

To start your AI crew and execute tasks locally with Gradio, run:
```bash
uv run app.py
```

✅ This will launch your app and Gradio will provide a local web interface.
Open your browser and go to the URL shown in the terminal, usually:

http://127.0.0.1:7860


By default, the original crewAI setup will generate a report.md file in the root folder with research output on LLMs.

## 🤖 Understanding Your Crew

The engineering_team Crew consists of multiple AI agents with unique roles, goals, and tools.
They collaborate on tasks defined in config/tasks.yaml, leveraging their collective skills.
The config/agents.yaml file outlines each agent's capabilities and configuration.
<img width="761" height="492" alt="tsp3" src="https://github.com/user-attachments/assets/9c0882d5-8247-445b-a7ae-0366e145774c" />
<img width="750" height="369" alt="tsp4" src="https://github.com/user-attachments/assets/00f2d405-7b80-43a2-ae23-2b1416518054" />
<img width="746" height="312" alt="tsp5" src="https://github.com/user-attachments/assets/511d290b-3bda-4d5d-afce-1e97d98ab7fb" />

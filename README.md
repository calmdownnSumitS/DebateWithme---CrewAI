# Debate Crew

Setting up crew.py:   main.py Functionality,Running the Debate, The importance of tracing functionality to observe the debate's progress and outcomes is also emphasized


Wire Up crew.py and main.py to Run a CrewAI Debate" focuses on setting up a debate system using Python and YAML configuration files. Here's a brief overview of what it covers:

Configuration Files Recap: It starts with a recap of the agents.yaml and tasks.yaml files, which define the agents and tasks needed for the debate.

Setting up crew.py: The instructor demonstrates how to define agents and tasks in the crew.py file by copying functions from a reference implementation. This involves ensuring that agent names match exactly with those in the YAML files to avoid errors.

main.py Functionality: The lecture then shifts to main.py, which is essential for setting the motion of the debate. The instructor explains how to create a function that allows for user input regarding the motion, making the system interactive.

Running the Debate: You'll see a demonstration of how to run the crew, executing tasks such as proposing, opposing, and deciding on the motion of the debate.

Monitoring Progress: The importance of tracing functionality to observe the debate's progress and outcomes is also emphasized.

Future Learning: The session concludes with a summary and hints at future lectures where these concepts will be revisited, encouraging participants to experiment with the code.


Welcome to the Debate Crew project, powered by [crewAI](https://crewai.com). This template is designed to help you set up a multi-agent AI system with ease, leveraging the powerful and flexible framework provided by crewAI. Our goal is to enable your agents to collaborate effectively on complex tasks, maximizing their collective intelligence and capabilities.

## Installation

Ensure you have Python >=3.10 <3.14 installed on your system. This project uses [UV](https://docs.astral.sh/uv/) for dependency management and package handling, offering a seamless setup and execution experience.

First, if you haven't already, install uv:

```bash
pip install uv
```

Next, navigate to your project directory and install the dependencies:

(Optional) Lock the dependencies and install them by using the CLI command:
```bash
crewai install
```
### Customizing

**Add your `OPENAI_API_KEY` into the `.env` file**

- Modify `src/debate/config/agents.yaml` to define your agents
- Modify `src/debate/config/tasks.yaml` to define your tasks
- Modify `src/debate/crew.py` to add your own logic, tools and specific args
- Modify `src/debate/main.py` to add custom inputs for your agents and tasks

## Running the Project

To kickstart your crew of AI agents and begin task execution, run this from the root folder of your project:

```bash
$ crewai run
```

This command initializes the debate Crew, assembling the agents and assigning them tasks as defined in your configuration.

This example, unmodified, will run the create a `report.md` file with the output of a research on LLMs in the root folder.

## Understanding Your Crew

The debate Crew is composed of multiple AI agents, each with unique roles, goals, and tools. These agents collaborate on a series of tasks, defined in `config/tasks.yaml`, leveraging their collective skills to achieve complex objectives. The `config/agents.yaml` file outlines the capabilities and configurations of each agent in your crew.

## Support

For support, questions, or feedback regarding the Debate Crew or crewAI.
- Visit our [documentation](https://docs.crewai.com)
- Reach out to us through our [GitHub repository](https://github.com/joaomdmoura/crewai)
- [Join our Discord](https://discord.com/invite/X4JWnZnxPb)
- [Chat with our docs](https://chatg.pt/DWjSBZn)

Let's create wonders together with the power and simplicity of crewAI.

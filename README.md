# NewsletterGen Crew with GUI

Welcome to the NewsletterGen Crew project, powered by crewAI. A multi-agent AI system with ease, leveraging the powerful and flexible framework provided by crewAI. Our goal is to enable your agents to collaborate effectively on complex tasks, maximizing their collective intelligence and capabilities.

# Installation
Ensure you have Python >=3.10 <=3.13 installed on your system. This project uses Poetry for dependency management and package handling, offering a seamless setup and execution experience.

First install Poetry:

pip install poetry
Next, navigate to your project directory and install the dependencies:

First lock the dependencies and then install them:
poetry lock
poetry install
Customizing
Add your GROQ_API_KEY into the .env file

# Running the Project
To kickstart your crew of AI agents and begin task execution, run this from the root folder of your project:

poetry run newsletter_gen
This command initializes the newsletter-gen Crew, assembling the agents and assigning them tasks as defined in your configuration.

This example, unmodified, will run the create a report.md file with the output of a research on LLMs in the root folser

# Understanding Your Crew
The newsletter-gen Crew is composed of multiple AI agents, each with unique roles, goals, and tools. These agents collaborate on a series of tasks, defined in config/tasks.yaml, leveraging their collective skills to achieve complex objectives. The config/agents.yaml file outlines the capabilities and configurations of each agent in your crew.

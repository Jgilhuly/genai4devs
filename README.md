# Unlock the Power of Generative AI with crewAI

![Unlock the Power of Generative AI with crewAI](genAI_for_Developers_1200x675_v2.jpg)

## Introduction
Welcome to the 'Unlock the Power of Generative AI with crewAI' Project! This project builds upon the CrewAI Stock Analysis project, extending it to a full-fledged Agentic application. Using the CrewAI framework, this service automates the investment analysis process by orchestrating autonomous AI agents to collaborate and execute complex tasks efficiently.

This repository has been created for demo purposes for the 'GenAI for Developers' Meetup on July 11, 2024, titled "Unlock the Power of Generative AI with CrewAI."

## Inspiration
The inspiration for CrewAI SaaS comes from [this video by @Kno2gether](https://www.youtube.com/watch?v=pFZHpFuzcBE&t=854s).

## Setup Virtual Environment
# Step 1 - install dependencies using poetry
>poetry install

# Step 2 - install Tensorflow via pip
>pip install tensorflow

## Setup Configurations
# Step 3 - Setup your .env KEYS
    OPENAI_API_KEY="KEY"
    NGROK_API_KEY="KEY"
    LLM_MODEL="gpt-4o"

# Step 4 - Setup the workflow
- I’ve only enabled the Monitoring crew / workflow
        services/service.py > performance_monitoring_flag = True 

- The 2x PDF files required as input into the Monitoring crew / workflow
are in the data folder {Asset Allocation Views March Quarter 2024 - Final.pdf, 2b. High Growth Monitoring Risks v5.1.pdf}

# Step 5 - Execute the workflow
- main.py

## Author
Developed by [@gvossos](https://github.com/gvossos/).

## License
This project is released under the MIT License.

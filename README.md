# Shopy - Salesforce Agentforce Project

This repository contains the configuration and metadata for **Shopy**, an intelligent [Agentforce](https://orgfarm-c6d2ea1dbc-dev-ed.develop.lightning.force.com/lightning/n/standard-AgentforceStudio) agent built using Salesforce Agentforce Studio.

## Overview
* **Agent Name:** Shopy
* **Created By:** Arjun .
* **Platform:** Salesforce Developer Edition

## Repository Structure
* `force-app/main/default/genAiPlanners/` - Contains the agent's planner and reasoning engine configurations.
* `force-app/main/default/bots/` - Core bot and agent definition metadata.
* `force-app/main/default/genAiPlugins/` - Associated topics, actions, and skill definitions.

## Setup & Deployment

### Prerequisites
* [Salesforce CLI (`sf`)](https://developer.salesforce.com/tools/sfdxcli) installed.
* Access to a Salesforce org with Agentforce enabled.

### 1. Authenticate to Your Org
```bash
sf org login web --alias <your-org-alias>

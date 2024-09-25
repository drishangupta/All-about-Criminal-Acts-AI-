# CrimeData

This repository contains an AI model designed to spread awareness about various types of crimes and offer prevention strategies. It provides insights into crime trends across different regions, helping users stay informed and vigilant.

Quick Guide
This guide helps you set up the AI model on your machine.

Install the Gaia Node by running the command below
```
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

Set Up Environment: After installation, run the command printed on the terminal to set up the environment path. This command starts with source.

Initialize Configuration: Update the configuration to use the crime dataset:
```
gaianet init --config https://raw.githubusercontent.com/drishangupta/All-about-Criminal-Acts-AI-/b4eb1932a3339bf0fa9bee401a4bc25d949c0981/config.json
```

Run the node
```
gaianet start
```

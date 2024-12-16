# A3C for Kung Fu
This repository contains code for implementing an Asynchronous Advantage Actor-Critic (A3C) agent to train on the Kung Fu Master environment from Atari.

## Getting Started
This code requires several external libraries. You can install them using the following command in your terminal:

pip install gymnasium["atari, accept-rom-license"] ale-py torch tqdm
Note: Installing the atari extra for gymnasium may require accepting a separate license agreement.

## Code Breakdown
The code is divided into several parts:

### Installation: 
This section installs the required libraries using pip.
### Importing Libraries: 
This section imports all the necessary libraries for building and training the A3C agent.
### Building the AI: 
This section defines the neural network architecture used by the agent.
### Training the AI:
### Setting Up the Environment: 
This section prepares the Kung Fu Master environment and preprocesses the observations.
### Initializing Hyperparameters: 
This section defines hyperparameters like learning rate and discount factor.
### Implementing the A3C Class: 
This section defines the Agent class, which handles acting, learning, and updating the network parameters.
### Initializing the Agent: 
This section creates an instance of the Agent class with the number of actions available in the environment.
### Evaluating the Agent: 
This section defines a function to evaluate the agent's performance on a single episode.
### Training the Agent: 
This section defines a class EnvBatch that manages multiple environments and trains the agent asynchronously using multiple processes.
## Running the Code
Clone this repository to your local machine.
Open a terminal in the project directory and install the required libraries using the command mentioned above.
Run the training script (train.py if it exists) to train the agent.
You can modify the hyperparameters and other settings in the code to experiment with different configurations.
## Additional Notes
This code snippet provides a high-level overview of the code's functionality. Refer to the actual code files for detailed implementation.
Training an A3C agent can take a significant amount of time and resources depending on the chosen hyperparameters.

I hope this Readme helps you understand the purpose and structure of this code. 

# Anthropic's Tool Use with Claude 3

This Jupyter Notebook demonstrates the usage of Anthropic's Tool use (function calling) feature with the Claude 3 model. The purpose of this exercise is to explore how Claude 3 can interact with external tools and retrieve relevant information based on user queries.

# Table of Contents
1. [Introduction](#introduction)
2. [Sample Output](#sample-output)
3. [Prerequisites](#prerequisites)
4. [Setup](#setup)
5. [Running the Notebook](#running-the-notebook)
6. [Output](#output)

<a name="introduction"></a>
## Introduction
This section provides an overview of the notebook's purpose and capabilities, highlighting its focus on demonstrating the Claude 3 model's interaction with function calling.

<a name="sample-output"></a>
## Sample Output
### Questions and Answers:
 - Question: Do you know anything about United Kingdom
 - Answer: ![Answer 1](/images/q1.png)


<a name="prerequisites"></a>
## Prerequisites
Before running this notebook, ensure the following are installed:
1. Python
2. Jupyter Notebook (install via `pip install jupyter`)
3. Required Python packages (install via `pip install -r requirements.txt`)
4. Anthropic Claude 3 API Key ([get it here](https://www.anthropic.com/api))
5. Ninja API Key ([get a free key here](https://api-ninjas.com/))

<a name="setup"></a>
## Setup
### Steps to Set Up Your Environment:
1. Clone this repository or download as a ZIP.
2. Navigate to the directory in your terminal.
3. Create a `.env` file with your Anthropic and Ninja API keys:


4. Launch Jupyter Notebook by running the following command in your terminal:

    ```jupyter notebook```


5. Open the `Claude 3 Function Call.ipynb.ipynb` file in Jupyter Notebook.

## Running the Notebook

1. Once you have the notebook open, you can run each cell in sequential order by clicking on the cell and pressing `Shift + Enter`.

2. The notebook will execute the code, set up the necessary configurations, and define the required functions.

3. At the end of the notebook, there are two example queries;
    - "do you know anything about United Kingdom"
    - "do you know anything about London"

4. The final answers will be printed with colored formatting for better readability.

5. Feel free to explore the code and modify the queries to experiment with different inputs and observe how Claude 3 responds.

<a name="output"></a>
## Output
### Questions and Answers:
 - Question: Do you know anything about United Kingdom
 - Answer: ![Answer 1](/images/q1.png)

    <br>
    <br>
 - Question: Do you know anything about London
 - Answer: ![Answer 2](/images/q2.png)

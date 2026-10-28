# CMPSC 105 Data Exploration - Lab 07: Interpreting Hypothesis Tests

## Overview
In this lab, we will explore building elements of a data analysis report. 

You will be working in pairs for this lab. Make sure to include both names in the `lab07.ipynb` notebook. 

## Part 1: The GitHub Workflow
In this course, our cadence for managing assignments relies on GitHub. Before we write any code, we need to set up your environment. Follow these steps:

1. **Fork the Repository:** Navigate to the provided lab repository link. In the top right corner, click the **Fork** button. This creates a personal copy of the repository under your own GitHub account.
2. **Clone the Repository:** Open your terminal in VS Code and clone your *forked* version of the repository to your local machine:
   ```bash
   git clone https://github.com/YOUR_USERNAME/cmpsc105-lab07.git
   ```
3. **Navigate and Open:** Open the `cmpsc105-lab07` folder in VS Code.

## Part 2: Setting up the Python Environment with `uv`
Before we run our analysis, we need an isolated environment to manage our dependencies. We use `uv`, an extremely fast Python package manager.

1. **Create the Virtual Environment:** In your terminal, ensure you are inside the `cmpsc105-lab07` directory, then run:
   ```bash
   uv venv
   ```
2. **Activate the Environment:** You must activate the environment so your terminal uses the isolated Python version.
   * On **macOS/Linux**:
     ```bash
     source .venv/bin/activate
     ```
   * On **Windows**:
     ```bash
     .venv\Scripts\activate
     ```
   If you run into an issue, try typing 
   ```bash
   uv init
   ```

3. **Install Libraries:** With the environment active, install the required library:
   ```bash
   uv add pandas
   uv add seaborn
   ```

## Part 3: Getting to Work
Open the `lab07.ipynb` notebook file to begin your analysis.

## Part 4: Submission

**Pushing Your Work:** Once you complete the lab, add, commit, and push your changes to your fork. In VS Code, this can be done by
- Clicking the Source Control icon in the left sidebar, 
- Staging your changes and writing a commit message
- Committing the changes by clicking the checkmark, and finally
- Pushing the changes to your forked repository by clicking the "..." menu and selecting "Push".

Once you've finished, hang tight and we'll look at some of the results together.
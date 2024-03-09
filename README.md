# CST440_Benchmark2

This jupyternotebook is a tool designed to efficiently mine and analyze pull requests from GitHub repositories. <br>
This README provides detailed instructions on how to install and run the application, as well as an overview of its features and functionalities.

## Features

- **Data Mining:** Ability to mine pull requests from specified GitHub repositories.
- **Analysis:** Perform analysis on a large amount of mined data, focusing on the categorization of pull requests as closed or merged.
- **Performance Logging:** Detailed logging of app activity, including API requests, execution timing, and error tracking.

## Installation

Before running the application, ensure you have Python and Jupyter Notebook installed on your system. The application relies on the `PyGithub` library for interacting with the GitHub API.

## Contents

This Repository contains:

  1. The CSV file.
  
  2. The Link to the repository mined.<br>
  https://github.com/langchain-ai/langchain/pulls
  
  3. The application repository is on GitHub.<br>
  
  4. Detailed instructions on installing and running the app in the README file.<br>
    1. Simply Run the Jupyternotebook Scripts.<br>
    2. Code involves Mining, Closed or Merged Predicator.
  
  5. Log file describing the app activity (requests made, timing, errors, etc)<br>
    1. With using PyGithub, the repository requests are made by Github API. <br>
    2. 1000 PR took `41m 44s`<br>
    3. No error occurred within the process<br>
      
  7. An analysis of the large amount of information processed.

# Travis, Why Do the Builds Keep Failing?: An Analysis on CI Failure Causes and Severity
**Authors:** Matt Sichterman, Easton Joachimsen, and Colin Cummings

<p align="center"><img src="https://github.com/msichterman/csce-496-project/blob/master/Travis-and-Github.png" width="600" /></p>

This repository is home to the artifacts from the semester long project for CSCE 496: Empirical Software Engineering. This project consisted of five milestones with the end goal of conductiing an experiment/analysis on a selected topic and then writing an [IEEE conference proceedings](https://www.ieee.org/conferences/publishing/templates.html) paper. We chose to do our study on data from Travis CI and GitHub via the [TravisTorrent data set](https://travistorrent.testroots.org/) in an effort to analyze the main causes of continuous integration build failures and categorize their severity. Our findings were presented and elaborated upon in our final report.

## Artifacts in this Repository
### Milestone Submissions:
* [Milestone 1 (Project Proposal)](https://github.com/msichterman/csce-496-project/blob/master/Milestone%201.docx)
* [Milestone 2 (Rough Draft)](https://github.com/msichterman/csce-496-project/blob/master/Milestone2.pdf)
* [Milestone 4 (Final Report)](https://github.com/msichterman/csce-496-project/blob/master/FinalReport.pdf)
* [Final Overleaf Zip](https://github.com/msichterman/csce-496-project/blob/master/ImperialEngineersOverleaf.zip)

### Writing Center Feedback
* [Feedback](https://github.com/msichterman/csce-496-project/blob/master/Writing%20Center%20Feedback.pdf)

### Data Set
* [TravisTorrent 3 Projects with Tests](https://github.com/msichterman/csce-496-project/blob/master/TravisTorrent-3-Projects-With-Tests.csv)

### Data Analysis Code
* [Python Jupyter Notebook](https://github.com/msichterman/csce-496-project/blob/master/CSCE496_Project.ipynb)

### Related Work
* [Oops, My Tests Broke the Build- An Explorative Analysis of Travis CI with GitHub](https://github.com/msichterman/csce-496-project/blob/master/Oops%2C%20My%20Tests%20Broke%20the%20Build-%20An%20Explorative%20Analysis%20of%20Travis%20CI%20with%20GitHub.pdf)
* [How Does Contributors’ Involvement Influence the Build Status of an Open-Source Software Project](https://github.com/msichterman/csce-496-project/blob/master/How%20Does%20Contributors%E2%80%99%20Involvement%20Influence%20the%20Build%20Status%20of%20an%20Open-Source%20Software%20Project_.pdf)
* [How Open Source Projects use Static Code Analysis Tools in Continuous Integration Pipelines](https://github.com/msichterman/csce-496-project/blob/master/How%20Open%20Source%20Projects%20use%20Static%20Code%20Analysis%20Tools%20in%20Continuous%20Integration%20Pipelines%20(1).pdf)
* ... and more (elaborated on in the final paper)

## How to Run the Data Analysis Code
1. Download this repository as a whole, or just download [CSCE496_Project.ipynb](https://github.com/msichterman/csce-496-project/blob/master/CSCE496_Project.ipynb) and [TravisTorrent-3-Projects-With-Tests.csv](https://github.com/msichterman/csce-496-project/blob/master/TravisTorrent-3-Projects-With-Tests.csv) and place them in the same directory.
2. Open the directory methioned aboce in the Jupyter Notebook software of your choice. We used [Google Colab](https://colab.research.google.com/) during our project, but tested the final file in Visual Studio Code with the [Jupyter extension](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) (recommended method to run).
3. Ensure the data set is imported correctly.
4. Run the sections labeled `RQ1 Analysis` and `RQ2 Analysis` to see the results for our research questions, respectively.

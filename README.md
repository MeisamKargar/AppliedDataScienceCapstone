# AppliedDataScienceCapstone
In this capstone, we will predict if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website, with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch. In this module, you will be provided with an overview of the problem and the tools you need to complete the course.
## Learning Objectives
<div>
  <ul>
    <li>Develop Python code to manipulate data in a Pandas data frame</li>
    <li>DConvert a JSON file into a Create a Python Pandas data frame by converting a JSON file</li>
    <li>Create a Jupyter notebook and make it sharable using GitHub</li>
<li>Utilize data science methodologies to define and formulate a real-world business problem</li>
<li>Utilize your data analysis tools to load a dataset, clean it, and find out interesting insights from it</li>
  </ul>
</div>

## Section 1: data collection from wikipedia: 
In the first step, we collect data from Wikipedia, which is available through the web scraping for watch this section you can click [here](https://github.com/MeisamKargar/AppliedDataScienceCapstone/blob/main/jupyter-labs-webscraping.ipynb)
## Section 2: Data wrangling:
In this [lab](https://github.com/MeisamKargar/AppliedDataScienceCapstone/blob/main/labs-jupyter-spacex-Data%20wrangling.ipynb)), we will perform some Exploratory Data Analysis (EDA) to find some patterns in the data and determine what would be the label for training supervised models.

In the data set, there are several different cases where the booster did not land successfully. Sometimes a landing was attempted but failed due to an accident; for example, True Ocean means the mission outcome was successfully landed to a specific region of the ocean while False Ocean means the mission outcome was unsuccessfully landed to a specific region of the ocean. True RTLS means the mission outcome was successfully landed to a ground pad False RTLS means the mission outcome was unsuccessfully landed to a ground pad.True ASDS means the mission outcome was successfully landed on a drone ship False ASDS means the mission outcome was unsuccessfully landed on a drone ship.

In this lab we will mainly convert those outcomes into Training Labels with 1 means the booster successfully landed 0 means it was unsuccessful.

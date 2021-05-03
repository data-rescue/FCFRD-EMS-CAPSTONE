# Using Advanced Data Analytics and Mapping Approaches to Facilitate Service Operations to the Local Comunity

## Data Rescue Team
* Michael McRae
* Jared Gauntt
* Mark Lee
* Elizabeth McLaughlin
* Angel Sierra
* Anup Upadhyaya

## Abstract
The Fairfax County Fire and Rescue Department (FCFRD) serves the largest county in the state of Virginia, and one of the fastest growing in the country.  The Data Analytics Strategy Management Division of the FCFRD is responsible for collecting and analyzing data from the activity of 38 fire stations and needs help prioritizing the application of their limited resources by identifying potential indicators and supporting insights to guide their future investigation and innovation efforts.  The Data Rescue Team from GMU developed a novel three-layer framework for data analysis. In the framework the team identifies indicators and supporting insights that guide investigations to be performed by the FCFRD. The team identified indicators (evidence that meaningful correlations or abnormalities exist within the data) and provided additional insights that support or further explain those indicators.  These indicators and insights may guide the application of FCFRD resources to perform further investigations that lead to the identification of real issues and potential solutions.  The team focused their efforts on the relationships between treatment (procedures and medications) and factors such as patient and provider gender and provider tenure. Additionally, the team analyzed trends in patient outcomes as related to provider tenure and individual stations and shifts.

## Project Objectives
The Data Rescue Team has four primary objectives for this project. These objectives include identifying meaningful correlations between features of interest, providing supporting analysis and insights for those correlations, providing possible recommendations, and enabling our partners to witness the approach and analytics utilized during this process.

**Objective 1:** Identify indicators - Determine if there are correlations that may indicate causal relationships between identified features in the datasets. The FCFRD provided the project team with four areas of interest where indicators may exist. 

* Patient Treatment vs Gender (patient and provider)
* Patient Treatment vs Tenure (provider)
* EMS Call Outcome vs Tenure (provider)
* EMS Call Patient Outcome vs Station and Shift

These indicators will serve as a “first blush” look at correlations that may indicate real issues such as fatigue or complacency among more experienced providers or empathetic effects that alter the consistency or quality of treatment based on gender of the patient or provider.

**Objective 2:** Provide Insights – When a significant correlation or pattern is found, further action is necessary to provide supporting insights, clarification and understanding. This action may be additional analysis that explains the significance or the meaning of these indicators. These insights provide focus and direction as well as potential justification for future investigative efforts. 

Additional insights might include more detail such as determining when in a provider’s tenure the fatigue or complacency is most likely to begin and when would be a good time to rotate out. These insights might also provide leads on possible root causes of any identified patterns.

**Objective 3:** Provide Recommendations – In many cases, the indicators and insights will only tell part of the story and a more detailed analysis of data that has not been sanitized to protect PHI will be needed. The project team will make every effort to provide recommendations for additional investigation and analysis that might lead to the improvement of the consistency, quality, and efficiency of EMS care provided by the FCFRD.

**Objective 4:** Share Our Approach – In addition to the results provided in meeting the first three objectives, the FCFRD has a strong desire to gain visibility into the approaches, methods, tools, and analytics that the Data Rescue Team employs during their analysis. Accomplished through weekly exchanges between the teams and the detailed report, briefings, and graphics provided by the Data Rescue Team, we will share our approach which the FCFRD can take and apply to their daily work as they see fit.

## Environment Configuration
The first step to leverage this repository is to configure your local environment properly and to achieve this, basic knowledge of Git, Python, and Anaconda is required. However, a configuration video was created and attached to the main artifacts delivered in compressed file.

Since we will not be able to cover all technical aspects about your development environment we wanted to provide a couple of internet resources we found useful in our journey.

For **Git** we recommend to start by reading the Git Configuration, and in particular make sure you set up your global user name and user email. Another beneficial item would be the Git Cheat Sheet provided by the GitHub Education site as it provides the most commonly use commands within Git.
* https://www.git-scm.com/book/en/v2/Customizing-Git-Git-Configuration
* https://education.github.com/git-cheat-sheet-education.pdf

For **Anaconda** we recommends to leverage the documentation provided by the community, especially for the Conda cheat sheet that contains the most commonly used commands.
* https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf

For **VSCode** we recommend to start by going through the Data Science in Visual Studio Code tutorial as it will provide the foundations you need to start running python scripts and jupyter notebooks within VSCode.
* https://code.visualstudio.com/docs/python/data-science-tutorial

Finally, to more easily understand many of our scripts in this projects it will be useful to have a **Pandas** cheat sheet with the most common pandas methods used delivered as a cheat sheet.
* https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf

### Environment Configuration Steps
In general, you will need to perform the following steps to configure the environment:
1. Clone the project in your local computer
2. Create an Anaconda environment using the requirements.yml file provided in this repository
3. Add the path where you cloned this project to the anaconda environment to ensure the environment can find the python modules created by the group.


## Additional Resources
It is likely that future CAPSTONE projects continue to be coordinated between George Masson University (GMU) and the Fairfax County Fire and Rescue Department (FCFRD). The needs of our partners at FCFRD may evolve and their analytics questions change base on the insights and indicators provided by the GMU students, resulting in different versions of the raw dataset and inclusion of new datasets.

For this reason, it is important to expect different artifacts to be provided by either FCFRD or GMU professor. At least, for this particular repository we have generated a set of artifacts that would provide you the necessary information to understand the analysis we have performed. 

In particular, we have included the raw data set we used for our analysis. This raw dataset is an important dependency to replicate all the results presented in this repository on your local machine.

In the file you will find the following artifacts:

* DAEN_690_Project_Paper-TeamDiRT-FINAL.pdf
* DAEN_690-EMS-TeamDiRT-FINAL.pptx
* 20210225-ems-raw-v04.xlsx
* DAEN_690-EMS-TeamDiRT-Environment-Configuration.mp4

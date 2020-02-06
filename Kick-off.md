<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Welcome to the Amsterdam Project!

## Content
- [Project Description](#project-description)
- [Project Goals](#project-goals)
- [Data Workflow](#data-workflow)
- [Requirements & Deliverables](#requirements-&-deliverables)
- [Mentoring](#mentoring)
- [Schedule](#schedule)
- [Datasets](#datasets)
- [Presentation](#presentation)
- [Tips & Tricks](#tips-&-tricks)
- [Asking Questions](#asking-questions)

## Project Description
In this project you will present an analysis of a topic of your choosing related to the city of Amsterdam.

Possible topics are:  
* Transportation
* Urban environment
* Population
* Administration
* Economics & business

In this project you will work in **teams**. Your team must come to an agreement with the other teams so that each of you work on a different topic.

Possible datasets you can use are suggested in the ```Datasets``` section below.

## Project Goals
During this project you will:
* Learn how to work in a team.
* Fork and manage your own git repository and avoid conflicts with your teammate's code.
* Ask yourself interesting questions related to your topic.
* Search and explore data that will help you answer your questions.
* Build a database.
* Perform a simple analysis and identify interesting insights.
* Focus on learning and developing Data Wrangling skills
* Learn something about Amsterdam!

## Initialization Steps
 - Divide up in groups
 - For each group one of the group members forks this template repository and invite the   other group members of to collaborate
 - The other group members accept the invitation, clone the forked repository and start collaborating on the same repository

## Requirements & Deliverables
The **mandatory** deliverables and requirements that you must turn in are:
* Link to the repository you used while working on your project (see below for more details)
* Your repository must be clean and organized; this means that it must include a *.gitignore* file and a README file and also have a functional file structure.
* The README file is based on the template you find here (in your_code folder)
  * Your README file must clearly include which topic you chose and which are the questions you would like to find an answer to.
  * Your README file should include a link to your group's TRELLO board. The project must be planned. 
    That is why creating a Kanban board is important. 
    You can find a template for Trello [here](https://trello.com/b/usAykV9K/project-2-barcelona). 
    **You are strongly advised not to start coding you until your project is planned and your questions defined**
  * Your README must include **links** to all the raw files you used to complete your analysis. Remember to commit often to avoid trouble in case you mess up: this means more than 1 commit!
  * Your README file must include a **link** to the database you created starting from the raw files.The database file should be of type *.sql
  * Your README file should include a **link** to your Entity Relationship Diagram (ERD) image that describes the structure of your database. You don't need to specify the data types of each column, only the tables you will create, the columns they have and the relationships between the tables. 
    Include the link to your ERD in your README file.
  * Your README file should contain a **link** to the project  presentation
* Your repository should contain a data folder for your data. **But the data should be used only locally not uploaded to the repository**. The links to the relevant data are placed in the jupyter analysis file that you are going to create for your project. The data are then to be downloaded and placed in the data folder. In your analysis remember to refer to the data folder in a relative way ( for example '../data'), **do not use absolute paths**.
* **Please use the folder on our google drive [here](https://drive.google.com/open?id=1DENzJ_zNs_Mr6lOfeuczX2ARbpSSp6lP) to store raw data, link to repository, databases, images and presentation files**. Please read the README files in the folders.
* The repository should contain only Jupyter and/or Python files with your analysis

## Please notice that:
**The database file and raw data files and images should be stored on our google drive not on repository** 
*  **NO PLOTTING IS ALLOWED IN THIS PROJECT**.
* The project needs to be presented to your colleagues on the day of the presentation.


The **deadline** to turn in the deliverables is right before the project presentations.
## Presentation time Saturday February 29th at **2 PM**! (last day of Module 1)

## Mentoring
Your teachers will be your mentors!

Your mentor will:
* Keep track of your project in general terms. Your mentor will be the second person that knows more about the project, after you.
* Check if you are following your plan: are you keeping up with your tasks and deadlines? Do you have any obstacles blocking you?
* Help/support you with specific questions.

Your mentors are **not** meant to:
* Know everything.
* Be your manager. You have to be responsible of your own tasks!

## Schedule

**Please note** that the following schedule is simply a guideline. Feel free to organize your work as you see fit.

**Phase 1**
* Choose your topic.
* Find interesting questions related to your topic.
* Brainstorm to find out what kind of data you can use to answer those questions.
* Research and look for the data you need. You can find some useful links to investigate in the ```Resources``` section.
* On Saturday 8th of February there will be individual sessions in which you will discuss your topic and research questions with your teachers. 
* On Tuesdag the 11th of February, there will be a session with your teachers in which you will present the data sets you will be using for this project. 

**Phase 2**
* Plan your project. Remember that we are providing you with a Trello [template](https://trello.com/b/usAykV9K/project-2-barcelona). Define tasks, specifying those to be done individually and those to be done together. Remember that you **CAN'T CODE** until your project is planned.
* Once you finish, start coding!
* Clean your data.
* Design and build your database.

**Phase 3**
* Analyze your data.
* Find the most interesting and meaningful insights.
* Start preparing the slides for Friday's presentation.

**Presentation**  
* Presentation time Saturday February 29th at **2 PM**! (last day of Module 1)

## Example Datasets

Below you'll find some data sets that have been used for projects in the Barcelona DA Bootcamp. 
Please have a look at these for inspiration
[here](https://drive.google.com/drive/folders/11Y09CijLBloNeLoOGu8wjx_56BhCxSmN?usp=sharing ).
However, you should find your own data set about **Amsterdam**. The example datasets are about Barcelona.

### Transportation
**accidents-2017**: List of accidents handled by the local police in the city of Barcelona.  
**bus-stops**: Bus stops, day bus stops, night bus stops, airport bus stops of the city of Barcelona.  
**public-transport**: Public transports (underground, Renfe, FGC, funicular, cable car, tramcar, etc) of the city of Barcelona.  

### Urban environment
**air-quality-nov-2017**: Measures of O3 (tropospheric Ozone), NO2 (Nitrogen dioxide) and PM10 (Suspended particles).  
**air-stations-nov-2017**: Main characteristics of the air quality measure stations of the city of Barcelona.    

### Population
**births**: Births by nationalities and by neighborhoods of the city of Barcelona (2013-2017).  
**deaths**: Deaths by quinquennial ages and by neighborhoods of the city of Barcelona (2015-2017).   
**immigrants_by_nationality**: Immigrants by nationality and by neighborhoods of the city of Barcelona (2015-2017).   
**immigrants_emigrants_by_age**: Immigrants and emigrants by quinquennial ages and by neighborhood of the city of Barcelona (2015-2017).  
**immigrants_emigrants_by_destination**: Immigrants and emigrants by place of origin and destination, respectively (2017).  
**immigrants_emigrants_by_sex**: Immigrants and emigrants by sex by neighborhoods of the city of Barcelona (2013-2017).  
**most_frequent_baby_names**: 25 Most common baby names in Barcelona, disaggregated by sex (1996-2016).  
**most_frequent_names**: 50 Most common names of the inhabitants of Barcelona, disaggregated by decade of birth and sex.  
**population**: Population by neighborhood, by quinquennial ages and by genre of the city of Barcelona (2013-2017). Reading registers of inhabitants.

### Administration
**general-election-results-2019**: Results of the general elections by census section in the city of Barcelona (2019).

### Economics & business
**unemployment**: Registered unemployment by neighborhood and genre in the city of Barcelona (2013-2017).

## Presentation
The presentation time limit is **15 minutes**! After each presentation, there will be a Q&A. 

Our suggestion is to include at least the following slides in your presentation but feel free to add or remove slides:

* Title of the project
* Team presentation
* Goals of the project
* Data - sources, problems and limitations
* Database - data wrangling/cleaning and database structure
* Main insights
* Questions you were not able to answer and why
* Learnings

**Remember to present your insights as understandably as possible without using plots!**

## Tips & Tricks
* Questions first. Data second.
* Think about the workflow of your analysis BEFORE starting to code.
* You will have more questions than answers. It's not a problem if you can't answer some or any of your questions. Just show us why you couldn't answer them, that itself will be interesting!

## Asking Questions
Imagine that our project is about the population of Amsterdam.
We could, for example, try to answer a *descriptive* question such as: How many people are living in my neighborhood? In this case you will simply need to find data that can directly answer your question.
Let's instead assume that your question is an *analytic* one such as: Is my neighborhood the best? In this case you will need to think what the word *best* means in this context. For example it could mean:
* Safer
* More cultural events
* More schools
* ...

Analytic questions require you to think about the *how* of answering a question.
This is one of the most interesting parts of the process and you will be doing it for the rest of the bootcamp (and most likely for the rest of your career as a data analyst).

### Resources (Suggested)
* [Data en Informatie (Dutch)](https://data.amsterdam.nl)
* [Kaggle](www.kaggle.com)
* [Rijkswaterstaat(Dutch)](https://www.rijkswaterstaat.nl/zakelijk/open-data)
* [Nationale Spoorwegen (Dutch)](https://www.ns.nl/reisinformatie/ns-api)
* [Google Dataset Search](https://datasetsearch.research.google.com)
* [Education (English)](https://www.ceicdata.com/en/netherlands/education-statistics)
* [Data en Overheid (Dutch)](https://data.overheid.nl/dataset/53928-lengte-van-spoorwegen--spoorwegkenmerken--provincie)
* [Data en Overheid (Amsterdam) (Dutch)](https://data.overheid.nl/dataset/1/25?sort=score%20desc%2C%20metadata_modified%20desc&facet_source_catalog%5B0%5D=https%3A//data.amsterdam.nl/)
* [Centraal Bureau voor de Statistiek (Data Portaal) (English and Dutch)](https://opendata.cbs.nl/statline/portal.html?_la=nl&_catalog=CBS)



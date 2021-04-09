# Gaming Behavioral Matchmaking System

## Working Prototype and Code
Prototype URL: https://ksuletsgame.azurewebsites.net/

Code URl: https://github.com/emergingsoftwar/ReactCode

## Sprint1 Documents
https://github.com/emergingsoftwar/documents/tree/main/Sprint%201

## Sprint2 Documents
https://github.com/emergingsoftwar/documents/tree/main/Sprint%202

## Team Name: ES 2021
### Team Members:             
Leul Endashaw:                  Product Owner<br/>
Gopi Macha:                     Scrum Master<br/>
Sai Krupa Bariki Vidura:        Development Team<br/>
Terry Boyett:                   Development Team<br/>

## Product Vision
### Near Vision
Our initial focus in our product is to have a functioning website with a start screen. Our product will have a home button, about section, settings page, and game modes section.
The home button will allow the player to return to the initial screen they were presented after the start screen. The about page will describe the team, the reasoning behind the website's creation and give an initial description of the website. It will give the player all the information they need. The game modes section will show a list of the game modes available to the player and allow the player to select the game mode of their choosing. It will also allow the player to change their search preferences and view what matches are available. The site is easy to navigate and match the player with others seamlessly.

### Far Vision
We will take in game data along with player and user generated behavior profiles to match the player with the teammates that best suit their skill and behavior. The matchmaking system will enable the users find users from their matches and then add them as a friend. The player and their newly found friends will be able to form groups. These groups can then search for matches together and matchmake with other players that fit their skill level and behavior. The player will also be able to view their profile. This includes the skill level, behavior profile, and playstyle archetype. All these together will reintroduce the human component to online teammates and improve the players experience in online multiplayer.

### Stakeholders
The stakeholders are game players and gaming companies.

## Product Backlog
#### [Product Backlog Items in Azure](https://dev.azure.com/sbarikiv/Gaming%20Behavioral%20Matchmaking%20System/_backlogs/backlog/Gaming%20Behavioral%20Matchmaking%20System%20Team/Backlog%20items)

## Definition of Ready
The story must include the following items to be considered in "Ready" state
* Title
* User story opening sentence
* Estimated in story points
* Acceptance Criteria clearly defined
* Dependencies are identified
* Priority is defined

## Rationale for Backlog Order
We have decided to build the behavioral matching system as a web application. In order to build the web application, the first stories that have the at most priority is selecting the framework that we will use to build the web application and building the initial layout of the web site containing header, footer, contact us, about us and place holders for other pages.  <br/>

The next stories will be about deciding the contents of the web pages we are creating based on the specifications provided and then implementing the functionality. These pages can range in different formats based on the product owner needs. The aim of the web app is to find players across different games that can be matched based on user defined filters. The player's data extracted from external API of our choosing will be filtered and displayed for the users. This data will also be used by the match making algorithm to find potential matches. <br/>

The core functionality can be accomplished by building web pages that can list the games for selection, capture match making preferences for filtering and provide a way to accept or reject the selected matches by viewing profile. The low priority stories related to adding players as friends and forming a group will be implemented in the last sprint after successful implementation of core match making functionality.  <br/>

We have ordered our product backlog items after carefully analyzing the dependencies,  priorities and risks. The first sprint will be primarily focused on building web page layout and adding initial content and then adding game selection page. The second sprint will be focused on implementing the match matching process and building the match selection pages. The third sprint will be focused on implementing the functionality related to adding players as friends and forming groups and end to end testing. <br/>


# Sprint 1
## Story Point: Forecast and Rationale 
### The forecast for the first sprint includes: 
* Build initail web application: 5 points
* Create home page and about us page: 3 points
* Create footor for each page: 2 points
* Provide game selection: 3 points

These inital tasks create the base for our application. It sets up the initail page the user will see and the first few pages the user will click on to understand the application. It is important to focus on creating a good framework for our application because we could run into other problems if we don't focus on this first and get ahead of ourselves. Being able to select the game is our first task because it how the matchmaking process will start.

## Sprint Product Backlog Tasks
#### [Sprint Product Backlog Tasks in Azure](https://dev.azure.com/sbarikiv/Gaming%20Behavioral%20Matchmaking%20System/_sprints/backlog/Gaming%20Behavioral%20Matchmaking%20System%20Team/Gaming%20Behavioral%20Matchmaking%20System/Sprint%201)

## Kanban Board: Sprint Backlog Tasks
#### [Kanban Board in Azure](https://dev.azure.com/sbarikiv/Gaming%20Behavioral%20Matchmaking%20System/_boards/board/t/Gaming%20Behavioral%20Matchmaking%20System%20Team/Backlog%20items)

## Burndown Chart
![alt text](Sprint%201/Burndown%20Chart.png "Burndown Chart")

## Mob Programming Video
https://youtu.be/rVZZJr0eBfw

## Sprint Review Video
https://web.microsoftstream.com/video/118261d8-2d75-4e11-9496-8de30dd50d1f

## Sprint Retrospective
### What went well during the sprint?
* Building initial web applicaion
* Learning the new React framework
* Mob programming and technical team meetings helped us achieve the sprint goals
### Is there anything that can be improved?
* Story Closures
* Burning hours
* Deployment
* Third party API usage
### How can we make those improvements?
* The stories should be moved to "Done" status once all the tasks are completed
* Hours should be burned for each task every day
* Set up auto deployment using azure pipelines instead of manual deployment
* Team need to spend some more time to understand the third gaming api that we are using for this application

# Sprint 2
## Story Point: Forecast and Rationale 
### The forecast for the second sprint includes: 
* Matchmaking process: 3 points<br/>
* Provide list of matched players for selection: 5 points<br/>
* Profile Viewer: 3 points<br/>
* CI/CD System: 2 points


The matchmaking is one of the core components of our application. We will spend the majority of the sprint focusing on this and making sure everything works properly. Giving a list of players for the user to pick is also important because it is the base of make later parts of the application. The profile viewer that will be completed during this sprint as well. The list of players will need to be working for this part of web app to work. It is imperative that this be completed first in the sprint. 

## Sprint Product Backlog Tasks
#### [Sprint Product Backlog Tasks in Azure](https://dev.azure.com/sbarikiv/Gaming%20Behavioral%20Matchmaking%20System/_sprints/taskboard/Gaming%20Behavioral%20Matchmaking%20System%20Team/Gaming%20Behavioral%20Matchmaking%20System/Sprint%202)

## Kanban Board: Sprint Backlog Tasks
#### [Kanban Board in Azure](https://dev.azure.com/sbarikiv/Gaming%20Behavioral%20Matchmaking%20System/_boards/board/t/Gaming%20Behavioral%20Matchmaking%20System%20Team/Backlog%20items)
![alt text](/Sprint%202/Kanban_Board.png "Kanban Chart")

## Burndown Chart
![alt text](/Sprint%202/Burndown_Chart.png "Burndown Chart")

## Mob Programming Video
https://web.microsoftstream.com/video/53f1426e-f53a-41ed-8242-ae350057f610

## Sprint Review Video
https://web.microsoftstream.com/video/fc5f80d2-3980-493d-8c91-d94c22450cbe

## Continuous Integration system 
https://dev.azure.com/sbarikiv/Gaming%20Behavioral%20Matchmaking%20System/_build?view=pipelines

Recent Run: https://dev.azure.com/sbarikiv/Gaming%20Behavioral%20Matchmaking%20System/_build/results?buildId=21&view=logs&j=275f1d19-1bd8-5591-b06b-07d489ea915a

## Continuous Deployment system 
https://dev.azure.com/sbarikiv/Gaming%20Behavioral%20Matchmaking%20System/_release?_a=releases&view=mine&definitionId=2

Recent Release: https://dev.azure.com/sbarikiv/Gaming%20Behavioral%20Matchmaking%20System/_releaseProgress?_a=release-pipeline-progress&releaseId=17 

## Test Runs and Result Trends in Azure DevOps

Test Result Trend Dashboard: https://dev.azure.com/sbarikiv/Gaming%20Behavioral%20Matchmaking%20System/_dashboards/dashboard/b3e6c02f-7928-45aa-a546-d94224327e9f
![alt text](/Sprint%202/Test_Results_Trend.png "Test Results Trend")

All Test Cases: https://dev.azure.com/sbarikiv/Gaming%20Behavioral%20Matchmaking%20System/_testManagement/runs?runId=10&_a=resultQuery
![alt text](/Sprint%202/Test_Results_Recent_Run.png "Test Results Recent Run")

Test Runs: https://dev.azure.com/sbarikiv/Gaming%20Behavioral%20Matchmaking%20System/_testManagement/runs?_a=runQuery

Recent Run: https://dev.azure.com/sbarikiv/Gaming%20Behavioral%20Matchmaking%20System/_testManagement/runs?_a=runCharts&runId=10

## Sprint Retrospective
### What went well during the sprint?
* Building the match making pages and process
* Learning the CICD pipelines
* Story and Task Closures
* Technical team meetings and frequest touchbase meetings helped us achieve the sprint goals
### Is there anything that can be improved?
* Story Pointing
* Publising test results with coverage
* Raising the issues early
* Early analysis of Third Party APIs and frameworks
### How can we make those improvements?
* The conflicting styling and alignment issues could have been avoided by early analysis
* Mapping of properties whats required vs available from API could have been done early
* Tests results with coverage can be published to undestand the code coverage
* Team should consider the complexity of the features before estimating the stories. The filerting functionality in match making page needed lot of effort and took longer than expected.

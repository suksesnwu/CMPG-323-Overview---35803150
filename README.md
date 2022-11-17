<a name="readme-top"></a>
<div id="header" align="center">
  <h1>CMPG-323-Overview---35803150</h1>
</div>

<details>
  <summary>In this document</summary/>
    <ol>
      <ul>
        <a href="#general-info">General Info</a>
        <ul>
          <li><a href="#projects-and-repository-links">Projects and Repository Links</a></li>
          <li><a href="#project-explained-with-diagram">Project Explained with Diagram</a></li>
          <li><a href="#branching-strategy">Branching Strategy</a></li>
          <li><a href="#gitignore-file">.gitignore file</a></li>
          <li><a href="#storage-credentials-and-sensitive-information">Storage credentials and sensitive information</a></li>
        </ul>
      </ul>
      <ul><a href="#projects-overview">Projects Overview</a>
        <ul>
          <li><a href="#project-1-overview">Project-1 Overview</a></li>
          <li><a href="#project-2-overview">Project-2 Overview</a></li>
          <li><a href="#project-3-overview">Project-3 Overview</a></li>
          <li><a href="#project-4-overview">Project-4 Overview</a></li>
          <li><a href="#project-5-overview">Project-5 Overview</a></li>
        </ul>
      </ul>
    </ol>
</details>

## General Info
## Projects and Repository Links:

#### Project 1 - Agile & Scrum
[CMPG-323-Overview---35803150](https://github.com/suksesnwu/CMPG-323-Overview---35803150)

#### Project 2 - API Development
[CMPG-323-Project2---35803150](https://github.com/suksesnwu/CMPG-323-Project2---35803150)

#### Project 3 - Standards & Patterns
[CMPG-323-Project3---35803150](https://github.com/suksesnwu/CMPG-323-Project3---35803150)

#### Project 4 - Testing & RPA
[CMPG-323-Project4---35803150](https://github.com/suksesnwu/CMPG-323-Project4---35803150)

#### Project 5 - Reporting & Monitoring
[CMPG-323-Project5---35803150](https://github.com/suksesnwu/CMPG-323-Project5---35803150)

## Project Explained with Diagram:

![Context Repo Diagram Final drawio (1)](https://user-images.githubusercontent.com/69342894/185395901-84c53b9b-da31-4b8e-9106-24d4b08c5feb.png)

## Branching Strategy:
As part of my development process, I will be using the Git Flow branching strategy.

A main branch will contain only production releases that have been tested and completed.

## gitignore file:
Contains untracked files that are to be ignored when code is commited/pushed to remote repository.

I plan to include Database Configuration Files as the configuration will be different on other operating systems.

## Storage credentials and sensitive information:
To keep users data like authentication credentials private, I will be using Azure Credential Scanner and Azure Key Vault. 

#### Azure Key Vault
Cloud secret manager service that will keep API keys and passwords secured. 

####  Azure Credential Scanner
Checks all the commits on GitHub to ensure no specific credentials such as passwords get merged to the main branch.
## Projects Overview
### Project-1 Overview
***

![Burndown chart by sprint](https://user-images.githubusercontent.com/69342894/202509255-5ab02b4f-fb63-45d7-b268-d3265a8737b5.png)

![Number of hours for each repo](https://user-images.githubusercontent.com/69342894/202519004-5dc4cb87-87de-45bf-9bdc-6ef23547914f.png)


### Project-2 Overview
***
#### IoT Device Management System
This is an IoT Web API Device Management System that helps administrators register, organise, monitor, and remotely manage all IoT devices deployed by the organisation. Users and Administrator must register/login to be authorized so that they can register IoT devices, categorise them and deploy them throughout  the  organisation's  buildings  in  predefined  zones. 

Representational State Transfer (REST) is a model and architectural style used for this IoT Device Management System, which makes the it possible to run it on the cloud, will be using azure in this case.


![api overview project2 diagram](https://user-images.githubusercontent.com/69342894/188290399-f5a30762-d863-4d0a-8824-c17b5e851adf.png)

** Register/Login **
_Register_
`POST /api/Authenticate/register`

_Login_
`POST /api/Authenticate/login`

_Create a new admin on the database_
`POST /api/Authenticate/register-admin`

** Categories **
_Retrieve all Categories entries from the database_
`GET /api/Categories`

_Create a new Category entry on the database_
`POST /api/Categories`

_Retrieve one Category from the database based on the ID parsed through_
`GET /api/Categories/{id}`

_Update an existing Category entry on the database_
`PUT /api/Categories/{id}`

** Zones **

##### Device 

### Project-3 Overview
***
####

### Project-4 Overview
***
####

### Project-5 Overview
***
####


<p align="right">(<a href="#readme-top">back to top</a>)</p>

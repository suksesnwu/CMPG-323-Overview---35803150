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
### Projects and Repository Links:
***

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

### Project Explained with Diagram:
***

![Context Repo Diagram Final drawio (1)](https://user-images.githubusercontent.com/69342894/185395901-84c53b9b-da31-4b8e-9106-24d4b08c5feb.png)

### Branching Strategy:
***
As part of my development process, I will be using the Git Flow branching strategy.

A main branch will contain only production releases that have been tested and completed.

### gitignore file:
***
Contains untracked files that are to be ignored when code is commited/pushed to remote repository.

I plan to include Database Configuration Files as the configuration will be different on other operating systems.

### Storage credentials and sensitive information:
***
To keep users data like authentication credentials private, I will be using Azure Credential Scanner and Azure Key Vault. 

### Azure Key Vault
Cloud secret manager service that will keep API keys and passwords secured. 

###  Azure Credential Scanner
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

### Register/Login 
_Register_

`POST /api/Authenticate/register`

_Login_

`POST /api/Authenticate/login`

_Create a new admin_

`POST /api/Authenticate/register-admin`

### Categories
_Retrieve all Categories entries from the database_

`GET /api/Categories`

_Create a new Category entry on the database_

`POST /api/Categories`

_Retrieve one Category from the database based on the ID parsed through_

`GET /api/Categories/{id}`

_Update an existing Category entry on the database_

`PUT /api/Categories/{id}`

_Delete an existing Category entry on the database_

`DELETE /api/Categories/{id}`

### Zones
_Retrieve all Zones entries from the database_

`GET /api/Zones`

_Create a new Zone entry on the database_

`POST /api/Zones`

_Retrieve one Zone from the database based on the ID parsed through_

`GET /api/Zones/{id}`

_Update an existing Zone entry on the database_

`PUT /api/Zones/{id}`

_Delete an existing Zone entry on the database_

`DELETE /api/Zones/{id}`

### Device 
_Retrieve all Devices entries from the database_

`GET /api/Devices`

_Create a new Device entry on the database_

`POST /api/Devices`

_Retrieve one Device from the database based on the ID parsed through_

`GET /api/Devices/{id}`

_Update an existing Device entry on the database_

`PUT /api/Devices/{id}`

_Delete an existing Device entry on the database_

`DELETE /api/Devices/{id}`

### Project-3 Overview
***
This is an <a href="https://iotsystem35803150.azurewebsites.net/" target="_blank">IoT Web App Device Management System</a> that helps administrators register, organise, monitor, and remotely manage all IoT devices deployed by the organisation. Users and Administrator must register/login to be authorized so that they can register IoT devices, categorise them and deploy them throughout  the  organisation's  buildings  in  predefined  zones. 

### Register/Login
**Register**: Go to <a href="https://iotsystem35803150.azurewebsites.net/Identity/Account/Register">Register</a> or click Register in the left sidebar.

**Login**: Go to <a href="https://iotsystem35803150.azurewebsites.net/Identity/Account/Login">Login</a> or click Login in the left sidebar.

![Home_Not logged_in](https://user-images.githubusercontent.com/69342894/202619928-e46f7bab-e390-4fb6-a9dd-a0ed268d1e26.png)

### Zones
Go to <a href="https://iotsystem35803150.azurewebsites.net/Zones">Zones</a> in the left sidebar (it appears when you're logged in).

There are options for each zones, click on the icons next to any zone to do the following (in order):

- **Create**: _Click the `plus` icon to **Create Zone**._
- **Edit**: _Opens **Edit Zone** so you can make changes to the Zone._
- **View**: _See **Zones Details**._
- **Delete**: _Opens **Delete Zone** so you can delete a Zone._

### Categories
Go to <a href="https://iotsystem35803150.azurewebsites.net/Categories">Categories</a> in the left sidebar (it appears when you're logged in).

There are options for each Categories, click on the icons next to any Category to do the following (in order):
- **Create**: _Click the `plus` icon to **Create Category**._
- **Edit**: _Opens **Edit Category** so you can make changes to the Category._
- **View**: _See **Categories Details**._
- **Delete**: _Opens **Delete Category** so you can delete a Category._


### Devices

Go to <a href="https://iotsystem35803150.azurewebsites.net/Devices">Devices</a> in the left sidebar (it appears when you're logged in).

There are options for each Devices, click on the icons next to any Device to do the following (in order):
- **Create**: _Click the `plus` icon to **Create Device**._
- **Edit**: _Opens **Edit Device** so you can make changes to the Device._
- **View**: _See **Devices Details**._
- **Delete**: _Opens **Delete Device** so you can delete a Device._

![Home_Logged_in](https://user-images.githubusercontent.com/69342894/202620039-7e9e9e95-3bfb-49af-a02a-a3aaa1875254.png)

### Project-4 Overview
***
This is an IoT UIPath Automation Device Management System that helps administrators register, organise, monitor, and remotely manage all IoT devices deployed by the organisation. Users and Administrator must login to be authorized so that they can register IoT devices, categorise them and deploy them throughout  the  organisation's  buildings  in  predefined  zones. 

### Quick Start
- Clone the repo

### Zones

There are workflows for each Zones, can be found Zones folder:

- **Create**: _Open **Zone.xaml** and execute the automation to **Create Zones**._
- **Edit**: _Opens **UpdateZones.xaml** to see automation for editing Zone._
- **View**: _Open **ReadZone.xaml** automation file to see Zones details ._
- **Delete**: _Open **DeleteZone.xaml** and observe the automation for deleting a Zone._


### Categories

There are workflows for each Categories, can be found Categories folder:

- **Create**: _Open **Category.xaml** and execute the automation to **Create Categories**._
- **Edit**: _Opens **UpdateCategories.xaml** to see automation for editing Category._
- **View**: _Open **ReadCategory.xaml** automation file to see categories details ._
- **Delete**: _Open **DeleteCategory.xaml** and observe the automation for deleting a Category._

### Devices

There are workflows for each Devices, can be found Devices folder:

- **Create**: _Open **Device.xaml** and execute the automation to **Create Devices**._
- **Edit**: _Opens **UpdateDevices.xaml** to see automation for editing Device._
- **View**: _Open **ReadDevice.xaml** automation file to see Devices details ._
- **Delete**: _Open **DeleteDevice.xaml** and observe the automation for deleting a Device._

### Orchestrator

Published to the UiPath Orchestrator 

![orchestrator proof](https://user-images.githubusercontent.com/69342894/198301325-51d9701c-af46-4b19-9616-7847eb246a4c.png)

### Project-5 Overview
***
####


<p align="right">(<a href="#readme-top">back to top</a>)</p>

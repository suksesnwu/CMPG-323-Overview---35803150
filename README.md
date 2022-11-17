<a name="readme-top"></a>
<div id="header" align="center">
  <h1>CMPG-323-Overview---35803150</h1>
</div>

<details>
  <summary>In this document</summary/>
    <ol>
      <ul>
        <a href="#general-info">General Info</a>
      </ul>
      <ul><a href="#projects-and-repository-links">Projects and Repository Links</a></ul>
      <ul><a href="#project-explained-with-diagram">Project Explained with Diagram</a>
      <ul><a href="#branching-strategy">Branching Strategy</a>
      <ul><a href="#.gitignore-file">.gitignore file</a>
      <ul><a href="#storage-credentials-and-sensitive-information">Storage credentials and sensitive information</a>
      <ul><a href="#Projects Overview">Projects Overview</a>
        <ul>
          <li><a href="#high-level-metrics">High-Level Metrics</a></li>
          <li><a href="#device-monitoring">Device Monitoring</a></li>
          <li><a href="#device-registration">Device Registration</a></li>
          <li><a href="#filtering">Filtering</a></li>
          <li><a href="#strech-tasks">Stretch Tasks</a></li>
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
As part of my development process, I will be using the Git Flow branching strategy..[^1]

A main branch will contain only production releases that have been tested and completed.

## .gitignore file:
Contains untracked files that are to be ignored when code is commited/pushed to remote repository.[^2]

I plan to include Database Configuration Files as the configuration will be different on other operating systems.

## Storage credentials and sensitive information:
To keep users data like authentication credentials private, I will be using Azure Credential Scanner and Azure Key Vault. 

#### Azure Key Vault
Cloud secret manager service that will keep API keys and passwords secured. [^3]

####  Azure Credential Scanner
Checks all the commits on GitHub to ensure no specific credentials such as passwords get merged to the main branch.[^4]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

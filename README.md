# CMPG-323-Overview---35803150

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

### References
[^1]: Microsoft Docs. 2022. Adopt a Git branching strategy (https://docs.microsoft.com/en-us/azure/devops/repos/git/git-branching-guidance?view=azure-devops) Date accessed: 18 August 2022
[^2]: Git Docs. 2022. gitignore (https://git-scm.com/docs/gitignore) Date accessed: 18 August 2022
[^3]: Microsoft Doc. 2022. Azure Key Vault basic concepts (https://docs.microsoft.com/en-us/azure/key-vault/general/basic-concepts) Date accessed: 18 August 2022
[^4]: Azure Managing Azure Secrets on GitHub Repositories (https://azure.microsoft.com/en-us/blog/managing-azure-secrets-on-github-repositories/) Date accessed: 18 August 2022

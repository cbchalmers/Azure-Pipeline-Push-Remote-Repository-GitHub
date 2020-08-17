# Project Title

Pipeline template for Azure DevOps to push into GitHub as remote SCM

## Description

Minimise the overhead of maintaining code in Azure DevOps and GitHub by automating a remote push when code is committed to the master branch within Azure DevOps. This gives the best of both worlds, and the same commit history, without having to worry about the two services becoming out of sync over time

### Prerequisites

* [Create a Personal Access Token](https://github.com/settings/tokens) with 'repo' (full control of private repositories) scope

### Configuration

* Create a variable group within the Azure DevOps project - https://dev.azure.com/{your-organization}/{your-project}/_library?itemType=VariableGroups
* Create a variable within the variable group to contain the GitHub Personal Access Token
* Replace github-pat-example-contoso-group with the name of your variable group
* Replace github-pat-example-contoso-variable with the name of your variable
* Replace example-contoso with the name of your GitHub organization
* Replace example-contoso-repository with the name of your GitHub repository
* Store the .yml file within the repository then create a pipeline

## Built With

YAML

## References

None

## Authors

Chris Chalmers - [LinkedIn](https://uk.linkedin.com/in/chris-chalmers)
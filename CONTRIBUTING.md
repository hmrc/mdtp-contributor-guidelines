# MDTP Contributor Guidelines

This page describes the process for contributing to the HMRC Multichannel Digital Tax Platform (MDTP). Every service or library on the MDTP is owned by a single team, in order to ensure no central repositories and/or teams constrain service delivery. Therefore this page is a description of the process for an individual or a team (the "Pull Requestor") to contribute a Pull Request to a repository (the "Repository") belonging to another team (the "Owning Team"). 

The contribution process is twofold: 
- MDTP Guidelines: uniform guidelines that apply to all repositories regardless of Pull Requestor, Owning Team, and Repository
- Repository Guidelines: contextual guidelines owned by the Owning Team for a specific Repository

It is the responsibility of both the Pull Requestor and Owning Team to follow these guidelines. If the Pull Requestor in particular does not follow these guidelines, it is highly likely the Owning Team will reject the changes and resist future Pull Requests from the Pull Requestor. 

It is important to remember that an Issue and a Pull Request is a placeholder for a conversation between the Pull Requestor and the Owning Team - people and interactions are important than processes and tools. The Pull Requestor should contact the Owning Team as soon as changes to the Repository are considered.

## MDTP Guidelines 

1. The Owning Team stands ready for Pull Requests and reserves some per-team capacity to monitor, review, and test Pull Requests
2. The Pull Requestor opens an Issue on the Repository and talks with the Owning Team about the proposed changes. 
3. The Owning Team informs the Pull Requestor:
    1. If the proposed change is unnecessary i.e. if the Repository already supports the desired outcome
    2. If the proposed change is undesirable e.g. rejected in the past from a different Pull Requestor
    3. If the proposed change can be reviewed and released into production in a timeline acceptable to both the Pull Requestor and the Owning Team
4. The Pull Requestor forks the Repository and makes the proposed changes - including new tests
5. The Pull Requestor runs the Repository build locally and ensures all tests pass
6. The Pull Requestor pushes their changes to their branch and raises a Pull Request against the Repository Issue
7. The Owning Team reviews the Pull Request according to the following criteria:
    1. Can the changes be compiled and tested?
    2. Do the changes clearly indicate what they are trying to achieve?
    2. Are the changes aligned with our coding standards and our architectural approach?
    3. Are the changes compatible with other in-flight changes to the Repository?
    4. Do the changes introduec any new operational concerns e.g. performance, security?
5. The Owning Team accepts or rejects the Pull Request
6. If rejected, the Pull Requestor asks the Owning Team for feedback
6. If accepted, the Pull Requestor and Owning Team discuss the timing of the optimal pre-production and production launch dates.
7. 

## Repository Guidelines

Repository-specific guidelines from the Owning Team go here, if necessary. 

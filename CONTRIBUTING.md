# MDTP Contributor Guidelines

Hello! Thank you for taking the time to contribute to the [HMRC Multichannel Digital Tax Platform](https://hmrc.github.io) (MDTP). Please take a few minutes to review this process and guidelines before you submit your request, otherwise it may be rejected. 

> It is important to remember that an Issue and a Pull Request are a placeholder for a conversation between the Pull Requestor and the Owning Team - people and interactions are more important than processes and tools. The Pull Requestor should contact the Owning Team as soon as changes to the Repository are considered.

## MDTP Contribution Process 

This process applies to all repos in our organisation. Every mircoservice or library on the MDTP is looked after by a particular service team, allowing them to have full control over the functionality that is core to their service. The owning service team are responsible for reviewing and choosing to accept your PR. 

1. The Owning Team stands ready for Pull Requests and reserves some per-team capacity to monitor, review, and test Pull Requests
2. The Pull Requestor opens an Issue on the Repository and talks with the Owning Team about the proposed changes
3. The Owning Team informs the Pull Requestor:
    1. If the proposed change is unnecessary i.e. if the Repository already supports the desired outcome
    2. If the proposed change is undesirable e.g. rejected in the past from a different Pull Requestor
    3. If the proposed change can be reviewed and released into production in a timeline acceptable to both the Pull Requestor and the Owning Team
4. The Pull Requestor:
    5. Forks the Repository and makes the proposed changes - including new tests
    5. Runs the Repository build locally and ensures all tests pass
    6. Pushes their changes to their fork and raises a Pull Request against the Repository Issue
7. The Owning Team reviews the Pull Request according to the following criteria:
    * Can the changes be compiled and tested?
    * Do the changes clearly indicate what they are trying to achieve?
    * Are the changes aligned with our coding standards and our architectural approach?
    * Are the changes compatible with other in-flight changes to the Repository?
    * Do the changes introduec any new operational concerns e.g. performance, security?
8. The Owning Team accepts or rejects the Pull Request
9. If rejected, the Pull Requestor asks the Owning Team for feedback
10. If accepted, the Owning Team merges the changes into the Repository and creates a new release

After the merge, it is the joint responsibility of the Pull Requestor and the Owning Team to:
    * discuss the optimal timing of pre-production and production releases
    * validate the functional and operational impact once the release reaches pre-production and production

It is the responsiblity of the Owning Team alone to deploy/schedule the release into the relevant pre-production and production environment(s).

## Repository Guidelines

_Repository-specific guidelines go here, at the discretion of the Owning Team._

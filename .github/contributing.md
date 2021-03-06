# Contributing to Eirini

Thank you for taking the time to contribute to Eirini. You can find more information about the project at:
1. [#eirini-dev](https://cloudfoundry.slack.com/messages/eirini-dev) slack channel.
1. [PivotalTracker](https://www.pivotaltracker.com/n/projects/2172361) show our current backlog and what we have planned for the near future.
1. [CI pipeline](https://ci.flintstone.cf.cloud.ibm.com/teams/eirini/pipelines/ci)
1. [Project page](https://www.cloudfoundry.org/project-eirini/)

# How to contribute

## Submitting a bug report

We use PivotalTracker to track bugs and a story is automatically created when you submit an issue on GitHub. To create the issue please use the following [template](ISSUE_TEMPLATE.md).

## Submitting a pull request

Pull requests are the best way to propose changes to the codebase. When a pull request is submitted, a story is automatically created in the Icebox in our PivotalTracker.

1. Sign and submit the appropriate [individual](https://www.cloudfoundry.org/wp-content/uploads/2017/01/CFF_Individual_CLA.pdf) or [corporate](https://www.cloudfoundry.org/wp-content/uploads/2017/01/CFF_Corporate_CLA.pdf) CLA
1. Fork this project into your GitHub organisation or username
1. Clone your fork on your local machine
1. Make sure you are up-to-date with the upstream `develop` branch
1. Create your feature branch
1. Commit your changes on your feature branch
1. [Run unit tests and static checks](#unit-tests--static-checks)
1. Push your feature branch to your fork
1. Issue a Pull request against **develop**

# Unit tests & static checks

Before you submit a Pull request, you must make sure that your contribution meets the following requirements:
* Your change has been well covered by unit tests (if applicable)
* All unit tests are passing
* All static code checks are passing. We enforce that by using [golangci-lint](https://github.com/golangci/golangci-lint#install)

You can check all that by executing the following script:

`$ ./scripts/check-everything.sh`

Thanks,<br/>
The Eirini team :heart:

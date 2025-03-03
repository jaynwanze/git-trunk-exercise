# Trunk-based Branching Exercise

An exercise for learning the [Trunk-based development model](https://www.atlassian.com/continuous-delivery/continuous-integration/trunk-based-development). This exercise will walk your team through adding features to an example application. 

Read the instructions for each stage carefully. If you're not sure what the instructions mean stop and take time to understand them. __If you rush into running Git commands you'll make mistakes and they can be difficult to undo.__  

## Scenario

The print magazine _Flavor_ has asked your firm to build and maintain an app so they can share recipes with their hungry audience.

The typical development cycle for the project is as follows:

- On the 1<sup>st</sup> of every month, your team receives a list of each writer's pick for recipe of the month.
- On the 15<sup>th</sup> of every month, the new version of the app is pushed to a staging server where the magazine's editors can do a final review.
- On the last day of the month, the new version of the app is pushed to production.

Development for `v1.0.0` of this project began in January. It is now the beginning of February and the development cycle for `v1.1.0` of the app has begun.

## Getting Started

Your team is made up of two or three developers. Each of you will contribute new content to the project from your computers and also review other developers contributions.

### Follow Along

Please leave this repository open in a browser tab so that you can follow along with the activities without referring to the presenter's screen.

### Project Structure
* Application code can be found in the [`/app/`](/app/) folder.
* The application contains a file named [`VERSION`](/app/VERSION) that contains the major, minor, and patch numbers for the project.
* Source files are written in markdown and can be identified by the `.md` file extension.

## Next

Next we will walk through the process of creating a GitHub Fork and local clone of this repository.

[Go](/walkthrough/1-setup.md)

## Quick Links

- [1. Setup](/walkthrough/1-setup.md)
- [2. Feature Branches](/walkthrough/2-feature-branches.md)

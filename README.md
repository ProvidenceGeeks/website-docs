# website-docs

## Overview
This repository is intended to be a top level README and documentation space for all aspects of contributions and development of the Providence Geeks [website](http://providencegeeks.com/).
There will be no code in this repo per se, but rather capture important information about the project's timeline, technical documentation, product information, developer documentation, and more!

## Roadmap
In general, all significant work will be captured in a Project at the [organization level](https://github.com/orgs/ProvidenceGeeks/projects).

| Project     |   Date   | Notes |
| ------------- | -------- | ------ |
| Infrastructure, Styleguide and Meetup.com Integration | 10/2017 | [Sprint 1](https://github.com/orgs/ProvidenceGeeks/projects/1) for the website project |
| Events Calendar, Posts, and WordPress Integration | 11/2017 | [Sprint 2](https://github.com/orgs/ProvidenceGeeks/projects/2) for the website project |

## Documentation
All important documentation for the project can be found over at the [wiki](https://github.com/ProvidenceGeeks/website-docs/wiki).  In this wiki, you'll find:

* Contributing guidelines, development environments, FAQ, etc can be found [here](https://github.com/ProvidenceGeeks/website-docs/wiki/Onboarding-Guide)
* [Product overview](https://github.com/ProvidenceGeeks/website-docs/wiki/Application-Design) of the website, user features, and styleguide
* [Technical documentation](https://github.com/ProvidenceGeeks/website-docs/wiki/Technical-Architecture) relating to all parts of the system and how they interact
* Documentation pertaining to the [backend APIs](https://github.com/ProvidenceGeeks/website-docs/wiki/API-Specification) as intended for client side consumption
* Deployment and release procedure information for the project is found [here](https://github.com/ProvidenceGeeks/website-docs/wiki/Release-Management)
* Test expectations, guidelines, and procedures are documented [here](https://github.com/ProvidenceGeeks/website-docs/wiki/Testing-Guide)

## Environments
URLs below are linked to the project staging and production environments:
- [Stage](http://stage.pvdgeeks.org) - http://stage.pvdgeeks.org/
- [Production](http://www.pvdgeeks.org) - http://www.pvdgeeks.org/

## Projects
Current projects used in the development and deployment of the Providence Geeks website:

- [website-api-events](https://github.com/ProvidenceGeeks/website-api-events) - Backend RESTful API for consuming event data from
- [website-api-posts](https://github.com/ProvidenceGeeks/website-api-posts) - Backend RESTful API for consuming blog post data from
- [website-frontend](https://github.com/ProvidenceGeeks/website-frontend) - UI frontend application for the website project
- [website-lambda-meetup](https://github.com/ProvidenceGeeks/website-lambda-meetup) - AWS Lambda for periodically retrieving data from the meetup.com API
- [website-lambda-wordpress](https://github.com/ProvidenceGeeks/website-lambda-wordpress) - AWS Lambda for periodically retrieving blog post data from the PVD Geeks WordPress REST API

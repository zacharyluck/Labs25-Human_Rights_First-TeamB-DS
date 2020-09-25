Police Use of Force API

## Contributors

| [API Design - Zachary Luck](https://github.com/zacharyluck) | [Modelling Engineer - Christopher Hartig](https://github.com/ChrisHartig44) |
| :---: | :---: |
| [<img src="https://i.imgur.com/ZyYw9Xc.png" width = "200" />](https://github.com/zacharyluck) | [<img src="https://i.imgur.com/fQGZNt1.jpg" width = "200" />](https://github.com/ChrisHartig44) |
| [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/zacharyluck) | [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/ChrisHartig44) |
| [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/zacharysluck/) | [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/christopher-hartig/) |

<br>
<br>

![MIT](https://img.shields.io/packagist/l/doctrine/orm.svg)
![React](https://img.shields.io/badge/react-v16.7.0--alpha.2-blue.svg)
![Typescript](https://img.shields.io/npm/types/typescript.svg?style=flat)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)

## Project Overview

[Trello Board](https://trello.com/b/QD7rXL7v/labs25hrfthierry)

[Product Canvas](https://whimsical.com/47hccoy2w65yxpK8dSfpwz)


Our team is developing an interactive map that identifies potential instances of police use of force across the United States of America for Human Rights First, an independent advocacy and action organization. 

 We're pulling data from similiar APIs(All locations V2 - https://raw.githubusercontent.com/2020PB/police-brutality/data_build/all-locations-v2.json, 846- https://api.846policebrutality.com/api/incidents) and from Twitter and Reddit. We want to identify aggregate these instances. 

Key Features

- Pulls and filters data from r/news
- Runs automatically
- Builds in Docker
- Pushable to AWS

## Tech Stack

### API built using:

- FastAPI

Why did we choose this framework?

- Built-in bootstrap
- Recommended to us
- Wanted to learn an in-demand framework

Other modules used:
- Pandas
- SciKit-Learn
- SpaCy
- newspaper3k
- PRAW
- fastapi-utils

# API Breakdown

The API, once running, automatically pulls and processes data from Reddit through PRAW

## PRAW

PRAW, The Python Reddit API Wrapper, makes it easy for users to analyze Reddit data. We used PRAW to scrape Reddit for potential instances of police of force.

# Environment Variables

In order for the app to function correctly, the user must set up their own environment variables. There should be a .env file containing the following inside the project folder locally before being built:

```
# These are the API keys generated when making a Reddit app
* PRAW_CLIENT_ID
* PRAW_CLIENT_SECRET
* PRAW_USER_AGENT
```

# Content Licenses

| Image Filename | Source / Creator | License                                                                      |
| -------------- | ---------------- | ---------------------------------------------------------------------------- |
| doodles.png    | Nicole Bennett   | [Creative Commons](https://www.toptal.com/designers/subtlepatterns/doodles/) |
| rings.svg      | Sam Herbert      | [MIT](https://github.com/SamHerbert/SVG-Loaders)                             |

# Installation Instructions

1. Clone the repository to your local machine

## Other Scripts

🚫replace these examples with your own

    * typecheck - runs the TypeScript compiler
    * build - creates a build of the application
    * start - starts the production server after a build is created
    * test - runs tests in **tests** directory \* eject - copy the configuration files and dependencies into the project so you have full control over them

# Contributing

When contributing to this repository, please first discuss the change you wish to make via issue, email, or any other method with the owners of this repository before making a change.

Please note we have a [code of conduct](./CODE_OF_CONDUCT.md). Please follow it in all your interactions with the project.

## Issue/Bug Request

**If you are having an issue with the existing project code, please submit a bug report under the following guidelines:**

- Check first to see if your issue has already been reported.
- Check to see if the issue has recently been fixed by attempting to reproduce the issue using the latest master branch in the repository.
- Create a live example of the problem.
- Submit a detailed bug report including your environment & browser, steps to reproduce the issue, actual and expected outcomes, where you believe the issue is originating from, and any potential solutions you have considered.

### Feature Requests

We would love to hear from you about new features which would improve this app and further the aims of our project. Please provide as much detail and information as possible to show us why you think your new feature should be implemented.

### Pull Requests

If you have developed a patch, bug fix, or new feature that would improve this app, please submit a pull request. It is best to communicate your ideas with the developers first before investing a great deal of time into a pull request to ensure that it will mesh smoothly with the project.

Remember that this project is licensed under the MIT license, and by submitting a pull request, you agree that your work will be, too.

#### Pull Request Guidelines

- Ensure any install or build dependencies are removed before the end of the layer when doing a build.
- Update the README.md with details of changes to the interface, including new plist variables, exposed ports, useful file locations and container parameters.
- Ensure that your code conforms to our existing code conventions and test coverage.
- Include the relevant issue number, if applicable.
- You may merge the Pull Request in once you have the sign-off of two other developers, or if you do not have permission to do that, you may request the second reviewer to merge it for you.

### Attribution

These contribution guidelines have been adapted from [this good-Contributing.md-template](https://gist.github.com/PurpleBooth/b24679402957c63ec426).

## Documentation

See [Backend Documentation](🚫*link to your backend readme here*) for details on the backend of our project.

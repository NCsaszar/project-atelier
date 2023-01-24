# Project Atelier

![Project Atelier logo](docs/daff_logo_with_icon.svg 'Project Atelier')

[![CircleCI](https://circleci.com/gh/Team-Daffodil/project-atelier.svg?style=shield&circle-token=92f484b28710e0723c8807019be57e964bcdbfdb)](https://circleci.com/gh/Team-Daffodil/project-atelier) ![Statements](https://img.shields.io/badge/statements-49.65%25-red.svg?style=flat)

Project Atelier is a frontend retail web portal for HackReactor's Front End Capstone project.

[JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![MUI](https://img.shields.io/badge/MUI-%230081CB.svg?style=for-the-badge&logo=mui&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)
![Styled Components](https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white)
![NPM](https://img.shields.io/badge/NPM-%23000000.svg?style=for-the-badge&logo=npm&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)

## Table of Contents

1. [Usage](#usage)
1. [Requirements](#requirements)
1. [Development](#development)

## Usage

To be filled out later.

## Requirements

To be filled out later.

## Development

The first step is to fork the project and set the upstream to Team Daffodil's main repo:

```bash
git remote add upstream https://github.com/Team-Daffodil/project-atelier.git
```

Verify upstream was added:

```bash
$ git remote -v

origin  https://github.com/<github_handle>/project-atelier.git (fetch)
origin  https://github.com/<github_handle>/project-atelier.git (push)
upstream        https://github.com/Team-Daffodil/project-atelier.git (fetch)
upstream        https://github.com/Team-Daffodil/project-atelier.git (push)
```

Install the dependencies:

```bash
npm install
```

### Creating a Pull Request

Procedure:

```bash
git checkout -b <branch-name>       # work on a new branch on your fork.
git add <files>                     # add changed files.
git commit -m 'descriptive message' # write a descriptive commit message.
git checkout main                   # switch to main branch
git pull upstream main              # pull latest changes from upstream before committing.
git merge <branch-name>             # merge new branch to main, make sure to resolve any merge conflicts before pushing.
git push                            # push to your fork

# Go to your fork on Github and initiate a pull request.
```

Rules for Pull Requests:

- each pull requests requires another developer's approval before being able to merge.

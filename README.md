# CI/CD Tools and Practices Final Project

**Project name:** ci-cd-final-project

This repository contains the Final Project for the Coursera course **CI/CD Tools and Practices**.

## Project Details

- **Project name:** ci-cd-final-project
- **Description:** A CI/CD pipeline for the Product Catalog (guestbook) microservice that
  automatically lints and unit-tests every change with GitHub Actions and deploys with
  a Tekton pipeline on Red Hat OpenShift.
- **Language / Test stack:** Python 3.9, flake8 (lint), nose (unit tests)

## Usage

This repository was created from the course template in my own GitHub account.

Name of the repo: `ci-cd-final-project`.

## Setup

After entering the lab environment you will need to run the `setup.sh` script in the `./bin` folder to install the prerequisite software.

```bash
bash bin/setup.sh
```

Then you must exit the shell and start a new one for the Python virtual environment to be activated.

```bash
exit
```

## Tasks

1. `.github/workflows/workflow.yml` – GitHub Actions CI workflow (lint with flake8 + unit tests with nose)
2. `.tekton/tasks.yml` – Tekton tasks (cleanup + nose test) used by the OpenShift pipeline

## License

Licensed under the Apache License. See [LICENSE](/LICENSE)

## Author

Skills Network

## <h3 align="center"> © IBM Corporation 2023. All rights reserved. <h3/>

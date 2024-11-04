# GitHub-Actions-CI-CD-Setup

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

## Description
This project aims to implement a Continuous Integration (CI) and Continuous Deployment (CD) pipeline using GitHub Actions. The goal is to ensure that all quality checks are met through automated testing and that the application is deployed seamlessly upon merging changes to the main branch.

## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Link](#link)
- [Questions](#questions)

## Installation
Clone the repo, install the dependencies with npm install and run the application with npm run start.To run the Cypress tests locally, use npm run cypress:open. Create GitHub Actions Workflows: Create the following YAML file in the .github/workflows directory: ci.yml: To run tests on pull requests to develop and cd.yml: To deploy on merges to main.



## Usage
To use this CI/CD pipeline, create a feature branch from develop and implement your changes, including any necessary tests. After pushing your branch, open a Pull Request against develop to trigger the CI workflow, which will run Cypress tests. Once your changes are stable and tested, merge into main to initiate automatic deployment.

## License
This project is licensed under the MIT license. For more information, please visit [MIT](https://opensource.org/licenses/MIT).


## Contributing
Contributions are welcome, please fork the repo and submit a pull request.


## Link
Please find the link of the application attached: [LINK](https://github-actions-ci-cd-setup-t9zi.onrender.com/).

## Questions
If you have any questions, you can find me on GitHub: [REPO](https://github.com/Sabrina-Sawyer/GitHub-Actions-CI-CD-Setup/).
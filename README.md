# What makes a good readme

-   Don't include any authentication details directly in this doc! It's fine to explain how to obtain them.
-   Not all sections are relevant to all projects : use common sense & adjust accordingly!

## Introduction

-   Briefly explain what the project does and its purpose.
-   Mention the project's key features or highlights.
-   Mention anything conceptually unusual about the approach taken (i.e. principle of least astonishment).

## System Requirements (web projects)

-   Detail what is required to get this project up and running (i.e. preconditions)
-   Framework and versions
-   PHP version
-   Database requirements
-   Any custom settings on the server - timeouts, post size limits etc

## System Requirements (non-web projects)

-   Detail what is required to get this project up and running (i.e. preconditions)
-   O.S. and dependency requirements and versions
-   Language and dependency requirements
-   Target platform (deliverable) requirements
-   Other custom settings

## How to Install Locally

-   Provide clear instructions on how to install the software in a local dev environment
-   Note down assumptions made about the user's environment - i.e. I expect you are going to be using Valet version XYZ
-   Include commands to copy and paste if possible
-   How to set up the required env files - Are their template env files in the repo? Where are they located?
-   How to get the database - Are there any changes you need to make to the local db to get it working compared to the live database?
-   How to get any media and/or supporting documents

## How to Deploy

-   Provide clear instructions on how to deploy changes to the system
-   Details about the staging environment, testing and live environments should be listed here.
-   Is there anything that goes against standard git flow in this project?
-   If SSH access is available, is this key based or username/password? If not is an alternative CLI solution available?

## Known issues

-   Are there any client-forced quirks with the system? Note them down!
-   Are there unfinished features?
-   Include a Frequently Asked Questions section here if you like.

_____

## Development

### Coding standards
-   Does this project adhere to any coding standards? For example [PSR 12](https://www.php-fig.org/psr/psr-12/)
-   Are there any tools to assist with spotting/fixing deviation? For example [PHP-CS-FIXER](https://github.com/PHP-CS-Fixer/PHP-CS-Fixer)

### Automated tests
-   What tech do they use? For example [Codeception](https://codeception.com/), [Cypress](https://www.cypress.io/), [unittest](https://docs.python.org/3/library/unittest.html) etc
-   What tests are available (unit, functional, acceptance, etc) & where are they located?
-   How do I set them up locally if any additional steps are required?
-   How do I run them?
-   How would I add one? Maybe just mention an example one?

### Command line tools
-   Are there any CLI based tools to assist with dev (e.g. ./neo & ./bin/magento)?
-   Are there any useful shell scripts?
-   How are caches cleared?

### Other
*todo: split this further as required*
-   Are there any git hooks? For example a post-commit to deploy.


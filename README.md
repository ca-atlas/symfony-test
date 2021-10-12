# Symfony Test

This repository will be used to hold test submissions for potential employees, to determine their level of knowledge of the Symfony framework

## Test

- Folk repo e.g. https://docs.github.com/en/get-started/quickstart/fork-a-repo#forking-a-repository
- Create feature branch this will be provided and follow the naming conversation of initials + date, e.g. js_2021-10-09
- Setup a symfony project inside a folder called `deploy` 
- Setup lando for your symfony project
    - https://docs.lando.dev/config/symfony.html#getting-started
- Task: Sync endpoint data
    - Endpoint: https://my-json-server.typicode.com/ca-atlas/test-data/blob/main/users
    - Create entity that mirrors the object structure of the data above
    - Create a command class which when actioned pulls data from endpoint and stores local
    - Present data stored locally via controller
- Create a **pull request** to the original repo e.g. https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork

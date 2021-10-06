# Symfony Test

This repository will be used to hold test submissions for potential employees, to determine their level of knowledge of the Symfony framework

## Test

- Create feature branch (using your initials and the date e.g. if your name was *John Smith*, `js_2021_10_05`)
- Setup a symfony project inside the folder `deploy` 
- Setup lando for your symfony project
    - https://docs.lando.dev/config/symfony.html#getting-started
- Task: Sync endpoint data
    - Endpoint: https://my-json-server.typicode.com/ca-atlas/test-data/blob/main/users
    - Create entity that mirrors the object structure of the data above
    - Create a command class which when actioned pulls data from endpoint and stores local
    - Present data stored locally via controller
- Push feature branch
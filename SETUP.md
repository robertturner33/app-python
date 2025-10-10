# Setup

This repository accompanies the [Building Neo4j Applications with Python course](https://graphacademy.neo4j.com/courses/app-python/) on [GraphAcademy](https://graphacademy.neo4j.com).

When the devcontainer is created, such as in a GitHub codespace, all the required software and packages will be installed.

Follow the [Setup Instructions in GraphAcademy](https://graphacademy.neo4j.com/courses/app-python/0-setup/1-setup/) to get started.

You will need to:

1. Create a new [`.env`](.env) file and copy the contents of the [`.env.example`](.env.example) file into it
2. Update the environment values in the [`.env`](.env) file with the values in the [Setup Instructions](https://graphacademy.neo4j.com/courses/app-python/0-setup/1-setup/)

You can run the application using the command:

```bash
export FLASK_APP=api
export FLASK_ENV=development
flask run
```
# Coding Assignment

## Requirements

- python 3.9 or above installed
- postgreSQL database or Docker
- Jupyter nootebooks or similar (I have used VSCode)

## Set up

1. Create a virtual env (if required, instal virtualenvs with `pip install virtualenv`) using `python -m virtualenv env` where `env` is the environment name.
2. Set up a PostgreSQL using Docker with `docker run --name some-postgres -e POSTGRES_PASSWORD=somepassword -p 5432:5432 -d postgres`, this is going to allow connections through localhost using port 5432, and it is going to create a brand new database.
3. Create a copy of .example_env, rename it to .env and update variables with your current credentials for postgres, consider that default PostgreSQL user is postgres and the same for default database.
4. Using Visual Studio Code, Open the video_processing.ipynb and run the cell with pip installs to install required packages, Chose the right environment and use local server, this way you can execute it without setting up a Jupyter server.
5. Execute cells from video_processing.ipynb secuentially to check the assignment.
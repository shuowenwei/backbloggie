## Installation
  - Install [Python](https://www.python.org/downloads/), [Pipenv](https://docs.pipenv.org/) and [Postgres](https://www.postgresql.org/) on your machine
  - Clone the repository `$ git clone https://github.com/jerichoruz/blogapi-tutorial.git`
  - Change into the directory `$ cd /blog_api`
  - Activate the project virtual environment with `$ pipenv shell` command
  - Install all required dependencies with `$ pipenv install`
  - Export the required environment variables
      ```
      $ export FLASK_ENV=development
      $ export FLASK_PORT=5005
      $ export DATABASE_URL=postgres://name:password@houst:port/blog_api_db
      $ export JWT_SECRET_KEY=es_secreto
      ```
  - Start the app with `python run.py`

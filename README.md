## fms

fms is an API for a flight management system.

## Key applications

- Search for flights
- Book flights
- Cancel flight bookings


## Set up development environment
-   Check that python 3.7 is installed:

    ```
    python --version
    >> Python 3.7
    ```

-   Install pipenv:

    ```
    brew install pipenv
    ```

-   Check pipenv is installed:
    ```
    pipenv --version
    >> pipenv, version 2018.11.26
    ```
-   Check that postgres is installed:

    ```
    postgres --version
    >> postgres (PostgreSQL) 10.1
    ```

-   Clone the repo and cd into it:

    ```
    git clone git@github.com:abadojack/fms.git
    ```

-   Install dependencies:

    ```
    pipenv install
    ```

-   Make a copy of the .env.sample file  and rename it to .env and update the variables accordingly:

    ```
    FLASK_ENV = "development" # development, production, testing
    ```

-   Activate a virtual environment:

    ```
    pipenv shell
    ```


-   Run the application with either commands:

    ```
    python manage.py runserver
    ```
    or
    ```
    flask run
    ```

-   Deactivate the virtual environment once you're done:
    ```
    exit
    ```

# BlueGhost Practical Test

## Instalation

Clone project

    git clone git@github.com:Stejsky/blueghost_app.git  
    
Build the containers (requires Docker Desktop)

    docker-compose up -d && docker-compose exec php bash  
Install dependencies

    composer install
Run migrations

    symfony console doctrine:migrations:execute


Go to http://localhost:8080/ and be amazed :-)

## Known limitations
* the note is only in JS alert window as it is for demostration purposes, so "click elsewhere" does not work
* there are no tests provided

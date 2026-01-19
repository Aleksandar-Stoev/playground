# Playground
This is a playground for the lab from the Git Branching and Pull Requests lesson from the Software Engineering and DevOps Course at SoftUni.

## Make your changes here
Quick Start
Clone the repository and navigate to the project folder:

Create .env from the example file and fill in the required values:

Start the application:

  docker-compose up

Apply migrations:

  docker-compose exec web python manage.py migrate
Create a superuser (Windows Git Bash):

winpty docker-compose run --rm web python manage.py createsuperuser
